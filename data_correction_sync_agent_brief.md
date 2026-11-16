# Agent Brief: Design a Data Correction & Sync System for a Scraping Research Project

## 0. How to use this document

You are an AI agent (or planning assistant). Read this whole brief, then work through the phases in Section 5 **in order**. Your job is to **learn the existing database, interview the user, and produce a detailed implementation plan**. You are **not** to implement anything until the user explicitly approves the plan.

Core rules:

1. **Do not assume. Ask.** If a requirement, schema detail, or workflow is unclear, ask the user. Prefer short batches of questions (3-5 at a time) over a giant questionnaire.
2. **Read-only first.** Treat every database as production. Only run `SELECT`, `EXPLAIN`, and schema introspection queries during discovery. Never run `INSERT/UPDATE/DELETE/ALTER/DROP` without explicit approval.
3. **Show your evidence.** When you state a fact about the schema or data (e.g., "table X has no unique key"), include the query or observation that supports it.
4. **Separate facts from proposals.** Label what you verified, what the user told you, and what you are proposing.
5. **Treat the proposed architecture in Section 3 as a starting hypothesis**, not a decision. Challenge it if the discovery phase shows it doesn't fit.

---

## 1. Background and problem statement

The user runs a data-heavy research project:

- Data is **scraped** from external sources and stored in a **relational database (PostgreSQL or MySQL; confirm which)** and also in **CSV/Excel files**.
- During processing and analysis, the team finds **mistakes in the data** and fixes them, usually **in Excel/CSV files**.
- **Those fixes are never written back to the database.** The database and the spreadsheets therefore drift apart, and the DB is no longer trustworthy as a source of truth.
- Exports from the database to CSV/Excel **do not include the primary key (ID)**, so edited rows cannot be reliably matched back to DB rows.
- Re-scraping can **change values in records that were already manually fixed**, which currently risks losing fixes or silently overwriting them.

### Team context (confirmed with the user)

- Database: PostgreSQL or MySQL (to be confirmed which).
- Number of people making corrections: **1-2**.
- Types of corrections: a **mix** of individual cell fixes, bulk/pattern fixes (whole columns), and whole-row additions/removals.
- Tables have a **stable unique ID** (user believes so; verify it).
- The user is considering a **synced "curated" copy** of the scraped database, edited through a UI such as **NocoDB** or **Streamlit** (or another platform), which then serves as the **endpoint for users to view and export** data.

---

## 2. Goals

1. The database (or a curated layer of it) becomes the **single source of truth**, including all corrections.
2. Every correction is **traceable**: what changed, old value, new value, who, when, why.
3. **Raw scraped data is never destroyed**. It remains available as an untouched record.
4. **Re-scraping does not silently overwrite fixes.** Conflicts are detected and surfaced for review.
5. Editing is done in a **proper UI** (spreadsheet-like, e.g., NocoDB) or a controlled workflow, not by passing files around.
6. Users can **view and export** curated data from a stable endpoint, with the primary key included.
7. The solution is **lightweight and maintainable** for a team of 1-2 people. Avoid over-engineering.

### Non-goals (unless the user says otherwise)

- True real-time two-way sync between raw and curated data.
- Enterprise-grade data governance, heavy orchestration platforms, or large infrastructure.

---

## 3. Starting-hypothesis architecture (to validate, not to assume)

### 3.1 Layers

```
Scrapers --> RAW DB (append/update by scraper only, never hand-edited)
                |
                |  sync job (one-directional: raw -> curated)
                v
         CURATED DB (edited via NocoDB / Streamlit / similar)
                |
                v
     Read-only role / views / export endpoint for users
```

- **Raw layer:** exact scraped data. Never edited by humans.
- **Curated layer:** raw data plus corrections. All human edits happen here (through the UI). This is what analysis and exports read from.
- **Sync direction:** raw -> curated only. **Never curated -> raw.** Avoid true two-way sync (conflicts, complexity).

### 3.2 Tracking corrections

Possible mechanisms (choose based on discovery):

- A **per-cell edits table**, e.g. `cell_edits(table_name, row_id, column_name, raw_at_fix, fixed_value, reason, author, created_at, status)`.
- **Row-level flags:** `is_excluded` (soft delete with reason), `source = 'scraped' | 'manual'` for manually added rows.
- **Bulk fixes** as versioned, re-runnable scripts (SQL/Python in git) or a `correction_rules` table (pattern -> replacement, with reason), re-applied after every sync.
- Optional: DB triggers writing every `UPDATE/DELETE` on curated tables to an **audit log**, so direct DB edits are also traceable.

### 3.3 Re-scrape conflict handling (three-way comparison per cell)

For each cell that has been manually edited, store `raw_at_fix` (the raw value at the time the fix was made). On each sync compare the **new raw value** against it:

| Situation | Action |
|---|---|
| Cell never edited | Auto-update from the new raw value |
| Edited, raw unchanged since fix | Keep the fix |
| Edited, raw **changed** since fix | **Conflict**: keep current fix for now, add to a **review queue** |
| Edited, new raw value now equals the fix | Source corrected itself: auto-resolve, mark the fix obsolete |

Review queue fields (suggested): `id, column, raw_at_fix, new_raw, current_fix, status, resolved_by, resolution, resolved_at, note`. Reviewer options: keep fix / accept new raw / enter a new value. Every resolution is logged.

Additional rules to consider:

- Re-run bulk correction rules after each sync.
- Excluded rows stay excluded even if the source row changes, but flag them if the content changed substantially.
- Rows that disappear from the source are marked `missing_from_source`, not deleted.
- **Normalize before comparing** (whitespace, casing, number/date formats) so trivial differences don't flood the review queue.
- Use a **per-row hash/version of raw data** to cheaply detect changed rows.
- The sync job is the **only** code that decides between auto-update, keep, and conflict.

### 3.4 Tooling options for the editing UI

| Tool | Notes |
|---|---|
| **NocoDB** | Connects directly to Postgres/MySQL; spreadsheet-style UI; roles; audit history; CSV export; REST API. Leading candidate: minimal code. |
| **Streamlit** | Custom validation and workflows (`st.data_editor`); you must build save, audit, and permission logic yourself. |
| **Metabase / Superset** | Good for read-only viewing and exports; not for editing. |
| Others (Retool, Baserow, Directus, Appsmith, etc.) | Evaluate if NocoDB/Streamlit don't fit. |

### 3.5 Handling the existing problem: exports without IDs

- Going forward: any export must include the **primary key as the first column**, and editors must not alter it. Optionally add `exported_at` to detect rows that changed in the DB after export.
- For **already-edited files without IDs**: recover the ID via a **natural key** (a column combination unique per row). Verify uniqueness first, join the file to the DB, and manually review rows that match nothing or match multiple rows.
- If using a curated copy plus UI, this problem largely disappears, but a one-time **backfill/reconciliation** of existing Excel/CSV fixes into the curated layer is still needed.

---

## 4. What you must figure out (information to gather)

### 4.1 From the database (discovery, read-only)

Collect and report:

- DB engine and version; hosting (local, cloud, managed); how you connect; user permissions available to you.
- All schemas, tables, columns, data types, nullability, defaults.
- **Primary keys, unique constraints, foreign keys, indexes** per table. Flag tables **without** a primary key or with weak/unstable keys.
- Row counts and approximate sizes per table; growth rate if inferable (e.g., timestamps).
- Presence of timestamp columns (`scraped_at`, `updated_at`, etc.), source identifiers (URL, source ID), or existing versioning/audit tables.
- **Natural-key candidates** (column combinations that are unique), with the query proving uniqueness.
- Data quality indicators: duplicates, nulls in important columns, inconsistent formats, obvious outliers.
- Existing triggers, views, materialized views, stored procedures, and jobs.
- How scraper writes happen (insert-only, upsert, truncate-and-reload?), if discoverable from the DB or code.

### 4.2 From the codebase / pipeline (if the user gives access)

- Scraper code: how records are identified, deduplicated, and written; scheduling and frequency.
- Existing export scripts and where CSV/Excel files are produced and stored.
- Existing processing/cleaning scripts and what they output.
- Tech stack (Python/pandas/SQLAlchemy? something else?), and deployment environment.

### 4.3 From the user (interview)

Ask these in logical batches. **Do not assume answers.** Adapt based on what discovery shows.

**A. Scope and data**
1. Which tables/datasets need correction tracking? Which are in scope first?
2. Roughly how many rows and how often does new data arrive?
3. Which columns are typically corrected? Are some columns never to be edited?
4. Are there columns whose values must follow rules (enums, ranges, formats) that validation should enforce?

**B. Rescraping behavior**
5. When re-scraping, do existing records get updated in place, replaced, or are only new records added?
6. How often do source values change? Are most changes meaningful or just formatting noise?
7. Can a record be uniquely re-identified across scrapes (source URL/ID)? What is that identifier?
8. What should happen when a source record disappears?

**C. Corrections workflow**
9. Who edits (1-2 people: roles, technical skill, comfort with SQL vs spreadsheet UI)?
10. Do corrections need a review/approval step, or is a single editor's change final?
11. Should every correction require a reason? Should there be correction categories?
12. How are bulk fixes currently done (Excel find/replace, pandas scripts)? Examples?
13. Is there a backlog of **existing Excel/CSV corrections** that must be reconciled into the system? How many files, and where are they?

**D. Consumers and exports**
14. Who consumes the data (internal analysts, external researchers, public)? How many?
15. Do consumers need to see the corrected data only, or also raw values / change history?
16. Preferred access: file exports, direct DB read access, API, dashboards?
17. Should exports include metadata (ID, last-edited-at, edited flag)?

**E. Constraints and preferences**
18. Hosting constraints (self-hosted only? cloud allowed? budget?).
19. Tool preferences or dislikes (NocoDB, Streamlit, others)? Any existing tools in use?
20. Security/privacy/compliance requirements (sensitive data, access control, audit needs).
21. How much engineering time can the team put in? Preference for minimal code vs custom build?
22. Backup/restore practices today. Is there a safe staging environment to test on?

Ask follow-ups whenever an answer reveals a new risk or ambiguity.

---

## 5. Phased workflow for the agent

### Phase 1: Orientation
- Restate the problem and goals in your own words (brief). Ask the user to confirm or correct.
- Confirm DB engine, access method, and whether read-only credentials are available.

### Phase 2: Discovery
- Run read-only introspection (Section 4.1). Review code if provided (Section 4.2).
- Produce a **Discovery Report** with: schema summary, key/uniqueness findings, data quality notes, risks, and open questions. Keep it concise, with evidence.

### Phase 3: Interview
- Present the Discovery Report highlights, then ask the interview questions (Section 4.3) in batches, tailored to what you found. Skip questions already answered by discovery.
- Summarize answers back to the user and get confirmation before moving on.

### Phase 4: Options analysis
- Compare 2-3 viable architectures (e.g., curated copy + NocoDB; in-place corrections layer + Streamlit; hybrid), with trade-offs on: complexity, maintenance, conflict handling, UX, cost, risk.
- Recommend one, with reasoning, and state what would change your recommendation.

### Phase 5: Detailed implementation plan
Produce a plan the user can approve. It must include:

1. **Architecture diagram** (text/ASCII or Mermaid) and data flow.
2. **Schema design:** DDL for corrections/edits table(s), review queue, audit log, row flags, and any curated tables or views.
3. **Sync job design:** step-by-step logic including insert-new, update-unedited, conflict detection (three-way comparison), missing-from-source handling, hashing, normalization rules, idempotency, scheduling, logging, and failure recovery.
4. **Bulk correction rules:** how they're defined, versioned, tested, and re-applied.
5. **Editing UI setup:** chosen tool, configuration, roles/permissions, views for editors, review-queue UI, validation rules.
6. **Export/consumption endpoint:** how users view/export data (with primary key and metadata), access control.
7. **Migration/backfill plan:** how to reconcile existing Excel/CSV fixes into the system (including natural-key matching for ID-less files, manual review of ambiguous matches).
8. **Testing strategy:** unit tests for sync logic using synthetic scenarios covering **every row of the conflict table**, plus a dry-run mode that reports what would change without writing.
9. **Rollout plan:** staging first, backups, phased table-by-table rollout, rollback steps.
10. **Operations:** monitoring, alerts (e.g., conflict queue growth), backup strategy, documentation, and a short runbook for editors and for whoever maintains the sync.
11. **Effort estimate and milestones**, ordered so the user gets value early (e.g., Milestone 1: IDs in exports + corrections table; Milestone 2: curated layer + UI; Milestone 3: sync with conflict queue; Milestone 4: backfill).
12. **Risks and open questions**, with mitigations.

### Phase 6: Approval gate
- Present the plan, ask for feedback, iterate. **Do not begin implementation until the user explicitly approves.**
- After approval, ask whether they want you to implement milestone by milestone, with confirmation before any write to the database.

---

## 6. Guardrails and design principles

- **Never overwrite or delete raw scraped data.**
- **Never silently resolve conflicts** where a manual fix and a changed source value disagree.
- **Prefer reversible changes:** soft deletes, versioned scripts, audit logs, full backups before migrations.
- **Idempotent sync:** running the sync twice must produce the same result as running it once.
- **Dry-run first:** every write-capable script gets a `--dry-run` mode.
- **Keep it simple:** this is a 1-2 person team. Choose boring, well-supported tools. Justify any added complexity.
- **Stable identifiers:** every exported dataset carries the primary key as its first column.
- **Document decisions:** record why each design choice was made, so the team can revisit later.

---

## 7. Expected deliverables

1. Discovery Report (Phase 2)
2. Summary of confirmed requirements (Phase 3)
3. Options analysis with recommendation (Phase 4)
4. Detailed implementation plan including schemas, sync logic, UI setup, migration, testing, and rollout (Phase 5)
5. (After approval) Implementation, delivered milestone by milestone

---

## 8. Opening message to send the user

Start the conversation roughly like this:

> I've read the brief. Before I touch anything, I'll confirm a few basics: which database engine you're on (PostgreSQL or MySQL), how I can connect (read-only credentials preferred), and whether I can also see the scraper and export code. Then I'll run read-only discovery on the schema and come back with findings and questions.
