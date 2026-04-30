# Prompt Library (User-Friendly View)

- Title: The Ultimate AI Prompt Library
- Version: 1.0.0
- Total prompts (declared): 500
- Total categories: 10
- Total prompts (computed): 500

## Category Overview

| # | Category | Prompt Count | Description |
|---|---|---:|---|
| 1 | Business & Strategy | 55 | Strategic prompts for business planning, analysis, and growth |
| 2 | Marketing & Copywriting | 60 | Prompts for advertising, content marketing, email, and persuasive copy |
| 3 | Writing & Content | 55 | Prompts for blog posts, articles, copywriting, and all types of written content |
| 4 | Coding & Development | 50 | Prompts for code generation, debugging, documentation, and development workflows |
| 5 | Productivity & Planning | 50 | Prompts for task management, goal setting, project planning, and personal productivity |
| 6 | Learning & Research | 45 | Prompts for studying, learning new skills, and conducting research |
| 7 | Personal Development | 45 | Prompts for self-improvement, mindset, habits, and personal growth |
| 8 | Creative & Design | 50 | Prompts for brainstorming, design thinking, visual design, and creative projects |
| 9 | Data & Analysis | 45 | Prompts for data interpretation, reporting, analytics, and decision-making |
| 10 | Communication & HR | 45 | Prompts for professional communication, team management, and HR tasks |

## Prompt Catalog

_Each prompt includes ID, title, and placeholders you need to replace._

### 1. Business & Strategy

#### bus-001 - Business Plan Generator
- Placeholders: `BUDGET, BUSINESS NAME, BUSINESS TYPE, INDUSTRY, TARGET MARKET, TIMEFRAME, UVP`
- Prompt:

```text
Create a comprehensive business plan for [BUSINESS NAME], a [BUSINESS TYPE] in the [INDUSTRY] industry.

Key details:
- Target market: [TARGET MARKET]
- Unique value proposition: [UVP]
- Initial investment: [BUDGET]
- Timeline: [TIMEFRAME]

Include these sections:
1. Executive Summary
2. Company Description
3. Market Analysis
4. Organization & Management
5. Service/Product Line
6. Marketing & Sales Strategy
7. Financial Projections (3 years)
8. Funding Requirements

Make it investor-ready with specific metrics and actionable milestones.
```

#### bus-002 - Competitive Analysis Framework
- Placeholders: `COMPETITOR 1, COMPETITOR 2, COMPETITOR 3, MARKET/INDUSTRY, YOUR COMPANY`
- Prompt:

```text
Conduct a detailed competitive analysis for [YOUR COMPANY] competing in [MARKET/INDUSTRY].

Analyze these competitors:
1. [COMPETITOR 1]
2. [COMPETITOR 2]
3. [COMPETITOR 3]

For each competitor, evaluate:
- Products/services and pricing strategy
- Target audience and market positioning
- Unique selling propositions
- Marketing channels and messaging
- Strengths and weaknesses
- Recent developments or pivots

Conclude with:
- Competitive gaps we can exploit
- Threats to monitor
- Strategic recommendations
- Differentiation opportunities
```

#### bus-003 - SWOT Analysis Deep Dive
- Placeholders: `COMPANY/PROJECT, GOAL, INDUSTRY, PRODUCT/SERVICE, STARTUP/GROWTH/MATURE`
- Prompt:

```text
Perform an in-depth SWOT analysis for [COMPANY/PROJECT] in the [INDUSTRY] sector.

Context:
- Current stage: [STARTUP/GROWTH/MATURE]
- Main offering: [PRODUCT/SERVICE]
- Key objective: [GOAL]

For each category, provide at least 5 detailed points:

STRENGTHS (Internal positives)
- What do we do better than competitors?
- What unique resources do we have?

WEAKNESSES (Internal negatives)
- Where do we lack resources?
- What could we improve?

OPPORTUNITIES (External positives)
- What market trends can we leverage?
- What gaps exist in the market?

THREATS (External negatives)
- What obstacles do we face?
- What are competitors doing?

End with a strategic action plan addressing each quadrant.
```

#### bus-004 - Pitch Deck Content Creator
- Placeholders: `FUNDING AMOUNT, FUNDING ROUND, HOW WE MAKE MONEY, KEY METRICS, MARKET, PROBLEM, SOLUTION, STARTUP NAME`
- Prompt:

```text
Create compelling content for a pitch deck for [STARTUP NAME], seeking [FUNDING AMOUNT] in [FUNDING ROUND] funding.

Company overview:
- Problem we solve: [PROBLEM]
- Our solution: [SOLUTION]
- Target market: [MARKET]
- Business model: [HOW WE MAKE MONEY]
- Traction so far: [KEY METRICS]

Generate content for these slides:
1. Title slide (tagline)
2. Problem (pain points with data)
3. Solution (how we solve it)
4. Market opportunity (TAM/SAM/SOM)
5. Product (key features)
6. Business model (revenue streams)
7. Traction (growth metrics)
8. Competition (positioning matrix)
9. Team (why we'll win)
10. Financial projections
11. The ask (use of funds)
12. Closing (vision statement)

Make each slide concise, compelling, and investor-focused.
```

#### bus-005 - Market Sizing Calculator
- Placeholders: `CUSTOMER SEGMENT, GEOGRAPHIC REGION, PRODUCT/SERVICE, TIMEFRAME`
- Prompt:

```text
Calculate the market size for [PRODUCT/SERVICE] targeting [CUSTOMER SEGMENT] in [GEOGRAPHIC REGION].

Provide:

1. TAM (Total Addressable Market)
- Define the entire market universe
- Use both top-down and bottom-up approaches
- Cite logical assumptions

2. SAM (Serviceable Addressable Market)
- Segment by our specific offering
- Consider geographic/demographic limits
- Factor in realistic reach

3. SOM (Serviceable Obtainable Market)
- Realistic capture in [TIMEFRAME]
- Based on similar company benchmarks
- Factor in competitive landscape

Include:
- Market growth rate (CAGR)
- Key market drivers
- Potential headwinds
- Data sources for validation

Present in both narrative and numerical format.
```

#### bus-006 - Revenue Model Designer
- Placeholders: `BUSINESS NAME, BUSINESS TYPE, CUSTOMER, OFFERING, RANGE`
- Prompt:

```text
Design a comprehensive revenue model for [BUSINESS NAME], a [BUSINESS TYPE].

Current situation:
- Product/Service: [OFFERING]
- Target customer: [CUSTOMER]
- Price point range: [RANGE]

Analyze and recommend:

1. Primary Revenue Streams
- Direct sales
- Subscriptions (monthly/annual)
- Freemium conversion
- Usage-based pricing
- Licensing

2. Secondary Revenue Streams
- Upsells and cross-sells
- Partnerships/affiliates
- Data monetization
- Premium features

3. Pricing Strategy
- Competitive positioning
- Value-based pricing analysis
- Price sensitivity considerations
- Discount/promotion strategy

4. Financial Projections
- Unit economics (CAC, LTV, margins)
- Break-even analysis
- 12-month revenue forecast

Provide specific pricing tiers with justification.
```

#### bus-007 - Partnership Proposal Writer
- Placeholders: `OBJECTIVE, PARTNER COMPANY, WHAT THEY BRING, WHAT WE BRING, YOUR COMPANY`
- Prompt:

```text
Write a compelling partnership proposal from [YOUR COMPANY] to [PARTNER COMPANY].

Context:
- Our offering: [WHAT WE BRING]
- Their strength: [WHAT THEY BRING]
- Partnership goal: [OBJECTIVE]
- Proposed structure: [TYPE - e.g., co-marketing, integration, reseller]

Structure the proposal:

1. Executive Summary
- The opportunity in 2-3 sentences
- Mutual benefit preview

2. About [YOUR COMPANY]
- Relevant credentials
- Why we're the right partner

3. Partnership Vision
- What we'll achieve together
- Target outcomes and metrics

4. Proposed Structure
- Roles and responsibilities
- Resource commitments
- Revenue/benefit sharing

5. Implementation Plan
- Phase 1: Quick wins
- Phase 2: Scaling
- Timeline and milestones

6. Next Steps
- Clear call to action

Tone: Professional, mutually beneficial, specific.
```

#### bus-008 - Investor Update Email
- Placeholders: `ACHIEVEMENT 1, ACHIEVEMENT 2, ACHIEVEMENT 3, AMOUNT, CHALLENGE 1, CHALLENGE 2, COMPANY NAME, MONTH/YEAR, MONTHS, NUMBER, X`
- Prompt:

```text
Write a monthly investor update email for [COMPANY NAME] for [MONTH/YEAR].

Key metrics this month:
- Revenue: [AMOUNT] ([X]% MoM)
- Users/Customers: [NUMBER]
- Burn rate: [AMOUNT]
- Runway: [MONTHS]

Highlights:
- [ACHIEVEMENT 1]
- [ACHIEVEMENT 2]
- [ACHIEVEMENT 3]

Challenges:
- [CHALLENGE 1]
- [CHALLENGE 2]

Structure:
1. TL;DR (3 bullet summary)
2. Key Metrics (table format)
3. Wins This Month
4. Challenges & Learnings
5. Product Updates
6. Team Updates
7. What's Next (focus areas)
8. How You Can Help (specific asks)

Tone: Transparent, confident, data-driven. Keep under 500 words.
```

#### bus-009 - OKR Framework Generator
- Placeholders: `CHALLENGE, COMPANY/TEAM, NUMBER, PRIORITY, STAGE`
- Prompt:

```text
Create a comprehensive OKR (Objectives and Key Results) framework for [COMPANY/TEAM] for [TIME PERIOD - Q1, H1, Annual].

Company context:
- Stage: [STAGE]
- Main focus: [PRIORITY]
- Team size: [NUMBER]
- Key challenge: [CHALLENGE]

Generate 3-5 Objectives, each with 3-4 Key Results:

For each Objective:
- Make it inspirational and qualitative
- Align with company mission
- Be ambitious but achievable

For each Key Result:
- Make it specific and measurable
- Include target numbers
- Set baseline and stretch goals
- Define how it will be measured

Also include:
- Alignment map showing how OKRs connect
- Suggested initiatives for each KR
- Tracking cadence recommendations
- Common pitfalls to avoid

Format as a clear, actionable document.
```

#### bus-010 - Board Meeting Agenda
- Placeholders: `COMPANY NAME, HOURS, NUMBER, Q1/Q2/Q3/Q4, STAGE, TOPIC`
- Prompt:

```text
Create a board meeting agenda for [COMPANY NAME]'s [Q1/Q2/Q3/Q4] board meeting.

Company stage: [STAGE]
Board composition: [NUMBER] members
Meeting duration: [HOURS]

Prepare:

1. Pre-Read Materials List
- Documents to send in advance
- Financial reports needed
- Key decisions requiring prep

2. Detailed Agenda
- Time allocations for each item
- Presenter assignments
- Discussion vs. decision items

Suggested sections:
- Opening & Approval of Minutes (5 min)
- CEO Update (15 min)
- Financial Review (20 min)
- Product/Ops Update (15 min)
- Strategic Discussion: [TOPIC] (30 min)
- Governance Items (10 min)
- Executive Session (15 min)
- Closing & Action Items (10 min)

3. Board Packet Outline
- What each section should contain
- Data visualizations needed
- Appendix materials

4. Follow-up Template
- Action items format
- Decision log
```

#### bus-011 - Exit Strategy Planner
- Placeholders: `AMOUNT, COMPANY NAME, INDUSTRY, NUMBER, PERCENTAGE, STATUS`
- Prompt:

```text
Develop an exit strategy framework for [COMPANY NAME] in the [INDUSTRY] industry.

Current metrics:
- Annual revenue: [AMOUNT]
- Growth rate: [PERCENTAGE]
- Profitability: [STATUS]
- Team size: [NUMBER]

Analyze potential exit paths:

1. Strategic Acquisition
- Likely acquirers (list 5-10)
- Strategic value we offer
- Typical multiples in space
- Timeline to position

2. Private Equity
- PE firm criteria we meet
- Growth levers they'd want
- Typical deal structures

3. IPO Path
- Requirements to meet
- Timeline and milestones
- Pros and cons

4. Management Buyout
- Feasibility assessment
- Financing options

For each path:
- Valuation range estimate
- Prerequisites to achieve
- 24-month preparation roadmap
- Key risks and mitigations

Recommend the optimal path with reasoning.
```

#### bus-012 - Due Diligence Prep Checklist
- Placeholders: `AMOUNT, COMPANY NAME, INDUSTRY, STAGE`
- Prompt:

```text
Create a comprehensive due diligence preparation checklist for [COMPANY NAME] preparing for [TYPE - acquisition/funding/IPO].

Company profile:
- Industry: [INDUSTRY]
- Stage: [STAGE]
- Deal size: [AMOUNT]

Organize by category:

1. Corporate Documents
- Formation documents
- Cap table and equity
- Board minutes and consents
- Stockholder agreements

2. Financial Information
- Historical financials (3 years)
- Projections and assumptions
- Audit reports
- Tax returns and compliance

3. Contracts & Agreements
- Customer contracts (top 20)
- Vendor agreements
- Partnership deals
- Lease agreements

4. Intellectual Property
- Patents and trademarks
- Domain ownership
- Licensing agreements
- Trade secrets protection

5. HR & Employment
- Employee list and agreements
- Compensation data
- Benefits and policies
- Litigation history

6. Operations & Technology
- System documentation
- Security protocols
- Vendor dependencies

For each item: document name, owner, status, location.
```

#### bus-013 - Franchise Model Developer
- Placeholders: `AMOUNT, BUSINESS NAME, BUSINESS TYPE, NUMBER, PERCENTAGE, USP`
- Prompt:

```text
Design a franchise model for [BUSINESS NAME], a successful [BUSINESS TYPE].

Current business:
- Locations: [NUMBER]
- Revenue per location: [AMOUNT]
- Profit margin: [PERCENTAGE]
- Key differentiator: [USP]

Develop:

1. Franchise Fee Structure
- Initial franchise fee (with justification)
- Ongoing royalties (% of revenue)
- Marketing fund contribution
- Technology/system fees

2. Franchisee Requirements
- Financial qualifications
- Experience requirements
- Territory definitions
- Commitment terms

3. Support Package
- Initial training program
- Site selection assistance
- Marketing support
- Ongoing operations support
- Technology systems provided

4. Operations Manual Outline
- Brand standards
- Operating procedures
- Quality control measures
- Reporting requirements

5. Financial Projections
- Franchisee investment breakdown
- Projected ROI timeline
- Franchisor revenue model

6. Legal Considerations
- FDD requirements
- Territory protection
- Renewal terms
```

#### bus-014 - Crisis Management Plan
- Placeholders: `COMPANY NAME, EMPLOYEES, HIGH/MEDIUM/LOW, INDUSTRY, LIST`
- Prompt:

```text
Create a crisis management plan for [COMPANY NAME] in the [INDUSTRY] industry.

Company size: [EMPLOYEES]
Public profile: [HIGH/MEDIUM/LOW]
Key stakeholders: [LIST]

Develop plans for these crisis types:

1. PR/Reputation Crisis
- Social media backlash
- Negative press coverage
- Executive misconduct

2. Operational Crisis
- Service outage
- Data breach
- Product recall

3. Financial Crisis
- Cash flow emergency
- Major client loss
- Fraud discovery

4. Legal Crisis
- Lawsuit filing
- Regulatory investigation
- IP infringement claim

For each type include:
- Early warning signs
- Immediate response steps (first hour)
- Stakeholder communication templates
- Escalation procedures
- Recovery roadmap
- Post-crisis review process

Also include:
- Crisis team roles and contacts
- Media response guidelines
- Social media protocols
- Legal hold procedures
```

#### bus-015 - Strategic Planning Offsite Agenda
- Placeholders: `1-3-5 YEARS, COMPANY NAME, MAIN ISSUE, NUMBER AND ROLES, STAGE`
- Prompt:

```text
Design a 2-day strategic planning offsite agenda for [COMPANY NAME].

Context:
- Attendees: [NUMBER AND ROLES]
- Company stage: [STAGE]
- Key challenge: [MAIN ISSUE]
- Planning horizon: [1-3-5 YEARS]

Day 1: Assessment & Vision

Morning Session (4 hours)
- Opening and context setting
- External environment analysis
- Competitive landscape review
- Customer insights presentation
- Breakout: Market opportunities

Afternoon Session (4 hours)
- Internal capabilities assessment
- Financial review and runway
- Team and culture check-in
- Breakout: Strengths to leverage

Evening
- Team dinner with vision discussion

Day 2: Strategy & Planning

Morning Session (4 hours)
- Vision and mission refinement
- Strategic priorities identification
- Trade-off discussions
- Breakout: Initiative brainstorm

Afternoon Session (4 hours)
- Initiative prioritization
- Resource allocation
- 90-day action planning
- Accountability assignments
- Closing and commitments

Include: Facilitation notes, materials needed, pre-work assignments.
```

#### bus-016 - Unit Economics Calculator
- Placeholders: `AMOUNT, BUSINESS MODEL TYPE, BUSINESS NAME, COGS, MONTHS/YEARS, NUMBER, PERCENTAGE, PRICE`
- Prompt:

```text
Calculate and analyze unit economics for [BUSINESS NAME], a [BUSINESS MODEL TYPE] business.

Input data:
- Average selling price: [PRICE]
- Cost of goods sold: [COGS]
- Customer acquisition cost breakdown:
  - Marketing spend: [AMOUNT]
  - Sales cost: [AMOUNT]
  - Customers acquired: [NUMBER]
- Average customer lifespan: [MONTHS/YEARS]
- Monthly churn rate: [PERCENTAGE]
- Gross margin: [PERCENTAGE]

Calculate and explain:

1. Core Metrics
- Customer Acquisition Cost (CAC)
- Lifetime Value (LTV)
- LTV:CAC Ratio
- Payback Period
- Gross Margin per Customer

2. Cohort Analysis Framework
- Month 1-12 retention curve
- Revenue per cohort
- Net revenue retention

3. Sensitivity Analysis
- Impact of improving retention by 10%
- Impact of reducing CAC by 20%
- Impact of increasing ARPU by 15%

4. Benchmarking
- Compare to industry standards
- Identify improvement areas

5. Recommendations
- Top 3 levers to improve economics
- Target metrics to achieve profitability
```

#### bus-017 - Negotiation Strategy Prep
- Placeholders: `ASSESSMENT, BEST ALTERNATIVE, DESCRIPTION, LIST, OTHER PARTY`
- Prompt:

```text
Prepare a negotiation strategy for [NEGOTIATION TYPE - contract, acquisition, partnership, salary] with [OTHER PARTY].

Context:
- Our position: [DESCRIPTION]
- Their likely position: [ASSESSMENT]
- Key issues: [LIST]
- Our BATNA: [BEST ALTERNATIVE]

Develop:

1. Pre-Negotiation Analysis
- Their interests and motivations
- Their constraints and pressures
- Decision-maker mapping
- Power dynamics assessment

2. Our Objectives
- Must-haves (non-negotiable)
- Nice-to-haves (tradeable)
- Walk-away points
- Ideal outcome

3. Strategy
- Opening position
- Concession strategy
- Value creation opportunities
- Anchor points

4. Tactics
- Questions to ask
- Information to share/withhold
- Silence and timing plays
- Deadlock breakers

5. Scenarios
- If they open with X, we respond...
- If they push back on Y, we...
- If negotiations stall, we...

6. Team Roles
- Lead negotiator
- Technical expert
- Observer/note-taker
- Good cop/bad cop (if applicable)
```

#### bus-018 - Vendor Selection Matrix
- Placeholders: `COMPANY NAME, LIST, MAIN REQUIREMENT, RANGE, VENDOR 1, VENDOR 2, VENDOR 3, VENDOR 4, VENDOR TYPE, WHEN NEEDED`
- Prompt:

```text
Create a vendor selection matrix for choosing a [VENDOR TYPE] for [COMPANY NAME].

Requirements:
- Primary need: [MAIN REQUIREMENT]
- Budget range: [RANGE]
- Timeline: [WHEN NEEDED]
- Must-have features: [LIST]

Vendors to evaluate:
1. [VENDOR 1]
2. [VENDOR 2]
3. [VENDOR 3]
4. [VENDOR 4]

Evaluation criteria with weightings:

1. Functionality (25%)
- Feature completeness
- Customization options
- Integration capabilities

2. Cost (20%)
- Initial investment
- Ongoing costs
- Hidden fees
- ROI potential

3. Vendor Stability (15%)
- Company financials
- Customer base
- Market position

4. Support & Service (15%)
- Implementation support
- Ongoing support options
- SLA terms

5. Technical Fit (15%)
- Architecture compatibility
- Security standards
- Scalability

6. User Experience (10%)
- Ease of use
- Training requirements
- User satisfaction

Provide scoring matrix and recommendation with justification.
```

#### bus-019 - Business Model Canvas
- Placeholders: `BUSINESS NAME, INDUSTRY, PRODUCT/SERVICE, STARTUP/GROWTH/MATURE`
- Prompt:

```text
Complete a Business Model Canvas for [BUSINESS NAME].

Business overview:
- Industry: [INDUSTRY]
- Stage: [STARTUP/GROWTH/MATURE]
- Primary offering: [PRODUCT/SERVICE]

Fill out each section with 3-5 detailed points:

1. Customer Segments
- Who are we creating value for?
- Define personas with specifics

2. Value Propositions
- What value do we deliver?
- Which problems do we solve?

3. Channels
- How do we reach customers?
- Which channels work best?

4. Customer Relationships
- What type of relationship?
- How do we maintain them?

5. Revenue Streams
- How do we make money?
- What are customers paying for?

6. Key Resources
- What do we need to deliver value?
- Physical, intellectual, human, financial?

7. Key Activities
- What must we do well?
- Production, problem-solving, platform?

8. Key Partnerships
- Who are our key partners?
- What do we get from them?

9. Cost Structure
- Major cost drivers?
- Fixed vs. variable costs?

Format as a visual canvas with clear sections.
```

#### bus-020 - Go-to-Market Strategy
- Placeholders: `DESCRIPTION, ICP, PRICE, PRODUCT/SERVICE, TIMEFRAME, USP`
- Prompt:

```text
Develop a comprehensive go-to-market strategy for [PRODUCT/SERVICE] launching in [TIMEFRAME].

Product details:
- What it does: [DESCRIPTION]
- Target customer: [ICP]
- Price point: [PRICE]
- Key differentiator: [USP]

Create a GTM plan covering:

1. Market Analysis
- Market size and opportunity
- Competitive landscape
- Timing considerations

2. Target Audience
- Primary segment (detailed persona)
- Secondary segments
- Early adopter profile

3. Positioning & Messaging
- Positioning statement
- Key messages by audience
- Objection handling

4. Channel Strategy
- Primary acquisition channels
- Channel-specific tactics
- Partner/distribution strategy

5. Launch Plan
- Pre-launch activities (4 weeks)
- Launch week activities
- Post-launch optimization

6. Sales Strategy
- Sales process and cycle
- Pricing and packaging
- Sales enablement needs

7. Success Metrics
- 30/60/90 day goals
- Leading indicators
- Tracking and reporting

8. Budget Allocation
- By channel/activity
- Expected ROI
```

#### bus-021 - Merger Integration Playbook
- Placeholders: `ACQUIRING COMPANY, AMOUNT, FULL/PARTIAL/BOLT-ON, FUNCTIONS, GOALS, TARGET COMPANY`
- Prompt:

```text
Create a 100-day merger integration playbook for [ACQUIRING COMPANY] acquiring [TARGET COMPANY].

Deal context:
- Deal size: [AMOUNT]
- Integration type: [FULL/PARTIAL/BOLT-ON]
- Overlap areas: [FUNCTIONS]
- Synergy targets: [GOALS]

Phase 1: Days 1-30 (Foundation)
- Day 1 activities and communications
- Integration team formation
- Quick wins identification
- Cultural assessment
- Retention planning for key talent

Phase 2: Days 31-60 (Alignment)
- Organizational structure decisions
- Systems and process mapping
- Customer communication plan
- Vendor relationship review
- Brand and go-forward strategy

Phase 3: Days 61-100 (Execution)
- Functional integration milestones
- Technology consolidation plan
- Synergy tracking and realization
- Change management activities
- Performance monitoring

For each phase include:
- Key decisions and decision-makers
- Communication cadence
- Risk mitigation strategies
- Success metrics
- Escalation procedures
```

#### bus-022 - Pricing Strategy Optimizer
- Placeholders: `COSTS, INSIGHTS, MARKET, PRICE, PRODUCT/SERVICE, RANGE`
- Prompt:

```text
Develop an optimized pricing strategy for [PRODUCT/SERVICE] in [MARKET].

Current situation:
- Current price: [PRICE]
- Cost structure: [COSTS]
- Competitor pricing: [RANGE]
- Customer feedback: [INSIGHTS]

Analyze and recommend:

1. Pricing Model Options
- One-time vs. recurring
- Per-user vs. per-use
- Tiered vs. flat rate
- Freemium considerations

2. Value-Based Analysis
- Customer value drivers
- Willingness to pay research framework
- Value quantification methods

3. Competitive Positioning
- Price position map
- Premium vs. value strategy
- Differentiation justification

4. Tier Structure
- Recommended tiers (3-4)
- Features per tier
- Price points with rationale
- Upgrade incentives

5. Discount Strategy
- Annual vs. monthly incentive
- Volume discounts
- Promotional pricing
- Enterprise negotiation bands

6. Implementation Plan
- Rollout approach
- Grandfather policy
- Communication strategy
- Testing methodology

Include projected revenue impact of recommendations.
```

#### bus-023 - Customer Advisory Board Setup
- Placeholders: `COMPANY NAME, NUMBER, OBJECTIVES, PRODUCT TYPE`
- Prompt:

```text
Design a Customer Advisory Board (CAB) program for [COMPANY NAME].

Company context:
- Customer base: [NUMBER] customers
- Product: [PRODUCT TYPE]
- Goals for CAB: [OBJECTIVES]

Create:

1. CAB Structure
- Ideal size (recommend 8-12)
- Customer segment mix
- Term length and rotation
- Meeting frequency

2. Member Selection Criteria
- Customer profile requirements
- Engagement level needed
- Diversity considerations
- Red flags to avoid

3. Invitation Process
- Outreach messaging
- Value proposition for members
- Commitment expectations
- Onboarding process

4. Meeting Format
- Agenda template
- Facilitation approach
- Feedback collection methods
- Follow-up process

5. Member Benefits
- Early access to features
- Executive access
- Networking opportunities
- Recognition programs

6. Program Management
- Success metrics
- Executive sponsor role
- Program manager responsibilities
- Annual program review

7. First Meeting Agenda
- Detailed 2-hour agenda
- Discussion topics
- Expected outcomes
```

#### bus-024 - Operational Efficiency Audit
- Placeholders: `COMPANY/DEPARTMENT, ISSUES, LIST, NUMBER, PARAMETERS`
- Prompt:

```text
Conduct an operational efficiency audit for [COMPANY/DEPARTMENT] to identify improvement opportunities.

Current state:
- Team size: [NUMBER]
- Key processes: [LIST]
- Known pain points: [ISSUES]
- Budget constraints: [PARAMETERS]

Audit framework:

1. Process Analysis
- Map current workflows
- Identify bottlenecks
- Measure cycle times
- Find redundancies

2. Resource Utilization
- Team capacity analysis
- Tool/system usage rates
- Meeting overhead assessment
- Communication efficiency

3. Cost Analysis
- Fixed vs. variable costs
- Cost per output unit
- Waste identification
- Automation opportunities

4. Quality Assessment
- Error/rework rates
- Customer satisfaction impact
- Compliance status
- Risk exposure

5. Benchmarking
- Industry standard comparisons
- Best practice gaps
- Technology lag assessment

6. Recommendations
- Quick wins (< 30 days)
- Medium-term improvements (30-90 days)
- Strategic initiatives (90+ days)
- Investment requirements
- Expected ROI

Prioritize recommendations by impact and effort.
```

#### bus-025 - Stakeholder Communication Plan
- Placeholders: `COMPANY, DESCRIPTION, DURATION, HIGH/MEDIUM/LOW, PROJECT/INITIATIVE`
- Prompt:

```text
Create a stakeholder communication plan for [PROJECT/INITIATIVE] at [COMPANY].

Project context:
- Project scope: [DESCRIPTION]
- Timeline: [DURATION]
- Impact: [WHO'S AFFECTED]
- Sensitivity level: [HIGH/MEDIUM/LOW]

Identify and plan for each stakeholder group:

1. Stakeholder Mapping
- Executive sponsors
- Project team
- Affected departments
- External partners
- Customers (if applicable)
- Board/investors (if applicable)

2. For Each Group Define:
- Information needs
- Preferred channels
- Frequency of updates
- Level of detail
- Two-way feedback mechanism

3. Communication Vehicles
- Email updates (template)
- Meetings (agenda framework)
- Dashboards/reports
- Town halls
- Slack/Teams channels

4. Key Messages by Phase
- Announcement
- Progress updates
- Milestone achievements
- Issue escalation
- Completion/transition

5. Escalation Protocol
- Issue categories
- Escalation paths
- Response timeframes
- Decision authorities

6. Success Metrics
- Engagement measures
- Feedback quality
- Issue resolution time
```

#### bus-026 - Annual Budget Builder
- Placeholders: `AMOUNT, COMPANY/DEPARTMENT, LIST, PERCENTAGE, YEAR`
- Prompt:

```text
Create an annual budget for [COMPANY/DEPARTMENT] for fiscal year [YEAR].

Context:
- Previous year revenue: [AMOUNT]
- Previous year expenses: [AMOUNT]
- Growth target: [PERCENTAGE]
- Key initiatives planned: [LIST]

Build budget covering:

1. Revenue Forecast
- By product/service line
- By customer segment
- By geography (if applicable)
- Monthly breakdown
- Assumptions documented

2. Cost of Goods Sold
- Direct costs by category
- Variable cost calculations
- Margin targets

3. Operating Expenses

a) People Costs
- Current headcount costs
- Planned hires by quarter
- Benefits and taxes
- Contractors/consultants

b) Technology & Tools
- Software subscriptions
- Infrastructure costs
- New tool investments

c) Marketing & Sales
- Channel-specific budgets
- Events and sponsorships
- Sales tools and enablement

d) G&A
- Facilities
- Legal and professional
- Insurance
- Travel and entertainment

4. Capital Expenditures
- Equipment
- Leasehold improvements

5. Summary
- P&L projection
- Cash flow impact
- Key metrics and ratios
- Quarterly review triggers
```

#### bus-027 - Risk Assessment Framework
- Placeholders: `COMPANY/PROJECT, GOALS, INDUSTRY, PERIOD, STAGE`
- Prompt:

```text
Develop a comprehensive risk assessment for [COMPANY/PROJECT].

Context:
- Industry: [INDUSTRY]
- Stage: [STAGE]
- Time horizon: [PERIOD]
- Key objectives: [GOALS]

Assess risks across categories:

1. Strategic Risks
- Market changes
- Competitive threats
- Technology disruption
- Business model viability

2. Operational Risks
- Process failures
- Supply chain issues
- Technology outages
- Quality problems

3. Financial Risks
- Cash flow
- Credit/collection
- Currency exposure
- Funding availability

4. Compliance Risks
- Regulatory changes
- Legal exposure
- Data privacy
- Industry standards

5. People Risks
- Key person dependency
- Talent acquisition
- Culture issues
- Safety concerns

For each identified risk:
- Likelihood (1-5)
- Impact (1-5)
- Risk score
- Current controls
- Recommended mitigations
- Owner assignment
- Monitoring frequency

Include risk heat map and top 10 priority list.
```

#### bus-028 - Customer Retention Strategy
- Placeholders: `AMOUNT, B2B/B2C/HYBRID, COMPANY, DESCRIPTION, IF KNOWN, PERCENTAGE`
- Prompt:

```text
Develop a customer retention strategy for [COMPANY] with current churn rate of [PERCENTAGE].

Business context:
- Customer type: [B2B/B2C/HYBRID]
- Average customer value: [AMOUNT]
- Primary churn reasons: [IF KNOWN]
- Current retention efforts: [DESCRIPTION]

Create a comprehensive plan:

1. Churn Analysis Framework
- Data needed to analyze
- Cohort analysis approach
- Leading indicators to track
- At-risk identification criteria

2. Retention Segments
- New customers (0-90 days)
- Growing customers
- Stable customers
- At-risk customers
- Win-back targets

3. Retention Tactics by Segment

Onboarding Phase:
- First 7-day experience
- 30-day milestones
- Success metrics

Growth Phase:
- Expansion opportunities
- Engagement programs
- Value reinforcement

At-Risk Intervention:
- Trigger identification
- Outreach playbook
- Save offers and limits

4. Loyalty Program Design
- Program structure
- Reward mechanics
- Tier benefits

5. Measurement
- Retention KPIs
- Tracking dashboard
- Review cadence

6. Team and Resources
- Roles needed
- Tools required
- Budget allocation
```

#### bus-029 - Internationalization Roadmap
- Placeholders: `AMOUNT, COMPANY, COUNTRY, DESCRIPTION, NONE/SOME/EXTENSIVE`
- Prompt:

```text
Create an international expansion roadmap for [COMPANY] planning to enter [TARGET MARKET(S)].

Current state:
- Home market: [COUNTRY]
- Annual revenue: [AMOUNT]
- Product/service: [DESCRIPTION]
- International experience: [NONE/SOME/EXTENSIVE]

Develop expansion plan:

1. Market Prioritization
- Selection criteria
- Market scoring matrix
- Recommended sequence
- Timeline by market

2. Entry Strategy Options
- Direct entry (subsidiary)
- Partnership/JV
- Distributor model
- Licensing
- Acquisition

Recommendation with pros/cons.

3. Localization Requirements
- Product adaptations
- Pricing strategy
- Marketing localization
- Support coverage
- Legal/compliance

4. Operational Setup
- Entity structure
- Banking and payments
- Tax considerations
- HR and hiring
- Office/presence

5. Go-to-Market Plan
- Launch strategy
- Channel approach
- Marketing investment
- Sales model

6. Financial Model
- Investment required
- Revenue projections
- Break-even timeline
- Risk factors

7. Success Metrics
- 6/12/24 month targets
- Go/no-go criteria
- Review triggers
```

#### bus-030 - Digital Transformation Roadmap
- Placeholders: `COMPANY, INDUSTRY, LIST, LOW/MEDIUM/HIGH, MONTHS/YEARS, RANGE`
- Prompt:

```text
Create a digital transformation roadmap for [COMPANY] in [INDUSTRY].

Current state:
- Digital maturity: [LOW/MEDIUM/HIGH]
- Key pain points: [LIST]
- Budget range: [RANGE]
- Timeline: [MONTHS/YEARS]

Develop transformation plan:

1. Current State Assessment
- Technology landscape
- Process digitization level
- Data infrastructure
- Digital capabilities gap
- Cultural readiness

2. Vision and Objectives
- Target state description
- Strategic objectives
- Success metrics
- Business outcomes expected

3. Transformation Pillars

a) Customer Experience
- Digital touchpoints
- Omnichannel strategy
- Personalization capabilities

b) Operations
- Process automation
- Workflow digitization
- Supply chain modernization

c) Data & Analytics
- Data platform strategy
- Analytics capabilities
- AI/ML opportunities

d) Technology Infrastructure
- Cloud migration
- System integration
- Security enhancement

e) People & Culture
- Skills development
- Change management
- New ways of working

4. Phased Roadmap
- Foundation (0-6 months)
- Acceleration (6-18 months)
- Optimization (18-36 months)

5. Investment and ROI
- Budget allocation
- Expected returns
- Quick wins vs. long-term

6. Governance
- Decision-making structure
- Program management
- Risk mitigation
```

#### bus-031 - Venture Capital Targeting List
- Placeholders: `AMOUNT, CITY/COUNTRY, COMPANY, INDUSTRY, KEY METRICS, NOTABLE POINTS, STAGE, TYPE`
- Prompt:

```text
Create a targeted VC outreach list for [COMPANY] raising a [STAGE] round of [AMOUNT].

Company profile:
- Industry: [INDUSTRY]
- Business model: [TYPE]
- Traction: [KEY METRICS]
- Location: [CITY/COUNTRY]
- Team background: [NOTABLE POINTS]

Develop:

1. Investment Criteria Matching
- Stage alignment
- Sector focus
- Check size fit
- Geographic preference
- Lead vs. follow

2. Tier 1 Targets (Best Fit)
- 10 funds with rationale
- Relevant portfolio companies
- Partner to approach
- Connection paths

3. Tier 2 Targets (Good Fit)
- 15 funds with rationale
- Why they might be interested
- Approach strategy

4. Tier 3 Targets (Stretch)
- 10 funds worth trying
- What would make them interested

5. Outreach Strategy
- Warm intro sources
- Cold outreach templates
- Timing considerations
- Follow-up cadence

6. Research Template
- For each fund, gather:
  - Recent investments
  - Investment thesis
  - Partner backgrounds
  - Portfolio company feedback
  - Decision timeline

7. Tracking System
- CRM setup
- Stage definitions
- Update cadence
```

#### bus-032 - Supply Chain Optimization
- Placeholders: `COMPANY, DESCRIPTION, IN-HOUSE/OUTSOURCED, ISSUES, NUMBER, PRODUCT TYPE`
- Prompt:

```text
Analyze and optimize the supply chain for [COMPANY] producing/selling [PRODUCT TYPE].

Current state:
- Suppliers: [NUMBER]
- Manufacturing: [IN-HOUSE/OUTSOURCED]
- Distribution: [DESCRIPTION]
- Key challenges: [ISSUES]

Analyze and recommend:

1. Current State Mapping
- End-to-end flow visualization
- Lead times by stage
- Cost breakdown by activity
- Quality control points
- Risk exposure areas

2. Supplier Analysis
- Vendor performance metrics
- Concentration risk assessment
- Cost comparison
- Alternative sourcing options
- Negotiation opportunities

3. Inventory Optimization
- Current inventory levels and turns
- Safety stock calculations
- Demand forecasting improvement
- SKU rationalization

4. Logistics Efficiency
- Transportation cost analysis
- Route optimization
- Warehouse utilization
- Last-mile considerations

5. Technology Enablement
- Visibility and tracking
- Automation opportunities
- Integration requirements
- Analytics capabilities

6. Risk Mitigation
- Single points of failure
- Geographic diversification
- Buffer strategies
- Contingency plans

7. Implementation Roadmap
- Quick wins
- Medium-term initiatives
- Strategic investments
- Expected savings/improvements
```

#### bus-033 - Employee Stock Option Plan
- Placeholders: `AMOUNT, COMPANY, NUMBER, STAGE`
- Prompt:

```text
Design an Employee Stock Option Plan (ESOP) for [COMPANY] at [STAGE] stage.

Company details:
- Current valuation: [AMOUNT]
- Total shares: [NUMBER]
- Employees: [NUMBER]
- Funding stage: [STAGE]

Create comprehensive ESOP:

1. Pool Size and Structure
- Recommended option pool (%)
- Authorized shares allocation
- Refresh pool considerations

2. Eligibility and Allocation
- Who's eligible
- Allocation by level:
  - Executives
  - Directors
  - Managers
  - Individual contributors
- New hire grant guidelines

3. Vesting Terms
- Vesting schedule (4-year with 1-year cliff typical)
- Acceleration triggers
- Termination provisions
- Change of control provisions

4. Exercise Terms
- Option type (ISO vs. NSO)
- Strike price methodology
- Exercise windows
- Early exercise provisions
- Post-termination exercise period

5. Administration
- Plan documentation needed
- Board approval process
- 409A valuation requirements
- Cap table management
- Employee communications

6. Tax Considerations
- Employee tax implications
- Company deductions
- International considerations

7. Communication Template
- Offer letter language
- Employee education materials
- FAQ document
```

#### bus-034 - Quality Management System
- Placeholders: `COMPANY, DESCRIPTION, IF ANY, INDUSTRY, ISO 9001/OTHER, LIST`
- Prompt:

```text
Design a Quality Management System (QMS) for [COMPANY] in [INDUSTRY].

Context:
- Product/service: [DESCRIPTION]
- Regulatory requirements: [IF ANY]
- Current quality issues: [LIST]
- Certification goals: [ISO 9001/OTHER]

Develop QMS framework:

1. Quality Policy
- Mission statement
- Quality objectives
- Management commitment

2. Process Documentation
- Core process map
- Standard operating procedures
- Work instructions
- Forms and templates

3. Quality Control
- Inspection points
- Acceptance criteria
- Testing protocols
- Sampling methodology

4. Quality Assurance
- Internal audit program
- Management review process
- Corrective action procedures
- Preventive action system

5. Document Control
- Numbering system
- Version control
- Approval workflows
- Distribution management

6. Training Program
- Competency requirements
- Training matrix
- Record keeping

7. Performance Metrics
- Key quality indicators
- Target setting
- Reporting dashboards
- Trend analysis

8. Continuous Improvement
- Improvement methodology
- Employee suggestion system
- Root cause analysis tools

9. Implementation Timeline
- Phase 1: Documentation
- Phase 2: Implementation
- Phase 3: Audit and certification
```

#### bus-035 - Revenue Operations Alignment
- Placeholders: `COMPANY, ISSUES, LIST, NUMBER`
- Prompt:

```text
Design a Revenue Operations (RevOps) framework to align [COMPANY]'s go-to-market teams.

Current state:
- Sales team size: [NUMBER]
- Marketing team size: [NUMBER]
- Customer success team: [NUMBER]
- Current tools: [LIST]
- Pain points: [ISSUES]

Create RevOps blueprint:

1. Team Alignment
- Unified revenue funnel definition
- Shared metrics and goals
- Handoff processes
- Communication protocols

2. Process Standardization
- Lead management workflow
- Opportunity stages
- Customer lifecycle stages
- Escalation procedures

3. Technology Stack
- CRM optimization
- Marketing automation
- Sales engagement tools
- Customer success platform
- Integration architecture

4. Data Management
- Single source of truth
- Data hygiene standards
- Enrichment strategy
- Reporting hierarchy

5. Performance Metrics
- Funnel metrics by stage
- Velocity metrics
- Efficiency metrics
- Leading indicators

6. Reporting and Analytics
- Executive dashboard
- Team-specific views
- Forecasting methodology
- Pipeline analysis

7. Planning and Strategy
- Territory design
- Quota setting
- Capacity planning
- Compensation alignment

8. Implementation Roadmap
- Priority initiatives
- Resource requirements
- Timeline
- Success metrics
```

#### bus-036 - Sustainability Strategy
- Placeholders: `COMPANY, DESCRIPTION, EMPLOYEES, IF ANY, INDUSTRY, LOCATIONS`
- Prompt:

```text
Develop a corporate sustainability strategy for [COMPANY] in [INDUSTRY].

Current state:
- Company size: [EMPLOYEES]
- Geographic footprint: [LOCATIONS]
- Key stakeholder expectations: [DESCRIPTION]
- Current initiatives: [IF ANY]

Create comprehensive strategy:

1. Materiality Assessment
- Stakeholder identification
- Issue prioritization
- Impact vs. importance matrix

2. Environmental Initiatives
- Carbon footprint measurement
- Reduction targets and timeline
- Energy efficiency measures
- Waste reduction programs
- Sustainable sourcing

3. Social Responsibility
- Employee wellbeing
- Diversity and inclusion
- Community engagement
- Supply chain labor practices

4. Governance
- Board oversight
- Ethics and compliance
- Transparency commitments
- Stakeholder engagement

5. Goal Setting
- Short-term targets (1-2 years)
- Medium-term goals (3-5 years)
- Long-term vision (2030/2050)
- Science-based targets alignment

6. Reporting Framework
- Standards to follow (GRI, SASB, etc.)
- Metrics and KPIs
- Reporting cadence
- Verification approach

7. Implementation Plan
- Priority initiatives
- Resource allocation
- Change management
- Quick wins vs. long-term

8. Communication Strategy
- Internal engagement
- External reporting
- Brand integration
```

#### bus-037 - Customer Segmentation Model
- Placeholders: `COMPANY, DATA POINTS, DESCRIPTION, LIST, NUMBER, OBJECTIVE`
- Prompt:

```text
Develop a customer segmentation model for [COMPANY] with [NUMBER] customers.

Business context:
- Product/service: [DESCRIPTION]
- Current segments (if any): [LIST]
- Available data: [DATA POINTS]
- Segmentation goal: [OBJECTIVE]

Create segmentation framework:

1. Segmentation Approach
- Methodology selection (RFM, behavioral, needs-based, firmographic)
- Data requirements
- Analysis technique

2. Segmentation Criteria

Quantitative Factors:
- Revenue/value
- Purchase frequency
- Product usage
- Engagement level

Qualitative Factors:
- Needs and pain points
- Decision process
- Success indicators

Firmographic (B2B):
- Industry
- Company size
- Geography
- Tech stack

3. Segment Definitions
- 4-6 distinct segments
- Naming convention
- Defining characteristics
- Size and value of each

4. Segment Profiles
For each segment:
- Detailed description
- Key behaviors
- Needs and motivations
- Preferred channels
- Lifetime value
- Growth potential

5. Strategic Implications
- Prioritization framework
- Resource allocation
- Messaging strategy
- Product development
- Service levels

6. Implementation
- Tagging methodology
- System integration
- Team training
- Review cadence
```

#### bus-038 - Intellectual Property Strategy
- Placeholders: `ASSESSMENT, COMPANY, DESCRIPTION, INDUSTRY, PATENTS/TRADEMARKS/ETC, REGIONS`
- Prompt:

```text
Develop an intellectual property (IP) strategy for [COMPANY] in [INDUSTRY].

Company context:
- Core technology/innovation: [DESCRIPTION]
- Current IP portfolio: [PATENTS/TRADEMARKS/ETC]
- Competitive landscape: [ASSESSMENT]
- Geographic markets: [REGIONS]

Create IP strategy:

1. IP Audit
- Existing assets inventory
- Unprotected innovations
- Third-party dependencies
- Gap analysis

2. Patent Strategy
- Innovation pipeline
- Filing priorities
- Provisional vs. utility
- Geographic coverage
- Continuation strategy
- Design patent opportunities

3. Trademark Strategy
- Brand architecture
- Registration priorities
- Geographic coverage
- Monitoring program
- Enforcement approach

4. Trade Secret Program
- Identification criteria
- Protection measures
- Employee obligations
- Partner/vendor controls

5. Copyright Considerations
- Software protection
- Content ownership
- Work-for-hire policies

6. Freedom to Operate
- Competitor landscape
- Potential blockers
- Design-around strategies
- Licensing opportunities

7. IP Monetization
- Licensing potential
- Cross-licensing opportunities
- Assertion strategy
- Valuation approach

8. Implementation Plan
- Priority filings
- Budget allocation
- Internal processes
- Outside counsel strategy
```

#### bus-039 - Remote Work Policy
- Placeholders: `COMPANY, DESCRIPTION, FULLY REMOTE/HYBRID/RETURNING, GEOGRAPHY, ISSUES, NUMBER`
- Prompt:

```text
Create a comprehensive remote/hybrid work policy for [COMPANY] with [NUMBER] employees.

Context:
- Current setup: [FULLY REMOTE/HYBRID/RETURNING]
- Locations: [GEOGRAPHY]
- Role types: [DESCRIPTION]
- Key concerns: [ISSUES]

Develop policy covering:

1. Work Arrangement Options
- Fully remote eligibility
- Hybrid schedule options
- In-office requirements
- Role-based exceptions

2. Eligibility Criteria
- Performance requirements
- Role compatibility
- Tenure considerations
- Manager approval process

3. Work Hours and Availability
- Core hours requirements
- Time zone considerations
- Response time expectations
- Meeting guidelines

4. Workspace Requirements
- Home office standards
- Equipment provision
- Ergonomic guidelines
- Security requirements
- Expense reimbursement

5. Communication Standards
- Tool usage guidelines
- Documentation expectations
- Video meeting norms
- Async communication practices

6. Performance Management
- Goal setting
- Check-in cadence
- Evaluation criteria
- Productivity measures

7. Team Collaboration
- Team meeting requirements
- Offsite/onsite gatherings
- Social connection initiatives
- New hire onboarding

8. Compliance and Legal
- Tax implications
- Workers compensation
- Employment law by location
- Data privacy requirements

9. Implementation
- Rollout timeline
- Manager training
- Employee communication
- Feedback mechanisms
```

#### bus-040 - Partner Ecosystem Strategy
- Placeholders: `COMPANY, DESCRIPTION, IF ANY, PERCENTAGE, TARGETS`
- Prompt:

```text
Design a partner ecosystem strategy for [COMPANY] to accelerate growth.

Business context:
- Product/service: [DESCRIPTION]
- Current partnerships: [IF ANY]
- Growth goals: [TARGETS]
- Partner-influenced revenue target: [PERCENTAGE]

Develop ecosystem strategy:

1. Partnership Types

a) Technology Partners
- Integration opportunities
- API strategy
- Marketplace presence

b) Channel Partners
- Reseller program
- Referral program
- Affiliate program

c) Strategic Partners
- Co-selling opportunities
- Co-marketing programs
- Joint solutions

d) Service Partners
- Implementation partners
- Consulting partners
- Managed service providers

2. Partner Program Structure
- Tier definitions
- Requirements per tier
- Benefits per tier
- Progression criteria

3. Economic Model
- Revenue sharing
- Referral fees
- Marketing development funds
- Incentive structures

4. Enablement Program
- Partner onboarding
- Training and certification
- Sales enablement
- Marketing resources
- Deal registration

5. Partner Management
- Recruitment strategy
- Partner success metrics
- QBR structure
- Conflict resolution

6. Technology Infrastructure
- Partner portal
- Deal tracking
- Resource library
- Communication tools

7. Launch Plan
- MVP program elements
- Pilot partners
- Timeline
- Success metrics
```

#### bus-041 - Scenario Planning Exercise
- Placeholders: `COMPANY, DESCRIPTION, FACTORS, INDUSTRY, MAIN QUESTION, X`
- Prompt:

```text
Conduct a strategic scenario planning exercise for [COMPANY] looking [X] years ahead.

Context:
- Industry: [INDUSTRY]
- Current position: [DESCRIPTION]
- Key uncertainties: [FACTORS]
- Strategic question: [MAIN QUESTION]

Develop scenarios:

1. Uncertainty Identification
- List top 10 uncertainties
- Rate by impact and unpredictability
- Select top 2 drivers for scenario axes

2. Scenario Framework
- 2x2 matrix with chosen drivers
- Name each quadrant
- Describe each scenario world

3. Scenario Narratives
For each of 4 scenarios:
- Detailed description of the world
- How it evolved from today
- Key characteristics
- Winners and losers
- Signals it's emerging

4. Strategic Implications
For each scenario:
- Threats to current strategy
- Opportunities created
- Capabilities needed
- Investment priorities

5. Robust Strategies
- Actions that work across all scenarios
- Hedging strategies
- Options to create
- Decisions to delay

6. Early Warning System
- Indicators to monitor
- Trigger points
- Review cadence
- Response protocols

7. Action Plan
- Immediate actions (next 90 days)
- Contingency preparations
- Capability building
- Monitoring responsibilities
```

#### bus-042 - Customer Onboarding Optimization
- Placeholders: `COMPANY, CURRENT DURATION, IF KNOWN, PERCENTAGE, PRODUCT/SERVICE, TEAM SIZE`
- Prompt:

```text
Optimize the customer onboarding process for [COMPANY]'s [PRODUCT/SERVICE].

Current state:
- Time to value: [CURRENT DURATION]
- Onboarding completion rate: [PERCENTAGE]
- Key drop-off points: [IF KNOWN]
- Resources available: [TEAM SIZE]

Develop optimized onboarding:

1. Journey Mapping
- Current state journey
- Pain points identification
- Moment of first value
- Success milestones

2. Onboarding Phases

Phase 1: Welcome (Day 1)
- Account setup
- Welcome communications
- Expectation setting
- Quick win achievement

Phase 2: Activation (Days 2-7)
- Core feature adoption
- Initial configuration
- First success milestone
- Check-in touchpoint

Phase 3: Engagement (Days 8-30)
- Advanced features
- Integration setup
- Team expansion
- Success review

Phase 4: Adoption (Days 31-90)
- Full utilization
- Best practices
- ROI demonstration
- Expansion discussion

3. Touchpoint Strategy
- Human vs. automated
- Channel selection
- Timing optimization
- Personalization approach

4. Content and Resources
- Welcome kit
- Tutorial videos
- Documentation
- Templates and examples
- Community access

5. Success Metrics
- Leading indicators
- Health score components
- Intervention triggers

6. Implementation Plan
- Tool requirements
- Team training
- Timeline
- A/B testing approach
```

#### bus-043 - M&A Target Identification
- Placeholders: `AMOUNT, COMPANY, INDUSTRY, RANGE, REGIONS, STRATEGIC OBJECTIVE`
- Prompt:

```text
Identify potential M&A targets for [COMPANY] pursuing [STRATEGIC OBJECTIVE].

Acquirer profile:
- Industry: [INDUSTRY]
- Revenue: [AMOUNT]
- Acquisition budget: [RANGE]
- Geographic focus: [REGIONS]

Develop target list:

1. Acquisition Criteria

Strategic Fit:
- Business model alignment
- Product/technology fit
- Customer overlap/expansion
- Geographic presence

Financial Criteria:
- Revenue range
- Growth rate
- Profitability
- Valuation expectations

Operational Criteria:
- Team quality
- Technology stack
- Customer base quality
- Integration complexity

2. Target Categories

a) Technology Acquisitions
- Capabilities to acquire
- Build vs. buy analysis
- IP value

b) Market Expansion
- New segments
- Geographic expansion
- Customer base acquisition

c) Talent Acquisitions
- Key expertise areas
- Team retention potential
- Cultural fit

3. Target Profiles
For top 10 targets:
- Company overview
- Strategic rationale
- Estimated valuation
- Key risks
- Synergy potential
- Deal complexity

4. Approach Strategy
- Outreach methodology
- Relationship building
- Timing considerations
- Advisor needs

5. Prioritization Matrix
- Scoring criteria
- Weighted ranking
- Action recommendations
```

#### bus-044 - Key Account Management Plan
- Placeholders: `ACCOUNT NAME, AMOUNT, DETAILS, LIST, YEARS, YOUR COMPANY`
- Prompt:

```text
Create a key account management plan for [ACCOUNT NAME], a strategic customer of [YOUR COMPANY].

Account overview:
- Annual revenue: [AMOUNT]
- Contract status: [DETAILS]
- Products used: [LIST]
- Relationship tenure: [YEARS]

Develop comprehensive plan:

1. Account Analysis
- Organization structure
- Decision-making process
- Budget and fiscal year
- Strategic priorities
- Competitive presence

2. Relationship Mapping
- Key stakeholders
  - Champion
  - Economic buyer
  - Technical evaluator
  - End users
- Relationship strength (1-5)
- Engagement history
- Risk assessment

3. Value Assessment
- Current value delivered
- ROI documentation
- Success stories
- Areas for improvement

4. Growth Strategy
- Expansion opportunities
- Cross-sell targets
- Upsell potential
- Timeline for each

5. Retention Strategy
- Renewal timeline
- Risk factors
- Competitive threats
- Mitigation plan

6. Engagement Plan
- Executive sponsorship
- QBR schedule
- Day-to-day touchpoints
- Special events/recognition

7. Success Metrics
- Health score components
- Usage targets
- NPS goals
- Revenue targets

8. Action Plan
- 30-day priorities
- 90-day milestones
- Annual objectives
- Resources needed
```

#### bus-045 - SaaS Metrics Dashboard
- Placeholders: `AMOUNT, COMPANY, DESCRIPTION, NUMBER, STAGE, TYPE`
- Prompt:

```text
Design a SaaS metrics dashboard for [COMPANY] at [STAGE] stage.

Business context:
- ARR: [AMOUNT]
- Customer count: [NUMBER]
- Pricing model: [TYPE]
- Current reporting: [DESCRIPTION]

Create dashboard framework:

1. Revenue Metrics
- MRR/ARR and growth rate
- Net new ARR breakdown
- Expansion revenue
- Churned revenue
- Net revenue retention

2. Customer Metrics
- Total customers
- New customers (cohorted)
- Churned customers
- Logo retention rate
- Customer concentration

3. Unit Economics
- CAC by channel
- LTV:CAC ratio
- Payback period
- Gross margin
- Customer profitability

4. Growth Efficiency
- Magic number
- Burn multiple
- Rule of 40
- CAC payback
- Sales efficiency

5. Engagement Metrics
- DAU/WAU/MAU
- Feature adoption
- Login frequency
- Health scores

6. Pipeline Metrics
- Pipeline coverage
- Stage conversion rates
- Sales cycle length
- Win rate

7. Dashboard Structure
- Executive summary view
- Functional deep-dives
- Trend analysis
- Cohort views

8. Implementation
- Data sources
- Tool recommendations
- Update frequency
- Alert thresholds
```

#### bus-046 - Product Portfolio Analysis
- Placeholders: `AMOUNT, COMPANY, LIST, NUMBER, PRIORITIES, REGIONS`
- Prompt:

```text
Conduct a product portfolio analysis for [COMPANY] with [NUMBER] products/SKUs.

Portfolio overview:
- Product categories: [LIST]
- Total revenue: [AMOUNT]
- Key markets: [REGIONS]
- Strategic focus: [PRIORITIES]

Analysis framework:

1. Revenue Analysis
- Revenue by product
- Growth rates
- Profitability by product
- Trend over 3 years

2. BCG Matrix Placement
- Stars (high growth, high share)
- Cash Cows (low growth, high share)
- Question Marks (high growth, low share)
- Dogs (low growth, low share)

3. Product Lifecycle Analysis
- Introduction stage products
- Growth stage products
- Maturity stage products
- Decline stage products

4. Strategic Fit Assessment
- Alignment with company direction
- Synergies between products
- Resource requirements
- Competitive position

5. Customer Analysis
- Products by customer segment
- Cross-sell patterns
- Bundling opportunities
- Cannibalization risks

6. Portfolio Optimization
- Investment priorities
- Products to accelerate
- Products to maintain
- Products to sunset
- New product gaps

7. Recommendations
- Portfolio rebalancing
- Resource reallocation
- M&A opportunities
- Innovation priorities

8. Implementation Roadmap
- Priority actions
- Timeline
- Success metrics
```

#### bus-047 - Conflict Resolution Framework
- Placeholders: `ASSESSMENT, COMPANY, DESCRIPTION, IF ANY, SITUATION TYPE, TYPE`
- Prompt:

```text
Create a conflict resolution framework for [SITUATION TYPE] at [COMPANY].

Context:
- Parties involved: [DESCRIPTION]
- Nature of conflict: [TYPE]
- Business impact: [ASSESSMENT]
- Previous attempts: [IF ANY]

Develop resolution approach:

1. Situation Analysis
- Root cause identification
- Stakeholder perspectives
- Impact assessment
- Urgency level

2. Resolution Approach Selection
- Collaboration (win-win)
- Compromise (split)
- Accommodation (yield)
- Competition (assert)
- Avoidance (delay)

Recommendation with rationale.

3. Preparation Phase
- Information gathering
- Ground rules establishment
- Neutral space selection
- Timing considerations

4. Resolution Process

Step 1: Opening
- Set constructive tone
- Establish shared goals
- Confirm commitment

Step 2: Understanding
- Each party shares perspective
- Active listening protocols
- Clarifying questions
- Common ground identification

Step 3: Problem-Solving
- Issue prioritization
- Option generation
- Evaluation criteria
- Agreement building

Step 4: Commitment
- Action items
- Accountability
- Follow-up schedule
- Escalation path

5. Documentation
- Agreement summary
- Next steps
- Success metrics
- Review date

6. Follow-Up Plan
- Check-in schedule
- Progress monitoring
- Relationship rebuilding
```

#### bus-048 - Business Continuity Plan
- Placeholders: `COMPANY, DESCRIPTION, INDUSTRY, LIST, NUMBER`
- Prompt:

```text
Create a Business Continuity Plan (BCP) for [COMPANY] in [INDUSTRY].

Company profile:
- Employees: [NUMBER]
- Locations: [LIST]
- Critical systems: [DESCRIPTION]
- Key dependencies: [LIST]

Develop comprehensive BCP:

1. Business Impact Analysis
- Critical business functions
- Recovery time objectives (RTO)
- Recovery point objectives (RPO)
- Maximum tolerable downtime
- Financial impact per hour/day

2. Risk Assessment
- Natural disasters
- Technology failures
- Cyber incidents
- Pandemic/health crises
- Supply chain disruption
- Key personnel loss

3. Recovery Strategies

a) Technology Recovery
- Data backup procedures
- System redundancy
- Cloud failover
- Communication systems

b) Workplace Recovery
- Alternate site options
- Remote work capabilities
- Essential equipment

c) People Recovery
- Emergency contacts
- Succession planning
- Cross-training needs
- External resources

d) Operations Recovery
- Critical vendor contacts
- Alternative suppliers
- Manual workarounds
- Customer communication

4. Plan Documentation
- Activation criteria
- Chain of command
- Communication tree
- Step-by-step procedures
- Resource inventory

5. Testing and Maintenance
- Test schedule
- Test types (tabletop, simulation)
- Update triggers
- Training requirements

6. Appendices
- Contact directories
- Checklists
- Forms
- Vendor agreements
```

#### bus-049 - Cost Reduction Analysis
- Placeholders: `AMOUNT, AMOUNT/PERCENTAGE, COMPANY/DEPARTMENT, CONTEXT, LIMITATIONS, LIST`
- Prompt:

```text
Develop a cost reduction strategy for [COMPANY/DEPARTMENT] with target savings of [AMOUNT/PERCENTAGE].

Current state:
- Total cost base: [AMOUNT]
- Major cost categories: [LIST]
- Recent changes: [CONTEXT]
- Constraints: [LIMITATIONS]

Analyze and recommend:

1. Cost Baseline
- Detailed cost breakdown
- Fixed vs. variable
- Direct vs. indirect
- Trends over 3 years
- Benchmarking to industry

2. Quick Wins (0-30 days)
- Immediate savings opportunities
- Low-risk actions
- No approval needed
- Estimated savings

3. Short-Term Initiatives (30-90 days)
- Process improvements
- Vendor renegotiations
- Resource optimization
- Approval requirements
- Implementation plan

4. Medium-Term Initiatives (90-180 days)
- Structural changes
- Technology investments
- Outsourcing opportunities
- Make vs. buy analysis

5. Strategic Initiatives (180+ days)
- Business model changes
- Major investments
- Transformational opportunities

6. Category Deep-Dives

a) People Costs
- Headcount optimization
- Contractor review
- Benefits analysis

b) Technology Costs
- License consolidation
- Cloud optimization
- Tool rationalization

c) Operations Costs
- Process automation
- Supplier consolidation
- Waste elimination

7. Implementation Roadmap
- Priority sequencing
- Resource needs
- Risk mitigation
- Tracking mechanism
```

#### bus-050 - Competitive Moat Analysis
- Placeholders: `COMPANY, DESCRIPTION, LIST, MARKET, NAMES, RANKING`
- Prompt:

```text
Analyze and strengthen the competitive moat for [COMPANY] in [MARKET].

Company overview:
- Core business: [DESCRIPTION]
- Market position: [RANKING]
- Key advantages: [LIST]
- Main competitors: [NAMES]

Analyze moat sources:

1. Current Moat Assessment

a) Network Effects
- Type (direct, indirect, data)
- Strength (1-10)
- Defensibility

b) Switching Costs
- Technical integration
- Data lock-in
- Learning curve
- Contract/relationship

c) Cost Advantages
- Scale economies
- Process efficiency
- Unique assets

d) Intangible Assets
- Brand strength
- Patents/IP
- Regulatory licenses
- Proprietary data

e) Efficient Scale
- Market size limitations
- Natural monopoly characteristics

2. Moat Sustainability
- Erosion risks
- Competitive threats
- Technology disruption
- Regulatory changes

3. Moat Strengthening Strategies

Short-term (0-12 months):
- Quick reinforcements
- Defensive moves

Medium-term (1-3 years):
- Investment priorities
- Capability building

Long-term (3+ years):
- Strategic bets
- New moat creation

4. Investment Recommendations
- Priority areas
- Resource allocation
- Success metrics
- Timeline

5. Monitoring Framework
- Moat health indicators
- Competitive signals
- Review cadence
```

#### bus-051 - Strategic Alliance Framework
- Placeholders: `DESCRIPTION, DURATION, OBJECTIVE, PARTNER NAME`
- Prompt:

```text
Design a strategic alliance with [PARTNER NAME] for [OBJECTIVE].

Context:
- Your company: [DESCRIPTION]
- Partner company: [DESCRIPTION]
- Alliance goal: [OBJECTIVE]
- Time horizon: [DURATION]

Develop alliance framework:

1. Strategic Rationale
- Why this partner
- Mutual benefits
- Market opportunity
- Competitive advantage

2. Alliance Scope
- In-scope activities
- Out-of-scope activities
- Geographic coverage
- Duration and milestones

3. Contribution Model

Your Contributions:
- Resources committed
- Capabilities provided
- Investment level
- IP/assets shared

Partner Contributions:
- Resources committed
- Capabilities provided
- Investment level
- IP/assets shared

4. Value Sharing
- Revenue allocation
- Cost sharing
- IP ownership
- Customer ownership

5. Governance Structure
- Steering committee
- Operating committee
- Decision rights
- Escalation process

6. Operating Model
- Joint team structure
- Communication cadence
- Reporting requirements
- Performance metrics

7. Risk Management
- Key risks identified
- Mitigation strategies
- Exit provisions
- Dispute resolution

8. Implementation Plan
- Phase 1: Setup
- Phase 2: Launch
- Phase 3: Scale
- Success criteria

9. Legal Framework
- Agreement structure
- Key terms
- Confidentiality
- Termination provisions
```

#### bus-052 - Turnaround Strategy
- Placeholders: `ASSESSMENT, COMPANY, CRISIS TYPE, LIST, RUNWAY`
- Prompt:

```text
Develop a turnaround strategy for [COMPANY] facing [CRISIS TYPE].

Current situation:
- Revenue trend: [DECLINING BY X%]
- Cash position: [RUNWAY]
- Key issues: [LIST]
- Stakeholder status: [ASSESSMENT]

Create turnaround plan:

1. Situation Assessment
- Root cause analysis
- Financial position deep-dive
- Stakeholder mapping
- Timeline/urgency

2. Stabilization Phase (Days 1-30)

Cash Management:
- Cash conservation measures
- Receivables acceleration
- Payables extension
- Credit line review

Quick Actions:
- Cost cuts (non-strategic)
- Revenue quick wins
- Communication plan

3. Strategic Phase (Days 31-90)

Business Assessment:
- Core vs. non-core
- Keep, fix, or exit
- Investment priorities

Operational Improvement:
- Process optimization
- Organizational restructure
- Performance management

4. Transformation Phase (Days 91-180)

Strategic Repositioning:
- Market focus
- Value proposition
- Business model refinement

Growth Restart:
- Revenue initiatives
- Customer retention
- New opportunities

5. Stakeholder Management
- Employee communication
- Customer retention
- Vendor negotiations
- Investor updates
- Board engagement

6. Monitoring and Control
- Weekly KPIs
- Cash flow forecasting
- Milestone tracking
- Contingency triggers

7. 100-Day Action Plan
- Detailed weekly actions
- Accountability assignments
- Success metrics
```

#### bus-053 - Customer Win-Back Campaign
- Placeholders: `AMOUNT, COMPANY, DESCRIPTION, LIST, NUMBER, PERCENTAGE`
- Prompt:

```text
Design a customer win-back campaign for [COMPANY] targeting churned customers.

Context:
- Product/service: [DESCRIPTION]
- Churn rate: [PERCENTAGE]
- Primary churn reasons: [LIST]
- Churned customer pool: [NUMBER]
- Average customer value: [AMOUNT]

Develop win-back strategy:

1. Segmentation
- Churned customer analysis
- Win-back likelihood scoring
- Segment prioritization:
  - High value, recent churn
  - High value, older churn
  - Medium value, winnable
  - Low priority

2. Root Cause Addressing
For each churn reason:
- What's changed since they left
- Improvement evidence
- Messaging angle

3. Offer Strategy
- Incentive structures:
  - Discount offers
  - Extended trials
  - Feature unlocks
  - Service upgrades
- Offer by segment
- ROI calculations

4. Campaign Structure

Wave 1: Outreach (Week 1-2)
- Email sequence
- Personal outreach criteria
- Messaging templates

Wave 2: Engagement (Week 3-4)
- Follow-up sequence
- Content sharing
- Soft offers

Wave 3: Conversion (Week 5-6)
- Strong offers
- Urgency creation
- Personal calls

5. Channel Strategy
- Email approach
- Phone outreach
- LinkedIn/social
- Retargeting ads

6. Success Metrics
- Response rates
- Conversion targets
- Revenue recovered
- CAC for win-backs
- Second churn rate

7. Long-Term Prevention
- Early warning system
- Intervention playbook
- Feedback integration
```

#### bus-054 - Board of Directors Recruitment
- Placeholders: `COMPANY, CURRENT MEMBERS, EVENTS, NEEDS, STAGE`
- Prompt:

```text
Create a Board of Directors recruitment plan for [COMPANY] at [STAGE].

Current board:
- Composition: [CURRENT MEMBERS]
- Gaps identified: [NEEDS]
- Company stage: [STAGE]
- Upcoming milestones: [EVENTS]

Develop recruitment plan:

1. Board Composition Strategy
- Optimal board size
- Mix of directors:
  - Investors
  - Independents
  - Executives
- Skills matrix needed
- Diversity goals

2. Gap Analysis
- Current skills/experience
- Missing capabilities
- Priority additions
- Timeline for filling

3. Director Profile
For each open seat:
- Industry experience
- Functional expertise
- Stage experience
- Network value
- Time commitment
- Compensation expectations

4. Candidate Sourcing
- Network activation
- Board placement firms
- Industry connections
- Investor recommendations
- Target companies

5. Target List
- 10-15 specific candidates
- Background summary
- Fit assessment
- Approach strategy
- Connection path

6. Evaluation Process
- Initial outreach
- Chemistry meetings
- Reference checks
- Conflict review
- Final selection

7. Onboarding Plan
- Pre-meeting materials
- Executive introductions
- Deep dives by function
- First meeting prep

8. Compensation Framework
- Cash compensation
- Equity grants
- Committee premiums
- Expense policies

9. Governance Updates
- Committee structure
- Meeting cadence
- Board materials
- Communication protocols
```

#### bus-055 - Corporate Venture Strategy
- Placeholders: `AMOUNT, AREAS, COMPANY, INDUSTRY, LIST`
- Prompt:

```text
Design a corporate venture capital (CVC) strategy for [COMPANY].

Company context:
- Industry: [INDUSTRY]
- Revenue: [AMOUNT]
- Strategic priorities: [LIST]
- Innovation gaps: [AREAS]

Develop CVC program:

1. Strategic Objectives
- Primary goals (strategic vs. financial)
- Innovation thesis
- Technology areas of interest
- Business model exploration

2. Fund Structure
- Fund size recommendation
- Investment pace
- Check size range
- Stage focus
- Geographic scope

3. Investment Thesis
- Target sectors
- Company stage preferences
- Synergy requirements
- Return expectations

4. Governance Model
- Reporting structure
- Investment committee
- Decision rights
- Conflict management
- Portfolio company access

5. Operating Model

a) Deal Sourcing
- Internal scouting
- VC relationships
- Accelerator partnerships
- Direct outreach

b) Due Diligence
- Process design
- Business unit involvement
- Technical evaluation
- Strategic fit assessment

c) Portfolio Management
- Value-add services
- BU collaboration
- Follow-on strategy
- Exit planning

6. Team Structure
- Dedicated team vs. hybrid
- Skill requirements
- Compensation model
- Reporting lines

7. Success Metrics
- Financial returns
- Strategic value
- Learnings generated
- Partnerships created

8. Implementation
- Phase 1: Setup (0-6 months)
- Phase 2: First investments (6-18 months)
- Phase 3: Scale (18+ months)
```

### 2. Marketing & Copywriting

#### mkt-001 - Facebook Ad Copy Generator
- Placeholders: `DEMOGRAPHIC, DISCOUNT/BONUS, MAIN BENEFIT, PRICE, PRODUCT NAME, PRODUCT/SERVICE`
- Prompt:

```text
Create high-converting Facebook ad copy for [PRODUCT/SERVICE].

Product details:
- Name: [PRODUCT NAME]
- Key benefit: [MAIN BENEFIT]
- Target audience: [DEMOGRAPHIC]
- Price: [PRICE]
- Offer: [DISCOUNT/BONUS]

Create 5 ad variations using these frameworks:
1. Problem-Agitate-Solution
2. Before-After-Bridge
3. Social Proof Lead
4. Curiosity Hook
5. Direct Benefit

For each ad include:
- Primary text (125 characters max for best display)
- Headline (40 characters)
- Description (30 characters)
- Call-to-action button suggestion

Optimize for [OBJECTIVE: awareness/traffic/conversions].
```

#### mkt-002 - Email Welcome Sequence
- Placeholders: `BRAND/COMPANY, DESCRIPTION, OBJECTIVE, PRODUCT/SERVICE, TONE`
- Prompt:

```text
Create a 5-email welcome sequence for new subscribers to [BRAND/COMPANY].

Business context:
- What we sell: [PRODUCT/SERVICE]
- Target customer: [DESCRIPTION]
- Brand voice: [TONE]
- Goal of sequence: [OBJECTIVE]

Email 1: Welcome (Sent immediately)
- Warm welcome
- Deliver promised lead magnet
- Set expectations
- Quick win or value

Email 2: Story (Day 2)
- Brand origin story
- Why we exist
- Connection building

Email 3: Value (Day 4)
- Educational content
- Prove expertise
- Build trust

Email 4: Social Proof (Day 6)
- Customer success stories
- Results and outcomes
- Credibility building

Email 5: Offer (Day 8)
- Introduce product/service
- Clear value proposition
- Call to action
- Urgency element

For each email provide:
- Subject line (+ 2 A/B test alternatives)
- Preview text
- Full email body
- CTA button text
```

#### mkt-003 - Landing Page Copy Framework
- Placeholders: `AMOUNT, DESCRIPTION, IF ANY, NAME, PAIN POINT, PRODUCT/SERVICE, PROFESSIONAL/CASUAL/URGENT, WHO`
- Prompt:

```text
Write conversion-focused landing page copy for [PRODUCT/SERVICE].

Product info:
- Name: [NAME]
- What it does: [DESCRIPTION]
- Target customer: [WHO]
- Main problem solved: [PAIN POINT]
- Price: [AMOUNT]
- Guarantee: [IF ANY]

Write copy for these sections:

1. Hero Section
- Headline (benefit-focused, 10 words max)
- Subheadline (expand on value)
- CTA button text
- Supporting credibility element

2. Problem Section
- Agitate pain points (3-5)
- Show understanding
- Create urgency

3. Solution Section
- Introduce product
- Key benefits (not features)
- Transformation promise

4. Features/Benefits
- 5-6 features with benefit-focused descriptions
- Icon suggestions for each

5. Social Proof
- Testimonial prompts
- Stats to highlight
- Trust badges

6. FAQ Section
- 6-8 common objections as questions
- Answers that overcome objections

7. Final CTA
- Urgency headline
- Value stack
- Risk reversal
- CTA button

Tone: [PROFESSIONAL/CASUAL/URGENT]
```

#### mkt-004 - Google Ads Copy Suite
- Placeholders: `DESCRIPTION, GEO, KEYWORDS, NAME, PRODUCT/SERVICE, URL, USP`
- Prompt:

```text
Create Google Search ads for [PRODUCT/SERVICE] targeting [KEYWORDS].

Business details:
- Company: [NAME]
- What we offer: [DESCRIPTION]
- Unique selling point: [USP]
- Target location: [GEO]
- Landing page URL: [URL]

Create for each match type:

1. Branded Campaign
- 3 responsive search ad variations
- Headlines (15 options, 30 chars each)
- Descriptions (4 options, 90 chars each)

2. Non-Branded - High Intent
- Keywords to target
- 3 ad variations
- Headlines focused on solution
- Descriptions with offers

3. Competitor Campaign
- Competitor names to target
- Differentiation-focused copy
- Comparison angles

4. Long-Tail Campaign
- Question-based keywords
- Problem-aware headlines
- Educational angle

For each ad include:
- Headlines (minimum 10 variations)
- Descriptions (minimum 4 variations)
- Sitelink suggestions (4)
- Callout extensions (6)
- Structured snippet ideas
```

#### mkt-005 - Social Media Content Calendar
- Placeholders: `BRAND, DESCRIPTION, IF ANY, INDUSTRY, LIST, PLATFORMS, TONE`
- Prompt:

```text
Create a 30-day social media content calendar for [BRAND] on [PLATFORMS].

Brand info:
- Industry: [INDUSTRY]
- Target audience: [DESCRIPTION]
- Brand voice: [TONE]
- Key products/services: [LIST]
- Campaign focus: [IF ANY]

For each day provide:
- Platform(s)
- Content type (carousel, reel, story, post)
- Topic/theme
- Caption (platform-appropriate length)
- Hashtag suggestions (10-15)
- Visual direction
- Best posting time

Content mix (per month):
- Educational posts: 8
- Entertaining posts: 6
- Promotional posts: 4
- Engagement posts: 6
- User-generated/social proof: 4
- Behind-the-scenes: 2

Include:
- Weekly themes
- Trending topic integration opportunities
- Cross-promotion strategy
- Engagement prompts
- Story ideas (if applicable)
```

#### mkt-006 - Product Launch Email Sequence
- Placeholders: `AMOUNT, DATE, NAME, NEW PRODUCT, SPECIAL DEAL, WHAT IT IS, WHO`
- Prompt:

```text
Create a product launch email sequence for [NEW PRODUCT] launching on [DATE].

Product details:
- Name: [NAME]
- Description: [WHAT IT IS]
- Price: [AMOUNT]
- Launch offer: [SPECIAL DEAL]
- Target audience: [WHO]

Pre-Launch Phase (1 week before):

Email 1: Teaser
- Build anticipation
- Hint at what's coming
- Create curiosity

Email 2: Behind the Scenes
- Why we created this
- Development story
- Problem it solves

Email 3: Early Access Announcement
- VIP list opportunity
- Exclusive benefits
- Urgency building

Launch Phase:

Email 4: Launch Day
- Product reveal
- Full details
- Launch offer
- CTA to buy

Email 5: Day 2 - Social Proof
- Early customer reactions
- Testimonials
- FAQ answers

Email 6: Day 3 - Deep Dive
- Feature spotlight
- Use cases
- Benefits expansion

Email 7: Last Chance
- Offer deadline
- Final reminder
- Scarcity element

For each email: Subject line, preview text, full copy, CTA.
```

#### mkt-007 - Brand Voice Guidelines
- Placeholders: `ADJECTIVES, BRAND NAME, DESCRIPTION, INDUSTRY`
- Prompt:

```text
Create comprehensive brand voice guidelines for [BRAND NAME].

Brand context:
- Industry: [INDUSTRY]
- Target audience: [DESCRIPTION]
- Brand personality: [ADJECTIVES]
- Competitors' voices: [DESCRIPTION]
- Differentiation goal: [HOW WE'RE DIFFERENT]

Create guidelines covering:

1. Voice Attributes
- 4-5 key characteristics
- Definition of each
- How it shows up in copy
- Do's and don'ts

2. Tone Variations
- Default tone
- When to be more formal
- When to be more casual
- Crisis/sensitive situations

3. Language Preferences
- Words we use
- Words we avoid
- Industry jargon stance
- Inclusive language guidelines

4. Grammar and Style
- Sentence length preferences
- Active vs. passive voice
- Contractions usage
- Emoji/exclamation usage
- Capitalization rules

5. Channel-Specific Guidelines
- Website copy
- Email
- Social media
- Customer support
- Advertising

6. Examples
- Before/after rewrites
- Good vs. bad examples
- Template phrases

7. Quick Reference Card
- One-page summary
- Key do's and don'ts
```

#### mkt-008 - SEO Content Brief
- Placeholders: `DESCRIPTION, INDUSTRY, OBJECTIVE, PRIMARY KEYWORD, URL`
- Prompt:

```text
Create an SEO content brief for an article targeting [PRIMARY KEYWORD].

Context:
- Website: [URL]
- Industry: [INDUSTRY]
- Target audience: [DESCRIPTION]
- Business goal: [OBJECTIVE]

Research and provide:

1. Keyword Analysis
- Primary keyword: search volume, difficulty
- Secondary keywords (5-10)
- LSI keywords (10-15)
- Questions to answer (from People Also Ask)
- Related searches

2. Search Intent
- Primary intent type
- User expectations
- Content format needed

3. Competitive Analysis
- Top 5 ranking pages
- Average word count
- Content gaps to exploit
- Unique angles available

4. Content Structure
- Recommended title (with keyword)
- Meta description (155 chars)
- H1 headline
- H2 sections outline
- H3 subsections
- Target word count

5. On-Page SEO
- Keyword placement guidelines
- Internal linking opportunities
- External source suggestions
- Image alt text themes
- Schema markup type

6. Content Requirements
- Must-cover topics
- Statistics to include
- Examples needed
- Expert quotes to seek
- Visuals to create

7. Success Metrics
- Target ranking position
- Traffic goal
- Engagement metrics
```

#### mkt-009 - Sales Page Long-Form Copy
- Placeholders: `DESCRIPTION, DETAILS, IDEAL BUYER, LIST, NAME, PRICE, PRODUCT/SERVICE, TOP 3`
- Prompt:

```text
Write a long-form sales page for [PRODUCT/SERVICE] priced at [PRICE].

Product info:
- Name: [NAME]
- What it is: [DESCRIPTION]
- Key benefits: [TOP 3]
- Target customer: [IDEAL BUYER]
- Common objections: [LIST]
- Guarantee: [DETAILS]

Write these sections:

1. Pre-Headline
- Pattern interrupt
- Qualify the reader

2. Main Headline
- Big promise
- Curiosity hook

3. Opening Story
- Relatable problem
- Emotional connection
- Transition to solution

4. Problem Amplification
- Cost of not solving
- Failed solutions
- Frustration acknowledgment

5. Solution Introduction
- The breakthrough
- Why it works
- Proof of concept

6. Product Reveal
- What they get
- How it works
- Feature-benefit pairs

7. Value Stack
- Everything included
- Dollar values
- Total value calculation

8. Social Proof Section
- Testimonial format
- Case study outline
- Results/statistics

9. Risk Reversal
- Guarantee details
- Why we offer it
- Trust building

10. FAQ
- Objection handling
- Clarifying questions

11. Final CTA
- Summary of value
- Urgency element
- Clear next step
```

#### mkt-010 - LinkedIn Content Strategy
- Placeholders: `DESCRIPTION, INDUSTRY, NUMBER, OBJECTIVES, PERSON/COMPANY, TOPICS, WHO`
- Prompt:

```text
Create a LinkedIn content strategy for [PERSON/COMPANY] in [INDUSTRY].

Profile:
- Role/business: [DESCRIPTION]
- Target audience: [WHO]
- Goals: [OBJECTIVES]
- Expertise areas: [TOPICS]
- Current following: [NUMBER]

Strategy components:

1. Content Pillars (4-5)
- Pillar name
- Topics within
- Why it matters to audience
- Example post ideas (3 each)

2. Post Formats Mix
- Text-only posts: templates
- Carousel ideas: topics
- Video content: themes
- Polls: question ideas
- Document posts: concepts

3. Weekly Posting Schedule
- Optimal days/times
- Content type by day
- Engagement windows

4. Hook Templates (10)
- Curiosity hooks
- Contrarian hooks
- Story hooks
- List hooks
- Question hooks

5. Engagement Strategy
- Commenting approach
- Connection outreach
- DM scripts
- Group participation

6. Growth Tactics
- Profile optimization
- Hashtag strategy
- Collaboration opportunities
- Content repurposing

7. 30-Day Content Plan
- Daily post topics
- Key messages
- CTAs to include

8. Success Metrics
- KPIs to track
- Benchmarks
- Review cadence
```

#### mkt-011 - Webinar Promotion Sequence
- Placeholders: `3-5 POINTS, DATE, LENGTH, NAME/TITLE, SUBJECT, WEBINAR TITLE, WHO`
- Prompt:

```text
Create a webinar promotion campaign for [WEBINAR TITLE] on [DATE].

Webinar details:
- Topic: [SUBJECT]
- Host: [NAME/TITLE]
- Target audience: [WHO]
- Key takeaways: [3-5 POINTS]
- Duration: [LENGTH]

Create:

1. Registration Page Copy
- Headline
- Bullet points (what they'll learn)
- Speaker bio
- Date/time
- Registration CTA

2. Pre-Webinar Emails

Email 1: Invitation (2 weeks before)
- Problem focus
- Solution teaser
- Registration CTA

Email 2: Reminder (1 week)
- New angle/benefit
- Urgency element

Email 3: Final call (Day before)
- Scarcity
- Recap of value

3. Social Media Posts (10 posts)
- Announcement post
- Speaker spotlight
- Benefit highlights
- Countdown posts
- FAQ posts

4. Post-Registration Emails
- Confirmation email
- Day-before reminder
- 1-hour reminder
- "We're live" notification

5. Post-Webinar
- Replay access email
- Follow-up sequence (3 emails)
- Offer/CTA campaign

6. No-Show Sequence
- "You missed it" email
- Replay offer
- Key highlights summary
```

#### mkt-012 - Case Study Template
- Placeholders: `COMPANY SIZE, CUSTOMER NAME, HOW WE HELPED, INDUSTRY, KEY METRICS, PROBLEM FACED, YOUR PRODUCT/SERVICE`
- Prompt:

```text
Create a compelling case study for [CUSTOMER NAME] using [YOUR PRODUCT/SERVICE].

Background:
- Customer industry: [INDUSTRY]
- Customer size: [COMPANY SIZE]
- Challenge: [PROBLEM FACED]
- Solution: [HOW WE HELPED]
- Results: [KEY METRICS]

Write case study with:

1. Title Options (3)
- Result-focused
- Challenge-focused
- Curiosity-driven

2. Executive Summary
- 2-3 sentence overview
- Key result highlight
- Quotable stat

3. Customer Profile
- Company background
- Industry context
- Size and scope

4. Challenge Section
- Business problem
- Previous approaches
- Cost/impact of problem
- Why they sought solution

5. Solution Section
- Why they chose us
- Implementation process
- Key features used
- Timeline

6. Results Section
- Quantitative results (metrics)
- Qualitative results (experience)
- Before/after comparison
- ROI calculation

7. Customer Quotes (3-5)
- On the problem
- On implementation
- On results
- Recommendation

8. Call to Action
- Next step for reader
- Contact information

9. Visual Suggestions
- Data visualizations
- Quote callouts
- Logo placement
```

#### mkt-013 - YouTube Video Script
- Placeholders: `CATEGORY, CHANNEL NAME, DEMOGRAPHIC, MINUTES, OBJECTIVE, TOPIC, TUTORIAL/VLOG/REVIEW/ETC`
- Prompt:

```text
Write a YouTube video script about [TOPIC] for [CHANNEL NAME].

Channel info:
- Niche: [CATEGORY]
- Target viewer: [DEMOGRAPHIC]
- Video style: [TUTORIAL/VLOG/REVIEW/ETC]
- Target length: [MINUTES]
- Goal: [OBJECTIVE]

Script structure:

1. Hook (First 30 seconds)
- Pattern interrupt
- Promise/benefit statement
- Curiosity loop
- Keep watching incentive

2. Intro (30-60 seconds)
- Brief context
- Credibility statement
- Episode overview
- Subscribe reminder

3. Main Content
- Section 1: [TOPIC]
  - Key points
  - Examples
  - Transition
- Section 2: [TOPIC]
  - Key points
  - Examples
  - Transition
- Section 3: [TOPIC]
  - Key points
  - Examples
  - Transition

4. Call to Action
- What to do next
- Subscribe/like reminder
- Comment prompt

5. Outro (30 seconds)
- Summary
- Next video tease
- Final CTA

Also provide:
- Title options (5, with keywords)
- Description (with timestamps)
- Tags (15-20)
- Thumbnail concept
- End screen strategy
```

#### mkt-014 - Affiliate Marketing Email
- Placeholders: `AMOUNT, DESCRIPTION, IF APPLICABLE, PERCENTAGE, PRODUCT, PRODUCT NAME, WHO`
- Prompt:

```text
Write affiliate promotion emails for [PRODUCT] as an affiliate marketer.

Product info:
- Name: [PRODUCT NAME]
- What it does: [DESCRIPTION]
- Price: [AMOUNT]
- Commission: [PERCENTAGE]
- Target audience: [WHO]
- Launch dates: [IF APPLICABLE]

Create 5-email affiliate sequence:

Email 1: Soft Introduction
- Personal story connection
- Problem identification
- Subtle product mention
- No hard sell

Email 2: Value-First Education
- Teach something related
- Position product as tool
- Show, don't tell

Email 3: Case Study/Story
- Success story
- Transformation narrative
- Results focus
- Product as vehicle

Email 4: Direct Recommendation
- Clear product pitch
- Feature-benefit breakdown
- Who it's for/not for
- Your personal experience
- Bonuses you're offering

Email 5: Final Push
- Deadline reminder
- FAQ/objection handling
- Last chance urgency
- Clear CTA

For each email:
- Subject line options (3)
- Preview text
- Full email body
- P.S. line
- Affiliate link placement
```

#### mkt-015 - Press Release Template
- Placeholders: `ANNOUNCEMENT TYPE, COMPANY NAME, NAMES/ROLES, PUBLICATIONS, WHEN, WHY IT MATTERS`
- Prompt:

```text
Write a press release for [ANNOUNCEMENT TYPE] by [COMPANY NAME].

Announcement details:
- News: [WHAT'S BEING ANNOUNCED]
- Date: [WHEN]
- Significance: [WHY IT MATTERS]
- Key stakeholders: [NAMES/ROLES]
- Target media: [PUBLICATIONS]

Press release structure:

1. Headline
- Clear, newsworthy statement
- Action verb
- Key information

2. Subheadline
- Supporting detail
- Expand on headline

3. Dateline
- City, State - Date

4. Opening Paragraph
- Who, what, when, where, why
- Most important facts
- Newsworthiness hook

5. Body Paragraphs

Paragraph 2:
- Expand on news
- Context and background

Paragraph 3:
- Quote from key executive
- Why this matters

Paragraph 4:
- Supporting details
- Statistics/data points

Paragraph 5:
- Quote from partner/customer
- External validation

Paragraph 6:
- Future implications
- What's next

6. Boilerplate
- About [Company]
- Standard company description

7. Contact Information
- PR contact name
- Email
- Phone

8. Media Kit Elements
- Photo suggestions
- Fact sheet points
- Interview availability
```

#### mkt-016 - Newsletter Growth Strategy
- Placeholders: `NEWSLETTER NAME, NUMBER, PERCENTAGE, SCHEDULE, TARGET SUBSCRIBERS, TOPIC`
- Prompt:

```text
Create a newsletter growth strategy for [NEWSLETTER NAME] about [TOPIC].

Current state:
- Subscribers: [NUMBER]
- Open rate: [PERCENTAGE]
- Frequency: [SCHEDULE]
- Goal: [TARGET SUBSCRIBERS]

Develop growth plan:

1. Lead Magnet Strategy
- 5 lead magnet ideas
- Landing page copy for each
- Delivery sequence

2. Opt-in Placement
- Website locations
- Blog post integration
- Exit intent strategy
- Social media links

3. Content Upgrades
- 10 content upgrade ideas
- Post-specific opt-ins
- Upgrade copy templates

4. Social Media Growth
- Platform-specific tactics
- Content teasers
- Thread-to-newsletter strategy
- Profile optimization

5. Cross-Promotion
- Newsletter swaps
- Recommendation programs
- Collaboration opportunities
- Guest features

6. Referral Program
- Program structure
- Reward tiers
- Promotion copy
- Share mechanics

7. Paid Growth
- Sponsorship opportunities
- Paid recommendations
- Ad strategies
- Budget allocation

8. Retention Tactics
- Welcome sequence
- Re-engagement campaigns
- Subscriber surveys
- Exclusive content

9. Metrics to Track
- Growth rate
- Engagement metrics
- Source tracking
- LTV indicators

10. 90-Day Action Plan
- Weekly milestones
- Priority initiatives
```

#### mkt-017 - Influencer Outreach Campaign
- Placeholders: `AMOUNT, BRAND, CHANNELS, DEMOGRAPHIC, DURATION, OBJECTIVE, PRODUCT`
- Prompt:

```text
Create an influencer marketing campaign for [BRAND] promoting [PRODUCT].

Campaign details:
- Budget: [AMOUNT]
- Timeline: [DURATION]
- Target platforms: [CHANNELS]
- Campaign goal: [OBJECTIVE]
- Target audience: [DEMOGRAPHIC]

Develop campaign:

1. Influencer Criteria
- Follower range
- Engagement rate minimum
- Content style fit
- Audience demographics
- Brand safety requirements

2. Influencer Tiers

Micro (10K-50K):
- Number to engage
- Budget per influencer
- Expected reach

Mid-Tier (50K-500K):
- Number to engage
- Budget per influencer
- Expected reach

Macro (500K+):
- Number to engage
- Budget per influencer
- Expected reach

3. Outreach Templates
- Initial DM script
- Email outreach template
- Follow-up messages
- Negotiation talking points

4. Campaign Brief
- Brand guidelines
- Key messages
- Required elements
- Hashtags/mentions
- Do's and don'ts
- Content examples

5. Compensation Models
- Pay per post
- Affiliate structure
- Product gifting
- Hybrid models

6. Content Requirements
- Deliverables per tier
- Usage rights
- FTC compliance
- Approval process

7. Tracking and Measurement
- Unique codes/links
- KPIs by tier
- Reporting template
- ROI calculation

8. Campaign Timeline
- Outreach phase
- Contracting
- Content creation
- Posting schedule
- Analysis period
```

#### mkt-018 - Cart Abandonment Sequence
- Placeholders: `AMOUNT, CATEGORY, ECOMMERCE STORE, IF ANY, TONE`
- Prompt:

```text
Create a cart abandonment email sequence for [ECOMMERCE STORE].

Store info:
- Product type: [CATEGORY]
- Average cart value: [AMOUNT]
- Typical discount offered: [IF ANY]
- Brand voice: [TONE]

Email Sequence:

Email 1: (1 hour after abandonment)
- Subject line options (3)
- Tone: Helpful reminder
- Cart contents display
- Simple return CTA
- No discount

Email 2: (24 hours after)
- Subject line options (3)
- Address common objections
- Social proof element
- Product benefits reminder
- Soft urgency

Email 3: (48 hours after)
- Subject line options (3)
- Create urgency (stock/time)
- Small incentive offer
- Testimonial inclusion
- Strong CTA

Email 4: (72 hours - final)
- Subject line options (3)
- Last chance messaging
- Best offer if applicable
- Alternative product suggestions
- Personal touch

For each email include:
- Subject line
- Preview text
- Email body
- CTA buttons
- Dynamic content placeholders
- Design notes

Bonus: SMS sequence (3 messages)
- Timing
- Message text
- Link strategy
```

#### mkt-019 - Brand Tagline Generator
- Placeholders: `COMPANY NAME, DESCRIPTION, IF KNOWN, INDUSTRY, TRAITS, USP, WHO`
- Prompt:

```text
Create brand tagline options for [COMPANY NAME].

Brand info:
- Industry: [INDUSTRY]
- What we do: [DESCRIPTION]
- Key differentiator: [USP]
- Target audience: [WHO]
- Brand personality: [TRAITS]
- Competitor taglines: [IF KNOWN]

Generate taglines in these categories:

1. Benefit-Focused (5 options)
- Emphasize customer outcome
- Clear value proposition

2. Emotional (5 options)
- Connect to feelings
- Aspirational tone

3. Clever/Witty (5 options)
- Wordplay
- Memorable phrases

4. Simple/Direct (5 options)
- Crystal clear
- Easy to remember

5. Action-Oriented (5 options)
- Call to action embedded
- Energizing tone

6. Trust-Building (5 options)
- Reliability focus
- Credibility emphasis

For each tagline provide:
- The tagline
- Why it works
- Where it works best
- Potential concerns

Top 3 Recommendations:
- Best overall with rationale
- Runner-up options
- Testing suggestions
```

#### mkt-020 - Marketing Budget Allocator
- Placeholders: `AMOUNT, AWARENESS/LEADS/SALES, COMPANY, DESCRIPTION, INDUSTRY, LIST, STARTUP/GROWTH/MATURE, TOTAL BUDGET`
- Prompt:

```text
Create a marketing budget allocation plan for [COMPANY] with [TOTAL BUDGET].

Business context:
- Industry: [INDUSTRY]
- Stage: [STARTUP/GROWTH/MATURE]
- Annual revenue: [AMOUNT]
- Primary goal: [AWARENESS/LEADS/SALES]
- Current channels: [LIST]
- Target customer: [DESCRIPTION]

Allocate budget across:

1. Digital Advertising
- Search ads (Google, Bing)
- Social ads (by platform)
- Display/retargeting
- Video advertising
- Budget split and rationale

2. Content Marketing
- Blog/SEO
- Video production
- Podcast
- Social media
- Email marketing

3. Events and Partnerships
- Trade shows
- Webinars
- Sponsorships
- Influencer partnerships

4. Brand and Creative
- Design and assets
- Brand development
- Photography/video

5. Technology and Tools
- Marketing automation
- Analytics tools
- CRM
- Other software

6. Agency/Contractor
- External support
- Specialized services

7. Testing and Experimentation
- New channel testing
- A/B testing budget

For each category:
- Recommended allocation ($)
- Percentage of total
- Expected ROI
- Key metrics
- Quarterly breakdown

Provide:
- Visual budget breakdown
- Alternative scenarios (aggressive/conservative)
- Quarterly review triggers
```

#### mkt-021 - Product Description Writer
- Placeholders: `DETAILS, LIST, LUXURY/CASUAL/TECHNICAL/PLAYFUL, PRODUCT NAME, RANGE, TYPE, WHEN/WHERE USED, WHO`
- Prompt:

```text
Write compelling product descriptions for [PRODUCT NAME].

Product details:
- Category: [TYPE]
- Key features: [LIST]
- Materials/specs: [DETAILS]
- Price point: [RANGE]
- Target buyer: [WHO]
- Use cases: [WHEN/WHERE USED]

Create:

1. Short Description (50-75 words)
- Perfect for category pages
- Key selling points
- Scannable format

2. Medium Description (150-200 words)
- Product page standard
- Benefits focus
- Feature highlights
- Emotional connection

3. Long Description (300-400 words)
- Full product page
- Storytelling approach
- Complete feature breakdown
- Use cases
- Social proof placement

4. Bullet Points (5-7)
- Quick-scan format
- Benefit-first writing
- Specific details

5. SEO-Optimized Version
- Keyword integration
- Meta description
- Alt text for images

6. Social Media Versions
- Instagram caption
- Pinterest description
- Facebook post
- Twitter/X post

7. Email Version
- Subject line
- Feature highlight email
- CTA integration

Tone: [LUXURY/CASUAL/TECHNICAL/PLAYFUL]
```

#### mkt-022 - Testimonial Request System
- Placeholders: `B2B/B2C, COMPANY, DESCRIPTION, LIST`
- Prompt:

```text
Create a system for collecting customer testimonials for [COMPANY].

Business type: [B2B/B2C]
Product/service: [DESCRIPTION]
Customer touchpoints: [LIST]

Develop:

1. Request Timing Strategy
- Optimal moment identification
- Trigger events
- Automation opportunities

2. Email Templates

Request Email 1: Initial Ask
- Subject line options
- Personalized opening
- Clear ask
- Easy response options

Request Email 2: Follow-up
- Gentle reminder
- Value proposition for sharing
- Alternative formats offered

Thank You Email:
- Appreciation message
- How it will be used
- Incentive delivery (if any)

3. Question Framework
- Before using our product, what was your biggest challenge?
- How did you find us?
- What results have you achieved?
- What do you like most about [product]?
- What would you tell someone considering [product]?
- Rating scale questions

4. Collection Formats
- Written testimonial template
- Video testimonial guide
- Social media review guide
- Platform-specific requests (G2, Capterra, etc.)

5. Incentive Structure
- What to offer
- How to deliver
- Legal considerations

6. Usage and Permission
- Release form template
- Usage rights explanation
- Platform permissions

7. Organization System
- Tagging categories
- Quality scoring
- Storage/retrieval
```

#### mkt-023 - Podcast Guest Pitch
- Placeholders: `DIFFERENTIATOR, IF PROMOTING, INDUSTRY/NICHE, LINKS, PERSON NAME, PREVIOUS APPEARANCES, TOPICS`
- Prompt:

```text
Create podcast guest pitches for [PERSON NAME] to appear on shows in [INDUSTRY/NICHE].

Guest profile:
- Name and title: [NAME, TITLE]
- Expertise: [TOPICS]
- Unique angle: [DIFFERENTIATOR]
- Book/product: [IF PROMOTING]
- Speaking credits: [PREVIOUS APPEARANCES]
- Website/social: [LINKS]

Create:

1. One-Liner Pitch
- Attention-grabbing summary
- Unique hook
- Clear expertise claim

2. Short Pitch (150 words)
- Who you are
- Why you're relevant to their audience
- What you'd discuss
- Credibility proof

3. Long Pitch (300 words)
- Full background
- Multiple topic options
- Story angles
- Audience value proposition

4. Episode Topic Ideas (5)
- Title for each
- Key talking points
- Listener takeaways
- Unique angle

5. Bio Versions
- Short bio (50 words)
- Medium bio (100 words)
- Long bio (200 words)

6. Pitch Email Template
- Subject line options
- Personalization hooks
- Value proposition
- Easy yes structure
- Follow-up sequence

7. One-Sheet/Media Kit Outline
- Photo requirements
- Topics covered
- Previous appearances
- Sample questions
- Contact information

8. Target Podcast List Criteria
- Audience size range
- Topic alignment
- Guest format
- Contact research approach
```

#### mkt-024 - Referral Program Copy
- Placeholders: `ANY CAPS OR RULES, COMPANY/PRODUCT, HOW IT WORKS, WHAT NEW PERSON GETS, WHAT THEY GET`
- Prompt:

```text
Create copy for a referral program for [COMPANY/PRODUCT].

Program details:
- Referrer reward: [WHAT THEY GET]
- Referee reward: [WHAT NEW PERSON GETS]
- Process: [HOW IT WORKS]
- Limitations: [ANY CAPS OR RULES]

Create:

1. Program Landing Page
- Headline options (3)
- How it works (3 steps)
- Benefit summary
- FAQ section
- Terms summary

2. Announcement Email
- Subject line options
- Program introduction
- Clear explanation
- CTA to share

3. Share Messages

Email to friend:
- Subject line
- Personal message template
- Value proposition

Social media posts:
- Twitter/X version
- LinkedIn version
- Facebook version
- Instagram caption

Direct message:
- WhatsApp/text template
- Messenger template

4. In-App/On-Site Copy
- Dashboard widget
- Share modal
- Success confirmation
- Progress tracker

5. Reminder Emails
- First reminder
- Milestone notification
- Reward earned notification

6. Thank You Messages
- Referral made
- Referral converted
- Reward delivered

7. Terms and Conditions
- Plain language summary
- Key rules
- Limitations
- Fraud prevention
```

#### mkt-025 - Competitive Positioning Statement
- Placeholders: `COMPANY, COMPETITOR 1, COMPETITOR 2, COMPETITOR 3, DESCRIPTION, LIST, MARKET, PREMIUM/MID/VALUE, WHO`
- Prompt:

```text
Create a competitive positioning strategy for [COMPANY] in the [MARKET].

Company info:
- Product/service: [DESCRIPTION]
- Target customer: [WHO]
- Key strengths: [LIST]
- Price position: [PREMIUM/MID/VALUE]

Competitors:
- [COMPETITOR 1]: [Their positioning]
- [COMPETITOR 2]: [Their positioning]
- [COMPETITOR 3]: [Their positioning]

Develop:

1. Positioning Statement
- For [target customer]
- Who [need/opportunity]
- [Product] is a [category]
- That [key benefit]
- Unlike [competition]
- We [key differentiator]

2. Positioning Alternatives
- Option A: Quality leader
- Option B: Innovation leader
- Option C: Value leader
- Option D: Specialist

Analysis and recommendation.

3. Competitive Comparison Matrix
- Features comparison
- Positioning map (2x2)
- Gap identification

4. Messaging Hierarchy
- Primary message
- Supporting messages (3)
- Proof points for each

5. Differentiation Statements
- Why we're different (5 angles)
- Competitor comparison (tactful)
- Objection preemption

6. Positioning by Audience
- C-Suite version
- End user version
- Technical buyer version

7. Competitive Battle Cards
- Win themes per competitor
- Landmines to avoid
- Trap questions
- Counter-positioning

8. Implementation
- Website copy updates
- Sales talking points
- Marketing materials
```

#### mkt-026 - Rebranding Announcement
- Placeholders: `COMPANY, CONTINUITY, DATE, ELEMENTS, NEW NAME/IDENTITY, OLD NAME/IDENTITY, REASONS`
- Prompt:

```text
Create announcement content for [COMPANY]'s rebrand from [OLD NAME/IDENTITY] to [NEW NAME/IDENTITY].

Rebrand context:
- What's changing: [ELEMENTS]
- Why the change: [REASONS]
- What stays the same: [CONTINUITY]
- Launch date: [DATE]

Create:

1. Internal Announcement
- Email to employees
- Talking points for managers
- FAQ for staff
- Brand training overview

2. External Announcement

Press Release:
- Headline
- Full release
- Quotes from leadership

Blog Post:
- Behind the rebrand story
- What it means for customers
- Visual showcase

3. Customer Communication
- Email announcement
- What changes for them
- Timeline of changes
- FAQ

4. Partner Communication
- Partner email
- Updated assets notice
- Co-branding guidance

5. Social Media Rollout
- Announcement posts (per platform)
- Profile update messaging
- Hashtag strategy
- Bio updates

6. Website Updates
- Homepage banner
- About page content
- 404/redirect messaging

7. Email Signature Update
- New template
- Transition message

8. Launch Day Checklist
- Hour-by-hour plan
- Coordinated posting schedule
- Monitoring plan
- Response templates
```

#### mkt-027 - A/B Test Hypotheses
- Placeholders: `METRICS, MONTHLY VISITORS, OBJECTIVE, PLATFORM, WEBSITE/EMAIL/AD`
- Prompt:

```text
Create A/B test hypotheses and plans for [WEBSITE/EMAIL/AD] optimization.

Context:
- Current performance: [METRICS]
- Conversion goal: [OBJECTIVE]
- Traffic volume: [MONTHLY VISITORS]
- Testing tool: [PLATFORM]

Generate test ideas:

1. High-Impact Tests (5)

For each:
- Element to test
- Hypothesis statement: "If we [change], then [metric] will [improve] because [reasoning]"
- Control vs. variation
- Success metric
- Expected lift
- Sample size needed
- Test duration estimate

2. Quick Win Tests (5)
- Easy implementation
- Fast results
- Low risk

3. Bold Tests (3)
- Significant changes
- Higher risk/reward
- Strategic insights

4. Test Prioritization
- ICE scoring (Impact, Confidence, Ease)
- Recommended sequence
- Resource requirements

5. Test Documentation Template
- Hypothesis
- Test design
- Start/end dates
- Results
- Learnings
- Next steps

6. Statistical Considerations
- Minimum sample size
- Confidence level
- Runtime calculator
- Avoiding common errors

7. Test Calendar
- Monthly test schedule
- Avoiding conflicts
- Seasonal considerations

8. Reporting Template
- Results summary
- Winner declaration criteria
- Implementation plan
- Archive documentation
```

#### mkt-028 - Holiday Marketing Campaign
- Placeholders: `AMOUNT, COMPANY, DESCRIPTION, HOLIDAY/SEASON, IF KNOWN, WHO`
- Prompt:

```text
Create a holiday marketing campaign for [COMPANY] for [HOLIDAY/SEASON].

Business info:
- Products/services: [DESCRIPTION]
- Target audience: [WHO]
- Budget: [AMOUNT]
- Past performance: [IF KNOWN]

Campaign plan:

1. Campaign Theme
- Creative concept
- Messaging angle
- Visual direction
- Hashtag/tagline

2. Offers and Promotions
- Primary offer
- Tiered discounts
- Bundle deals
- Gift card promotions
- Free shipping threshold

3. Timeline
- Pre-holiday teaser
- Early access period
- Main sale period
- Last-minute push
- Post-holiday extension

4. Email Campaign (8-10 emails)
- Teaser email
- Launch announcement
- Category spotlights
- Gift guides
- Deadline reminders
- Last chance
- Extended sale

5. Social Media Plan
- Platform-specific content
- Daily posting schedule
- Story/reel ideas
- User-generated content
- Engagement campaigns

6. Paid Advertising
- Campaign structure
- Audience targeting
- Ad creative concepts
- Budget allocation
- Bidding strategy

7. Website Updates
- Homepage takeover
- Landing pages
- Collection pages
- Pop-up strategy
- Gift guide pages

8. Customer Service Prep
- FAQ updates
- Response templates
- Shipping cutoff communication

9. Success Metrics
- KPIs to track
- Comparison benchmarks
- Real-time monitoring
```

#### mkt-029 - SaaS Trial to Paid Sequence
- Placeholders: `DAYS, KEY ACTIONS, LIST, NAME, SAAS PRODUCT, TIERS`
- Prompt:

```text
Create an email sequence to convert free trial users to paid customers for [SAAS PRODUCT].

Product info:
- Product: [NAME]
- Trial length: [DAYS]
- Key features: [LIST]
- Pricing: [TIERS]
- Activation metrics: [KEY ACTIONS]

14-Day Trial Sequence:

Day 1: Welcome
- Getting started guide
- Quick win focus
- Support resources
- First action CTA

Day 2: Feature Spotlight #1
- Core feature highlight
- How-to guidance
- Success metric

Day 4: Check-In
- Progress acknowledgment
- Common questions
- Help offer

Day 6: Feature Spotlight #2
- Advanced feature
- Use case examples
- Integration highlight

Day 8: Social Proof
- Customer success story
- Results data
- Similar user example

Day 10: Midpoint Review
- Trial progress
- Features unused
- Personalized tips

Day 12: Upgrade Preview
- Plan comparison
- Paid benefits
- Pricing introduction

Day 13: Urgency Building
- Trial ending soon
- What happens next
- Easy upgrade path

Day 14: Final Day
- Last chance
- Special offer (if applicable)
- Simple CTA

Day 15: Post-Expiry
- Trial ended
- Data retention notice
- Comeback offer

For each: Subject, preview text, body, CTA.
```

#### mkt-030 - Customer Survey Questions
- Placeholders: `COMPANY, CUSTOMER SEGMENT, HOW DATA WILL BE USED, OBJECTIVE, TYPE OF FEEDBACK`
- Prompt:

```text
Create a customer survey for [COMPANY] to gather [TYPE OF FEEDBACK].

Survey goal: [OBJECTIVE]
Target respondent: [CUSTOMER SEGMENT]
Intended use: [HOW DATA WILL BE USED]

Create survey with:

1. Introduction
- Purpose explanation
- Time estimate
- Incentive mention (if any)
- Privacy assurance

2. Screening Questions (if needed)
- Qualification criteria
- Routing logic

3. Core Questions by Category

Product/Service Satisfaction:
- Overall satisfaction (scale)
- Feature-specific ratings
- Comparison to alternatives
- Value perception

Customer Experience:
- Ease of use
- Support quality
- Onboarding experience
- Communication satisfaction

Needs and Preferences:
- Feature requests
- Use case exploration
- Pain point identification
- Priority ranking

Loyalty Indicators:
- NPS question
- Renewal likelihood
- Recommendation likelihood
- Testimonial willingness

4. Open-Ended Questions
- What's working well?
- What needs improvement?
- Biggest challenge?
- Wishlist item?

5. Demographics/Firmographics
- Role/title
- Company size
- Industry
- Use case

6. Closing
- Thank you message
- Follow-up opt-in
- Incentive delivery

7. Survey Logic
- Skip patterns
- Conditional questions
- Progress indicators

8. Analysis Framework
- Key metrics to calculate
- Segment comparisons
- Trending analysis
```

#### mkt-031 - Podcast Sponsorship Script
- Placeholders: `BRAND, BRAND VOICE, DESCRIPTION, LANDING PAGE, MAIN VALUE, PODCAST TYPE, PROMO CODE/DEAL`
- Prompt:

```text
Write podcast ad scripts for [BRAND] sponsoring [PODCAST TYPE] shows.

Brand info:
- Product/service: [DESCRIPTION]
- Key benefit: [MAIN VALUE]
- Offer: [PROMO CODE/DEAL]
- URL: [LANDING PAGE]
- Tone: [BRAND VOICE]

Create:

1. Pre-Roll (15-30 seconds)
- Quick hook
- Core message
- CTA with URL/code

2. Mid-Roll (60 seconds)
- Host-read style
- Story/use case lead
- Product details
- Offer explanation
- CTA

3. Post-Roll (30 seconds)
- Reminder format
- Offer recap
- Final CTA

4. Integrated/Native Read (90 seconds)
- Personal experience angle
- Conversational style
- Organic transition
- Natural CTA

5. Variations by Podcast Genre
- Business podcast version
- Comedy podcast version
- True crime podcast version
- Interview show version

6. Host Talking Points
- Key messages
- Approved claims
- Required disclosures
- Pronunciation guide
- Things to avoid

7. A/B Test Versions
- Different hooks
- Different CTAs
- Different offers

8. Tracking Setup
- Unique codes per show
- Landing page variations
- Attribution methodology
```

#### mkt-032 - Account-Based Marketing Campaign
- Placeholders: `AMOUNT, AVERAGE VALUE, COMPANY, DESCRIPTION, LENGTH, NUMBER, TARGET ACCOUNT TYPE`
- Prompt:

```text
Create an Account-Based Marketing (ABM) campaign for [COMPANY] targeting [TARGET ACCOUNT TYPE].

Campaign context:
- Product/service: [DESCRIPTION]
- Deal size: [AVERAGE VALUE]
- Sales cycle: [LENGTH]
- Target accounts: [NUMBER]
- Budget: [AMOUNT]

Develop ABM campaign:

1. Account Selection
- Ideal account profile
- Selection criteria
- Tiering methodology
- Account research template

2. Account Intelligence
- Research checklist
- Key stakeholder mapping
- Trigger events to monitor
- Personalization data points

3. Tier 1 (1:1 Accounts)
- Fully personalized approach
- Custom content
- Executive outreach
- Events/dinners
- Direct mail

4. Tier 2 (1:Few Accounts)
- Industry/segment personalization
- Targeted advertising
- Personalized email sequences
- Webinars/roundtables

5. Tier 3 (1:Many Accounts)
- Scaled personalization
- Programmatic advertising
- Automated sequences
- Digital events

6. Content Strategy
- Account-specific content
- Industry content
- Persona content
- Stage-appropriate assets

7. Channel Orchestration
- Advertising (LinkedIn, display)
- Email sequences
- Sales outreach
- Direct mail
- Social engagement
- Website personalization

8. Sales Alignment
- Handoff criteria
- Joint planning process
- Feedback loops
- Shared metrics

9. Technology Stack
- ABM platform
- Intent data
- Personalization tools
- Measurement

10. Metrics and ROI
- Account engagement score
- Pipeline influence
- Revenue attribution
```

#### mkt-033 - Local SEO Optimization
- Placeholders: `BUSINESS NAME, BUSINESS TYPE, IF KNOWN, LIST, LOCATION, NUMBER, RADIUS/AREAS`
- Prompt:

```text
Create a local SEO optimization plan for [BUSINESS NAME] in [LOCATION].

Business info:
- Type: [BUSINESS TYPE]
- Service area: [RADIUS/AREAS]
- Locations: [NUMBER]
- Current rankings: [IF KNOWN]
- Main services: [LIST]

Optimization plan:

1. Google Business Profile
- Profile optimization checklist
- Category selection
- Service/product setup
- Photo strategy
- Post schedule
- Q&A preparation
- Review generation plan

2. Website Optimization
- Location page template
- Local keyword integration
- NAP consistency
- Schema markup
- Mobile optimization
- Local content strategy

3. Local Keywords
- Primary local keywords (20)
- Long-tail variations (30)
- Question keywords (10)
- Near me variations
- Neighborhood terms

4. Citation Building
- Top directories to claim
- Industry-specific directories
- Local directories
- Data aggregator submission
- NAP audit checklist

5. Review Strategy
- Review generation tactics
- Review request templates
- Response templates (positive/negative)
- Review monitoring

6. Local Content
- Blog post ideas (10)
- Local event coverage
- Community involvement content
- Local partnerships

7. Local Link Building
- Local sponsorships
- Chamber of commerce
- Local news/blogs
- Partnership opportunities

8. Tracking and Reporting
- Local ranking tracker
- GBP insights
- Conversion tracking
- Monthly report template
```

#### mkt-034 - Video Marketing Strategy
- Placeholders: `AMOUNT, BRAND, DESCRIPTION, INDUSTRY, OBJECTIVES, PLATFORMS, RESOURCES`
- Prompt:

```text
Create a video marketing strategy for [BRAND] on [PLATFORMS].

Brand info:
- Industry: [INDUSTRY]
- Target audience: [DESCRIPTION]
- Marketing goals: [OBJECTIVES]
- Budget: [AMOUNT]
- In-house vs. outsourced: [RESOURCES]

Strategy components:

1. Video Content Pillars (4-5)
- Pillar theme
- Video types within
- Target platforms
- Publishing frequency

2. Video Types by Funnel Stage

Awareness:
- Educational videos
- Entertainment content
- Brand story
- Thought leadership

Consideration:
- How-to tutorials
- Product demos
- Comparison videos
- Behind-the-scenes

Decision:
- Customer testimonials
- Case studies
- FAQ videos
- Product deep-dives

3. Platform Strategy

YouTube:
- Content approach
- SEO strategy
- Publishing cadence
- Playlist structure

Short-Form (TikTok, Reels, Shorts):
- Content style
- Trending format integration
- Posting frequency
- Cross-posting approach

LinkedIn:
- Professional content
- Thought leadership
- Behind-the-scenes

4. Production Framework
- Video formats and specs
- Equipment needs
- Workflow process
- Brand guidelines

5. Content Calendar (Monthly)
- Video schedule by platform
- Themes and topics
- Production timeline

6. Distribution Strategy
- Organic posting
- Paid promotion
- Embedding strategy
- Repurposing plan

7. Metrics and Optimization
- KPIs by platform
- A/B testing plan
- Performance review cadence
```

#### mkt-035 - Trade Show Marketing Plan
- Placeholders: `AMOUNT, COMPANY, DATES, DIMENSIONS, EVENT NAME, NAME, OBJECTIVES, VENUE`
- Prompt:

```text
Create a trade show marketing plan for [COMPANY] exhibiting at [EVENT NAME].

Event details:
- Event name: [NAME]
- Date: [DATES]
- Location: [VENUE]
- Booth size: [DIMENSIONS]
- Budget: [AMOUNT]
- Goals: [OBJECTIVES]

Complete plan:

1. Pre-Show Marketing (8-4 weeks)

Announcements:
- Email to database
- Social media posts
- Press release
- Website banner

Appointment Setting:
- Target account outreach
- Meeting scheduler setup
- Calendar holds

Promotions:
- Booth attraction offer
- Giveaway/contest
- Exclusive preview

2. Booth Strategy
- Design concept
- Key messaging
- Interactive elements
- Demo stations
- Lead capture setup
- Staffing plan

3. At-Show Activities
- Speaking opportunities
- Networking events
- Media interviews
- Social media coverage
- Daily recap emails

4. Lead Capture
- Qualification criteria
- Lead scoring
- Notes/tagging system
- Prize drawing

5. Post-Show Follow-Up

Immediate (Day 1-3):
- Thank you emails
- Hot lead calls
- Social posts

Week 1:
- Segmented follow-up
- Content delivery
- Meeting requests

Week 2-4:
- Nurture sequence
- Sales handoff
- ROI calculation

6. Materials Checklist
- Print materials
- Giveaways
- Technology needs
- Staffing supplies

7. Success Metrics
- Lead targets
- Meeting goals
- Brand awareness measures
- ROI calculation
```

#### mkt-036 - Growth Hacking Experiments
- Placeholders: `COMPANY/PRODUCT, LIST, LOW/MEDIUM/HIGH, NORTH STAR, NUMBER, STARTUP/GROWTH`
- Prompt:

```text
Generate growth hacking experiments for [COMPANY/PRODUCT].

Context:
- Stage: [STARTUP/GROWTH]
- Primary metric: [NORTH STAR]
- Current channels: [LIST]
- Budget: [LOW/MEDIUM/HIGH]
- Team size: [NUMBER]

Generate experiments:

1. Acquisition Experiments (10)

For each:
- Experiment name
- Hypothesis
- Implementation steps
- Required resources
- Success metric
- Expected impact
- Time to implement
- Risk level

2. Activation Experiments (5)
- Onboarding improvements
- Aha moment optimization
- Time to value reduction

3. Retention Experiments (5)
- Engagement loops
- Re-activation triggers
- Stickiness features

4. Revenue Experiments (5)
- Pricing tests
- Upsell optimization
- Expansion triggers

5. Referral Experiments (5)
- Viral loops
- Incentive structures
- Shareability features

6. Experiment Prioritization
- ICE scoring
- Recommended sequence
- Quick wins vs. big bets

7. Experiment Template
- Hypothesis format
- Success criteria
- Test duration
- Documentation
- Learning capture

8. 90-Day Experiment Calendar
- Weekly experiments
- Resource allocation
- Learning reviews
```

#### mkt-037 - Marketing Automation Workflows
- Placeholders: `B2B/B2C/ECOM, COMPANY, LIST, MONTHLY SENDS, PLATFORM`
- Prompt:

```text
Design marketing automation workflows for [COMPANY] using [PLATFORM].

Business context:
- Business type: [B2B/B2C/ECOM]
- Lifecycle stages: [LIST]
- Key conversion points: [LIST]
- Email volume: [MONTHLY SENDS]

Create workflows:

1. Lead Nurture Workflow
- Entry criteria
- Segmentation logic
- Email sequence (5-7 emails)
- Timing and delays
- Exit criteria
- Branch logic

2. Welcome Workflow
- Trigger event
- Onboarding sequence
- Engagement scoring
- Handoff triggers

3. Re-Engagement Workflow
- Inactivity definition
- Win-back sequence
- Offer ladder
- Sunset process

4. Post-Purchase Workflow
- Thank you sequence
- Onboarding/usage tips
- Review request
- Cross-sell/upsell
- Renewal reminder

5. Event-Based Workflows
- Webinar registration
- Content download
- Feature usage
- Support ticket

6. Lead Scoring Model
- Demographic scoring
- Behavioral scoring
- Engagement scoring
- Threshold actions

7. Sales Handoff Workflow
- MQL criteria
- SQL notification
- Assignment rules
- Follow-up tracking

8. Workflow Diagram Template
- Visual flow
- Decision points
- Actions at each step
- Integration touchpoints

9. Testing and Optimization
- A/B test points
- Performance metrics
- Optimization schedule
```

#### mkt-038 - Competitive Intelligence Report
- Placeholders: `COMPETITOR NAMES, INDUSTRY, LIST, PRODUCT/PRICING/MARKETING/ETC, WEEKLY/MONTHLY/QUARTERLY`
- Prompt:

```text
Create a competitive intelligence report template for monitoring [COMPETITOR NAMES] in [INDUSTRY].

Monitoring scope:
- Competitors: [LIST]
- Key areas: [PRODUCT/PRICING/MARKETING/ETC]
- Update frequency: [WEEKLY/MONTHLY/QUARTERLY]

Report structure:

1. Executive Summary
- Key changes this period
- Significant moves
- Recommended actions

2. Product Intelligence
- New features launched
- Product roadmap signals
- Technology changes
- Pricing updates

3. Marketing Intelligence
- Campaign observations
- Content themes
- Channel activity
- Messaging changes
- Ad creative examples

4. Sales Intelligence
- Win/loss insights
- Sales tactics observed
- Partnership announcements
- Case studies published

5. Company Intelligence
- Hiring patterns
- Funding news
- Leadership changes
- Press coverage
- Earnings highlights

6. Competitive Positioning
- Updated positioning map
- Messaging comparison
- Feature comparison matrix

7. Threat Assessment
- New threats identified
- Competitive moves anticipated
- Market share implications

8. Opportunity Identification
- Gaps to exploit
- Counter-positioning opportunities
- Timing advantages

9. Data Sources
- Monitoring tools
- Manual research checklist
- Customer feedback integration

10. Action Items
- Immediate responses needed
- Strategic considerations
- Follow-up research
```

#### mkt-039 - Crisis Communication Plan
- Placeholders: `COMPANY, EMPLOYEES, HIGH/MEDIUM/LOW, INDUSTRY, PLATFORMS`
- Prompt:

```text
Create a crisis communication plan for [COMPANY] for marketing/PR crises.

Company context:
- Industry: [INDUSTRY]
- Size: [EMPLOYEES]
- Public profile: [HIGH/MEDIUM/LOW]
- Social media presence: [PLATFORMS]

Crisis plan:

1. Crisis Categories

Category A: Social Media Backlash
- Viral negative post
- Hashtag hijacking
- Influencer criticism

Category B: PR Crisis
- Negative press coverage
- Product issue publicity
- Executive controversy

Category C: Brand Attack
- Competitor attack
- False information spread
- Review bombing

2. Escalation Matrix
- Level 1: Monitor only
- Level 2: Respond required
- Level 3: Executive involvement
- Level 4: External support

3. Response Team
- Core team members
- Extended team
- External contacts
- Decision authority

4. Response Timelines
- Initial acknowledgment
- Full response
- Updates frequency

5. Response Templates

Social Media:
- Initial acknowledgment
- Apology statement
- Update/resolution

Press Statement:
- Holding statement
- Full statement
- Follow-up

Email to Customers:
- Issue acknowledgment
- Resolution communication

6. Channel-Specific Protocols
- Twitter/X response
- Facebook response
- Instagram response
- LinkedIn response
- Review site response

7. Do's and Don'ts
- Approved actions
- Forbidden actions
- Tone guidelines

8. Post-Crisis
- Analysis template
- Reputation repair plan
- Process improvements
```

#### mkt-040 - Conversion Rate Optimization Audit
- Placeholders: `ACTION, ECOM/SAAS/LEAD GEN, PERCENTAGE, VISITORS, WEBSITE URL`
- Prompt:

```text
Conduct a conversion rate optimization (CRO) audit for [WEBSITE URL].

Website context:
- Type: [ECOM/SAAS/LEAD GEN]
- Primary conversion: [ACTION]
- Current conversion rate: [PERCENTAGE]
- Monthly traffic: [VISITORS]

Audit framework:

1. Homepage Analysis
- Value proposition clarity
- Hero section effectiveness
- Navigation usability
- CTA visibility
- Trust elements
- Mobile experience

2. Product/Service Pages
- Information hierarchy
- Benefit communication
- Social proof placement
- Pricing presentation
- CTA optimization
- Cross-sell/upsell

3. Lead Capture/Signup
- Form length
- Field optimization
- CTA button copy
- Error handling
- Progress indication
- Exit intent

4. Checkout/Conversion Flow
- Step reduction
- Friction points
- Trust signals
- Payment options
- Cart abandonment
- Confirmation page

5. Technical Performance
- Page speed
- Mobile responsiveness
- Cross-browser compatibility
- Error pages
- Broken links

6. Copy and Messaging
- Headline effectiveness
- Body copy clarity
- CTA copy
- Microcopy review

7. Trust and Credibility
- Social proof audit
- Testimonial quality
- Security indicators
- Contact accessibility

8. Quick Wins (10)
- Easy implementation
- Expected impact
- Priority order

9. Major Recommendations (5)
- Strategic changes
- A/B test suggestions
- Resource requirements
```

#### mkt-041 - Partnership Marketing Campaign
- Placeholders: `DESCRIPTION, NAME/DESCRIPTION, OBJECTIVE, PARTNER COMPANY, WHAT EACH BRINGS`
- Prompt:

```text
Create a co-marketing campaign plan with [PARTNER COMPANY] for [OBJECTIVE].

Partnership context:
- Your company: [NAME/DESCRIPTION]
- Partner company: [NAME/DESCRIPTION]
- Shared audience: [DESCRIPTION]
- Campaign goal: [OBJECTIVE]
- Combined resources: [WHAT EACH BRINGS]

Campaign plan:

1. Campaign Concept
- Theme/angle
- Key messaging
- Value proposition
- Unique hook

2. Campaign Assets

Content Pieces:
- Co-branded ebook/guide
- Joint webinar
- Blog post exchange
- Case study

Creative Assets:
- Co-branded graphics
- Video content
- Social media assets

3. Distribution Strategy

Your Channels:
- Email sends
- Social posts
- Blog promotion
- Paid amplification

Partner Channels:
- Their email sends
- Their social posts
- Their blog
- Their paid support

4. Lead Sharing Agreement
- Lead definition
- Attribution model
- Handoff process
- Follow-up rules
- Data sharing

5. Campaign Timeline
- Pre-launch prep
- Launch activities
- Ongoing promotion
- Wrap-up

6. Responsibilities Matrix
- Your tasks
- Partner tasks
- Shared tasks
- Deadlines

7. Budget and Resources
- Cost sharing
- Resource allocation
- Approval process

8. Success Metrics
- Shared KPIs
- Individual metrics
- Reporting schedule
- Post-campaign review
```

#### mkt-042 - Customer Lifecycle Email Strategy
- Placeholders: `B2B/B2C/ECOM, COMPANY, LIST, OPENS/CLICKS/ETC, TOOL`
- Prompt:

```text
Create a complete customer lifecycle email strategy for [COMPANY].

Business type: [B2B/B2C/ECOM]
Customer journey stages: [LIST]
Email platform: [TOOL]
Current email metrics: [OPENS/CLICKS/ETC]

Lifecycle Strategy:

1. Prospect Stage

Lead Magnet Delivery:
- Confirmation email
- Content delivery
- Next step suggestion

Lead Nurture:
- Educational sequence
- Social proof
- Soft offers
- Hard offer

2. New Customer Stage

Welcome Series:
- Day 1: Welcome + quick start
- Day 3: Feature spotlight
- Day 7: Success tips
- Day 14: Check-in

Onboarding:
- Getting started guide
- First milestone celebration
- Common mistakes to avoid

3. Active Customer Stage

Engagement:
- Monthly newsletter
- Feature updates
- Tips and tricks
- Community highlights

Expansion:
- Upgrade prompts
- Cross-sell recommendations
- Usage milestone rewards

4. At-Risk Customer Stage

Re-Engagement:
- "We miss you" email
- Value reminder
- Special offer
- Feedback request

5. Churned Customer Stage

Win-Back:
- Exit survey
- Improvement updates
- Special comeback offer
- Final goodbye

6. Advocacy Stage

- Review/testimonial request
- Referral program
- Case study invitation
- Community ambassador

7. Transactional Emails
- Order confirmations
- Shipping updates
- Invoice/receipt
- Renewal reminders

8. Email Calendar
- Frequency caps
- Preference center
- Suppression rules
```

#### mkt-043 - Content Repurposing Plan
- Placeholders: `COMPANY, NUMBER`
- Prompt:

```text
Create a content repurposing strategy for [COMPANY]'s existing content.

Content inventory:
- Blog posts: [NUMBER]
- Videos: [NUMBER]
- Podcasts: [NUMBER]
- Webinars: [NUMBER]
- Ebooks/guides: [NUMBER]

Repurposing strategy:

1. Content Audit
- Performance analysis
- Evergreen identification
- Update candidates
- Repurposing potential

2. Pillar Content Strategy
- Identify pillar pieces
- Cluster content around pillars
- Interlinking strategy

3. Format Transformation Matrix

Blog Post to:
- Social media posts (10+)
- Email newsletter
- Video script
- Infographic
- Podcast talking points
- LinkedIn article
- Twitter/X thread

Video to:
- Blog post
- Short clips
- Audiogram
- Quote graphics
- GIFs
- Transcription content

Webinar to:
- Blog series
- Video clips
- Slide deck
- Ebook chapter
- Email sequence
- Social content

Podcast to:
- Blog post
- Quote graphics
- Audiograms
- Video clips
- Newsletter content

4. Platform-Specific Adaptation
- LinkedIn format
- Instagram format
- Twitter/X format
- YouTube format
- TikTok format
- Pinterest format

5. Content Calendar Integration
- Repurposed content schedule
- Original vs. repurposed ratio
- Platform distribution

6. Tools and Workflow
- Repurposing tools
- Process documentation
- Team responsibilities

7. 30-Day Repurposing Sprint
- Priority content selection
- Daily output targets
- Distribution schedule
```

#### mkt-044 - Marketing Dashboard Design
- Placeholders: `COMPANY, DAILY/WEEKLY/MONTHLY, LIST, NUMBER, OBJECTIVES, PLATFORMS`
- Prompt:

```text
Design a marketing performance dashboard for [COMPANY].

Context:
- Marketing channels: [LIST]
- Key goals: [OBJECTIVES]
- Team size: [NUMBER]
- Reporting frequency: [DAILY/WEEKLY/MONTHLY]
- Tools used: [PLATFORMS]

Dashboard design:

1. Executive Summary View
- Total leads generated
- Marketing qualified leads
- Pipeline influenced
- Revenue attributed
- Month/quarter vs. goal
- Key trend indicators

2. Channel Performance

Organic Search:
- Traffic trend
- Keyword rankings
- Conversions
- Top pages

Paid Advertising:
- Spend vs. budget
- Impressions
- Clicks/CTR
- Conversions/CPA
- ROAS

Email Marketing:
- Sends/deliverability
- Open rates
- Click rates
- Conversions
- List growth

Social Media:
- Followers growth
- Engagement rate
- Click-throughs
- Content performance

Content Marketing:
- Page views
- Time on page
- Downloads
- Conversions

3. Campaign Performance
- Active campaigns
- Campaign results
- A/B test results
- ROI by campaign

4. Funnel Metrics
- Stage-by-stage conversion
- Velocity metrics
- Drop-off identification

5. Attribution View
- Multi-touch attribution
- First touch report
- Last touch report
- Channel influence

6. Visualization Guidelines
- Chart types for each metric
- Color coding
- Threshold indicators
- Drill-down structure

7. Implementation Plan
- Data sources
- Tool integration
- Refresh schedule
- Access permissions
```

#### mkt-045 - Thought Leadership Content Plan
- Placeholders: `COMPANY, EXECUTIVE NAME, HOURS/WEEK, POSITION, TOPICS, WHAT TO ACHIEVE, WHO`
- Prompt:

```text
Create a thought leadership content strategy for [EXECUTIVE NAME] from [COMPANY].

Executive profile:
- Title: [POSITION]
- Expertise areas: [TOPICS]
- Target audience: [WHO]
- Goals: [WHAT TO ACHIEVE]
- Time available: [HOURS/WEEK]

Content strategy:

1. Thought Leadership Pillars (3-5)
- Topic area
- Unique perspective
- Key messages
- Target audience segment

2. Content Mix

Long-Form (Monthly):
- LinkedIn articles
- Guest posts
- Bylined articles
- Blog posts

Short-Form (Weekly):
- LinkedIn posts
- Twitter/X threads
- Comment strategy

Spoken (Quarterly):
- Podcast appearances
- Webinars
- Speaking opportunities
- Video content

3. Topic Calendar (12 months)
- Monthly themes
- Content pieces per month
- Publication schedule

4. Content Creation Process
- Ideation sources
- Interview/extraction process
- Ghostwriting approach
- Approval workflow
- Publishing schedule

5. Platform Strategy

LinkedIn:
- Posting frequency
- Content format
- Engagement approach
- Network growth

Twitter/X:
- Posting frequency
- Content style
- Thread strategy

Podcast/Speaking:
- Target opportunities
- Pitch approach
- Preparation process

6. Amplification
- Company sharing
- Team engagement
- Paid promotion
- Email integration

7. Metrics
- Engagement KPIs
- Influence metrics
- Business impact tracking
```

#### mkt-046 - Marketing Tech Stack Audit
- Placeholders: `AMOUNT, COMPANY, ISSUES, LIST CURRENT TOOLS BY CATEGORY, NUMBER`
- Prompt:

```text
Conduct a marketing technology stack audit for [COMPANY].

Current tools:
[LIST CURRENT TOOLS BY CATEGORY]

Team size: [NUMBER]
Budget: [AMOUNT]
Pain points: [ISSUES]

Audit framework:

1. Current Stack Inventory
- Tool name
- Category
- Annual cost
- Primary users
- Utilization level
- Contract renewal date

2. Category Assessment

CRM/Database:
- Current tool
- Effectiveness (1-10)
- Gaps
- Recommendations

Marketing Automation:
- Current tool
- Effectiveness
- Gaps
- Recommendations

Analytics:
- Current tools
- Effectiveness
- Gaps
- Recommendations

Advertising:
- Current tools
- Effectiveness
- Gaps
- Recommendations

Content/SEO:
- Current tools
- Effectiveness
- Gaps
- Recommendations

Social Media:
- Current tools
- Effectiveness
- Gaps
- Recommendations

3. Integration Assessment
- Current integrations
- Data flow map
- Integration gaps
- API availability

4. Optimization Opportunities
- Consolidation candidates
- Upgrade opportunities
- Tools to sunset
- New tools needed

5. Recommended Stack
- Essential tools
- Nice-to-have tools
- Future additions
- Total cost comparison

6. Implementation Roadmap
- Priority changes
- Migration plan
- Training needs
- Timeline
```

#### mkt-047 - Customer Value Proposition
- Placeholders: `DESCRIPTION, IF ANY, NAMES, PRODUCT/SERVICE, WHO`
- Prompt:

```text
Develop a compelling customer value proposition for [PRODUCT/SERVICE].

Product info:
- What it is: [DESCRIPTION]
- Target customer: [WHO]
- Key competitors: [NAMES]
- Current positioning: [IF ANY]

Develop:

1. Customer Analysis
- Primary customer segment
- Jobs to be done
- Pains (frustrations)
- Gains (desired outcomes)

2. Value Map
- Products and services
- Pain relievers
- Gain creators

3. Value Proposition Canvas
- Customer profile fit
- Value map alignment
- Fit assessment

4. Core Value Proposition Statement
- Template: For [target customer] who [need], [product] is a [category] that [key benefit]. Unlike [competitors], we [key differentiator].
- 3-5 variations

5. Elevator Pitches
- 10-second version
- 30-second version
- 60-second version

6. Value Proposition by Segment
- Segment 1: Tailored VP
- Segment 2: Tailored VP
- Segment 3: Tailored VP

7. Supporting Messages
- Proof points
- Feature-benefit translations
- Objection responses

8. Value Proposition Testing
- A/B test versions
- Customer interview questions
- Feedback collection

9. Implementation Guide
- Website application
- Sales pitch integration
- Marketing materials
- Internal alignment
```

#### mkt-048 - Seasonal Marketing Calendar
- Placeholders: `BUSINESS TYPE, DESCRIPTION, INDUSTRY, REGIONS, WHEN, WHO`
- Prompt:

```text
Create an annual seasonal marketing calendar for [BUSINESS TYPE].

Business info:
- Industry: [INDUSTRY]
- Product/service: [DESCRIPTION]
- Target audience: [WHO]
- Key sales periods: [WHEN]
- Geographic focus: [REGIONS]

Calendar by quarter:

Q1 (January-March):
- Key holidays/events
- Seasonal themes
- Campaign ideas
- Content topics
- Sales/promotions
- Industry events

Q2 (April-June):
- Key holidays/events
- Seasonal themes
- Campaign ideas
- Content topics
- Sales/promotions
- Industry events

Q3 (July-September):
- Key holidays/events
- Seasonal themes
- Campaign ideas
- Content topics
- Sales/promotions
- Industry events

Q4 (October-December):
- Key holidays/events
- Seasonal themes
- Campaign ideas
- Content topics
- Sales/promotions
- Industry events

Monthly Details:
- Awareness days relevant to brand
- Email campaign themes
- Social media content themes
- Blog post topics
- Promotion schedule
- Creative asset needs

Planning Timeline:
- When to plan each campaign
- Creative deadlines
- Approval milestones
- Launch dates

Budget Allocation:
- Spend distribution by month
- Peak period allocation
- Buffer for opportunities
```

#### mkt-049 - Brand Awareness Campaign
- Placeholders: `AMOUNT, COMPANY, DESCRIPTION, DURATION, LOW/MEDIUM/HIGH, MAIN POINT, NEW MARKET/AUDIENCE`
- Prompt:

```text
Create a brand awareness campaign for [COMPANY] launching into [NEW MARKET/AUDIENCE].

Brand info:
- Current awareness level: [LOW/MEDIUM/HIGH]
- Target audience: [DESCRIPTION]
- Budget: [AMOUNT]
- Timeline: [DURATION]
- Key message: [MAIN POINT]

Campaign plan:

1. Campaign Strategy
- Campaign objectives (SMART goals)
- Target audience personas
- Key message framework
- Creative concept
- Campaign tagline

2. Channel Mix

Paid Media:
- Display advertising
- Social media ads
- Programmatic
- Streaming/CTV
- Audio/podcast
- Out-of-home (if applicable)

Earned Media:
- PR strategy
- Influencer partnerships
- Media outreach
- Event participation

Owned Media:
- Content strategy
- Social media
- Email
- Website

3. Creative Strategy
- Visual direction
- Video concepts
- Static ad concepts
- Social content themes
- Messaging variations

4. Media Plan
- Channel allocation
- Audience targeting
- Placement strategy
- Flight dates
- Frequency goals

5. Influencer/Partner Strategy
- Partner criteria
- Activation ideas
- Collaboration types

6. Content Plan
- Hero content pieces
- Supporting content
- Social content calendar

7. Measurement Framework
- Awareness metrics
- Engagement metrics
- Brand lift study
- Attribution model

8. Campaign Timeline
- Pre-launch activities
- Launch week
- Ongoing phases
- Optimization windows
```

#### mkt-050 - Marketing Attribution Model
- Placeholders: `ACTIONS, COMPANY, DURATION, IF ANY, LIST, SOURCES`
- Prompt:

```text
Design a marketing attribution model for [COMPANY].

Marketing context:
- Channels used: [LIST]
- Average sales cycle: [DURATION]
- Conversion points: [ACTIONS]
- Data available: [SOURCES]
- Current attribution: [IF ANY]

Attribution framework:

1. Attribution Model Selection

Model Options:
- First touch
- Last touch
- Linear
- Time decay
- Position-based
- Custom weighted
- Data-driven

Recommendation with rationale.

2. Implementation Design

Tracking Setup:
- UTM conventions
- Cookie strategy
- Cross-device tracking
- Offline touchpoints

Data Collection:
- Required data points
- Source systems
- Integration requirements
- Data warehouse

3. Touchpoint Mapping
- Marketing touchpoints list
- Weight assignments
- Credit distribution
- Lookback window

4. Channel Definitions
- Channel groupings
- Source/medium rules
- Campaign taxonomy
- Content categorization

5. Reporting Framework
- Attribution reports
- Channel performance
- Campaign ROI
- Path analysis
- Assisted conversions

6. Testing and Validation
- Holdout testing
- Incrementality measurement
- A/B attribution tests
- Model calibration

7. Optimization Process
- Insight generation
- Budget reallocation
- Channel optimization
- Review cadence

8. Implementation Timeline
- Phase 1: Tracking setup
- Phase 2: Model configuration
- Phase 3: Reporting build
- Phase 4: Optimization
```

#### mkt-051 - User-Generated Content Campaign
- Placeholders: `BRAND, CHANNELS, DESCRIPTION, OBJECTIVE, WHO`
- Prompt:

```text
Create a user-generated content (UGC) campaign for [BRAND].

Brand info:
- Product/service: [DESCRIPTION]
- Target audience: [WHO]
- Social platforms: [CHANNELS]
- Campaign goal: [OBJECTIVE]

UGC Campaign:

1. Campaign Concept
- Theme/hook
- Participation mechanism
- Hashtag
- Prize/incentive

2. Content Guidelines
- What to create
- Do's and don'ts
- Brand requirements
- Technical specs
- Rights and permissions

3. Launch Strategy

Seeding Phase:
- Brand content examples
- Influencer participation
- Employee content

Promotion Phase:
- Announcement posts
- Email blast
- Paid amplification
- Partner promotion

4. Participation Mechanics
- How to enter
- Submission process
- Selection criteria
- Winner announcement

5. Legal Requirements
- Terms and conditions
- Content rights
- Privacy compliance
- Disclosure requirements

6. Moderation Plan
- Content monitoring
- Approval workflow
- Brand safety guidelines
- Response protocols

7. Amplification Strategy
- Resharing cadence
- Feature highlights
- Creator spotlights
- Best content curation

8. Content Repurposing
- Website galleries
- Ad creative
- Social proof
- Email content
- Product pages

9. Metrics
- Participation volume
- Engagement rates
- Reach/impressions
- Conversion impact
- Content quality score
```

#### mkt-052 - Email Deliverability Optimization
- Placeholders: `COMPANY, NUMBER, PERCENTAGE, PLATFORM`
- Prompt:

```text
Create an email deliverability optimization plan for [COMPANY].

Current situation:
- List size: [NUMBER]
- Average open rate: [PERCENTAGE]
- Bounce rate: [PERCENTAGE]
- Spam complaint rate: [PERCENTAGE]
- ESP: [PLATFORM]

Optimization plan:

1. Deliverability Audit
- Sender reputation check
- Domain authentication status
- IP reputation
- Blacklist check
- Spam filter testing

2. Authentication Setup
- SPF configuration
- DKIM implementation
- DMARC policy
- BIMI consideration

3. List Hygiene
- Inactive subscriber definition
- Re-engagement campaign
- Sunset policy
- List cleaning process
- Double opt-in strategy

4. Sending Practices
- Optimal frequency
- Consistent sending patterns
- IP warming (if needed)
- Segmentation strategy
- Preference center

5. Content Optimization
- Spam trigger word audit
- Image-to-text ratio
- Link practices
- Personalization
- Subject line best practices

6. Technical Checklist
- Unsubscribe visibility
- Physical address inclusion
- List-unsubscribe header
- Feedback loop setup
- Complaint monitoring

7. Monitoring Dashboard
- Key metrics to track
- Alert thresholds
- Reporting cadence
- Tool recommendations

8. Recovery Plan
- If blacklisted
- If reputation damaged
- If deliverability drops

9. Ongoing Maintenance
- Weekly tasks
- Monthly tasks
- Quarterly review
```

#### mkt-053 - Retargeting Campaign Strategy
- Placeholders: `AD PLATFORMS, AMOUNT, COMPANY, DESCRIPTION, MONTHLY VISITORS, PERCENTAGE`
- Prompt:

```text
Create a comprehensive retargeting strategy for [COMPANY].

Business context:
- Website traffic: [MONTHLY VISITORS]
- Conversion rate: [PERCENTAGE]
- Products/services: [DESCRIPTION]
- Platforms: [AD PLATFORMS]
- Budget: [AMOUNT]

Retargeting strategy:

1. Audience Segments

Homepage Visitors:
- Recency: 1-7 days, 8-30 days
- Message: Brand awareness
- Offer: Value proposition

Product Viewers:
- Specific products viewed
- Category viewers
- Message: Product benefits
- Offer: Social proof

Cart Abandoners:
- Recency segmentation
- Value-based segmentation
- Message: Complete purchase
- Offer: Incentive ladder

Past Purchasers:
- Time since purchase
- Product category
- Message: Replenishment/cross-sell
- Offer: Loyalty rewards

2. Platform Strategy

Google Display:
- Campaign structure
- Audience setup
- Creative formats

Meta (Facebook/Instagram):
- Custom audiences
- Lookalike expansion
- Ad formats

LinkedIn (B2B):
- Matched audiences
- Account targeting
- Message ads

3. Creative Strategy
- Dynamic product ads
- Sequential messaging
- Social proof ads
- Offer-based ads

4. Frequency Management
- Cap settings
- Burn pixels
- Exclusion lists

5. Offer Ladder
- Day 1-3: Reminder
- Day 4-7: Soft incentive
- Day 8-14: Stronger offer
- Day 15-30: Final push

6. Cross-Platform Coordination
- Unified frequency
- Sequential exposure
- Attribution handling

7. Measurement
- View-through window
- Click-through window
- Incrementality testing
- ROI calculation
```

#### mkt-054 - Micro-Content Strategy
- Placeholders: `BRAND, DEMOGRAPHICS, INDUSTRY, OBJECTIVES, TEAM/BUDGET, TIKTOK/REELS/SHORTS`
- Prompt:

```text
Create a micro-content strategy for [BRAND] on short-form platforms.

Brand info:
- Industry: [INDUSTRY]
- Target audience: [DEMOGRAPHICS]
- Platforms: [TIKTOK/REELS/SHORTS]
- Content resources: [TEAM/BUDGET]
- Goals: [OBJECTIVES]

Micro-content strategy:

1. Platform Priorities
- Primary platform and why
- Secondary platforms
- Cross-posting strategy

2. Content Pillars (4-5)
- Educational content
- Entertainment content
- Behind-the-scenes
- Trend participation
- Product showcases

3. Content Formats

Trending Formats:
- Current trends to adapt
- Audio trends to use
- Challenge participation

Evergreen Formats:
- Tutorial style
- Before/after
- Day-in-the-life
- Quick tips
- Product demos

4. Publishing Strategy
- Posting frequency
- Best times
- Content calendar
- Real-time content

5. Hook Strategies
- First 1-second hooks
- Opening lines that work
- Visual hooks
- Loop strategies

6. Production Framework
- Quick production workflow
- Batch creation
- Lo-fi vs. polished
- UGC integration

7. Growth Tactics
- Hashtag strategy
- Collaboration approach
- Comment strategy
- Trend jumping

8. Metrics
- View completion
- Engagement rate
- Follower growth
- Virality indicators

9. 30-Day Content Plan
- Daily content themes
- Trend response windows
- Evergreen backup content
```

#### mkt-055 - International Marketing Localization
- Placeholders: `AMOUNT, COMPANY, COUNTRY/REGION, DESCRIPTION, DURATION, EXISTING, TARGET MARKET`
- Prompt:

```text
Create a marketing localization strategy for [COMPANY] expanding to [TARGET MARKET].

Expansion context:
- Product/service: [DESCRIPTION]
- Target market: [COUNTRY/REGION]
- Current markets: [EXISTING]
- Budget: [AMOUNT]
- Timeline: [DURATION]

Localization strategy:

1. Market Analysis
- Cultural considerations
- Local competitors
- Consumer behavior
- Channel preferences
- Regulatory requirements

2. Brand Localization
- Brand name adaptation
- Tagline translation
- Visual adaptations
- Color considerations
- Imagery guidelines

3. Message Adaptation
- Value proposition adjustments
- Local pain points
- Cultural references
- Humor/emotion calibration
- Formal vs. informal tone

4. Content Localization

Website:
- Translation approach
- Local landing pages
- SEO localization
- Currency/units
- Local payment options

Social Media:
- Local platforms
- Content adaptation
- Posting schedule
- Engagement style

Email:
- Timing adjustments
- Content localization
- Compliance (GDPR, etc.)

5. Channel Strategy
- Preferred channels in market
- Local media opportunities
- Influencer landscape
- Partnership opportunities

6. Local Team/Partners
- In-market resources
- Agency recommendations
- Freelancer networks

7. Measurement
- Market-specific KPIs
- Benchmark establishment
- Reporting structure

8. Launch Plan
- Phased approach
- Pilot markets
- Scale strategy
```

#### mkt-056 - Marketing Team Structure
- Placeholders: `AMOUNT, COMPANY, DESCRIPTION, EMPLOYEES, GOALS, LIST, STAGE/SIZE`
- Prompt:

```text
Design an optimal marketing team structure for [COMPANY] at [STAGE/SIZE].

Context:
- Company size: [EMPLOYEES]
- Marketing budget: [AMOUNT]
- Current team: [DESCRIPTION]
- Primary channels: [LIST]
- Key objectives: [GOALS]

Team structure:

1. Current State Assessment
- Existing roles
- Skill gaps
- Capacity issues
- Outsourced functions

2. Recommended Structure

Leadership:
- Head of Marketing
- Reporting structure
- Executive alignment

Core Functions:

Demand Generation:
- Role descriptions
- Key responsibilities
- Headcount

Content/Brand:
- Role descriptions
- Key responsibilities
- Headcount

Product Marketing:
- Role descriptions
- Key responsibilities
- Headcount

Marketing Operations:
- Role descriptions
- Key responsibilities
- Headcount

3. In-House vs. Agency
- Functions to keep in-house
- Functions to outsource
- Hybrid approaches
- Criteria for decisions

4. Hiring Roadmap
- Immediate hires (0-3 months)
- Short-term (3-6 months)
- Medium-term (6-12 months)
- Future roles (12+ months)

5. Role Profiles
- Job descriptions
- Skill requirements
- Experience levels
- Compensation ranges

6. Team Development
- Training needs
- Career paths
- Performance metrics
- OKR alignment

7. Collaboration Model
- Team rituals
- Cross-functional work
- Communication tools
- Meeting cadence

8. Budget Allocation
- Headcount costs
- Tool costs
- Agency costs
- Training budget
```

#### mkt-057 - Product Marketing Launch Plan
- Placeholders: `COMPANY, DATE, DESCRIPTION, DETAILS, NAME, NEW PRODUCT/FEATURE, WHO`
- Prompt:

```text
Create a product marketing launch plan for [NEW PRODUCT/FEATURE] from [COMPANY].

Product details:
- Product name: [NAME]
- What it does: [DESCRIPTION]
- Target user: [WHO]
- Launch date: [DATE]
- Pricing: [DETAILS]

Launch plan:

1. Positioning and Messaging
- Positioning statement
- Key messages (3-5)
- Unique value proposition
- Competitive differentiation

2. Audience Definition
- Primary audience
- Secondary audiences
- Persona updates
- Segment-specific messaging

3. Sales Enablement

Materials:
- Battle card
- FAQ document
- Demo script
- Objection handling
- Competitive comparison

Training:
- Product training
- Messaging training
- Demo certification

4. Marketing Assets

Core Assets:
- Product page
- Landing page
- Launch video
- Product demo
- Feature graphics

Content Assets:
- Blog post
- Press release
- Case study
- Documentation
- Social content

5. Launch Campaign

Pre-Launch (2 weeks):
- Teaser campaign
- Internal alignment
- Press briefings
- Beta feedback

Launch Day:
- Email announcement
- Social media blitz
- PR outreach
- Website update
- Advertising launch

Post-Launch (2 weeks):
- Follow-up content
- Customer stories
- Feature deep-dives
- Optimization

6. Channel Plan
- Email strategy
- Social media plan
- Paid advertising
- PR activities
- Partner activation

7. Success Metrics
- Launch goals
- Adoption metrics
- Revenue targets
- Feedback collection
```

#### mkt-058 - Community Marketing Strategy
- Placeholders: `BRAND/PRODUCT, DESCRIPTION, IF ANY, OBJECTIVE, TEAM/BUDGET, WHO`
- Prompt:

```text
Create a community marketing strategy for [BRAND/PRODUCT].

Context:
- Product/service: [DESCRIPTION]
- Target audience: [WHO]
- Community goal: [OBJECTIVE]
- Resources: [TEAM/BUDGET]
- Existing community: [IF ANY]

Community strategy:

1. Community Vision
- Purpose statement
- Value proposition for members
- Desired outcomes
- Success metrics

2. Platform Selection
- Platform evaluation:
  - Discord
  - Slack
  - Facebook Groups
  - Circle
  - Custom forum
- Recommendation with rationale

3. Community Structure
- Membership tiers
- Access levels
- Channel/space organization
- Moderation approach

4. Launch Strategy
- Founding member recruitment
- Beta period
- Public launch
- Onboarding experience

5. Content Strategy
- Content pillars
- Programming calendar
- Event schedule
- Member spotlight features

6. Engagement Tactics
- Discussion prompts
- Challenges/programs
- AMAs/office hours
- Member recognition
- Gamification elements

7. Growth Strategy
- Referral mechanisms
- Marketing integration
- Product integration
- Partnership opportunities

8. Moderation Framework
- Community guidelines
- Moderation playbook
- Escalation procedures
- Volunteer moderators

9. Measurement
- Engagement metrics
- Growth metrics
- Business impact
- Health indicators

10. Resource Requirements
- Community manager role
- Tool costs
- Programming budget
- Content creation
```

#### mkt-059 - Marketing Personalization Strategy
- Placeholders: `B2B/B2C, COMPANY, DESCRIPTION, LIST, STATUS, TOOLS`
- Prompt:

```text
Create a personalization strategy for [COMPANY]'s marketing efforts.

Context:
- Business type: [B2B/B2C]
- Channels: [LIST]
- Data available: [DESCRIPTION]
- Tech stack: [TOOLS]
- Current personalization: [STATUS]

Personalization strategy:

1. Personalization Maturity Assessment
- Current state
- Target state
- Gap analysis

2. Data Foundation
- Data sources available
- Data points to collect
- Data unification approach
- Privacy compliance

3. Segmentation Strategy
- Behavioral segments
- Demographic segments
- Psychographic segments
- Intent-based segments

4. Channel Personalization

Website:
- Homepage personalization
- Product recommendations
- Content recommendations
- CTAs and messaging
- Exit intent

Email:
- Subject line personalization
- Content blocks
- Product recommendations
- Send time optimization
- Journey personalization

Ads:
- Audience targeting
- Creative personalization
- Dynamic ads
- Retargeting

5. Personalization Use Cases
- New visitor experience
- Returning visitor experience
- Customer experience
- Account-based personalization

6. Technology Requirements
- CDP needs
- Personalization engine
- Testing tools
- Analytics

7. Implementation Roadmap
- Phase 1: Foundation
- Phase 2: Basic personalization
- Phase 3: Advanced personalization
- Phase 4: AI-driven

8. Testing Framework
- A/B testing approach
- Holdout groups
- Success measurement
- Iteration process
```

#### mkt-060 - Marketing ROI Calculator
- Placeholders: `AMOUNT, COMPANY, LENGTH, METHOD, TYPE`
- Prompt:

```text
Create a marketing ROI calculation framework for [COMPANY].

Business context:
- Business model: [TYPE]
- Average deal size: [AMOUNT]
- Sales cycle: [LENGTH]
- Marketing budget: [AMOUNT]
- Current attribution: [METHOD]

ROI framework:

1. Cost Tracking

Direct Costs:
- Advertising spend
- Tool subscriptions
- Content production
- Events
- Agency fees

Indirect Costs:
- Team salaries (allocated)
- Overhead
- Technology infrastructure

2. Revenue Attribution

First Touch:
- Calculation method
- Use cases
- Limitations

Last Touch:
- Calculation method
- Use cases
- Limitations

Multi-Touch:
- Linear model
- Time decay
- Position-based
- Custom weighted

3. Key Metrics Calculations

Cost Metrics:
- Cost per lead (CPL)
- Cost per MQL
- Cost per SQL
- Cost per opportunity
- Customer acquisition cost (CAC)

Return Metrics:
- Marketing-influenced revenue
- Marketing-sourced revenue
- Return on ad spend (ROAS)
- Customer lifetime value (LTV)
- LTV:CAC ratio

4. Channel ROI
- ROI calculation per channel
- Comparison framework
- Optimization triggers

5. Campaign ROI
- Campaign-level tracking
- Incrementality measurement
- A/B test ROI

6. Reporting Templates
- Executive dashboard
- Monthly report
- Quarterly review
- Annual analysis

7. Optimization Process
- ROI-based budget allocation
- Performance thresholds
- Reallocation triggers
- Testing budget
```

### 3. Writing & Content

#### wrt-001 - Blog Post Generator
- Placeholders: `INFORMATIVE/CONVERSATIONAL/AUTHORITATIVE, KEYWORD, LIST, NUMBER, TARGET AUDIENCE, TOPIC`
- Prompt:

```text
Write a comprehensive blog post about [TOPIC] for [TARGET AUDIENCE].

Specifications:
- Target word count: [NUMBER]
- Tone: [INFORMATIVE/CONVERSATIONAL/AUTHORITATIVE]
- Primary keyword: [KEYWORD]
- Secondary keywords: [LIST]

Structure the post with:

1. Hook opening (capture attention in first 2 sentences)
2. Brief intro establishing relevance
3. Main content with H2/H3 headers (scannable)
4. Actionable tips or takeaways (at least 5)
5. Examples or case studies
6. Conclusion with clear CTA

Also provide:
- 5 title options (include numbers and power words)
- Meta description (155 characters)
- Featured image concept
- 3 internal linking suggestions
- Social media snippets for promotion
```

#### wrt-002 - LinkedIn Article Writer
- Placeholders: `BUILD AUTHORITY/SHARE INSIGHTS/START DISCUSSION, PROFESSIONAL ROLE, TOPIC`
- Prompt:

```text
Write a thought leadership LinkedIn article on [TOPIC] for a [PROFESSIONAL ROLE].

Article goal: [BUILD AUTHORITY/SHARE INSIGHTS/START DISCUSSION]

Write with:
- Personal perspective and experience
- Industry insights
- Actionable advice
- Engaging storytelling

Format for LinkedIn:
- Short paragraphs (2-3 sentences max)
- Use bullet points and lists
- Bold key phrases
- Include relevant statistics
- End with a thought-provoking question

Target length: 1,000-1,500 words

Provide:
- The complete article
- 5 headline options
- Opening hook paragraph
- 5 relevant hashtags
- Engagement prompt for comments
```

#### wrt-003 - Email Newsletter Writer
- Placeholders: `BRAND/PUBLICATION, DAILY/WEEKLY/MONTHLY, DESCRIPTION, EDUCATE/ENTERTAIN/SELL, SUBSCRIBERS DESCRIPTION, TOPIC/THEME`
- Prompt:

```text
Write an email newsletter for [BRAND/PUBLICATION] about [TOPIC/THEME].

Newsletter details:
- Audience: [SUBSCRIBERS DESCRIPTION]
- Frequency: [DAILY/WEEKLY/MONTHLY]
- Primary goal: [EDUCATE/ENTERTAIN/SELL]
- Brand voice: [DESCRIPTION]

Include these sections:
1. Greeting and personal intro
2. Main content/story (3-5 paragraphs)
3. Key takeaways or tips
4. Featured resource/product (if applicable)
5. Community highlight or Q&A
6. Call to action
7. Sign-off with personality

Provide:
- Subject line (+ 2 A/B test options)
- Preview text (40-50 characters)
- Complete newsletter content
- Suggested images/GIFs
- Click-worthy CTA button text
```

#### wrt-004 - Product Description Writer
- Placeholders: `DIFFERENTIATOR, LIST 5-7, PRODUCT NAME, RANGE, TYPE, WHO BUYS THIS`
- Prompt:

```text
Write compelling product descriptions for [PRODUCT NAME].

Product details:
- Category: [TYPE]
- Key features: [LIST 5-7]
- Target customer: [WHO BUYS THIS]
- Price point: [RANGE]
- Unique selling point: [DIFFERENTIATOR]

Create these versions:

1. Short description (50-75 words)
- Perfect for category pages
- Scannable and punchy

2. Full description (200-300 words)
- Feature-benefit focused
- Emotional connection
- Trust elements

3. Technical specifications format
- Bullet point list
- Key specs highlighted

4. Story-driven description (150 words)
- Lifestyle focus
- Use case scenario

Also provide:
- SEO-optimized title
- Meta description
- 5 bullet points for listings (Amazon-style)
```

#### wrt-005 - Case Study Writer
- Placeholders: `CLIENT/PROJECT, DURATION, INDUSTRY, METRICS/OUTCOMES, PROBLEM, WHAT YOU DID, YOUR COMPANY`
- Prompt:

```text
Write a detailed case study about [CLIENT/PROJECT] for [YOUR COMPANY].

Case study details:
- Client industry: [INDUSTRY]
- Challenge faced: [PROBLEM]
- Solution provided: [WHAT YOU DID]
- Results achieved: [METRICS/OUTCOMES]
- Timeline: [DURATION]

Structure:

1. Title (result-focused)
2. Executive Summary (2-3 sentences)
3. Client Profile (company background)
4. The Challenge (pain points, stakes)
5. The Solution (approach, implementation)
6. The Results (quantified outcomes)
7. Client Testimonial (formatted quote)
8. Key Takeaways
9. Call to Action

Tone: Professional but engaging
Length: 800-1,200 words

Include:
- Pull quotes for social sharing
- Data visualizations suggestions
- Before/after comparisons
```

#### wrt-006 - White Paper Outline
- Placeholders: `EDUCATE/ESTABLISH AUTHORITY/GENERATE LEADS, PAGES, SECTOR, TARGET AUDIENCE, TOPIC`
- Prompt:

```text
Create a comprehensive white paper on [TOPIC] for [TARGET AUDIENCE].

Purpose: [EDUCATE/ESTABLISH AUTHORITY/GENERATE LEADS]
Industry: [SECTOR]
Length target: [PAGES]

Provide:

1. Executive Summary
- Key findings
- Main recommendations

2. Detailed Outline
- Introduction (problem statement)
- Background/Context
- Methodology (if applicable)
- Key Findings (3-5 sections)
- Analysis and Insights
- Recommendations
- Conclusion
- Appendix/Resources

3. For each section:
- Main points to cover
- Data/research to include
- Charts/graphs suggestions
- Expert quotes to seek

4. Supporting Elements
- Sidebar topics
- Callout boxes
- Infographic concepts

5. Lead Generation
- Landing page headline
- Form copy
- Follow-up email content
```

#### wrt-007 - Social Media Caption Pack
- Placeholders: `BRAND/CONTENT THEME, DESCRIPTION, ENGAGEMENT/AWARENESS/CONVERSIONS, INSTAGRAM/TWITTER/LINKEDIN/FACEBOOK`
- Prompt:

```text
Create a pack of social media captions for [BRAND/CONTENT THEME].

Brand voice: [DESCRIPTION]
Target platforms: [INSTAGRAM/TWITTER/LINKEDIN/FACEBOOK]
Content goal: [ENGAGEMENT/AWARENESS/CONVERSIONS]

Create 20 captions organized by:

1. Engagement Posts (5)
- Question prompts
- This or that
- Fill in the blank
- Poll introductions
- Discussion starters

2. Educational Posts (5)
- Tips and tricks
- How-to introductions
- Myth busters
- Quick facts

3. Promotional Posts (5)
- Product highlights
- Offer announcements
- Feature spotlights
- Testimonial introductions

4. Entertainment Posts (5)
- Relatable moments
- Behind-the-scenes
- Trending topic tie-ins
- Humor/wit

For each caption include:
- The caption text (platform-appropriate length)
- 10-15 relevant hashtags
- Best posting time
- Content format (photo, carousel, video)
- CTA suggestion
```

#### wrt-008 - Press Release Template
- Placeholders: `ANNOUNCEMENT TYPE, NAME, PUBLICATIONS/BEAT, RELEASE DATE`
- Prompt:

```text
Write a press release for [ANNOUNCEMENT TYPE].

Company: [NAME]
Announcement: [WHAT'S BEING ANNOUNCED]
Date: [RELEASE DATE]
Target media: [PUBLICATIONS/BEAT]

Press release structure:

1. Headline
- Clear, newsworthy statement
- Under 80 characters

2. Subheadline
- Supporting detail
- Expand on headline

3. Dateline
- City, State — Date

4. Lead Paragraph
- Who, what, when, where, why
- Most important information
- Hook for journalists

5. Body Paragraphs (3-4)
- Supporting details
- Quotes from stakeholders
- Context and background
- Statistics/data

6. Boilerplate
- About [Company]
- Company description

7. Contact Information
- PR contact details

Also provide:
- Email pitch template to journalists
- Social media announcement posts
- Internal announcement version
```

#### wrt-009 - Script Writer
- Placeholders: `DURATION IN MINUTES, EDUCATIONAL/ENTERTAINING/INSPIRATIONAL, TOPIC, WHAT VIEWERS SHOULD DO/FEEL/LEARN`
- Prompt:

```text
Write a script for a [CONTENT TYPE - video/podcast/presentation] about [TOPIC].

Details:
- Length: [DURATION IN MINUTES]
- Audience: [WHO'S WATCHING/LISTENING]
- Tone: [EDUCATIONAL/ENTERTAINING/INSPIRATIONAL]
- Goal: [WHAT VIEWERS SHOULD DO/FEEL/LEARN]

Script format:

1. Hook (First 30 seconds)
- Attention grabber
- Promise of value
- Keep watching incentive

2. Introduction (30-60 seconds)
- Introduce topic
- Establish credibility
- Preview content

3. Main Content (organize by sections)
- Clear transitions
- Examples and stories
- Visual/audio cues
- Engagement points

4. Conclusion (60 seconds)
- Summarize key points
- Call to action
- Sign off

Include:
- Time stamps for each section
- B-roll/visual suggestions
- Music/sound effect notes
- On-screen text suggestions
```

#### wrt-010 - Website Copy Framework
- Placeholders: `BRAND VOICE, COMPANY TYPE, DESCRIPTION, USP, WHO`
- Prompt:

```text
Write website copy for [COMPANY TYPE] website.

Business: [DESCRIPTION]
Target audience: [WHO]
Key differentiator: [USP]
Tone: [BRAND VOICE]

Create copy for:

1. Homepage
- Hero headline and subheadline
- Value proposition section
- Services/products overview
- Social proof section
- Final CTA

2. About Page
- Company story
- Mission statement
- Team section intro
- Values/principles

3. Services/Products Page
- Page headline
- Service descriptions
- Benefits list
- Process explanation
- Pricing section intro

4. Contact Page
- Headline
- Contact methods
- Form introduction
- FAQ preview

5. Common Elements
- Navigation labels
- Footer content
- CTA buttons (5 variations)
- Testimonial prompts
```

#### wrt-011 - Ebook Chapter Writer
- Placeholders: `BRIEF, OVERALL TOPIC, TITLE, TOTAL, WORDS, X`
- Prompt:

```text
Write a chapter for an ebook about [OVERALL TOPIC].

Chapter details:
- Chapter title: [TITLE]
- Chapter number: [X] of [TOTAL]
- Target length: [WORDS]
- Previous chapter summary: [BRIEF]
- Next chapter preview: [WHAT'S COMING]

Chapter structure:

1. Opening Hook
- Story or surprising fact
- Connection to reader's challenges

2. Chapter Introduction
- What this chapter covers
- Why it matters
- Learning objectives

3. Main Content (3-5 sections)
- Key concepts
- Step-by-step guidance
- Examples and illustrations
- Common mistakes to avoid

4. Practical Application
- Exercises or worksheets
- Action steps
- Self-assessment questions

5. Chapter Summary
- Key takeaways
- Transition to next chapter

Include:
- Sidebar content ideas
- Pull quote suggestions
- Graphic/diagram concepts
```

#### wrt-012 - Storytelling Framework
- Placeholders: `CORE MESSAGE/THEME, JOURNEY, LESSON, OBSTACLE, OUTCOME, WHO`
- Prompt:

```text
Create a compelling story for [PURPOSE - brand, presentation, content marketing] about [CORE MESSAGE/THEME].

Story parameters:
- Protagonist: [WHO]
- Challenge/conflict: [OBSTACLE]
- Resolution: [OUTCOME]
- Moral/takeaway: [LESSON]
- Emotional arc: [JOURNEY]

Use this structure:

1. The Hook
- Open with intrigue
- Establish stakes

2. The Setup
- Introduce protagonist
- Show the "before" state
- Create relatability

3. The Conflict
- Present the challenge
- Build tension
- Show failed attempts

4. The Turning Point
- Moment of insight
- Decision or discovery
- Beginning of transformation

5. The Resolution
- Show the "after" state
- Demonstrate change
- Reveal results

6. The Takeaway
- Extract the lesson
- Connect to audience
- Inspire action

Provide story in:
- Full narrative version (500-800 words)
- Condensed version (150 words)
- Elevator pitch (30 seconds)
```

#### wrt-013 - Technical Documentation
- Placeholders: `BEGINNER/INTERMEDIATE/ADVANCED, DESCRIPTION, PRODUCT/FEATURE/API, USER GUIDE/API DOCS/README/TUTORIAL`
- Prompt:

```text
Write technical documentation for [PRODUCT/FEATURE/API].

Documentation type: [USER GUIDE/API DOCS/README/TUTORIAL]
Audience technical level: [BEGINNER/INTERMEDIATE/ADVANCED]
Product/feature: [DESCRIPTION]

Create:

1. Overview Section
- What it is
- What it does
- Who it's for
- Prerequisites

2. Getting Started
- Installation/setup
- Quick start example
- First success moment

3. Core Concepts
- Key terminology
- Architecture overview
- How it works

4. Usage Guide
- Step-by-step instructions
- Code examples
- Screenshots placeholders
- Common use cases

5. Reference
- Complete feature list
- Parameter descriptions
- Configuration options

6. Troubleshooting
- Common issues
- Error messages
- Solutions

7. FAQ
- Frequently asked questions
- Quick answers

Format for [PLATFORM - docs site, README, wiki]
```

#### wrt-014 - Interview Questions Generator
- Placeholders: `CONVERSATIONAL/PROFESSIONAL/DEEP-DIVE, GOAL, INTERVIEWEE ROLE/EXPERTISE, LENGTH`
- Prompt:

```text
Create interview questions for a [CONTENT TYPE - podcast, blog, video] featuring [INTERVIEWEE ROLE/EXPERTISE].

Interview purpose: [GOAL]
Target audience: [WHO'S READING/LISTENING]
Tone: [CONVERSATIONAL/PROFESSIONAL/DEEP-DIVE]
Duration: [LENGTH]

Provide:

1. Opening Questions (3-5)
- Ice breakers
- Background/journey
- Establish credibility

2. Core Topic Questions (10-15)
- Expertise deep-dive
- Unique perspectives
- Controversial takes
- Practical advice

3. Storytelling Prompts (3-5)
- Memorable experiences
- Lessons learned
- Behind-the-scenes

4. Audience Value Questions (5)
- Actionable tips
- Common mistakes
- Recommendations
- Resources

5. Closing Questions (3)
- Future predictions
- Current projects
- How to connect/follow

For each question include:
- The question
- Why to ask it
- Potential follow-ups
- Time allocation
```

#### wrt-015 - Content Repurposing Guide
- Placeholders: `BLOG POST/VIDEO/PODCAST/ETC, DURATION/WORD COUNT, PASTE OR DESCRIBE CONTENT`
- Prompt:

```text
Create a repurposing plan for this content piece:

Original content: [PASTE OR DESCRIBE CONTENT]
Original format: [BLOG POST/VIDEO/PODCAST/ETC]
Content length: [DURATION/WORD COUNT]

Repurpose into:

1. Social Media Content
- 10 Twitter/X posts (with hooks)
- 5 LinkedIn posts
- 5 Instagram captions
- 3 carousel concepts
- TikTok/Reel ideas

2. Long-Form Content
- Expanded blog post angle
- Ebook chapter concept
- Newsletter edition
- Presentation slides outline

3. Visual Content
- Infographic concept
- Quote graphics (5)
- Data visualization ideas
- Thumbnail concepts

4. Audio/Video
- Podcast episode outline
- Video script adaptation
- Audiogram clips

5. Lead Magnets
- Checklist version
- Template concept
- Worksheet idea

For each format, provide:
- Content adaptation
- Best platform
- Posting strategy
```

#### wrt-016 - FAQ Section Writer
- Placeholders: `COMMON QUESTIONS, DESCRIPTION, LIST, PRODUCT/SERVICE/TOPIC, WHO`
- Prompt:

```text
Write a comprehensive FAQ section for [PRODUCT/SERVICE/TOPIC].

Context:
- What it is: [DESCRIPTION]
- Target audience: [WHO]
- Common objections: [LIST]
- Support issues: [COMMON QUESTIONS]

Create 25 FAQs organized by category:

1. Getting Started (5 questions)
- How to begin
- Requirements
- Setup process

2. Features & Usage (7 questions)
- How things work
- Capabilities
- Best practices

3. Pricing & Plans (5 questions)
- Cost questions
- Plan differences
- Billing

4. Troubleshooting (5 questions)
- Common issues
- Error solutions
- Support access

5. Policies (3 questions)
- Refunds
- Privacy
- Terms

For each FAQ:
- Question (customer language)
- Answer (clear, concise, helpful)
- Related questions
- SEO keywords

Also provide schema markup format for SEO.
```

#### wrt-017 - Grant Proposal Writer
- Placeholders: `DESCRIPTION, FUNDER NAME/TYPE, NAME AND MISSION, ORGANIZATION/PROJECT, PROJECT DURATION, PURPOSE, REQUEST`
- Prompt:

```text
Write a grant proposal for [ORGANIZATION/PROJECT] seeking funding for [PURPOSE].

Project details:
- Organization: [NAME AND MISSION]
- Project: [DESCRIPTION]
- Funding amount: [REQUEST]
- Grant maker: [FUNDER NAME/TYPE]
- Timeline: [PROJECT DURATION]

Proposal sections:

1. Executive Summary (1 page)
- Problem statement
- Proposed solution
- Expected outcomes
- Funding request

2. Statement of Need
- Problem documentation
- Data and statistics
- Target population
- Why now

3. Project Description
- Goals and objectives
- Methods and approach
- Activities timeline
- Staffing

4. Evaluation Plan
- Success metrics
- Data collection
- Reporting schedule

5. Budget Narrative
- Cost breakdown
- Justification
- Matching funds

6. Organizational Capacity
- Track record
- Key personnel
- Partnerships

7. Sustainability
- Future funding
- Long-term impact

Tone: Compelling but professional
```

#### wrt-018 - Persuasive Copywriting
- Placeholders: `AMOUNT, BIGGEST HESITATION, DESCRIPTION, PRODUCT/SERVICE, WHAT THEY SHOULD DO, WHO`
- Prompt:

```text
Write persuasive copy for [PURPOSE - sales page, ad, email] selling [PRODUCT/SERVICE].

Product/service: [DESCRIPTION]
Price: [AMOUNT]
Target buyer: [WHO]
Main objection: [BIGGEST HESITATION]
Desired action: [WHAT THEY SHOULD DO]

Use these persuasion frameworks:

1. Problem-Agitate-Solution
- Identify the problem
- Twist the knife
- Present the solution

2. Before-After-Bridge
- Current painful state
- Desired future state
- How to get there

3. Features-Advantages-Benefits
- What it has
- Why that matters
- What they get

4. Social Proof Integration
- Testimonials
- Statistics
- Credibility markers

5. Risk Reversal
- Guarantee
- No-brainer positioning

6. Urgency/Scarcity
- Time limits
- Quantity limits
- Exclusive access

Provide:
- Long-form version
- Short-form version
- Headline variations (5)
- CTA variations (5)
```

#### wrt-019 - Resume/CV Writer
- Placeholders: `ATS-FRIENDLY/CREATIVE/EXECUTIVE, COMPANY/INDUSTRY, DEGREES, FROM JOB POSTING, HIGHLIGHTS, JOB TITLE, LIST, NUMBER, POSITION, SECTOR, TITLE`
- Prompt:

```text
Write or improve a resume/CV for [POSITION] at [COMPANY/INDUSTRY].

Candidate details:
- Current/recent role: [TITLE]
- Years of experience: [NUMBER]
- Key skills: [LIST]
- Notable achievements: [HIGHLIGHTS]
- Education: [DEGREES]

Target role:
- Position: [JOB TITLE]
- Industry: [SECTOR]
- Key requirements: [FROM JOB POSTING]

Create:

1. Professional Summary
- 3-4 sentences
- Value proposition
- Relevant keywords

2. Experience Section
- Achievement-focused bullets
- Quantified results
- Action verbs
- Relevant skills highlighted

3. Skills Section
- Technical skills
- Soft skills
- Certifications

4. Education Section
- Relevant coursework
- Honors/awards

5. Additional Sections (as relevant)
- Projects
- Publications
- Volunteer work
- Languages

Format for [ATS-FRIENDLY/CREATIVE/EXECUTIVE]
Also provide:
- Keywords to include
- Sections to emphasize
- Tailoring tips for specific roles
```

#### wrt-020 - Comparison Article Writer
- Placeholders: `FACTOR, OPTION A, OPTION B, PRODUCT TYPE, WHAT MATTERS, WHAT THEY WANT TO ACHIEVE`
- Prompt:

```text
Write a comprehensive comparison article: [OPTION A] vs [OPTION B].

Comparison context:
- Category: [PRODUCT TYPE]
- Target reader: [WHO'S DECIDING]
- Key decision factors: [WHAT MATTERS]
- Reader's goal: [WHAT THEY WANT TO ACHIEVE]

Article structure:

1. Introduction
- Hook (decision challenge)
- What we'll compare
- How to use this guide

2. Quick Comparison Table
- Feature matrix
- Pricing
- Best for

3. Option A Deep-Dive
- Overview
- Key features
- Pros
- Cons
- Best for

4. Option B Deep-Dive
- Same structure

5. Head-to-Head Comparison
- Category 1: [FACTOR]
- Category 2: [FACTOR]
- Category 3: [FACTOR]
- Winner per category

6. Use Case Recommendations
- Choose A if...
- Choose B if...
- Consider alternatives if...

7. Verdict
- Overall winner
- Nuanced recommendation

SEO elements:
- Title options
- Meta description
- FAQ section
```

#### wrt-021 - Course Curriculum Outline
- Placeholders: `BEGINNER/INTERMEDIATE/ADVANCED, COURSE NAME, HOURS, TOPIC, VIDEO/TEXT/INTERACTIVE, WHO`
- Prompt:

```text
Create a curriculum outline for an online course about [TOPIC].

Course details:
- Title: [COURSE NAME]
- Target student: [WHO]
- Skill level: [BEGINNER/INTERMEDIATE/ADVANCED]
- Course length: [HOURS]
- Format: [VIDEO/TEXT/INTERACTIVE]

Create:

1. Course Description (150-200 words)
- What they'll learn
- Why it matters
- End result

2. Learning Outcomes (5-7)
- Specific skills gained
- Measurable outcomes

3. Module Breakdown (6-8 modules)

For each module:
- Module title
- Description
- Lessons (3-5 per module)
- Lesson objectives
- Duration estimate
- Activities/exercises
- Resources needed

4. Bonus Materials
- Templates
- Checklists
- Worksheets
- Resource lists

5. Assessment Strategy
- Quizzes
- Projects
- Certification criteria

6. Student Support
- Community access
- Q&A format
- Feedback mechanisms

7. Sales Page Elements
- Headline
- Bullet points
- FAQ
```

#### wrt-022 - Annual Report Writer
- Placeholders: `CELEBRATORY/TRANSPARENT/PROFESSIONAL, HIGHLIGHTS, NAME, ORGANIZATION TYPE, STAKEHOLDERS, YEAR`
- Prompt:

```text
Write content for an annual report for [ORGANIZATION TYPE].

Organization: [NAME]
Year: [YEAR]
Audience: [STAKEHOLDERS]
Key achievements: [HIGHLIGHTS]

Create content for:

1. Letter from Leadership
- Year in review
- Key accomplishments
- Challenges addressed
- Future vision
- Thank you message

2. Mission & Impact Section
- Mission statement
- Impact statistics
- Success stories
- Visual data suggestions

3. Program Highlights
- Program 1 overview and results
- Program 2 overview and results
- New initiatives

4. Financial Summary
- Revenue sources narrative
- Expense categories narrative
- Financial health statement
- Donor recognition

5. Team & Governance
- Leadership updates
- Staff highlights
- Board acknowledgment

6. Looking Ahead
- Goals for next year
- Strategic priorities
- Call to action

Tone: [CELEBRATORY/TRANSPARENT/PROFESSIONAL]
Include infographic concepts for key data.
```

#### wrt-023 - Speech/Presentation Writer
- Placeholders: `EVENT TYPE, INFORM/INSPIRE/PERSUADE/ENTERTAIN, MINUTES, NAME/ROLE, OCCASION, TOPIC, WHO`
- Prompt:

```text
Write a speech/presentation for [OCCASION] on [TOPIC].

Speech details:
- Speaker: [NAME/ROLE]
- Audience: [WHO]
- Duration: [MINUTES]
- Occasion: [EVENT TYPE]
- Goal: [INFORM/INSPIRE/PERSUADE/ENTERTAIN]

Speech structure:

1. Opening (Hook)
- Attention grabber
- Establish connection
- Preview content

2. Introduction
- Context setting
- Credibility
- Roadmap

3. Main Points (3-5)
- Point 1 with story/example
- Point 2 with data/evidence
- Point 3 with application
- Transitions between points

4. Memorable Moments
- Quotable lines
- Callback opportunities
- Audience interaction

5. Conclusion
- Summarize key messages
- Emotional peak
- Call to action
- Memorable closing line

Include:
- Stage directions
- Pause marks
- Emphasis notes
- Visual aid cues
- Time stamps per section
```

#### wrt-024 - Testimonial Request and Templates
- Placeholders: `DESCRIPTION, PRODUCT/SERVICE, WHO BUYS`
- Prompt:

```text
Create a testimonial collection system for [PRODUCT/SERVICE].

Business: [DESCRIPTION]
Customer type: [WHO BUYS]
Use cases for testimonials: [WHERE THEY'LL APPEAR]

Provide:

1. Request Email Template
- Subject line
- Personal greeting
- Specific ask
- Easy response options
- Incentive mention

2. Question Framework
- What was your situation before?
- What made you choose us?
- What results did you achieve?
- What surprised you most?
- Who would you recommend us to?

3. Response Templates for Customers
- Short testimonial (50 words)
- Medium testimonial (100 words)
- Detailed testimonial (200 words)

4. Follow-up Sequence
- First reminder
- Second reminder
- Thank you message

5. Permission & Usage
- Release form language
- Photo request
- Video testimonial script

6. Testimonial Formats
- Quote format
- Case study format
- Video script format
- Social proof format
```

#### wrt-025 - SEO Content Optimizer
- Placeholders: `IF KNOWN, LIST, PASTE EXISTING CONTENT HERE, PRIMARY KEYWORD, WHAT PAGE SHOULD RANK FOR`
- Prompt:

```text
Optimize this content for SEO:

[PASTE EXISTING CONTENT HERE]

Target keyword: [PRIMARY KEYWORD]
Secondary keywords: [LIST]
Current ranking: [IF KNOWN]
Goal: [WHAT PAGE SHOULD RANK FOR]

Provide:

1. Content Audit
- Current keyword usage
- Content gaps
- Structural issues
- Readability score

2. Optimized Version
- Rewritten with better keyword integration
- Improved headings (H1, H2, H3)
- Enhanced meta title
- Optimized meta description
- Better internal linking suggestions

3. Additions Needed
- Missing topics to cover
- FAQ section
- Statistics to add
- Expert quotes needed

4. Technical SEO
- URL suggestion
- Schema markup recommendation
- Image alt text suggestions
- Featured snippet optimization

5. Content Enhancement
- Word count recommendation
- Multimedia suggestions
- User experience improvements

6. Competitor Gap Analysis
- What top pages have that this lacks
- Unique angle opportunities
```

#### wrt-026 - Book Proposal Writer
- Placeholders: `AUDIENCE, BOOK CONCEPT, CREDENTIALS, DIFFERENTIATOR, PUBLISHER TYPE, TITLE, TYPE`
- Prompt:

```text
Write a book proposal for [BOOK CONCEPT] targeting [PUBLISHER TYPE].

Book details:
- Working title: [TITLE]
- Genre/category: [TYPE]
- Target reader: [AUDIENCE]
- Unique angle: [DIFFERENTIATOR]
- Author platform: [CREDENTIALS]

Proposal sections:

1. Overview (2 pages)
- Hook statement
- Book description
- Why this book now
- Market opportunity

2. Target Audience
- Primary readers
- Secondary readers
- Reader demographics
- Pain points/desires

3. Competitive Analysis
- Comparable titles (5-7)
- How this book differs
- Market positioning

4. Author Bio
- Credentials
- Platform metrics
- Previous publications
- Media experience

5. Marketing Plan
- Author's promotional reach
- Marketing ideas
- Speaking opportunities
- Partnership possibilities

6. Chapter Outline
- Chapter summaries
- Key takeaways per chapter

7. Sample Chapters
- Chapter selection rationale

8. Technical Details
- Estimated word count
- Delivery timeline
- Special requirements
```

#### wrt-027 - Content Style Guide
- Placeholders: `BRAND/PUBLICATION, DESCRIPTION, SECTOR, TRAITS, WHO`
- Prompt:

```text
Create a content style guide for [BRAND/PUBLICATION].

Brand context:
- Industry: [SECTOR]
- Audience: [WHO]
- Brand personality: [TRAITS]
- Existing voice: [DESCRIPTION]

Style guide sections:

1. Voice and Tone
- Brand voice attributes (4-5)
- Tone variations by context
- Do's and don'ts
- Example phrases

2. Writing Principles
- Core writing rules
- Sentence structure
- Paragraph length
- Clarity guidelines

3. Grammar and Mechanics
- Oxford comma stance
- Capitalization rules
- Number formatting
- Date formatting
- Acronym usage

4. Vocabulary
- Preferred terms
- Avoided terms
- Industry jargon policy
- Inclusive language

5. Content Types
- Blog post standards
- Social media standards
- Email standards
- Technical content standards

6. Formatting
- Header hierarchy
- List formatting
- Link text
- CTA formatting

7. Brand-Specific Rules
- Product name usage
- Trademark guidelines
- Legal requirements

8. Examples
- Before/after edits
- Good vs. bad examples
```

#### wrt-028 - Ghostwriting Brief
- Placeholders: `AREA, ARTICLE/SPEECH/BOOK CHAPTER, CLIENT/AUTHOR, CONTENT TYPE, DATE, DESCRIPTION, POINTS TO MAKE, POSITION, SUBJECT, WORD COUNT`
- Prompt:

```text
Create a ghostwriting brief for [CONTENT TYPE] on behalf of [CLIENT/AUTHOR].

Project details:
- Content type: [ARTICLE/SPEECH/BOOK CHAPTER]
- Topic: [SUBJECT]
- Length: [WORD COUNT]
- Deadline: [DATE]

Client information:
- Role/title: [POSITION]
- Industry expertise: [AREA]
- Communication style: [DESCRIPTION]
- Key messages: [POINTS TO MAKE]

Gathering brief:

1. Voice Analysis
- Speaking style
- Common phrases
- Sentence patterns
- Personality traits

2. Content Direction
- Main argument/thesis
- Key points (3-5)
- Stories to include
- Data/examples to reference
- Opinions to express

3. Audience Consideration
- Who's reading
- Their knowledge level
- What they care about
- Desired reaction

4. Research Needs
- Background information
- Statistics to find
- Expert opinions
- Trending context

5. Review Process
- Draft stages
- Feedback format
- Final approval

6. Deliverables
- Format
- Versions needed
- Rights and attribution
```

#### wrt-029 - Announcement Writer
- Placeholders: `AUDIENCE, DATE/TIMING, DESCRIPTION, SIGNIFICANCE`
- Prompt:

```text
Write announcement content for [TYPE - new product, partnership, update, event].

Announcement details:
- What: [DESCRIPTION]
- When: [DATE/TIMING]
- Why it matters: [SIGNIFICANCE]
- Who's affected: [AUDIENCE]

Create announcements for:

1. Internal Communication
- Email to team
- Slack/Teams message
- Town hall talking points

2. Customer Communication
- Email announcement
- In-app notification
- Account manager script

3. Public Communication
- Press release
- Blog post
- Social media posts (per platform)

4. Sales Enablement
- One-pager
- FAQ for sales team
- Customer objection handling

5. Partner Communication
- Partner email
- Co-marketing materials

For each version:
- Appropriate tone
- Key messages
- Call to action
- Timing recommendations
```

#### wrt-030 - Tutorial/How-To Writer
- Placeholders: `BEGINNER/INTERMEDIATE/ADVANCED, BLOG POST/VIDEO SCRIPT/DOCUMENTATION, HOW TO DO SOMETHING, TASK/SKILL, WHAT THEY NEED`
- Prompt:

```text
Write a step-by-step tutorial on [HOW TO DO SOMETHING].

Tutorial details:
- Topic: [TASK/SKILL]
- Audience skill level: [BEGINNER/INTERMEDIATE/ADVANCED]
- Prerequisites: [WHAT THEY NEED]
- End result: [WHAT THEY'LL ACHIEVE]

Tutorial structure:

1. Introduction
- What we're creating/doing
- Why it matters
- Time estimate
- Difficulty level

2. Prerequisites
- Tools/software needed
- Prior knowledge
- Setup instructions

3. Step-by-Step Instructions

For each step:
- Clear action heading
- Detailed instructions
- Screenshot/image placeholder
- Pro tips
- Common mistakes
- Troubleshooting

4. Checkpoints
- Verification points
- Expected results
- What to do if stuck

5. Conclusion
- Summary of what was achieved
- Next steps
- Related tutorials

6. Resources
- Reference links
- Downloadable files
- Further learning

Format: [BLOG POST/VIDEO SCRIPT/DOCUMENTATION]
```

#### wrt-031 - Controversy/Opinion Piece
- Placeholders: `CONTROVERSIAL/UNCONVENTIONAL, PASSIONATE/MEASURED/PROVOCATIVE, PROVOKE THOUGHT/CHANGE MINDS/START DISCUSSION, TOPIC, WORD COUNT, YOUR POSITION`
- Prompt:

```text
Write an opinion piece taking a [CONTROVERSIAL/UNCONVENTIONAL] stance on [TOPIC].

Stance: [YOUR POSITION]
Target publication: [WHERE IT'LL BE PUBLISHED]
Audience: [WHO'S READING]
Goal: [PROVOKE THOUGHT/CHANGE MINDS/START DISCUSSION]

Article structure:

1. Provocative Opening
- Bold statement
- Challenge conventional wisdom
- Hook readers immediately

2. Establish Credentials
- Why you're qualified to speak
- Personal stake in topic

3. Present the Argument
- Clear thesis statement
- Supporting point 1 (with evidence)
- Supporting point 2 (with evidence)
- Supporting point 3 (with evidence)

4. Address Counterarguments
- Acknowledge opposing views
- Refute with logic/evidence
- Show nuance

5. Real-World Implications
- Why this matters
- What should change
- Who benefits

6. Call to Action
- What readers should do
- Discussion invitation

Tone: [PASSIONATE/MEASURED/PROVOCATIVE]
Length: [WORD COUNT]
```

#### wrt-032 - Listicle Generator
- Placeholders: `ACHIEVE RESULT, NUMBER, SUBJECT, THINGS, WHAT READERS DO AFTER, WHERE, WHO`
- Prompt:

```text
Create an engaging listicle: "[NUMBER] [THINGS] to [ACHIEVE RESULT]"

Topic: [SUBJECT]
Target audience: [WHO]
Publication: [WHERE]
Desired action: [WHAT READERS DO AFTER]

Listicle structure:

1. Introduction (100-150 words)
- Hook with problem/desire
- Promise of value
- How to use this list

2. The List Items ([NUMBER] items)

For each item:
- Catchy item headline
- Why it matters (2-3 sentences)
- How to implement (2-3 sentences)
- Pro tip or example
- Visual suggestion

3. Bonus Items (2-3)
- Extra value
- Exclusive tips

4. Conclusion
- Summary
- Primary CTA
- Share prompt

SEO elements:
- Title variations (5)
- Meta description
- Featured snippet format
- Internal linking opportunities

Engage elements:
- Tweetable quotes
- Shareable graphics concepts
- Interactive elements
```

#### wrt-033 - Newsletter Welcome Sequence
- Placeholders: `NEWSLETTER NAME, SCHEDULE, SUBJECT, WHAT THEY SIGNED UP FOR, WHO SUBSCRIBES`
- Prompt:

```text
Create a welcome email sequence for new subscribers to [NEWSLETTER NAME].

Newsletter details:
- Topic/niche: [SUBJECT]
- Publishing frequency: [SCHEDULE]
- Audience: [WHO SUBSCRIBES]
- Lead magnet: [WHAT THEY SIGNED UP FOR]

Create 5-email sequence:

Email 1: Immediate Welcome
- Deliver lead magnet
- Set expectations
- Quick win content
- Encourage reply

Email 2: Day 2 - About the Creator
- Personal story
- Why this newsletter exists
- Credibility building
- Encourage engagement

Email 3: Day 4 - Best Content
- Curated best articles
- Most popular posts
- Resources hub

Email 4: Day 6 - Community
- How to participate
- Social channels
- Community highlights
- User success stories

Email 5: Day 8 - Soft Offer
- Paid offering preview
- Exclusive value
- No-pressure CTA

For each email:
- Subject line (+ A/B variant)
- Preview text
- Full email copy
- CTA button text
```

#### wrt-034 - Content Brief Generator
- Placeholders: `BLOG/VIDEO/PODCAST/SOCIAL, CONTENT TYPE, DATE, INTERNAL/EXTERNAL, TARGET, TOPIC`
- Prompt:

```text
Create a content brief for [CONTENT TYPE] about [TOPIC].

Content parameters:
- Format: [BLOG/VIDEO/PODCAST/SOCIAL]
- Length: [TARGET]
- Writer/creator: [INTERNAL/EXTERNAL]
- Deadline: [DATE]

Content brief sections:

1. Content Overview
- Working title
- Content type and format
- Target length
- Due date

2. Objectives
- Business goal
- SEO goal
- Audience goal
- Success metrics

3. Target Audience
- Primary persona
- Their problem/question
- Their knowledge level
- What they want to achieve

4. Keyword Strategy
- Primary keyword
- Secondary keywords
- Questions to answer
- Search intent

5. Content Requirements
- Angle/unique perspective
- Key points to cover
- Required sections
- Must-mention items
- Sources to reference

6. Competitive Context
- Top ranking content
- Gaps to fill
- Differentiation

7. Brand Guidelines
- Tone of voice
- Style requirements
- Formatting rules

8. Visuals
- Image requirements
- Video needs
- Graphics to create

9. Publishing
- Platform
- Category/tags
- Internal links
- Promotion plan
```

#### wrt-035 - Micro-Copy Writer
- Placeholders: `APPLICATION/WEBSITE, DESCRIPTION, TONE, WHO`
- Prompt:

```text
Write micro-copy for [APPLICATION/WEBSITE] covering all user touchpoints.

Product: [DESCRIPTION]
Brand voice: [TONE]
Target user: [WHO]

Create micro-copy for:

1. Buttons and CTAs
- Primary action buttons (10 variations)
- Secondary actions
- Navigation labels
- Form submit buttons

2. Form Fields
- Field labels
- Placeholder text
- Helper text
- Character limits

3. Validation Messages
- Success messages
- Error messages
- Warning messages
- Info messages

4. Empty States
- No content yet
- No results found
- First-time user states

5. Loading States
- Loading messages
- Progress indicators
- Skeleton text

6. Notifications
- Toast messages
- Alert dialogs
- Confirmation dialogs
- Push notifications

7. Error Pages
- 404 page
- 500 page
- Maintenance page
- Offline message

8. Onboarding
- Welcome screens
- Tooltips
- Feature introductions
- Completion messages

For each: provide 2-3 variations with rationale.
```

#### wrt-036 - Bio/About Writer
- Placeholders: `DESCRIPTION, HIGHLIGHTS, NAME, PERSON/COMPANY, TRAITS, WHERE BIOS WILL APPEAR`
- Prompt:

```text
Write professional bios and about page content for [PERSON/COMPANY].

Subject: [NAME]
Role/business: [DESCRIPTION]
Key achievements: [HIGHLIGHTS]
Personality: [TRAITS]
Use cases: [WHERE BIOS WILL APPEAR]

Create:

1. One-Line Bio (15-20 words)
- Conference speaker intro
- Byline format

2. Short Bio (50-75 words)
- Social media profiles
- Author box
- Speaker page

3. Medium Bio (100-150 words)
- Website about page
- Media kit
- Guest post intro

4. Long Bio (250-300 words)
- Full about page
- Press materials
- Awards submissions

5. Casual/Fun Bio (75 words)
- Personal blog
- Creative contexts
- Social media with personality

6. Third Person Versions
- All lengths in third person

7. First Person Versions
- All lengths in first person

For each version:
- Professional variant
- Personal variant
- Different emphasis options
```

#### wrt-037 - Call-to-Action Generator
- Placeholders: `DESCRIPTION, PRODUCT/SERVICE/CONTENT, WHAT THEY SHOULD DO, WHERE CTA APPEARS, WHO`
- Prompt:

```text
Generate high-converting CTAs for [PRODUCT/SERVICE/CONTENT].

Context:
- What we're offering: [DESCRIPTION]
- Desired action: [WHAT THEY SHOULD DO]
- Target audience: [WHO]
- Placement: [WHERE CTA APPEARS]

Generate CTAs for:

1. Button Text (20 variations)
- Action-oriented
- Benefit-focused
- Urgency-driven
- Curiosity-based
- Value-focused

2. Headlines Before CTAs (10)
- Compelling lead-ins
- Problem-solution format
- Social proof integrated

3. Supporting Text (10)
- Subtext under buttons
- Value reinforcement
- Risk reversal

4. Pop-up CTAs (5)
- Exit intent
- Time-delayed
- Scroll-triggered

5. Email CTAs (10)
- Link text
- Button text
- P.S. line CTAs

6. Social Media CTAs (10)
- Engagement prompts
- Click drivers
- Share requests

For each CTA:
- The text
- Why it works
- Best placement
- A/B test suggestion
```

#### wrt-038 - Data Storytelling
- Placeholders: `ARTICLE/PRESENTATION/REPORT, AUTHORITATIVE/ACCESSIBLE/URGENT, LIST MAIN POINTS, REPORT/STUDY/SURVEY, WHO NEEDS TO UNDERSTAND`
- Prompt:

```text
Transform this data/research into a compelling narrative:

Data source: [REPORT/STUDY/SURVEY]
Key findings: [LIST MAIN POINTS]
Target audience: [WHO NEEDS TO UNDERSTAND]
Format: [ARTICLE/PRESENTATION/REPORT]

Create:

1. Headline/Title
- Attention-grabbing
- Key insight forward
- Newsworthy angle

2. Lead Paragraph
- Most important finding
- Why it matters
- Context setting

3. Story Arc
- The situation (context)
- The discovery (what data shows)
- The implications (what it means)
- The action (what to do)

4. Data Visualization Suggestions
- Chart type for each finding
- Visual metaphors
- Comparison frameworks

5. Quote Integration
- Expert quote placements
- How to frame quotes

6. Humanizing Elements
- Real-world examples
- Case studies to include
- Relatable scenarios

7. Key Takeaways
- Bullet point summary
- Action items
- Next steps

Tone: [AUTHORITATIVE/ACCESSIBLE/URGENT]
```

#### wrt-039 - Apology/Crisis Response
- Placeholders: `COMPANY/PERSON, INCIDENT, PUBLIC REACTION, SINCERE/PROFESSIONAL/HUMBLE, SITUATION, STAKEHOLDERS`
- Prompt:

```text
Write a crisis response/apology for [SITUATION].

Crisis details:
- What happened: [INCIDENT]
- Who's affected: [STAKEHOLDERS]
- Current sentiment: [PUBLIC REACTION]
- Organization: [COMPANY/PERSON]

Create responses for:

1. Initial Statement (within hours)
- Acknowledgment
- Responsibility (if applicable)
- Immediate actions
- Promise of update

2. Full Apology Statement
- Sincere acknowledgment
- Specific apology
- Explanation (not excuse)
- Corrective actions
- Commitment to change
- Gratitude for patience

3. Internal Communication
- Employee message
- Leadership talking points
- FAQ for staff

4. Customer Communication
- Direct email
- Account-specific messaging
- Support team scripts

5. Social Media Responses
- Platform-appropriate statements
- Reply templates for comments

6. Media Statement
- Press-ready quote
- Interview talking points

7. Follow-Up Communication
- Progress update template
- Resolution announcement

Tone: [SINCERE/PROFESSIONAL/HUMBLE]
```

#### wrt-040 - Proposal/Pitch Writer
- Placeholders: `CLIENT/PROSPECT, EXPECTED, FORMAL DOCUMENT/SLIDE DECK, IF KNOWN, OFFERING, PROFESSIONAL/CONSULTATIVE/CONFIDENT, PROJECT/SERVICE, THEIR PROBLEM, WHO ELSE IS PITCHING`
- Prompt:

```text
Write a business proposal/pitch for [PROJECT/SERVICE] to [CLIENT/PROSPECT].

Proposal context:
- What we're proposing: [OFFERING]
- Client need: [THEIR PROBLEM]
- Budget range: [IF KNOWN]
- Timeline: [EXPECTED]
- Competition: [WHO ELSE IS PITCHING]

Proposal sections:

1. Executive Summary (1 page)
- Problem synthesis
- Proposed solution
- Why us
- Investment summary

2. Understanding Their Need
- Problem statement
- Business impact
- Desired outcomes
- Success criteria

3. Our Solution
- Approach overview
- Methodology
- Deliverables
- Timeline

4. Why Choose Us
- Relevant experience
- Case studies
- Team credentials
- Differentiators

5. Investment
- Pricing structure
- Payment terms
- What's included
- Optional add-ons

6. Next Steps
- Decision timeline
- Getting started process
- Contact information

Tone: [PROFESSIONAL/CONSULTATIVE/CONFIDENT]
Format: [FORMAL DOCUMENT/SLIDE DECK]
```

#### wrt-041 - Podcast Show Notes
- Placeholders: `LENGTH, NAME AND BIO, PODCAST, SUBJECT, TITLE`
- Prompt:

```text
Create comprehensive show notes for a podcast episode.

Episode details:
- Show name: [PODCAST]
- Episode title: [TITLE]
- Guest (if any): [NAME AND BIO]
- Topic: [SUBJECT]
- Duration: [LENGTH]

Show notes template:

1. Episode Summary (150-200 words)
- What's covered
- Key insights
- Why listen

2. Key Takeaways (5-7)
- Bullet point format
- Actionable insights
- Quotable moments

3. Time Stamps
- [00:00] - Introduction
- [XX:XX] - Topic 1
- [XX:XX] - Topic 2
- Continue for full episode

4. Resources Mentioned
- Books
- Websites
- Tools
- People mentioned

5. Guest Information
- Bio
- Links
- How to connect

6. Transcript Excerpt
- Key quote (100-150 words)
- Highlighted moment

7. Call to Action
- Subscribe prompt
- Review request
- Related episodes

8. SEO Elements
- Episode title (SEO-optimized)
- Description for directories
- Tags/categories
```

#### wrt-042 - Email Subject Line Generator
- Placeholders: `EMAIL CAMPAIGN TYPE, GOAL, TONE, WHAT, WHO`
- Prompt:

```text
Generate high-performing email subject lines for [EMAIL CAMPAIGN TYPE].

Campaign context:
- Email purpose: [GOAL]
- Audience: [WHO]
- Offer/content: [WHAT]
- Brand voice: [TONE]

Generate 30 subject lines organized by:

1. Curiosity-Based (5)
- Open loops
- Unexpected angles
- Mystery elements

2. Benefit-Focused (5)
- Clear value proposition
- Outcome-driven
- Result-oriented

3. Urgency-Driven (5)
- Time-sensitive
- Scarcity
- FOMO triggers

4. Personalization (5)
- Name tokens
- Behavior-based
- Segment-specific

5. Question Format (5)
- Pain point questions
- Curiosity questions
- Engagement questions

6. Numbers/Lists (5)
- Data-driven
- Listicle format
- Specific numbers

For each subject line:
- The subject line
- Character count
- Preview text suggestion
- Why it works
- A/B test pairing
```

#### wrt-043 - Product Update Announcement
- Placeholders: `BENEFIT, DESCRIPTION, FEATURE/UPDATE, USERS, WHEN/WHO`
- Prompt:

```text
Write a product update announcement for [FEATURE/UPDATE].

Update details:
- What's new: [DESCRIPTION]
- Why it matters: [BENEFIT]
- Who it affects: [USERS]
- Availability: [WHEN/WHO]

Create announcements for:

1. Email Announcement
- Subject line
- Hero section
- Feature explanation
- Visual suggestions
- CTA to try it

2. In-App Notification
- Short headline
- Brief description
- CTA button

3. Blog Post
- Full announcement
- How to use
- Customer quotes
- Future roadmap tease

4. Social Media
- Twitter thread
- LinkedIn post
- Instagram caption
- Video script (30-60 sec)

5. Changelog Entry
- Technical description
- Breaking changes
- Migration guide if needed

6. Sales Enablement
- One-liner
- Customer-facing FAQ
- Competitive advantage

7. Press Brief (if major)
- Press-worthy angle
- Quote from leadership
```

#### wrt-044 - Review Response Templates
- Placeholders: `BUSINESS TYPE, DESCRIPTION, TONE, WHERE`
- Prompt:

```text
Create templates for responding to customer reviews for [BUSINESS TYPE].

Business: [DESCRIPTION]
Review platforms: [WHERE]
Brand voice: [TONE]

Create templates for:

1. Positive Reviews (5-star)
- Thank you response
- Personalized appreciation
- Invitation to return
- Share request

2. Neutral Reviews (3-4 star)
- Appreciation for feedback
- Address specific points
- Improvement commitment
- Invitation to discuss

3. Negative Reviews (1-2 star)
- Sincere apology
- Issue acknowledgment
- Resolution offer
- Take conversation offline

4. Specific Situations
- Product issue
- Service complaint
- Pricing concern
- Wait time complaint
- Staff complaint
- Competitor comparison

5. Platform-Specific
- Google Reviews
- Yelp
- TripAdvisor
- G2/Capterra
- Amazon

For each template:
- Response text
- Personalization points
- Do's and don'ts
- Escalation triggers
```

#### wrt-045 - Award Submission Writer
- Placeholders: `AWARD NAME, CATEGORY, COMPANY/PROJECT/PERSON, CONFIDENT/HUMBLE/INSPIRING, LIMIT, REQUIREMENTS`
- Prompt:

```text
Write an award submission for [AWARD NAME] for [COMPANY/PROJECT/PERSON].

Award details:
- Award category: [CATEGORY]
- Criteria: [REQUIREMENTS]
- Word limit: [LIMIT]
- Judges: [WHO'S DECIDING]

Submission sections:

1. Executive Summary
- Key achievement
- Impact statement
- Why we deserve this

2. Project/Initiative Overview
- What we did
- Innovation involved
- Challenges overcome

3. Results and Impact
- Quantified outcomes
- Qualitative improvements
- Industry impact
- Stakeholder testimonials

4. Innovation/Uniqueness
- What's different
- First-of-its-kind elements
- Creative approach

5. Team/Leadership
- Key contributors
- Leadership vision
- Collaboration highlights

6. Future Impact
- Sustainability
- Scalability
- Industry influence

7. Supporting Materials
- Evidence to include
- Testimonials to gather
- Visuals to prepare

Tone: [CONFIDENT/HUMBLE/INSPIRING]
```

#### wrt-046 - Headline Generator
- Placeholders: `BLOG/AD/EMAIL/LANDING PAGE, CLICKS/CONVERSIONS/SHARES, CONTENT TYPE, FEAR/DESIRE/CURIOSITY, TOPIC, WHO`
- Prompt:

```text
Generate powerful headlines for [CONTENT TYPE] about [TOPIC].

Content context:
- Format: [BLOG/AD/EMAIL/LANDING PAGE]
- Goal: [CLICKS/CONVERSIONS/SHARES]
- Audience: [WHO]
- Emotional driver: [FEAR/DESIRE/CURIOSITY]

Generate 25 headlines using:

1. Number Headlines (5)
- "X Ways to..."
- "X Secrets of..."
- "X Mistakes..."

2. How-To Headlines (5)
- Step-by-step promise
- Transformation focus
- Specific outcome

3. Question Headlines (5)
- Pain point questions
- Curiosity drivers
- Self-qualifying questions

4. Power Word Headlines (5)
- Emotional triggers
- Action words
- Benefit words

5. Unique Angle Headlines (5)
- Contrarian takes
- Surprising facts
- New perspectives

For each headline:
- The headline
- Character count
- Why it works
- Best use case
- A/B test variant
```

#### wrt-047 - Content Outline Generator
- Placeholders: `CONTENT PIECE, OBJECTIVE, TARGET, TOPIC, TYPE, WHO`
- Prompt:

```text
Create a detailed content outline for [CONTENT PIECE] about [TOPIC].

Content specs:
- Format: [TYPE]
- Length: [TARGET]
- Audience: [WHO]
- Goal: [OBJECTIVE]

Outline structure:

1. Title Brainstorm
- 5 title options
- SEO considerations
- Emotional appeal

2. Introduction Outline
- Hook approach
- Problem statement
- Thesis/promise
- Transition to body

3. Body Sections

For each major section:
- Section heading
- Key points (3-5)
- Supporting evidence needed
- Examples to include
- Visual suggestions
- Transition to next section

4. Conclusion Outline
- Summary points
- Final insight
- Call to action
- Closing hook

5. Supporting Elements
- Sidebar content
- Pull quotes
- Graphics needed
- Internal links
- External sources

6. SEO Notes
- Primary keyword placement
- Secondary keywords
- Meta description approach
- Featured snippet opportunity

7. Research Needed
- Data to find
- Experts to quote
- Examples to research
```

#### wrt-048 - Elevator Pitch Writer
- Placeholders: `COMPANY/PRODUCT/IDEA, DESCRIPTION, DIFFERENTIATOR, PAIN POINT, TARGET`
- Prompt:

```text
Create elevator pitches for [COMPANY/PRODUCT/IDEA].

Context:
- What it is: [DESCRIPTION]
- Who it's for: [TARGET]
- Problem solved: [PAIN POINT]
- Unique value: [DIFFERENTIATOR]

Create pitches for:

1. 10-Second Pitch
- One sentence
- Core value only
- Memorable hook

2. 30-Second Pitch
- Problem-solution format
- Key benefit
- Credibility element
- Conversation starter

3. 60-Second Pitch
- Full narrative
- Problem agitation
- Solution details
- Social proof
- Clear ask

4. 2-Minute Pitch
- Complete story arc
- Competitive context
- Traction/results
- Vision
- Call to action

5. Written Versions
- Email intro
- LinkedIn message
- Website hero
- Investor teaser

6. Situation-Specific
- Investor pitch
- Customer pitch
- Partner pitch
- Press pitch

For each: provide variations for different audiences.
```

#### wrt-049 - Survey Question Writer
- Placeholders: `IF ANY, METHOD, MINUTES/QUESTIONS, RESEARCH OBJECTIVE, RESPONDENT TYPE, WHAT TO LEARN`
- Prompt:

```text
Create survey questions for [RESEARCH OBJECTIVE] targeting [RESPONDENT TYPE].

Survey goal: [WHAT TO LEARN]
Distribution: [METHOD]
Length target: [MINUTES/QUESTIONS]
Incentive: [IF ANY]

Create:

1. Screening Questions
- Qualification criteria
- Disqualification triggers

2. Core Research Questions

For each question:
- Question text
- Question type (multiple choice, scale, open)
- Answer options (if applicable)
- Skip logic
- Why this question

Question categories:
- Behavior questions
- Attitude questions
- Preference questions
- Demographic questions
- Open-ended questions

3. Scale Questions
- Satisfaction scales
- Likelihood scales
- Agreement scales

4. Open-Ended Prompts
- Exploratory questions
- Feedback requests
- Suggestion prompts

5. Survey Flow
- Question order
- Logic branches
- Progress indicators

6. Introduction and Closing
- Welcome message
- Purpose explanation
- Thank you page
- Follow-up opt-in
```

#### wrt-050 - Influencer Brief
- Placeholders: `CAMPAIGN, NAME, OBJECTIVE, RANGE, WHAT, WHO`
- Prompt:

```text
Create an influencer collaboration brief for [CAMPAIGN].

Campaign details:
- Brand: [NAME]
- Product: [WHAT]
- Campaign goal: [OBJECTIVE]
- Target audience: [WHO]
- Budget tier: [RANGE]

Brief sections:

1. Campaign Overview
- Brand introduction
- Campaign concept
- Key message
- Timeline

2. Content Requirements
- Number of posts
- Platforms
- Content format (photo, video, story)
- Mandatory elements
- Hashtags to use
- Mentions required

3. Brand Guidelines
- Tone and voice
- Visual style
- Do's and don'ts
- Competitor mentions
- Approval process

4. Key Messages
- Primary message
- Talking points
- Features to highlight
- CTA required

5. Deliverables
- Content specifications
- Deadlines
- Usage rights
- Exclusivity period

6. Compensation
- Payment terms
- Product gifting
- Affiliate opportunity

7. FTC Compliance
- Disclosure requirements
- Approved language

8. Creative Examples
- Inspiration
- Past successful posts
- What to avoid
```

#### wrt-051 - Terms of Service Summary
- Placeholders: `COMMON QUESTIONS, DESCRIPTION, LIST, PRODUCT/SERVICE`
- Prompt:

```text
Create a plain-language summary of Terms of Service for [PRODUCT/SERVICE].

Service type: [DESCRIPTION]
Key legal points: [LIST]
User concerns: [COMMON QUESTIONS]

Create:

1. TL;DR Summary (100 words)
- Key points
- Important rights
- Notable restrictions

2. Section Summaries

For each standard section:
- Legal section name
- Plain English explanation
- What it means for users
- Important callouts

Sections:
- Account terms
- User responsibilities
- Payment terms
- Content ownership
- Privacy summary
- Liability limits
- Termination
- Dispute resolution

3. FAQ Format
- Common questions answered
- Plain language responses

4. Key Rights Highlight
- What users CAN do
- What users CANNOT do
- What company can do

5. Red Flag Highlights
- Unusual terms
- Important limitations
- Points users should know

6. Visual Summary
- Icons and key points
- Quick reference card

Tone: Friendly, clear, honest
```

#### wrt-052 - Meeting Agenda and Minutes
- Placeholders: `GOAL, LENGTH, MEETING TYPE, ROLES, SCHEDULE, TEAM/CLIENT/BOARD/PROJECT`
- Prompt:

```text
Create meeting agenda and minutes template for [MEETING TYPE].

Meeting context:
- Type: [TEAM/CLIENT/BOARD/PROJECT]
- Frequency: [SCHEDULE]
- Duration: [LENGTH]
- Attendees: [ROLES]
- Purpose: [GOAL]

Create:

1. Agenda Template
- Meeting header
- Attendees section
- Time allocations
- Topics with owners
- Discussion items
- Decision items
- Action item preview
- Next meeting

2. Pre-Meeting Communication
- Agenda email
- Pre-read materials
- Preparation requests

3. Minutes Template
- Meeting summary
- Attendance record
- Decisions made
- Action items (who, what, when)
- Key discussion points
- Parking lot items
- Next steps

4. Follow-Up Email
- Minutes distribution
- Action item reminders
- Next meeting confirmation

5. Standing Items
- Regular updates
- Recurring topics
- Metrics review

6. Best Practices
- Time management tips
- Engagement techniques
- Decision-making framework
```

#### wrt-053 - Testimonial Editing
- Placeholders: `PASTE RAW TESTIMONIALS, PRODUCT/SERVICE`
- Prompt:

```text
Edit and enhance these raw customer testimonials for [PRODUCT/SERVICE].

Raw testimonials:
[PASTE RAW TESTIMONIALS]

Guidelines:
- Keep authentic voice
- Make more compelling
- Highlight results
- Maintain honesty

For each testimonial, provide:

1. Polished Version
- Edited for clarity
- Key points highlighted
- Quotable sections marked

2. Short Version (50 words)
- Social media ready
- Key message preserved

3. Pull Quotes
- 2-3 quotable snippets
- Headline-worthy phrases

4. Use Case Tags
- Best placement
- Content theme
- Buyer persona match

5. Enhancement Suggestions
- Missing elements
- Follow-up questions
- Context to add

6. Visual Presentation
- Attribution format
- Image suggestions
- Display recommendations

Maintain: Authenticity, specific results, emotional resonance
```

#### wrt-054 - Seasonal Content Calendar
- Placeholders: `BRAND/PUBLICATION, LIST, PLATFORMS, SEASON/QUARTER, SECTOR, WHO`
- Prompt:

```text
Create a seasonal content calendar for [BRAND/PUBLICATION] for [SEASON/QUARTER].

Business context:
- Industry: [SECTOR]
- Audience: [WHO]
- Content channels: [PLATFORMS]
- Key products/services: [LIST]

Calendar structure:

1. Monthly Themes
- Month 1 theme and focus
- Month 2 theme and focus
- Month 3 theme and focus

2. Key Dates
- Holidays
- Industry events
- Awareness days
- Company milestones

3. Content by Week
For each week:
- Blog post topic
- Social media themes
- Email newsletter focus
- Video/podcast ideas

4. Campaign Integration
- Seasonal promotions
- Product launches
- Special events

5. Content Types Mix
- Educational content
- Promotional content
- Engagement content
- User-generated content

6. Resource Planning
- Creation timeline
- Asset requirements
- Team assignments

7. Performance Goals
- Traffic targets
- Engagement metrics
- Conversion goals
```

#### wrt-055 - Executive Summary Writer
- Placeholders: `DECISIONS NEEDED, DOCUMENT TYPE, FORMAL/ACCESSIBLE, GOAL, LIST, SUBJECT, WORDS/PAGES`
- Prompt:

```text
Write an executive summary for [DOCUMENT TYPE] about [SUBJECT].

Document context:
- Full document purpose: [GOAL]
- Audience: [WHO'S READING]
- Key findings/points: [LIST]
- Recommended actions: [DECISIONS NEEDED]

Executive summary structure:

1. Opening Statement
- Context in one sentence
- Why this matters

2. Key Findings/Highlights
- Most important points (3-5)
- Critical data
- Surprising discoveries

3. Implications
- What this means
- Impact on business
- Risk assessment

4. Recommendations
- Proposed actions
- Priority order
- Resource requirements

5. Next Steps
- Immediate actions
- Decision points
- Timeline

6. Conclusion
- Summary statement
- Call to action

Length target: [WORDS/PAGES]
Tone: [FORMAL/ACCESSIBLE]

Also provide:
- Bullet point version
- One-paragraph version
- Slide adaptation
```

### 4. Coding & Development

#### code-001 - Code Review Assistant
- Placeholders: `LANGUAGE, PASTE CODE HERE`
- Prompt:

```text
Review the following [LANGUAGE] code and provide comprehensive feedback:

```
[PASTE CODE HERE]
```

Analyze for:

1. **Bugs & Issues**
- Logic errors
- Edge cases not handled
- Potential runtime errors
- Memory leaks
- Race conditions

2. **Performance**
- Time complexity analysis
- Space complexity analysis
- Optimization opportunities
- Caching possibilities

3. **Security**
- SQL injection vulnerabilities
- XSS vulnerabilities
- Authentication/authorization issues
- Input validation gaps
- Sensitive data exposure

4. **Best Practices**
- Naming conventions
- Code organization
- DRY principle violations
- SOLID principle adherence
- Error handling patterns

5. **Readability**
- Comment quality
- Function/method length
- Variable naming
- Code structure

For each issue:
- Severity: Critical/High/Medium/Low
- Location: Line number(s)
- Problem: What's wrong
- Solution: Corrected code

End with overall quality score (1-10) and summary.
```

#### code-002 - Function Generator
- Placeholders: `CASES, FUNCTION DESCRIPTION, LANGUAGE, NAME, PARAMS, TYPE`
- Prompt:

```text
Write a [LANGUAGE] function that [FUNCTION DESCRIPTION].

Requirements:
- Function name: [NAME]
- Input parameters: [PARAMS]
- Return type: [TYPE]
- Edge cases to handle: [CASES]

Include:
1. Complete function implementation
2. Type hints/annotations (if applicable)
3. Docstring/comments explaining logic
4. Input validation
5. Error handling
6. Unit tests (at least 5 test cases including edge cases)
7. Usage examples
8. Time and space complexity analysis

Code style: [STYLE GUIDE - e.g., PEP 8, Airbnb, Google]

Also provide alternative implementations if there are different approaches (iterative vs. recursive, etc.).
```

#### code-003 - Debug This Code
- Placeholders: `DESCRIBE THE PROBLEM, ERROR, LANGUAGE, PASTE BUGGY CODE HERE, WHAT IT ACTUALLY DOES, WHAT IT SHOULD DO, WHEN/WHERE IT FAILS`
- Prompt:

```text
Help me debug the following [LANGUAGE] code that's [DESCRIBE THE PROBLEM]:

```
[PASTE BUGGY CODE HERE]
```

Expected behavior: [WHAT IT SHOULD DO]
Actual behavior: [WHAT IT ACTUALLY DOES]
Error message (if any): [ERROR]
Context: [WHEN/WHERE IT FAILS]

Please:
1. Identify the root cause of the bug
2. Explain why this bug occurs
3. Provide the corrected code
4. Suggest how to prevent similar bugs
5. Add any helpful logging/debugging statements
6. Recommend test cases to verify the fix

If there are multiple potential causes, list them in order of likelihood.
```

#### code-004 - API Endpoint Generator
- Placeholders: `ENDPOINT PURPOSE, FRAMEWORK, GET/POST/PUT/DELETE, IF ANY, ROUTE PATH, SCHEMA, TYPE`
- Prompt:

```text
Create a REST API endpoint in [FRAMEWORK - Express/FastAPI/Flask/etc.] for [ENDPOINT PURPOSE].

Endpoint specification:
- Route: [ROUTE PATH]
- Method: [GET/POST/PUT/DELETE]
- Request body: [SCHEMA]
- Query parameters: [IF ANY]
- Response format: [SCHEMA]
- Authentication: [TYPE]

Include:
1. Complete endpoint implementation
2. Request validation
3. Error handling with appropriate HTTP status codes
4. Database interaction (if applicable)
5. Authentication/authorization middleware
6. Rate limiting consideration
7. API documentation (OpenAPI/Swagger format)
8. Unit tests
9. Example requests using curl

Follow RESTful best practices and [FRAMEWORK] conventions.
```

#### code-005 - Database Query Optimizer
- Placeholders: `APPROXIMATE ROWS, LIST, MYSQL/POSTGRESQL/ETC, PASTE SQL QUERY HERE, TIME`
- Prompt:

```text
Optimize the following SQL query for better performance:

```sql
[PASTE SQL QUERY HERE]
```

Context:
- Database: [MYSQL/POSTGRESQL/ETC]
- Table sizes: [APPROXIMATE ROWS]
- Current execution time: [TIME]
- Indexes available: [LIST]

Provide:
1. Analysis of current query issues
2. Optimized query version
3. Recommended indexes to add
4. Execution plan analysis
5. Performance improvement estimate
6. Alternative query approaches
7. Caching strategy if applicable

Explain each optimization decision and its expected impact.
```

#### code-006 - Refactoring Assistant
- Placeholders: `LANGUAGE, PASTE CODE HERE`
- Prompt:

```text
Refactor the following [LANGUAGE] code to improve quality:

```
[PASTE CODE HERE]
```

Refactoring goals:
- [GOAL 1 - e.g., improve readability]
- [GOAL 2 - e.g., reduce duplication]
- [GOAL 3 - e.g., add type safety]

Apply these principles:
1. SOLID principles
2. DRY (Don't Repeat Yourself)
3. KISS (Keep It Simple, Stupid)
4. Separation of concerns

Provide:
1. Refactored code
2. Explanation of each change
3. Before/after comparison
4. Any design patterns applied
5. Tests to ensure behavior unchanged
6. Potential further improvements for the future
```

#### code-007 - Unit Test Generator
- Placeholders: `JEST/PYTEST/JUNIT/ETC, LANGUAGE, PASTE CODE HERE`
- Prompt:

```text
Generate comprehensive unit tests for the following [LANGUAGE] code:

```
[PASTE CODE HERE]
```

Testing framework: [JEST/PYTEST/JUNIT/ETC]

Create tests covering:
1. Happy path scenarios
2. Edge cases
3. Error conditions
4. Boundary values
5. Null/undefined handling
6. Type validation

For each test include:
- Descriptive test name
- Arrange/Act/Assert structure
- Clear assertions
- Necessary mocks/stubs
- Comments explaining what's being tested

Also provide:
- Test coverage estimate
- Suggestions for integration tests
- Mock data factories if needed
- Setup/teardown utilities
```

#### code-008 - Documentation Generator
- Placeholders: `LANGUAGE, MARKDOWN/JSDOC/SPHINX/ETC, PASTE CODE HERE`
- Prompt:

```text
Generate comprehensive documentation for the following [LANGUAGE] code:

```
[PASTE CODE HERE]
```

Documentation format: [MARKDOWN/JSDOC/SPHINX/ETC]

Create:

1. Overview Section
- Purpose and description
- Key features
- Dependencies
- Installation/setup

2. API Reference
- All public functions/methods
- Parameters with types
- Return values
- Exceptions/errors thrown
- Usage examples

3. Code Examples
- Basic usage
- Advanced scenarios
- Common patterns
- Anti-patterns to avoid

4. Architecture Notes
- Design decisions
- Data flow
- Integration points

5. Changelog Template
- Version history format
- Breaking changes section
```

#### code-009 - Design Pattern Implementation
- Placeholders: `ANY LIMITATIONS, DESCRIPTION, EXISTING CODE/SYSTEMS, LANGUAGE, USE CASE`
- Prompt:

```text
Implement the [DESIGN PATTERN - e.g., Factory, Observer, Strategy] pattern in [LANGUAGE] for [USE CASE].

Context:
- Problem being solved: [DESCRIPTION]
- Constraints: [ANY LIMITATIONS]
- Integration with: [EXISTING CODE/SYSTEMS]

Provide:

1. Pattern Explanation
- What this pattern does
- When to use it
- Pros and cons

2. Implementation
- Complete code with all classes/interfaces
- Type annotations
- Comments explaining each part

3. Usage Example
- How to use the pattern in practice
- Common variations

4. UML Diagram (text-based)
- Class relationships
- Sequence diagram if applicable

5. Testing
- Unit tests for the implementation

6. Alternatives
- When NOT to use this pattern
- Alternative patterns to consider
```

#### code-010 - Code Explanation
- Placeholders: `BEGINNER/INTERMEDIATE/ADVANCED, LANGUAGE, PASTE CODE HERE`
- Prompt:

```text
Explain the following [LANGUAGE] code in detail:

```
[PASTE CODE HERE]
```

Explanation level: [BEGINNER/INTERMEDIATE/ADVANCED]

Provide:

1. High-Level Overview
- What does this code do?
- What problem does it solve?

2. Line-by-Line Breakdown
- Explain each significant line
- Why each decision was made
- What alternatives exist

3. Key Concepts Used
- Programming concepts
- Language-specific features
- Design patterns if any

4. Data Flow
- How data moves through the code
- State changes
- Side effects

5. Complexity Analysis
- Time complexity
- Space complexity

6. Potential Improvements
- What could be done better
- Modern alternatives

7. Common Mistakes
- Pitfalls to avoid
- Debugging tips
```

#### code-011 - Regex Pattern Builder
- Placeholders: `EXAMPLES OF INVALID, EXAMPLES OF VALID MATCHES, JAVASCRIPT/PYTHON/PCRE/ETC, LANGUAGE, WHAT TO EXTRACT, WHAT TO MATCH`
- Prompt:

```text
Create a regular expression for [WHAT TO MATCH].

Requirements:
- Language/flavor: [JAVASCRIPT/PYTHON/PCRE/ETC]
- Should match: [EXAMPLES OF VALID MATCHES]
- Should NOT match: [EXAMPLES OF INVALID]
- Capture groups needed: [WHAT TO EXTRACT]

Provide:

1. The Regular Expression
- Complete pattern
- Flags needed (g, i, m, etc.)

2. Pattern Breakdown
- Explain each component
- What each part matches

3. Test Cases
- Strings that should match
- Strings that should NOT match
- Edge cases

4. Code Examples
- How to use in [LANGUAGE]
- Extraction examples
- Replace examples

5. Performance Notes
- Potential backtracking issues
- Optimization suggestions

6. Common Variations
- How to modify for similar cases
```

#### code-012 - Error Handling Strategy
- Placeholders: `APPLICATION/MODULE DESCRIPTION, DATABASE/NETWORK/USER INPUT/ETC, DESCRIPTION, LANGUAGE, WEB/API/CLI/ETC, YES/NO`
- Prompt:

```text
Design an error handling strategy for [APPLICATION/MODULE DESCRIPTION] in [LANGUAGE].

Context:
- Application type: [WEB/API/CLI/ETC]
- Error sources: [DATABASE/NETWORK/USER INPUT/ETC]
- Logging system: [DESCRIPTION]
- User-facing: [YES/NO]

Create:

1. Error Classification
- Error categories
- Severity levels
- Error codes system

2. Custom Error Classes
- Base error class
- Specific error types
- Error properties (code, message, context)

3. Error Handling Patterns
- Try-catch strategies
- Middleware/interceptors
- Fallback mechanisms
- Circuit breaker pattern

4. User-Facing Errors
- Error message formatting
- Safe information disclosure
- Localization considerations

5. Logging and Monitoring
- What to log
- Log formats
- Alerting triggers

6. Recovery Strategies
- Retry logic
- Graceful degradation
- Rollback procedures

7. Example Implementation
- Complete code examples
- Integration patterns
```

#### code-013 - CLI Tool Generator
- Placeholders: `IF ANY, LANGUAGE, LIST, NAME, TOOL PURPOSE, YES/NO`
- Prompt:

```text
Create a command-line tool in [LANGUAGE] that [TOOL PURPOSE].

Tool specifications:
- Command name: [NAME]
- Subcommands: [IF ANY]
- Arguments: [LIST]
- Options/flags: [LIST]
- Config file support: [YES/NO]

Include:

1. Main Entry Point
- Argument parsing
- Help text generation
- Version display

2. Command Implementation
- Each subcommand/action
- Input validation
- Output formatting

3. User Experience
- Progress indicators
- Color output
- Interactive prompts
- Error messages

4. Configuration
- Config file format
- Environment variables
- Default values

5. Installation
- Package setup
- Global installation
- Shell completion

6. Documentation
- Usage examples
- Man page or help text
- README content

7. Testing
- Unit tests
- Integration tests
```

#### code-014 - Data Structure Implementation
- Placeholders: `LANGUAGE, SIZE/MEMORY/PERFORMANCE, YES/NO`
- Prompt:

```text
Implement a [DATA STRUCTURE - e.g., linked list, binary tree, hash map] in [LANGUAGE] with full functionality.

Requirements:
- Operations needed: [LIST - insert, delete, search, etc.]
- Constraints: [SIZE/MEMORY/PERFORMANCE]
- Thread-safe: [YES/NO]

Provide:

1. Class/Structure Definition
- Node/element structure
- Main class with all properties
- Type definitions

2. Core Operations
- Insert/Add
- Delete/Remove
- Search/Find
- Update
- Traversal methods

3. Utility Methods
- Size/Length
- IsEmpty
- Clear
- ToArray/ToList
- Iterator implementation

4. Complexity Analysis
- Time complexity for each operation
- Space complexity
- Best/worst case scenarios

5. Testing
- Unit tests for all operations
- Edge case tests
- Performance benchmarks

6. Usage Examples
- Common use cases
- Best practices
```

#### code-015 - Algorithm Implementation
- Placeholders: `ALGORITHM NAME, ANY LIMITS, INPUT FORMAT, LANGUAGE, OUTPUT FORMAT, USE CASE`
- Prompt:

```text
Implement the [ALGORITHM NAME] algorithm in [LANGUAGE] for [USE CASE].

Input: [INPUT FORMAT]
Output: [OUTPUT FORMAT]
Constraints: [ANY LIMITS]

Provide:

1. Algorithm Explanation
- How it works (step-by-step)
- When to use it
- Comparison with alternatives

2. Implementation
- Clean, readable code
- Comments explaining key steps
- Type hints/annotations

3. Complexity Analysis
- Time complexity (best, average, worst)
- Space complexity
- Recurrence relation (if applicable)

4. Variations
- Iterative vs. recursive
- Optimized versions
- In-place modifications

5. Test Cases
- Standard test cases
- Edge cases
- Large input testing

6. Visualization
- Step-by-step trace example
- ASCII diagram if helpful

7. Common Mistakes
- Pitfalls to avoid
- Off-by-one errors
- Edge case handling
```

#### code-016 - Microservice Design
- Placeholders: `DESCRIPTION, EXTERNAL SERVICES, REQUESTS/SEC, SERVICE PURPOSE, TECH STACK`
- Prompt:

```text
Design a microservice architecture for [SERVICE PURPOSE] using [TECH STACK].

Requirements:
- Expected load: [REQUESTS/SEC]
- Data storage needs: [DESCRIPTION]
- Integration points: [EXTERNAL SERVICES]
- Scaling requirements: [DESCRIPTION]

Provide:

1. Service Architecture
- Service boundaries
- API contracts
- Data ownership
- Communication patterns (sync/async)

2. API Design
- Endpoints specification
- Request/response schemas
- Error handling
- Versioning strategy

3. Data Layer
- Database schema
- Caching strategy
- Data consistency approach

4. Infrastructure
- Containerization (Dockerfile)
- Kubernetes/deployment config
- Service discovery
- Load balancing

5. Resilience
- Circuit breakers
- Retry policies
- Fallback mechanisms
- Health checks

6. Observability
- Logging strategy
- Metrics collection
- Distributed tracing
- Alerting

7. Security
- Authentication/authorization
- API security
- Secrets management

8. Code Structure
- Project layout
- Key files and modules
```

#### code-017 - Migration Script Generator
- Placeholders: `DESCRIPTION, MIGRATION PURPOSE, TOOL, TYPE`
- Prompt:

```text
Create a database migration script to [MIGRATION PURPOSE].

Context:
- Database: [TYPE]
- ORM (if any): [TOOL]
- Current schema: [DESCRIPTION]
- Target schema: [DESCRIPTION]
- Data to migrate: [DESCRIPTION]

Provide:

1. Migration Up Script
- Schema changes
- Data transformations
- Index modifications
- Constraint updates

2. Migration Down Script
- Rollback procedures
- Data restoration
- Schema reversion

3. Data Migration
- Batch processing logic
- Progress tracking
- Error handling
- Validation checks

4. Safety Checks
- Pre-migration validations
- Post-migration validations
- Data integrity checks

5. Performance Considerations
- Large table handling
- Zero-downtime strategies
- Lock management

6. Rollback Plan
- Step-by-step rollback
- Point of no return identification
- Backup recommendations

7. Testing Plan
- Test data setup
- Verification queries
- UAT checklist
```

#### code-018 - Authentication System
- Placeholders: `DESCRIPTION, DURATION, EMAIL/PASSWORD/SOCIAL/2FA, FIELDS, FRAMEWORK`
- Prompt:

```text
Implement a [AUTH TYPE - JWT/Session/OAuth] authentication system in [FRAMEWORK].

Requirements:
- User model: [FIELDS]
- Auth methods: [EMAIL/PASSWORD/SOCIAL/2FA]
- Token expiry: [DURATION]
- Refresh strategy: [DESCRIPTION]

Provide:

1. User Registration
- Signup endpoint
- Input validation
- Password hashing
- Email verification (optional)

2. Login/Logout
- Login endpoint
- Token generation
- Session management
- Logout handling

3. Password Management
- Password reset flow
- Change password
- Password strength validation

4. Token Management
- Token generation
- Token validation middleware
- Refresh token mechanism
- Token revocation

5. Protected Routes
- Auth middleware
- Role-based access
- Route protection patterns

6. Security Measures
- Rate limiting
- Brute force protection
- Secure cookie settings
- CSRF protection

7. Testing
- Auth flow tests
- Security tests
- Edge case handling
```

#### code-019 - WebSocket Implementation
- Placeholders: `DESCRIPTION, LANGUAGE/FRAMEWORK, LIST, METHOD, YES/NO`
- Prompt:

```text
Implement a WebSocket server and client for [USE CASE - chat, real-time updates, etc.] in [LANGUAGE/FRAMEWORK].

Requirements:
- Message types: [LIST]
- Rooms/channels: [YES/NO]
- Authentication: [METHOD]
- Scaling needs: [DESCRIPTION]

Provide:

1. Server Implementation
- WebSocket server setup
- Connection handling
- Message routing
- Room/channel management
- Error handling

2. Client Implementation
- Connection establishment
- Reconnection logic
- Message sending/receiving
- Event handling

3. Message Protocol
- Message format (JSON schema)
- Event types
- Acknowledgment system

4. Authentication
- Connection authentication
- Token refresh handling
- Session management

5. Scaling Considerations
- Pub/sub for multiple servers
- Redis adapter setup
- Horizontal scaling

6. Error Handling
- Connection errors
- Message errors
- Timeout handling

7. Testing
- Connection tests
- Message tests
- Load testing approach
```

#### code-020 - Caching Strategy
- Placeholders: `APPLICATION COMPONENT, CACHE TECHNOLOGY, DESCRIPTION, RATIO, TTL`
- Prompt:

```text
Design and implement a caching strategy for [APPLICATION COMPONENT] using [CACHE TECHNOLOGY].

Context:
- Data type: [DESCRIPTION]
- Read/write ratio: [RATIO]
- Cache invalidation needs: [DESCRIPTION]
- Data freshness requirement: [TTL]

Provide:

1. Cache Design
- Cache key structure
- TTL strategy
- Eviction policy
- Size limits

2. Implementation
- Cache client setup
- Read-through pattern
- Write-through/behind pattern
- Cache-aside pattern

3. Cache Operations
- Get/Set operations
- Bulk operations
- Atomic operations
- TTL management

4. Invalidation Strategy
- Event-based invalidation
- Time-based expiry
- Manual purge
- Cache warming

5. Error Handling
- Cache miss handling
- Connection failures
- Fallback mechanisms

6. Monitoring
- Hit/miss ratio
- Latency metrics
- Memory usage

7. Code Examples
- Decorator/wrapper patterns
- Middleware integration
- Testing utilities
```

#### code-021 - Logging System Design
- Placeholders: `APPLICATION TYPE, CONSOLE/FILE/EXTERNAL, DURATION, JSON/TEXT/CUSTOM, LANGUAGE/FRAMEWORK, LIST`
- Prompt:

```text
Design a comprehensive logging system for [APPLICATION TYPE] in [LANGUAGE/FRAMEWORK].

Requirements:
- Log levels needed: [LIST]
- Output destinations: [CONSOLE/FILE/EXTERNAL]
- Log format: [JSON/TEXT/CUSTOM]
- Retention policy: [DURATION]

Provide:

1. Logger Configuration
- Logger setup
- Level configuration
- Output handlers
- Formatting

2. Log Message Structure
- Required fields
- Context data
- Correlation IDs
- Timestamp format

3. Logging Patterns
- Request/response logging
- Error logging
- Performance logging
- Audit logging

4. Integration
- Framework integration
- Middleware/interceptors
- Error handler integration

5. Performance
- Async logging
- Buffer management
- Sampling strategies

6. Log Management
- Rotation configuration
- Compression
- Cleanup automation

7. External Integration
- ELK stack setup
- Cloud logging services
- Alerting integration

8. Example Code
- Logger wrapper class
- Usage examples
- Best practices
```

#### code-022 - File Processing Pipeline
- Placeholders: `BATCH/REAL-TIME, FORMAT, LANGUAGE, PROCESSING DESCRIPTION, RANGE, WHERE`
- Prompt:

```text
Create a file processing pipeline in [LANGUAGE] that [PROCESSING DESCRIPTION].

Input:
- File format: [FORMAT]
- File size range: [RANGE]
- Processing frequency: [BATCH/REAL-TIME]

Output:
- Result format: [FORMAT]
- Destination: [WHERE]

Provide:

1. File Reading
- File discovery/watching
- Format parsing
- Streaming for large files
- Encoding handling

2. Validation
- Schema validation
- Data quality checks
- Error records handling

3. Transformation
- Data mapping
- Calculations
- Enrichment
- Aggregation

4. Output
- Result formatting
- File writing
- External service integration

5. Error Handling
- Malformed data
- Partial failures
- Retry logic
- Dead letter queue

6. Monitoring
- Progress tracking
- Performance metrics
- Alerting

7. Performance
- Parallel processing
- Memory management
- Checkpointing

8. Code Implementation
- Complete pipeline code
- Configuration options
- Testing utilities
```

#### code-023 - GraphQL Schema Generator
- Placeholders: `DESCRIBE RELATIONSHIPS, DOMAIN/APPLICATION, ENTITY 1, ENTITY 2, ENTITY 3, FIELDS`
- Prompt:

```text
Design and implement a GraphQL schema for [DOMAIN/APPLICATION].

Data entities:
- [ENTITY 1]: [FIELDS]
- [ENTITY 2]: [FIELDS]
- [ENTITY 3]: [FIELDS]

Relationships:
- [DESCRIBE RELATIONSHIPS]

Provide:

1. Schema Definition
- Type definitions
- Input types
- Enums
- Interfaces
- Unions

2. Queries
- Single entity queries
- List queries with pagination
- Filtered queries
- Nested queries

3. Mutations
- Create operations
- Update operations
- Delete operations
- Batch operations

4. Resolvers
- Query resolvers
- Mutation resolvers
- Field resolvers
- DataLoader for N+1 prevention

5. Subscriptions (if needed)
- Real-time updates
- Event handling

6. Authentication/Authorization
- Directive-based auth
- Field-level permissions

7. Error Handling
- Error types
- Error formatting
- Client-friendly messages

8. Testing
- Query tests
- Mutation tests
- Integration tests
```

#### code-024 - Rate Limiter Implementation
- Placeholders: `API/SERVICE, IP/USER/API KEY, LANGUAGE, REQUESTS, TIME WINDOW, TOKEN BUCKET/SLIDING WINDOW/FIXED WINDOW, YES/NO`
- Prompt:

```text
Implement a rate limiting system for [API/SERVICE] in [LANGUAGE].

Requirements:
- Rate limit: [REQUESTS] per [TIME WINDOW]
- Algorithm: [TOKEN BUCKET/SLIDING WINDOW/FIXED WINDOW]
- Scope: [IP/USER/API KEY]
- Distributed: [YES/NO]

Provide:

1. Algorithm Implementation
- Core rate limiting logic
- Time window management
- Counter/bucket management

2. Storage Backend
- In-memory option
- Redis option (for distributed)
- Database option

3. Middleware Integration
- Express/FastAPI/etc. middleware
- Request identification
- Response headers (X-RateLimit-*)

4. Configuration
- Rate limit rules
- Custom limits per endpoint
- Dynamic configuration

5. Response Handling
- 429 Too Many Requests
- Retry-After header
- Custom error messages

6. Advanced Features
- Burst allowance
- Graceful degradation
- Rate limit bypass (whitelist)

7. Monitoring
- Metrics collection
- Alerting thresholds
- Dashboard suggestions

8. Testing
- Unit tests
- Load tests
- Edge case tests
```

#### code-025 - Feature Flag System
- Placeholders: `APPLICATION, BOOLEAN/PERCENTAGE/USER SEGMENT, CONFIG/DATABASE/SERVICE, LANGUAGE/FRAMEWORK, REAL-TIME/POLLING`
- Prompt:

```text
Implement a feature flag system for [APPLICATION] in [LANGUAGE/FRAMEWORK].

Requirements:
- Flag types: [BOOLEAN/PERCENTAGE/USER SEGMENT]
- Storage: [CONFIG/DATABASE/SERVICE]
- Update mechanism: [REAL-TIME/POLLING]

Provide:

1. Core System
- Flag definition schema
- Flag evaluation logic
- Default value handling

2. Flag Types
- Boolean flags
- Percentage rollout
- User targeting
- Environment-based

3. Storage Layer
- Configuration file option
- Database storage
- External service integration

4. SDK/Client
- Flag checking API
- Caching strategy
- Fallback handling

5. Evaluation Rules
- User attribute matching
- Segment definitions
- Override logic

6. Administrative
- CRUD operations
- Audit logging
- Emergency kill switch

7. Integration Patterns
- Middleware approach
- Decorator pattern
- React/Vue components

8. Testing
- Unit tests with flag mocking
- Integration tests
- A/B test support
```

#### code-026 - Background Job System
- Placeholders: `DESCRIPTION, LANGUAGE/FRAMEWORK, LIST, REDIS/RABBITMQ/DATABASE, WORKERS`
- Prompt:

```text
Implement a background job processing system in [LANGUAGE/FRAMEWORK].

Requirements:
- Job types: [LIST]
- Queue backend: [REDIS/RABBITMQ/DATABASE]
- Concurrency: [WORKERS]
- Retry policy: [DESCRIPTION]

Provide:

1. Job Definition
- Job base class/interface
- Job parameters
- Job metadata
- Priority levels

2. Queue Management
- Queue connection
- Job enqueuing
- Job dequeuing
- Multiple queues

3. Worker Implementation
- Worker process
- Concurrent execution
- Graceful shutdown
- Worker pools

4. Job Lifecycle
- Job states
- Progress tracking
- Result storage
- Completion callbacks

5. Error Handling
- Retry mechanisms
- Exponential backoff
- Dead letter queue
- Error notifications

6. Scheduling
- Delayed jobs
- Recurring jobs (cron)
- Job dependencies

7. Monitoring
- Job metrics
- Queue depth
- Worker status
- Dashboard setup

8. Testing
- Job testing utilities
- Queue mocking
- Integration tests
```

#### code-027 - Search Implementation
- Placeholders: `APPLICATION, CRITERIA, DATA TYPE, FULL-TEXT/FUZZY/FILTERS/FACETS, LIST, RESPONSE TIME, SEARCH ENGINE/DATABASE`
- Prompt:

```text
Implement search functionality for [DATA TYPE] in [APPLICATION] using [SEARCH ENGINE/DATABASE].

Requirements:
- Searchable fields: [LIST]
- Search features: [FULL-TEXT/FUZZY/FILTERS/FACETS]
- Result ranking: [CRITERIA]
- Performance target: [RESPONSE TIME]

Provide:

1. Index Design
- Index schema
- Field mappings
- Analyzers/tokenizers
- Synonym handling

2. Indexing Pipeline
- Document indexing
- Bulk indexing
- Real-time updates
- Re-indexing strategy

3. Search API
- Query parsing
- Filter building
- Sorting options
- Pagination

4. Query Features
- Full-text search
- Fuzzy matching
- Phrase matching
- Boosting

5. Facets and Filters
- Facet extraction
- Filter application
- Range queries
- Aggregations

6. Performance
- Query optimization
- Caching
- Async indexing

7. Relevance Tuning
- Scoring customization
- A/B testing approach
- User feedback integration

8. Code Implementation
- Search service
- API endpoints
- Frontend integration
```

#### code-028 - Event-Driven Architecture
- Placeholders: `AT LEAST ONCE/EXACTLY ONCE, DESCRIPTION, EVENT 1, EVENT 2, EVENT 3, KAFKA/RABBITMQ/SQS/ETC, LANGUAGE/FRAMEWORK, REQUIRED/NOT REQUIRED, USE CASE`
- Prompt:

```text
Design an event-driven system for [USE CASE] in [LANGUAGE/FRAMEWORK].

Event types:
- [EVENT 1]: [DESCRIPTION]
- [EVENT 2]: [DESCRIPTION]
- [EVENT 3]: [DESCRIPTION]

Requirements:
- Message broker: [KAFKA/RABBITMQ/SQS/ETC]
- Ordering: [REQUIRED/NOT REQUIRED]
- Delivery guarantee: [AT LEAST ONCE/EXACTLY ONCE]

Provide:

1. Event Schema
- Event structure
- Metadata fields
- Versioning strategy
- Schema registry

2. Event Producer
- Event creation
- Publishing logic
- Retry handling
- Batching

3. Event Consumer
- Subscription setup
- Message handling
- Acknowledgment
- Consumer groups

4. Event Processing
- Idempotency handling
- Error handling
- Dead letter queue
- Replay capability

5. Event Sourcing (if applicable)
- Event store
- Aggregate reconstruction
- Snapshots

6. CQRS (if applicable)
- Command handling
- Query optimization
- Eventual consistency

7. Monitoring
- Event tracking
- Lag monitoring
- Error alerting

8. Testing
- Event testing
- Integration tests
- Chaos testing
```

#### code-029 - Configuration Management
- Placeholders: `APPLICATION TYPE, LANGUAGE, SCHEMA, YES/NO`
- Prompt:

```text
Design a configuration management system for [APPLICATION TYPE] in [LANGUAGE].

Configuration sources:
- Environment variables
- Configuration files
- Secret manager
- Remote config service

Requirements:
- Environment-specific configs
- Secret handling
- Hot reload: [YES/NO]
- Validation: [SCHEMA]

Provide:

1. Configuration Schema
- Config structure
- Type definitions
- Default values
- Required fields

2. Loading Strategy
- Source priority order
- Override rules
- Merge logic

3. Validation
- Schema validation
- Type coercion
- Custom validators
- Error messaging

4. Environment Handling
- Environment detection
- Config per environment
- Feature toggles

5. Secrets Management
- Secure storage
- Access patterns
- Rotation support
- Encryption at rest

6. Runtime Behavior
- Hot reload mechanism
- Change notifications
- Fallback handling

7. Developer Experience
- IDE support (typing)
- Documentation
- Example configs

8. Code Implementation
- Config module
- Access patterns
- Testing utilities
```

#### code-030 - CI/CD Pipeline Generator
- Placeholders: `FRAMEWORK, LANGUAGE, PROJECT TYPE, TEST FRAMEWORK`
- Prompt:

```text
Create a CI/CD pipeline for [PROJECT TYPE] using [CI/CD TOOL - GitHub Actions/GitLab CI/Jenkins].

Project details:
- Language: [LANGUAGE]
- Framework: [FRAMEWORK]
- Testing: [TEST FRAMEWORK]
- Deployment: [TARGET - K8s/AWS/Heroku/etc.]

Provide:

1. Pipeline Configuration
- Complete YAML/Jenkinsfile
- Stages definition
- Job dependencies

2. Build Stage
- Dependency installation
- Compilation/build
- Artifact creation

3. Test Stage
- Unit tests
- Integration tests
- Code coverage
- Linting/formatting

4. Security Scanning
- Dependency scanning
- SAST scanning
- Secret detection

5. Deploy Stage
- Environment-specific deploys
- Deployment strategies
- Rollback procedures

6. Advanced Features
- Matrix builds
- Caching strategies
- Parallel execution
- Manual approvals

7. Notifications
- Slack/email notifications
- Status badges
- Failure alerts

8. Best Practices
- Branch protection
- Environment variables
- Secrets management
```

#### code-031 - Database Connection Pool
- Placeholders: `DATABASE TYPE, LANGUAGE, MIN-MAX, SECONDS, YES/NO`
- Prompt:

```text
Implement a database connection pool for [DATABASE TYPE] in [LANGUAGE].

Requirements:
- Pool size: [MIN-MAX]
- Connection timeout: [SECONDS]
- Idle timeout: [SECONDS]
- Health checks: [YES/NO]

Provide:

1. Pool Configuration
- Configuration options
- Default values
- Validation

2. Connection Management
- Connection creation
- Connection acquisition
- Connection release
- Connection validation

3. Pool Behavior
- Min/max pool size
- Connection eviction
- Overflow handling
- Waiting queue

4. Health Monitoring
- Connection health checks
- Pool statistics
- Metrics exposure

5. Error Handling
- Connection failures
- Pool exhaustion
- Recovery mechanisms

6. Thread Safety
- Lock management
- Concurrent access
- Deadlock prevention

7. Integration
- Framework integration
- Transaction support
- Context managers

8. Testing
- Pool tests
- Stress tests
- Failure scenario tests
```

#### code-032 - Middleware Chain Pattern
- Placeholders: `FRAMEWORK/APPLICATION, LANGUAGE, MIDDLEWARE 1, MIDDLEWARE 2, MIDDLEWARE 3, PURPOSE`
- Prompt:

```text
Implement a middleware chain pattern for [FRAMEWORK/APPLICATION] in [LANGUAGE].

Middleware use cases:
- [MIDDLEWARE 1]: [PURPOSE]
- [MIDDLEWARE 2]: [PURPOSE]
- [MIDDLEWARE 3]: [PURPOSE]

Provide:

1. Middleware Interface
- Base middleware class/interface
- Next function pattern
- Context passing

2. Chain Management
- Middleware registration
- Ordering control
- Conditional middleware

3. Common Middlewares
- Logging middleware
- Authentication middleware
- Error handling middleware
- Request validation middleware
- CORS middleware

4. Context Object
- Request context
- Response modifications
- State sharing

5. Error Handling
- Error propagation
- Error recovery
- Error middleware

6. Performance
- Async middleware
- Early termination
- Caching in chain

7. Testing
- Middleware isolation
- Chain testing
- Mock utilities

8. Code Examples
- Complete chain setup
- Custom middleware
- Integration examples
```

#### code-033 - ORM Model Generator
- Placeholders: `COLUMNS, DATABASE SCHEMA, DESCRIBE RELATIONSHIPS, TABLE 1, TABLE 2, TABLE 3`
- Prompt:

```text
Generate ORM models for [DATABASE SCHEMA] using [ORM - SQLAlchemy/TypeORM/Prisma/etc.].

Tables:
- [TABLE 1]: [COLUMNS]
- [TABLE 2]: [COLUMNS]
- [TABLE 3]: [COLUMNS]

Relationships:
- [DESCRIBE RELATIONSHIPS]

Provide:

1. Model Definitions
- All model classes
- Column definitions
- Type mappings
- Constraints

2. Relationships
- One-to-one
- One-to-many
- Many-to-many
- Self-referential

3. Indexes
- Primary keys
- Foreign keys
- Unique constraints
- Composite indexes

4. Validations
- Field validators
- Custom validations
- Constraints

5. Query Helpers
- Common queries
- Eager loading
- Filtering helpers

6. Migrations
- Initial migration
- Migration commands

7. Serialization
- To dict/JSON
- Nested serialization
- Excluding fields

8. Repository Pattern
- Base repository
- Entity-specific repositories
- CRUD operations
```

#### code-034 - Notification System
- Placeholders: `APPLICATION, CHANNEL 1, CHANNEL 2, EMAIL/SMS/PUSH/IN-APP, LANGUAGE`
- Prompt:

```text
Design and implement a notification system for [APPLICATION] in [LANGUAGE].

Notification channels:
- [CHANNEL 1]: [EMAIL/SMS/PUSH/IN-APP]
- [CHANNEL 2]: [EMAIL/SMS/PUSH/IN-APP]

Requirements:
- User preferences
- Templates
- Scheduling
- Tracking

Provide:

1. Notification Types
- Type definitions
- Priority levels
- Category system

2. Channel Implementations
- Email sender
- SMS sender
- Push notification
- In-app notification

3. Template System
- Template structure
- Variable substitution
- Localization

4. User Preferences
- Preference model
- Channel preferences
- Frequency settings
- Do-not-disturb

5. Delivery System
- Queue integration
- Retry logic
- Batching
- Rate limiting

6. Tracking
- Delivery status
- Read receipts
- Click tracking
- Analytics

7. API
- Send notification
- Get notifications
- Mark as read
- Preference management

8. Testing
- Mock senders
- Integration tests
- Template tests
```

#### code-035 - Serialization/Deserialization
- Placeholders: `DATA STRUCTURE, HANDLING, JSON/PROTOBUF/MSGPACK/CUSTOM, LANGUAGE, SPEED/SIZE, YES/NO`
- Prompt:

```text
Implement custom serialization/deserialization for [DATA STRUCTURE] in [LANGUAGE].

Requirements:
- Format: [JSON/PROTOBUF/MSGPACK/CUSTOM]
- Backward compatibility: [YES/NO]
- Performance priority: [SPEED/SIZE]
- Nullable fields: [HANDLING]

Provide:

1. Schema Definition
- Data structure
- Field types
- Optional fields
- Nested structures

2. Serialization
- Encoding logic
- Type handling
- Null handling
- Date/time handling

3. Deserialization
- Decoding logic
- Type coercion
- Validation
- Error handling

4. Versioning
- Version field
- Migration logic
- Backward compatibility
- Forward compatibility

5. Custom Types
- Custom type handlers
- Enum handling
- Binary data

6. Performance
- Streaming support
- Buffer management
- Benchmarks

7. Edge Cases
- Circular references
- Large objects
- Unicode handling

8. Testing
- Round-trip tests
- Edge case tests
- Performance tests
```

#### code-036 - Dependency Injection Container
- Placeholders: `LANGUAGE/FRAMEWORK, SINGLETON/TRANSIENT/SCOPED, YES/NO`
- Prompt:

```text
Implement a dependency injection container for [LANGUAGE/FRAMEWORK].

Requirements:
- Lifetime scopes: [SINGLETON/TRANSIENT/SCOPED]
- Auto-wiring: [YES/NO]
- Lazy loading: [YES/NO]

Provide:

1. Container Implementation
- Registration API
- Resolution logic
- Lifetime management

2. Registration Methods
- Type registration
- Instance registration
- Factory registration
- Named registrations

3. Resolution
- Dependency resolution
- Circular dependency detection
- Optional dependencies

4. Lifetime Scopes
- Singleton scope
- Transient scope
- Scoped lifetime
- Custom scopes

5. Auto-Wiring
- Constructor injection
- Property injection
- Method injection

6. Integration
- Framework integration
- Middleware setup
- Controller injection

7. Advanced Features
- Decorators
- Interceptors
- Child containers

8. Testing
- Container tests
- Mock injection
- Scope tests
```

#### code-037 - HTTP Client Wrapper
- Placeholders: `LANGUAGE`
- Prompt:

```text
Create a robust HTTP client wrapper for [LANGUAGE] with [BASE LIBRARY - axios/fetch/httpx/etc.].

Features needed:
- Request/response interceptors
- Retry logic
- Timeout handling
- Authentication
- Response caching

Provide:

1. Client Configuration
- Base URL
- Default headers
- Timeout settings
- SSL configuration

2. Request Methods
- GET, POST, PUT, DELETE, PATCH
- Request body handling
- Query parameters
- File uploads

3. Interceptors
- Request interceptors
- Response interceptors
- Error interceptors

4. Retry Logic
- Retry conditions
- Exponential backoff
- Max retries
- Retry callbacks

5. Error Handling
- HTTP error classes
- Network errors
- Timeout errors
- Error normalization

6. Authentication
- Bearer token
- API key
- OAuth flow
- Token refresh

7. Caching
- Response caching
- Cache invalidation
- ETag support

8. Testing
- Mock server
- Request assertions
- Error simulation
```

#### code-038 - State Machine Implementation
- Placeholders: `DESCRIPTION, FROM, LANGUAGE, STATE 1, STATE 2, STATE 3, TO, TRIGGER`
- Prompt:

```text
Implement a state machine for [USE CASE - order processing, workflow, etc.] in [LANGUAGE].

States:
- [STATE 1]: [DESCRIPTION]
- [STATE 2]: [DESCRIPTION]
- [STATE 3]: [DESCRIPTION]

Transitions:
- [FROM] -> [TO]: [TRIGGER]

Provide:

1. State Definition
- State enum/constants
- State metadata
- Initial state
- Final states

2. Transition Definition
- Transition rules
- Guards/conditions
- Actions
- Side effects

3. State Machine Core
- Current state tracking
- Transition execution
- Event dispatching
- State history

4. Guards
- Guard conditions
- Async guards
- Guard composition

5. Actions
- Entry actions
- Exit actions
- Transition actions
- Action error handling

6. Persistence
- State storage
- State restoration
- History tracking

7. Visualization
- State diagram generation
- Current state display

8. Testing
- Transition tests
- Guard tests
- Action tests
- Integration tests
```

#### code-039 - Metrics Collection System
- Placeholders: `APPLICATION, METRIC 1, METRIC 2, METRIC 3, TYPE`
- Prompt:

```text
Implement a metrics collection system for [APPLICATION] using [METRICS BACKEND - Prometheus/StatsD/Custom].

Metrics needed:
- [METRIC 1]: [TYPE - counter/gauge/histogram]
- [METRIC 2]: [TYPE]
- [METRIC 3]: [TYPE]

Provide:

1. Metric Types
- Counter implementation
- Gauge implementation
- Histogram implementation
- Summary implementation

2. Metric Registry
- Metric registration
- Naming conventions
- Labels/tags
- Help text

3. Collection
- Automatic collection
- Custom collectors
- Collection intervals

4. Instrumentation
- Request duration
- Request count
- Error rates
- Custom business metrics

5. Export
- Prometheus endpoint
- Push gateway
- Multiple backends

6. Best Practices
- Metric naming
- Cardinality control
- Label best practices

7. Dashboards
- Grafana dashboard JSON
- Key visualizations
- Alert conditions

8. Testing
- Metric assertions
- Mock collectors
- Integration tests
```

#### code-040 - Data Validation Library
- Placeholders: `LANGUAGE`
- Prompt:

```text
Create a data validation library for [LANGUAGE] similar to [ZOD/YUP/CERBERUS/etc.].

Features needed:
- Schema definition
- Type validation
- Custom validators
- Error messages
- Async validation

Provide:

1. Schema Builders
- String schema
- Number schema
- Boolean schema
- Array schema
- Object schema
- Custom schema

2. Validation Rules
- Required/optional
- Min/max length
- Pattern matching
- Email/URL/UUID
- Enum values

3. Composition
- Schema merging
- Conditional schemas
- Union types
- Intersection types

4. Custom Validators
- Custom rule creation
- Async validators
- Cross-field validation

5. Error Handling
- Error structure
- Path tracking
- Custom messages
- Internationalization

6. Type Inference
- Type generation
- IDE support
- Generic types

7. Transformations
- Coercion
- Default values
- Trimming/normalization

8. Testing
- Validation tests
- Error tests
- Type tests
```

#### code-041 - API Rate Limiter Client
- Placeholders: `FIFO/PRIORITY, LANGUAGE, SHARED/SEPARATE LIMITS, YES/NO`
- Prompt:

```text
Implement a client-side rate limiter for API calls in [LANGUAGE].

Requirements:
- Rate limit: [X requests per Y seconds]
- Queue strategy: [FIFO/PRIORITY]
- Retry on 429: [YES/NO]
- Multiple endpoints: [SHARED/SEPARATE LIMITS]

Provide:

1. Rate Limiter Core
- Token bucket/sliding window
- Time tracking
- Request queuing

2. Queue Management
- Request queue
- Priority handling
- Queue limits
- Timeout handling

3. Request Execution
- Rate-limited execution
- Batch support
- Cancellation

4. Retry Logic
- 429 handling
- Retry-After header
- Exponential backoff

5. Multiple Endpoints
- Per-endpoint limits
- Global limits
- Rate limit pools

6. Monitoring
- Queue depth
- Wait times
- Rejection rates

7. Integration
- HTTP client wrapper
- Decorator pattern
- Async support

8. Testing
- Rate limit tests
- Queue tests
- Timing tests
```

#### code-042 - Plugin System Architecture
- Placeholders: `API/EVENTS, APPLICATION, DYNAMIC/STATIC, LANGUAGE, SANDBOXED/TRUSTED, TYPES`
- Prompt:

```text
Design and implement a plugin system for [APPLICATION] in [LANGUAGE].

Requirements:
- Plugin types: [TYPES]
- Loading: [DYNAMIC/STATIC]
- Isolation: [SANDBOXED/TRUSTED]
- Communication: [API/EVENTS]

Provide:

1. Plugin Interface
- Base plugin class
- Lifecycle hooks
- Metadata structure
- Version requirements

2. Plugin Manager
- Plugin discovery
- Loading/unloading
- Dependency resolution
- Version checking

3. Lifecycle Management
- Initialize
- Activate
- Deactivate
- Uninstall

4. Extension Points
- Hook system
- Event bus
- API extension
- UI extension

5. Plugin Communication
- Inter-plugin communication
- Host application API
- Event subscriptions

6. Security
- Permission system
- Sandboxing
- Resource limits

7. Configuration
- Plugin settings
- User preferences
- Defaults

8. Example Plugin
- Complete plugin example
- Documentation
- Best practices
```

#### code-043 - Concurrent Task Executor
- Placeholders: `CPU-BOUND/IO-BOUND, LANGUAGE, NUMBER, PATTERN, USE CASE, YES/NO`
- Prompt:

```text
Implement a concurrent task executor in [LANGUAGE] for [USE CASE].

Requirements:
- Max concurrency: [NUMBER]
- Task types: [CPU-BOUND/IO-BOUND]
- Priority support: [YES/NO]
- Result handling: [PATTERN]

Provide:

1. Task Definition
- Task interface
- Task metadata
- Priority levels
- Cancellation tokens

2. Executor Core
- Worker pool
- Task scheduling
- Concurrency control
- Load balancing

3. Queue Management
- Task queue
- Priority queue
- Fair scheduling
- Starvation prevention

4. Result Handling
- Future/Promise pattern
- Callback pattern
- Result aggregation
- Partial results

5. Error Handling
- Task failures
- Worker failures
- Circuit breaker
- Fallbacks

6. Lifecycle
- Startup
- Graceful shutdown
- Forced shutdown
- Worker recycling

7. Monitoring
- Active tasks
- Queue depth
- Completion rates
- Error rates

8. Testing
- Concurrency tests
- Edge case tests
- Performance tests
```

#### code-044 - Query Builder Pattern
- Placeholders: `DATABASE TYPE, LANGUAGE`
- Prompt:

```text
Implement a fluent query builder for [DATABASE TYPE] in [LANGUAGE].

Features:
- SELECT, INSERT, UPDATE, DELETE
- WHERE clauses
- JOINs
- Subqueries
- Aggregations

Provide:

1. Builder Core
- Fluent interface
- Query state
- Method chaining

2. SELECT Operations
- Column selection
- Aliases
- Distinct
- Aggregate functions

3. WHERE Clauses
- Comparison operators
- Logical operators
- IN, LIKE, BETWEEN
- NULL checks
- Nested conditions

4. JOIN Operations
- Inner join
- Left/right join
- Cross join
- Multiple joins

5. Grouping & Ordering
- GROUP BY
- HAVING
- ORDER BY
- LIMIT/OFFSET

6. Subqueries
- Subquery support
- EXISTS/NOT EXISTS
- IN subquery

7. Query Execution
- SQL generation
- Parameter binding
- Execution methods

8. Testing
- SQL output tests
- Integration tests
- Edge cases
```

#### code-045 - File Upload Handler
- Placeholders: `FRAMEWORK, LIST, SIZE, YES/NO`
- Prompt:

```text
Implement a robust file upload handler for [FRAMEWORK] supporting [STORAGE - local/S3/GCS].

Requirements:
- Max file size: [SIZE]
- Allowed types: [LIST]
- Chunked upload: [YES/NO]
- Resume support: [YES/NO]

Provide:

1. Upload Endpoint
- Multipart handling
- Streaming upload
- Progress tracking

2. Validation
- File size check
- MIME type validation
- File extension check
- Malware scanning hook

3. Storage
- Local storage
- S3/GCS integration
- Path generation
- Naming strategy

4. Chunked Upload
- Chunk handling
- Chunk assembly
- Resume token
- Cleanup

5. Post-Processing
- Image resizing
- Video transcoding
- Thumbnail generation

6. Security
- Path traversal prevention
- Filename sanitization
- Access control

7. Response
- Progress events
- Success response
- Error handling

8. Testing
- Upload tests
- Large file tests
- Error scenario tests
```

#### code-046 - API Versioning Strategy
- Placeholders: `DESCRIPTION, FRAMEWORK, LIST, URL/HEADER/QUERY PARAM`
- Prompt:

```text
Implement API versioning for [FRAMEWORK] REST API.

Versioning method: [URL/HEADER/QUERY PARAM]
Current versions: [LIST]
Deprecation policy: [DESCRIPTION]

Provide:

1. Version Detection
- Version extraction
- Default version
- Version validation

2. Routing Strategy
- Version-based routing
- Controller organization
- Shared logic handling

3. URL Path Versioning
- Route prefixes
- Version constraints
- Documentation URLs

4. Header Versioning
- Custom header handling
- Content negotiation
- Accept header parsing

5. Response Handling
- Version in response
- Deprecation warnings
- Sunset headers

6. Documentation
- Per-version docs
- Version comparison
- Migration guides

7. Backward Compatibility
- Response transformation
- Field mapping
- Graceful degradation

8. Testing
- Version tests
- Compatibility tests
- Migration tests
```

#### code-047 - Audit Logging System
- Placeholders: `APPLICATION, EVENT TYPE 1, EVENT TYPE 2, EVENT TYPE 3, LANGUAGE`
- Prompt:

```text
Implement an audit logging system for [APPLICATION] in [LANGUAGE].

Events to track:
- [EVENT TYPE 1]
- [EVENT TYPE 2]
- [EVENT TYPE 3]

Requirements:
- Immutability
- Searchable
- Compliance: [GDPR/HIPAA/SOC2/etc.]

Provide:

1. Audit Event Schema
- Event structure
- Required fields
- Metadata
- Timestamps

2. Event Capture
- Automatic capture
- Manual logging
- Context propagation
- Request tracking

3. Storage
- Database schema
- Immutability enforcement
- Retention policy
- Archival strategy

4. User Context
- User identification
- IP tracking
- User agent
- Session info

5. Change Tracking
- Before/after values
- Diff generation
- Related entities

6. Query Interface
- Search API
- Filtering
- Date range queries
- Export functionality

7. Security
- Access control
- Encryption
- Tamper detection

8. Compliance
- Retention automation
- Export for audits
- Report generation
```

#### code-048 - Health Check Endpoints
- Placeholders: `APPLICATION/SERVICE, CACHE, DATABASE, EXTERNAL API, FRAMEWORK, MESSAGE QUEUE`
- Prompt:

```text
Implement health check endpoints for [APPLICATION/SERVICE] in [FRAMEWORK].

Dependencies to check:
- [DATABASE]
- [CACHE]
- [EXTERNAL API]
- [MESSAGE QUEUE]

Provide:

1. Health Endpoint
- Liveness probe
- Readiness probe
- Deep health check

2. Check Implementation
- Database connectivity
- Cache connectivity
- External service checks
- Disk space
- Memory usage

3. Response Format
- Health status schema
- Component status
- Response times
- Error details

4. Timeout Handling
- Per-check timeouts
- Overall timeout
- Async checks

5. Caching
- Check result caching
- Cache invalidation
- Freshness control

6. Kubernetes Integration
- Liveness probe config
- Readiness probe config
- Startup probe

7. Alerting Integration
- Metric exposure
- Alert rules
- Dashboard config

8. Testing
- Health check tests
- Failure simulation
- Timeout tests
```

#### code-049 - Batch Processing Framework
- Placeholders: `DATA TYPE, LANGUAGE, SIZE, SKIP/RETRY/FAIL, YES/NO`
- Prompt:

```text
Implement a batch processing framework for [DATA TYPE] in [LANGUAGE].

Requirements:
- Batch size: [SIZE]
- Parallel processing: [YES/NO]
- Checkpointing: [YES/NO]
- Error handling: [SKIP/RETRY/FAIL]

Provide:

1. Batch Definition
- Batch configuration
- Item type
- Processing function

2. Reader
- Data source reading
- Chunking logic
- Cursor management

3. Processor
- Item transformation
- Validation
- Business logic

4. Writer
- Output handling
- Bulk operations
- Transaction management

5. Error Handling
- Skip policies
- Retry configuration
- Error logging
- Recovery strategies

6. Checkpointing
- Progress saving
- Resume capability
- Checkpoint storage

7. Monitoring
- Progress tracking
- Performance metrics
- Status reporting

8. Testing
- Unit tests
- Integration tests
- Large dataset tests
```

#### code-050 - Code Generation Template
- Placeholders: `FORMAT, LANGUAGE/FRAMEWORK`
- Prompt:

```text
Create a code generation system for [ARTIFACT TYPE - models, APIs, tests] from [SOURCE - schema, spec, database].

Input format: [FORMAT]
Output: [LANGUAGE/FRAMEWORK]

Provide:

1. Parser
- Input parsing
- Schema validation
- Type extraction

2. Template Engine
- Template syntax
- Variable substitution
- Loops and conditionals
- Partials/includes

3. Code Templates
- Model template
- Repository template
- Controller template
- Test template

4. Type Mapping
- Source to target types
- Nullable handling
- Array/list types
- Custom types

5. Generation Logic
- File organization
- Naming conventions
- Import management
- Comment generation

6. Customization
- Template overrides
- Custom helpers
- Hooks/plugins

7. CLI Interface
- Command structure
- Options
- Watch mode

8. Testing
- Template tests
- Output validation
- Compilation tests
```

### 5. Productivity & Planning

#### prod-001 - Weekly Planning System
- Placeholders: `HOURS PER DAY, LIST, MEETINGS/APPOINTMENTS, PRIORITIES`
- Prompt:

```text
Help me create an effective weekly plan for the upcoming week.

Context:
- Top 3 priorities this week: [PRIORITIES]
- Fixed commitments: [MEETINGS/APPOINTMENTS]
- Current projects: [LIST]
- Available work hours: [HOURS PER DAY]

Create a plan that includes:

1. Weekly Theme
- One overarching focus
- Success definition for the week

2. Priority Matrix
- Must complete (non-negotiable)
- Should complete (important)
- Could complete (if time permits)
- Delegate or defer

3. Time Blocking Schedule
- Deep work blocks
- Meeting windows
- Admin time
- Buffer time
- Personal time

4. Daily Focus
- Monday: Theme and top 3
- Tuesday: Theme and top 3
- Wednesday: Theme and top 3
- Thursday: Theme and top 3
- Friday: Theme and top 3

5. Energy Management
- High-energy task slots
- Low-energy task slots
- Break schedule

6. Weekly Review Prep
- Success metrics
- Reflection questions
- Adjustment triggers
```

#### prod-002 - Goal Setting Framework (SMART+)
- Placeholders: `DURATION, ROUGH GOAL, STARTING POINT, TARGET`
- Prompt:

```text
Help me set a comprehensive goal using an enhanced SMART framework.

Goal area: [CATEGORY - career, health, financial, etc.]
Initial goal idea: [ROUGH GOAL]
Timeframe: [DURATION]
Current situation: [STARTING POINT]

Create a complete goal plan:

1. Goal Refinement
- Specific: Exactly what will be achieved
- Measurable: Numbers and metrics
- Achievable: Reality check
- Relevant: Why this matters
- Time-bound: Deadline and milestones

2. Extended Framework
- Exciting: Emotional motivation
- Recorded: Documentation method
- Visible: Daily reminder system

3. Milestone Breakdown
- 25% milestone: [TARGET]
- 50% milestone: [TARGET]
- 75% milestone: [TARGET]
- 100% completion: [TARGET]

4. Action Steps
- Daily actions
- Weekly actions
- Monthly check-ins

5. Obstacle Anticipation
- Likely challenges
- Prevention strategies
- Contingency plans

6. Accountability System
- Tracking method
- Review schedule
- Support system

7. Reward Structure
- Milestone rewards
- Completion celebration
```

#### prod-003 - Decision Matrix Builder
- Placeholders: `DECISION, LIST OF CRITERIA, OPTION 1, OPTION 2, OPTION 3`
- Prompt:

```text
Help me make a decision using a weighted decision matrix.

Decision to make: [DECISION]
Options: 
1. [OPTION 1]
2. [OPTION 2]
3. [OPTION 3]

Important factors: [LIST OF CRITERIA]

Create a decision framework:

1. Criteria Definition
- List all decision criteria
- Define what "good" looks like for each
- Add any missing criteria

2. Weight Assignment
- Rate importance of each criterion (1-10)
- Justify each weight
- Ensure weights reflect true priorities

3. Option Scoring
- Score each option on each criterion (1-10)
- Provide reasoning for scores
- Note assumptions

4. Weighted Analysis
- Calculate weighted scores
- Rank options
- Identify close calls

5. Sensitivity Analysis
- What if weights changed?
- What if circumstances changed?
- Robustness of decision

6. Hidden Factors
- Gut feeling check
- Regret minimization
- Long-term implications

7. Recommendation
- Clear recommendation
- Key deciding factors
- Next steps to implement
```

#### prod-004 - Project Breakdown Structure
- Placeholders: `DATE, LIMITATIONS, NAME, PROJECT NAME/DESCRIPTION, TEAM/BUDGET`
- Prompt:

```text
Break down this project into manageable components:

Project: [PROJECT NAME/DESCRIPTION]
Deadline: [DATE]
Resources: [TEAM/BUDGET]
Constraints: [LIMITATIONS]

Create a complete breakdown:

1. Project Overview
- Objective statement
- Success criteria
- Key stakeholders
- Scope boundaries

2. Work Breakdown Structure

Phase 1: [NAME]
- Task 1.1
- Task 1.2
- Task 1.3

Phase 2: [NAME]
- Task 2.1
- Task 2.2
- Task 2.3

[Continue for all phases]

3. Task Details
For each major task:
- Description
- Deliverable
- Duration estimate
- Dependencies
- Owner
- Resources needed

4. Timeline
- Gantt chart structure
- Critical path
- Milestones
- Buffer time

5. Risk Assessment
- Potential risks
- Impact and likelihood
- Mitigation strategies

6. Communication Plan
- Status update schedule
- Stakeholder updates
- Issue escalation
```

#### prod-005 - Morning Routine Designer
- Placeholders: `HIGH/MEDIUM/LOW, ISSUES, TIME, WHAT YOU WANT TO ACHIEVE`
- Prompt:

```text
Design an optimal morning routine based on my goals and constraints.

Current situation:
- Wake up time: [TIME]
- Must leave by: [TIME]
- Current morning struggles: [ISSUES]
- Goals for morning: [WHAT YOU WANT TO ACHIEVE]
- Energy level in morning: [HIGH/MEDIUM/LOW]

Design a routine:

1. Pre-Sleep Preparation
- Evening routine elements
- Sleep optimization
- Next-day preparation

2. Wake-Up Protocol
- Alarm strategy
- No-snooze tactics
- First 5-minute actions

3. Time-Blocked Morning
- [TIME]: Activity 1
- [TIME]: Activity 2
- [Continue...]

4. Routine Components
Physical:
- Exercise/movement
- Hydration
- Nutrition

Mental:
- Meditation/mindfulness
- Learning
- Planning

Productivity:
- Priority identification
- Deep work block
- Quick wins

5. Flexibility Framework
- Rushed morning version (50%)
- Standard version (100%)
- Extended version (when time permits)

6. Habit Stacking
- Linked habit chains
- Trigger-routine-reward

7. Tracking System
- Daily checklist
- Weekly review
```

#### prod-006 - Procrastination Buster
- Placeholders: `SUSPECTED REASON, TASK, WHEN DUE`
- Prompt:

```text
Help me overcome procrastination on this task:

Task I'm avoiding: [TASK]
Deadline: [WHEN DUE]
Why I'm procrastinating: [SUSPECTED REASON]
Past attempts: [WHAT I'VE TRIED]

Create an anti-procrastination plan:

1. Root Cause Analysis
- Fear of failure
- Perfectionism
- Task overwhelm
- Lack of clarity
- Low motivation
- Other factors

2. Task Deconstruction
- Break into smallest possible steps
- First 2-minute action
- Next 10-minute block
- Clear stopping points

3. Environment Design
- Remove distractions
- Create starting ritual
- Prepare materials
- Optimize workspace

4. Motivation Strategies
- Connect to bigger purpose
- Visualize completion
- Implementation intentions
- Accountability setup

5. Energy Matching
- Best time to attempt
- Pre-task energizers
- Break structure

6. Reward System
- Immediate rewards
- Completion reward
- Progress celebrations

7. Fallback Plan
- If I still can't start...
- Minimum viable progress
- When to ask for help
```

#### prod-007 - Meeting Optimizer
- Placeholders: `GOAL, HOW OFTEN, ISSUES, LENGTH, WHO`
- Prompt:

```text
Help me optimize this meeting:

Meeting details:
- Purpose: [GOAL]
- Current duration: [LENGTH]
- Attendees: [WHO]
- Frequency: [HOW OFTEN]
- Current pain points: [ISSUES]

Optimize the meeting:

1. Meeting Necessity Check
- Could this be an email?
- Could this be async?
- Is the frequency right?

2. Purpose Refinement
- Clear objective
- Expected outcomes
- Decision to be made (if any)

3. Attendee Optimization
- Must attend (decision makers)
- Should attend (contributors)
- Optional (FYI only)
- Who can be removed?

4. Time Optimization
- Recommended duration
- Time of day suggestion
- Frequency adjustment

5. Agenda Structure
- Timed agenda items
- Owner per item
- Pre-work requirements
- Decision vs. discussion items

6. Engagement Tactics
- Participation prompts
- Round-robin techniques
- Silent brainstorming

7. Action Item Protocol
- Capture method
- Assignment process
- Follow-up system

8. Meeting Template
- Reusable structure
- Documentation format
```

#### prod-008 - Email Management System
- Placeholders: `CATEGORIES, HOURS, ISSUES, NUMBER`
- Prompt:

```text
Create an email management system to achieve inbox zero.

Current situation:
- Daily email volume: [NUMBER]
- Time spent on email: [HOURS]
- Main email challenges: [ISSUES]
- Email types: [CATEGORIES]

Create a system:

1. Processing Schedule
- When to check email
- Time limits per session
- No-email times

2. Triage System
- 4 D's: Delete, Do, Delegate, Defer
- 2-minute rule application
- Priority identification

3. Folder/Label Structure
- Action required
- Waiting for
- Reference
- Archive
- Category-specific folders

4. Template Library
- Common response templates
- Meeting request template
- Follow-up template
- Decline template

5. Automation Rules
- Auto-filtering
- Priority flagging
- Newsletter handling
- Notification management

6. Response Time Framework
- Urgent: within X hours
- Important: within X hours
- Standard: within X days
- Set expectations

7. Weekly Maintenance
- Archive ritual
- Subscription cleanup
- System review
```

#### prod-009 - Focus Session Planner
- Placeholders: `DURATION, HIGH/MEDIUM/LOW, LIST, TASK`
- Prompt:

```text
Plan a deep work/focus session for maximum productivity.

Task to focus on: [TASK]
Available time: [DURATION]
Energy level: [HIGH/MEDIUM/LOW]
Typical distractions: [LIST]

Create a focus session plan:

1. Pre-Session Prep (10 min before)
- Clear workspace
- Gather materials
- Close unnecessary tabs
- Phone management
- Communication status

2. Session Structure
- Warm-up activity (5 min)
- Main focus blocks
- Break schedule
- Transition rituals

3. Pomodoro Variation
- Work interval length
- Break length
- Number of cycles
- Long break timing

4. Distraction Management
- Distraction capture list
- Environment modifications
- App/website blockers
- Notification settings

5. Mental Preparation
- Intention setting
- Visualization
- Focus music/sounds

6. Energy Maintenance
- Hydration reminders
- Movement breaks
- Eye rest (20-20-20 rule)
- Posture checks

7. Session Close
- Progress documentation
- Next session prep
- Transition activity
- Reward
```

#### prod-010 - Quarterly Review & Planning
- Placeholders: `Q1/Q2/Q3/Q4`
- Prompt:

```text
Conduct a quarterly review and plan the next quarter.

Quarter just completed: [Q1/Q2/Q3/Q4]
Areas to review:
- [AREA 1 - e.g., career]
- [AREA 2 - e.g., health]
- [AREA 3 - e.g., relationships]
- [AREA 4 - e.g., finances]

1. Quarter Review

For each area:
- What went well?
- What didn't go well?
- Key lessons learned?
- Metrics/progress?

2. Goal Assessment
- Goals achieved
- Goals partially completed
- Goals abandoned (why?)
- Unexpected wins

3. Time Analysis
- Where did time go?
- Time well spent vs. wasted
- Ideal time allocation

4. Next Quarter Planning

For each area:
- Top 3 goals
- Key habits to build/break
- Projects to complete
- Metrics to track

5. Resource Allocation
- Time commitments
- Financial investments
- Energy management
- Support needed

6. 90-Day Milestones
- Month 1 targets
- Month 2 targets
- Month 3 targets

7. Success Rituals
- Daily review
- Weekly review
- Monthly check-in
```

#### prod-011 - Habit Tracker Design
- Placeholders: `FREQUENCY, HABIT 1, HABIT 2, HABIT 3, OBSTACLES`
- Prompt:

```text
Design a habit tracking system for building [HABIT(S)].

Habits to track:
1. [HABIT 1]: [FREQUENCY]
2. [HABIT 2]: [FREQUENCY]
3. [HABIT 3]: [FREQUENCY]

Current status: [EXISTING VS. NEW]
Biggest challenges: [OBSTACLES]

Create a tracking system:

1. Habit Specifications
For each habit:
- Precise definition
- Minimum viable version
- Trigger (when/where)
- Time required
- Success metric

2. Habit Stacking
- Chain habits together
- Existing habit anchors
- Sequence optimization

3. Tracking Method
- Daily tracker template
- Weekly view
- Monthly view
- Streak counting

4. Accountability System
- Daily check-in
- Weekly review
- Partner/group
- Public commitment

5. Reward Structure
- Daily rewards
- Streak milestones (7, 21, 30, 66 days)
- Ultimate reward

6. Failure Recovery
- Miss = not failure plan
- Never miss twice rule
- Restart protocol

7. Progress Visualization
- Habit scorecard
- Trend analysis
- Correlation tracking
```

#### prod-012 - Priority Management System
- Placeholders: `DEADLINE/URGENCY, HIGH/MEDIUM/LOW, PRIORITY 1, PRIORITY 2, PRIORITY 3, PRIORITY 4, TIME/RESOURCES`
- Prompt:

```text
Help me manage competing priorities effectively.

Current priorities:
1. [PRIORITY 1]: [DEADLINE/URGENCY]
2. [PRIORITY 2]: [DEADLINE/URGENCY]
3. [PRIORITY 3]: [DEADLINE/URGENCY]
4. [PRIORITY 4]: [DEADLINE/URGENCY]

Constraints: [TIME/RESOURCES]
Stress level: [HIGH/MEDIUM/LOW]

Create a priority system:

1. Eisenhower Matrix Analysis
- Urgent + Important: Do first
- Important + Not Urgent: Schedule
- Urgent + Not Important: Delegate
- Neither: Eliminate

2. Impact Assessment
- Consequence of not doing
- Value of completing
- Deadline flexibility
- Dependencies

3. Energy Matching
- High-energy tasks
- Low-energy tasks
- Time of day alignment

4. Sequencing Strategy
- Task dependencies
- Quick wins first vs. big rocks first
- Batching opportunities

5. Daily Top 3
- Non-negotiable daily priorities
- Everything else is bonus
- Focus protection

6. Weekly Review
- Priority reassessment
- Progress check
- Adjustment process

7. Saying No
- Decline scripts
- Renegotiation tactics
- Boundary setting
```

#### prod-013 - Time Audit
- Placeholders: `IDEAL ALLOCATION, LIST, WEEK/MONTH`
- Prompt:

```text
Conduct a time audit to understand where my time goes.

Time period to analyze: [WEEK/MONTH]
Main roles/responsibilities: [LIST]
Goals for time use: [IDEAL ALLOCATION]

Time audit framework:

1. Tracking Method
- Time logging approach
- Categories to track
- Tools to use
- Tracking duration

2. Category Template
- Deep work
- Shallow work
- Meetings
- Communication
- Administrative
- Health/wellness
- Relationships
- Entertainment
- Learning
- Transition/travel

3. Analysis Questions
- Where does time actually go?
- Biggest time drains?
- Productive vs. busy?
- Energy vs. time alignment?

4. Gap Analysis
- Current vs. ideal allocation
- Overinvested areas
- Underinvested areas
- Surprising discoveries

5. Time Thieves
- Identify top 5 time wasters
- Root causes
- Elimination strategies

6. Optimization Plan
- Time to reclaim
- New time allocation
- Protection strategies
- Tracking going forward

7. Implementation
- Week 1 changes
- Week 2 changes
- Month 1 review
```

#### prod-014 - Delegation Framework
- Placeholders: `TASK, TIMELINE, WHO, YOU`
- Prompt:

```text
Help me delegate this task effectively:

Task to delegate: [TASK]
Current owner: [YOU]
Potential delegatee: [WHO]
Urgency: [TIMELINE]

Create a delegation plan:

1. Delegation Decision
- Should this be delegated?
- Why delegate to this person?
- What level of authority?

2. Task Definition
- Clear outcome expected
- Quality standards
- Boundaries/constraints
- Resources available

3. Context Transfer
- Background information
- Why this matters
- Common pitfalls
- Success examples

4. Authority Levels
- Level 1: Wait to be told
- Level 2: Ask what to do
- Level 3: Recommend, then act
- Level 4: Act, then report
- Level 5: Act independently

5. Support Structure
- Check-in schedule
- Questions welcome
- Escalation triggers
- Available resources

6. Handoff Meeting Agenda
- Task overview
- Walk through details
- Q&A
- Confirm understanding

7. Follow-Up Plan
- Milestone check-ins
- Feedback approach
- Completion criteria
- Learning capture
```

#### prod-015 - Creative Problem Solving
- Placeholders: `BACKGROUND, DESCRIBE THE PROBLEM, INDUSTRY, LIMITATIONS`
- Prompt:

```text
Help me solve this problem creatively:

Problem: [DESCRIBE THE PROBLEM]
Context: [BACKGROUND]
Constraints: [LIMITATIONS]
Past solutions tried: [WHAT'S BEEN ATTEMPTED]

Apply creative problem-solving:

1. Problem Reframing
- How might we...?
- What if...?
- Reverse the problem
- Analogy exploration

2. First Principles Thinking
- Break down to fundamentals
- Challenge assumptions
- Build up from scratch

3. Brainstorming Techniques
- Traditional brainstorm (20 ideas)
- SCAMPER method
- Random word association
- Worst possible idea

4. Cross-Industry Ideas
- How would [INDUSTRY] solve this?
- Historical solutions
- Nature-inspired solutions

5. Constraint Removal
- What if no budget limit?
- What if no time limit?
- What if anything was possible?

6. Solution Evaluation
- Feasibility check
- Impact assessment
- Resource requirements
- Quick wins vs. long-term

7. Action Plan
- Top 3 solutions to try
- Testing approach
- Success criteria
```

#### prod-016 - Annual Planning
- Placeholders: `OVERVIEW, YEAR`
- Prompt:

```text
Help me create a comprehensive annual plan.

Year: [YEAR]
Life areas to plan:
- Career/Work
- Health/Fitness
- Relationships
- Finances
- Personal Growth
- Fun/Recreation

Current life assessment: [OVERVIEW]

1. Vision Statement
- What does success look like?
- How do I want to feel?
- What story will I tell?

2. Area-by-Area Goals
For each area:
- 1-year vision
- Top 3 goals
- Key metrics
- Major projects

3. Quarterly Breakdown
- Q1 focus and goals
- Q2 focus and goals
- Q3 focus and goals
- Q4 focus and goals

4. Key Habits
- Habits to start
- Habits to stop
- Habits to continue

5. Major Milestones
- By end of Q1...
- By mid-year...
- By end of Q3...
- By year-end...

6. Support Systems
- Skills to develop
- Resources needed
- People to connect with
- Investments to make

7. Review Rhythm
- Weekly review
- Monthly review
- Quarterly review
- Annual review
```

#### prod-017 - Energy Management Plan
- Placeholders: `HIGH/MEDIUM/LOW, LIST, WHAT DEPLETES YOU, WHAT ENERGIZES YOU`
- Prompt:

```text
Create an energy management plan to optimize my productivity.

Current energy patterns:
- Morning energy: [HIGH/MEDIUM/LOW]
- Afternoon energy: [HIGH/MEDIUM/LOW]
- Evening energy: [HIGH/MEDIUM/LOW]
- Energy drains: [WHAT DEPLETES YOU]
- Energy boosters: [WHAT ENERGIZES YOU]

Create an energy optimization plan:

1. Energy Audit
- Track energy levels for a week
- Identify patterns
- Note correlations

2. Task-Energy Matching
- High-energy tasks: [LIST]
- Medium-energy tasks: [LIST]
- Low-energy tasks: [LIST]

3. Daily Energy Blueprint
- Morning routine for energy
- Midday energy boost
- Afternoon slump strategy
- Evening wind-down

4. Physical Energy
- Sleep optimization
- Nutrition timing
- Exercise scheduling
- Hydration reminders
- Movement breaks

5. Emotional Energy
- Positive interactions
- Stress management
- Boundary setting
- Recovery activities

6. Mental Energy
- Focus blocks
- Cognitive load management
- Decision fatigue prevention
- Creative vs. analytical timing

7. Environment Design
- Workspace optimization
- Lighting and temperature
- Sound management
- Clutter control
```

#### prod-018 - Project Post-Mortem
- Placeholders: `GOAL, PROJECT NAME, START TO END, SUCCESS/PARTIAL/FAILURE, WHO`
- Prompt:

```text
Conduct a post-mortem analysis for [PROJECT NAME].

Project overview:
- Objective: [GOAL]
- Timeline: [START TO END]
- Team: [WHO]
- Outcome: [SUCCESS/PARTIAL/FAILURE]

Post-mortem analysis:

1. Project Summary
- Original goals
- Actual results
- Key deliverables
- Budget/resource usage

2. What Went Well
- Top 5 successes
- Key enablers
- Unexpected wins
- Strengths to leverage

3. What Could Improve
- Top 5 challenges
- Root causes
- Impact of issues
- Warning signs missed

4. Process Analysis
- Planning effectiveness
- Communication quality
- Decision-making
- Risk management
- Stakeholder management

5. Lessons Learned
- Key insights
- What to repeat
- What to change
- What to stop

6. Action Items
- Immediate improvements
- Long-term changes
- Owners and deadlines
- Documentation needs

7. Knowledge Capture
- Document for future projects
- Training opportunities
- Tool improvements
- Process updates
```

#### prod-019 - Workflow Automation
- Placeholders: `BEGINNER/INTERMEDIATE/ADVANCED, LIST, TASK 1, TASK 2, TASK 3, TIME SPENT`
- Prompt:

```text
Identify automation opportunities in my workflow.

Current tasks:
1. [TASK 1]: [TIME SPENT]
2. [TASK 2]: [TIME SPENT]
3. [TASK 3]: [TIME SPENT]

Tools available: [LIST]
Technical ability: [BEGINNER/INTERMEDIATE/ADVANCED]

Automation analysis:

1. Automation Candidates
For each task:
- Repetitiveness (1-10)
- Rule-based (yes/no)
- Time consumed
- Error frequency
- Automation potential

2. Quick Win Automations
- Immediate implementations
- No-code solutions
- Low complexity

3. Medium-Term Automations
- Requires some setup
- Integration needs
- Learning curve

4. Advanced Automations
- Complex workflows
- Custom development
- Long-term investment

5. Tool Recommendations
- Email automation
- Task automation
- Data automation
- Communication automation

6. Implementation Priority
- Ranked by ROI
- Difficulty level
- Time to implement
- Maintenance needs

7. Step-by-Step Guides
- Top 3 automations
- Setup instructions
- Testing approach
- Troubleshooting
```

#### prod-020 - Stress Management Protocol
- Placeholders: `HOW IT MANIFESTS, LIST, SITUATION/PERIOD`
- Prompt:

```text
Create a stress management protocol for [SITUATION/PERIOD].

Current stressors: [LIST]
Stress symptoms: [HOW IT MANIFESTS]
Past coping methods: [WHAT'S WORKED/NOT WORKED]

Stress management plan:

1. Stress Assessment
- Stress sources (rank by impact)
- Controllable vs. uncontrollable
- Acute vs. chronic

2. Immediate Relief Techniques
- 5-minute interventions
- Breathing exercises
- Grounding techniques
- Physical release

3. Daily Stress Prevention
- Morning stress buffer
- Midday reset
- Evening decompression
- Sleep protection

4. Lifestyle Factors
- Exercise schedule
- Nutrition for stress
- Sleep hygiene
- Social support

5. Cognitive Strategies
- Reframing techniques
- Worry time scheduling
- Perspective exercises
- Gratitude practice

6. Boundary Setting
- Work-life boundaries
- Energy boundaries
- Communication boundaries
- Time boundaries

7. Emergency Protocol
- Overwhelm response
- Crisis resources
- Support contacts
- Recovery plan

8. Long-Term Solutions
- Root cause addressing
- Life changes needed
- Professional support
```

#### prod-021 - Learning Plan Design
- Placeholders: `BEGINNER/INTERMEDIATE/ADVANCED, FOCUS, HOURS PER WEEK, IF ANY, SKILL/TOPIC, VISUAL/AUDITORY/KINESTHETIC/READING, WHAT TO LEARN`
- Prompt:

```text
Create a learning plan to master [SKILL/TOPIC].

Learning goal: [WHAT TO LEARN]
Current level: [BEGINNER/INTERMEDIATE/ADVANCED]
Time available: [HOURS PER WEEK]
Learning style: [VISUAL/AUDITORY/KINESTHETIC/READING]
Deadline: [IF ANY]

Learning plan:

1. Skill Breakdown
- Sub-skills to learn
- Prerequisite knowledge
- Skill hierarchy
- Core vs. advanced

2. Resource Curation
- Online courses
- Books
- Videos
- Podcasts
- Practice platforms
- Communities

3. Learning Schedule
- Weekly time blocks
- Daily practice windows
- Review sessions
- Project time

4. Milestone Roadmap
- Week 1-2: [FOCUS]
- Week 3-4: [FOCUS]
- Month 2: [FOCUS]
- Month 3: [FOCUS]

5. Practice Strategy
- Deliberate practice approach
- Feedback loops
- Spaced repetition
- Active recall

6. Project-Based Learning
- Beginner projects
- Intermediate projects
- Capstone project

7. Progress Tracking
- Skill assessments
- Portfolio building
- Milestone celebrations
- Adjustment triggers
```

#### prod-022 - System Design for Life Areas
- Placeholders: `FINANCES/HEALTH/RELATIONSHIPS/HOME/ETC, GOAL, HOURS/WEEK, ISSUES, LIFE AREA`
- Prompt:

```text
Design a personal operating system for managing [LIFE AREA].

Life area: [FINANCES/HEALTH/RELATIONSHIPS/HOME/ETC]
Current pain points: [ISSUES]
Desired state: [GOAL]
Time to invest: [HOURS/WEEK]

System design:

1. Current State Analysis
- What's working
- What's not working
- Time/energy spent
- Results achieved

2. System Components
- Daily routines
- Weekly routines
- Monthly routines
- Quarterly/annual reviews

3. Tracking Metrics
- Key indicators
- Measurement method
- Tracking frequency
- Target benchmarks

4. Tool Stack
- Apps/software
- Physical tools
- Templates
- Checklists

5. Automation Opportunities
- Recurring tasks
- Reminders
- Auto-payments/actions
- Scheduled reviews

6. Decision Frameworks
- Common decisions
- Pre-made choices
- Default options
- Exception handling

7. Maintenance Plan
- Daily upkeep
- Weekly maintenance
- System reviews
- Iteration approach

8. Implementation
- Week 1 setup
- Week 2 refinement
- Month 1 review
```

#### prod-023 - Meeting Notes Template
- Placeholders: `GOAL, MEETING TYPE, REGULAR/PROJECT/CLIENT/ETC, ROLES, SCHEDULE`
- Prompt:

```text
Create a meeting notes system for [MEETING TYPE].

Meeting context:
- Type: [REGULAR/PROJECT/CLIENT/ETC]
- Frequency: [SCHEDULE]
- Participants: [ROLES]
- Purpose: [GOAL]

Meeting notes template:

1. Meeting Header
- Date/Time
- Attendees
- Absent
- Facilitator
- Note-taker

2. Agenda Review
- Pre-set agenda items
- Time allocations
- Added items

3. Discussion Notes

For each agenda item:
- Topic
- Key points discussed
- Different viewpoints
- Conclusions

4. Decisions Made
- Decision statement
- Rationale
- Who decided
- Effective date

5. Action Items
- Task description
- Owner
- Due date
- Status column

6. Parking Lot
- Items for later
- Ideas to explore
- Questions unanswered

7. Follow-Up
- Next meeting date
- Pre-work required
- Distribution list

8. Quick Reference
- Key takeaways
- Critical deadlines
- Immediate next steps
```

#### prod-024 - Batching Strategy
- Placeholders: `DESCRIPTION, FREQUENCY, ISSUES, TASK TYPE 1, TASK TYPE 2, TASK TYPE 3, TIMES`
- Prompt:

```text
Create a task batching strategy for my workflow.

Common tasks:
1. [TASK TYPE 1]: [FREQUENCY]
2. [TASK TYPE 2]: [FREQUENCY]
3. [TASK TYPE 3]: [FREQUENCY]

Current workflow: [DESCRIPTION]
Biggest time wasters: [ISSUES]

Batching strategy:

1. Task Categorization
- Administrative tasks
- Creative tasks
- Communication tasks
- Analytical tasks
- Meetings

2. Natural Batches
- Tasks that group well
- Similar tool usage
- Similar mental mode
- Similar energy requirement

3. Batch Schedule
- Daily batches
- Weekly batches
- Monthly batches

4. Time Blocks
- Email batch: [TIMES]
- Admin batch: [TIMES]
- Creative batch: [TIMES]
- Meeting batch: [TIMES]

5. Transition Minimization
- Reduce context switching
- Theme days
- Batch windows

6. Implementation Tips
- Start small
- Protect batch times
- Communicate boundaries
- Handle urgencies

7. Batch Templates
- What to do during each batch
- Maximum time limits
- Completion criteria
```

#### prod-025 - Personal Kanban Setup
- Placeholders: `DESCRIPTION, ISSUES, NUMBER, PHYSICAL/DIGITAL, TYPE 1, TYPE 2, TYPE 3`
- Prompt:

```text
Set up a personal Kanban system for managing my work.

Work types:
- [TYPE 1]: [DESCRIPTION]
- [TYPE 2]: [DESCRIPTION]
- [TYPE 3]: [DESCRIPTION]

Current challenges: [ISSUES]
Tool preference: [PHYSICAL/DIGITAL]

Kanban setup:

1. Column Structure
- Backlog (all ideas)
- This Week (selected for week)
- Today (daily focus)
- In Progress (WIP)
- Blocked (waiting on something)
- Done (completed)

2. Card Design
- Task title
- Category/tag
- Priority indicator
- Due date
- Estimate
- Notes

3. Work in Progress Limits
- In Progress max: [NUMBER]
- Today max: [NUMBER]
- Reasoning

4. Flow Management
- Weekly planning ritual
- Daily standup with self
- Replenishment triggers
- Completion celebration

5. Color Coding
- By project
- By priority
- By energy level
- By deadline urgency

6. Review Cadence
- Daily review
- Weekly retrospective
- Monthly analysis

7. Metrics to Track
- Throughput
- Lead time
- Blocked time
- WIP accuracy
```

#### prod-026 - Context Switching Reducer
- Placeholders: `ESTIMATE, LIST, OFFICE/REMOTE/HYBRID`
- Prompt:

```text
Help me reduce context switching in my workday.

Current situation:
- Main types of work: [LIST]
- Interruption sources: [LIST]
- Average switches per day: [ESTIMATE]
- Work environment: [OFFICE/REMOTE/HYBRID]

Context switching reduction plan:

1. Switch Audit
- Track switches for 3 days
- Identify patterns
- Calculate time lost
- Find root causes

2. Work Bundling
- Group similar tasks
- Theme hours/days
- Batch communication
- Single-tasking blocks

3. Environment Design
- Multiple desktops/workspaces
- Tool consolidation
- Tab management
- Physical workspace zones

4. Communication Boundaries
- Async first policy
- Response time expectations
- Status indicators
- Scheduled availability

5. Transition Rituals
- Context closing checklist
- Context loading checklist
- Mental bookmark technique
- Physical movement

6. Interruption Management
- Urgent vs. not urgent
- Interrupt-free windows
- Handling requests
- Saying no/later

7. Tool Setup
- Notification management
- Focus modes
- Blocking apps
- Quick-capture system
```

#### prod-027 - Deadline Management
- Placeholders: `1-10, DATE, ITEM 1, ITEM 2, ITEM 3, ITEM 4, RESOURCES`
- Prompt:

```text
Help me manage multiple deadlines effectively.

Upcoming deadlines:
1. [ITEM 1]: [DATE]
2. [ITEM 2]: [DATE]
3. [ITEM 3]: [DATE]
4. [ITEM 4]: [DATE]

Current stress level: [1-10]
Support available: [RESOURCES]

Deadline management plan:

1. Deadline Triage
- Hard vs. soft deadlines
- Consequences of missing
- Negotiation possibility
- Dependencies

2. Reverse Planning
For each deadline:
- Final deadline
- Buffer time needed
- Review/revision time
- Creation/work time
- Research/prep time
- Start date

3. Weekly Allocation
- Week 1 focus
- Week 2 focus
- Week 3 focus
- Parallel work strategy

4. Daily Targets
- Progress milestones
- Minimum viable progress
- Stretch goals

5. Risk Mitigation
- Buffer identification
- Backup plans
- Escalation points
- Help requests

6. Focus Protection
- Non-essential elimination
- Distraction blocking
- Energy preservation

7. Tracking Dashboard
- Visual progress
- Days remaining
- Completion percentage
- Alert triggers
```

#### prod-028 - Brain Dump Processing
- Placeholders: `FOR PROCESSING, PASTE YOUR BRAIN DUMP HERE, REASON, THEMES`
- Prompt:

```text
Help me process this brain dump into actionable items:

[PASTE YOUR BRAIN DUMP HERE]

Context:
- What triggered this dump: [REASON]
- Main concerns: [THEMES]
- Available time: [FOR PROCESSING]

Brain dump processing:

1. Capture Review
- All items identified
- Duplicates combined
- Clarifications added

2. Categorization
- Tasks (actionable)
- Projects (multi-step)
- Ideas (someday/maybe)
- Reference (information)
- Trash (not needed)

3. Task Processing
For each task:
- Next action defined
- Context assigned
- Time estimate
- Priority level
- Due date (if any)

4. Project Identification
- Projects recognized
- First next action
- Project folder needed

5. Calendar Items
- Date-specific items
- Deadlines
- Appointments needed

6. Waiting For
- Delegated items
- Responses expected
- Follow-up dates

7. Reference Filing
- Information to save
- Where to file
- How to find later

8. Action Plan
- Today's items
- This week's items
- Next actions list
```

#### prod-029 - Productivity Audit
- Placeholders: `1-10, DESCRIPTION, LIST`
- Prompt:

```text
Conduct a personal productivity audit.

Current productivity rating: [1-10]
Main productivity challenges: [LIST]
Productivity tools used: [LIST]
Work style: [DESCRIPTION]

Productivity audit:

1. Time Assessment
- Hours worked vs. productive hours
- Prime time identification
- Time leaks
- Transition time

2. Energy Assessment
- Energy patterns
- Energy drains
- Energy boosters
- Recovery practices

3. Focus Assessment
- Deep work capability
- Distraction frequency
- Flow state access
- Concentration duration

4. System Assessment
- Task management
- Calendar usage
- Note-taking
- File organization
- Communication tools

5. Habit Assessment
- Productive habits
- Unproductive habits
- Missing habits
- Habit consistency

6. Environment Assessment
- Workspace setup
- Tool availability
- Noise/interruptions
- Ergonomics

7. Mindset Assessment
- Motivation levels
- Clarity of priorities
- Stress impact
- Growth areas

8. Improvement Plan
- Top 3 priorities
- Quick fixes
- Long-term changes
- Resources needed
```

#### prod-030 - One-on-One Meeting Prep
- Placeholders: `GOALS, LIST, MANAGER/REPORT/PEER/CLIENT, PERSON/ROLE, SCHEDULE`
- Prompt:

```text
Prepare for a one-on-one meeting with [PERSON/ROLE].

Meeting context:
- Relationship: [MANAGER/REPORT/PEER/CLIENT]
- Frequency: [SCHEDULE]
- Topics to discuss: [LIST]
- Outcomes wanted: [GOALS]

Preparation guide:

1. Status Updates
- Progress since last meeting
- Completed items
- Blocked items
- Upcoming focus

2. Discussion Topics
- Priority items (must discuss)
- Secondary items (if time)
- Quick updates (FYI only)

3. Questions to Ask
- Feedback requests
- Clarification needs
- Strategic questions
- Development discussions

4. Feedback to Share
- Appreciation/recognition
- Constructive feedback
- Process improvements
- Resource needs

5. Support Requests
- Decisions needed
- Resources needed
- Barriers to remove
- Introductions needed

6. Career/Development
- Progress on goals
- Learning opportunities
- Growth discussions
- Future planning

7. Action Items Follow-Up
- Previous commitments
- Status updates
- New commitments

8. Meeting Notes Template
- Pre-fill structure
- Quick capture format
```

#### prod-031 - Accountability System
- Placeholders: `DESCRIPTION, DURATION, GOAL, PEOPLE/RESOURCES, WHY FAILED BEFORE`
- Prompt:

```text
Design an accountability system for achieving [GOAL].

Goal: [DESCRIPTION]
Timeline: [DURATION]
Past challenges: [WHY FAILED BEFORE]
Support available: [PEOPLE/RESOURCES]

Accountability system:

1. Goal Clarity
- Specific outcome
- Measurable progress
- Daily/weekly targets
- Success definition

2. Tracking Method
- Daily check-in format
- Progress metrics
- Tracking tool
- Visual progress display

3. Accountability Partner
- Who to involve
- Check-in schedule
- Reporting format
- Consequence agreement

4. Public Commitment
- Who to tell
- How to share
- Update schedule
- Social pressure leverage

5. Reward System
- Milestone rewards
- Daily wins
- Final celebration
- Self-reward rules

6. Consequence System
- Stakes involved
- Penalty for missing
- Escalation plan
- Recovery protocol

7. Environment Design
- Reminders setup
- Friction reduction
- Temptation removal
- Support access

8. Review Rhythm
- Daily reflection
- Weekly review
- Monthly assessment
- Course correction
```

#### prod-032 - Information Diet Design
- Placeholders: `COUNT, HOURS, ISSUES, LIST, PLATFORMS/TIME, WHAT YOU WANT`
- Prompt:

```text
Design an intentional information diet for better focus.

Current consumption:
- News sources: [LIST]
- Social media: [PLATFORMS/TIME]
- Email newsletters: [COUNT]
- Podcasts/videos: [HOURS]

Information overload symptoms: [ISSUES]
Goals: [WHAT YOU WANT]

Information diet plan:

1. Consumption Audit
- Time spent per source
- Value vs. time
- Anxiety impact
- Action value

2. Source Curation
- Must-keep sources
- Nice-to-have sources
- Elimination candidates
- New sources to try

3. Consumption Schedule
- When to consume
- Time limits
- Batch reading
- No-input times

4. Input Processing
- Capture system
- Processing ritual
- Action extraction
- Archive/delete

5. Social Media Rules
- Platform purposes
- Time limits
- No-scroll times
- Engagement rules

6. News Diet
- How to stay informed
- Frequency reduction
- Anxiety management
- Action focus

7. Learning Input
- Priority topics
- Depth vs. breadth
- Implementation focus
- Output requirement

8. Digital Boundaries
- Device-free times
- Notification settings
- App limits
- Physical barriers
```

#### prod-033 - Sprint Planning
- Placeholders: `DAYS/WEEKS, GOAL/PROJECT, LIMITATIONS, OBJECTIVE, PER DAY`
- Prompt:

```text
Plan a productivity sprint for [GOAL/PROJECT].

Sprint goal: [OBJECTIVE]
Duration: [DAYS/WEEKS]
Available hours: [PER DAY]
Constraints: [LIMITATIONS]

Sprint planning:

1. Sprint Definition
- Specific deliverable
- Success criteria
- Out of scope
- Dependencies

2. Task Breakdown
- All tasks needed
- Estimated hours each
- Priority order
- Dependencies mapped

3. Daily Allocation

Day 1:
- Focus area
- Tasks to complete
- Hours allocated

Day 2:
- [Continue for each day]

4. Buffer Planning
- Contingency time
- Overflow handling
- Priority shifts

5. Environment Setup
- Workspace preparation
- Tools ready
- Distractions blocked
- Support arranged

6. Energy Management
- Peak energy slots
- Break schedule
- Nutrition plan
- Sleep protection

7. Progress Tracking
- Daily check-ins
- Burndown chart
- Velocity monitoring
- Adjustment triggers

8. Sprint Wrap-Up
- Completion criteria
- Review process
- Lessons learned
- Celebration plan
```

#### prod-034 - Second Brain Setup
- Placeholders: `APP, LEARNING/WORK/PERSONAL, NOTES/ARTICLES/IDEAS/ETC, ORGANIZATION ISSUES`
- Prompt:

```text
Set up a second brain/personal knowledge management system.

Note-taking tool: [APP]
Main purposes: [LEARNING/WORK/PERSONAL]
Content types: [NOTES/ARTICLES/IDEAS/ETC]
Current pain: [ORGANIZATION ISSUES]

Second brain setup:

1. Folder/Area Structure
- PARA method or custom
- Projects folder
- Areas folder
- Resources folder
- Archive folder

2. Capture System
- Quick capture tools
- Inbox processing
- Mobile capture
- Web clipping

3. Processing Workflow
- Daily review
- Weekly processing
- Categorization rules
- Linking approach

4. Note Templates
- Meeting notes
- Book notes
- Project notes
- Idea notes
- Daily notes

5. Tagging System
- Tag categories
- Naming conventions
- Status tags
- Topic tags

6. Linking Strategy
- Bi-directional links
- Hub notes/MOCs
- Reference linking
- Idea connections

7. Retrieval System
- Search optimization
- Browse structure
- Quick access
- Regular review

8. Maintenance Routine
- Daily habits
- Weekly review
- Monthly cleanup
- Quarterly audit
```

#### prod-035 - Saying No Framework
- Placeholders: `CONTEXT, REASON, WORRIES`
- Prompt:

```text
Help me decline this request professionally:

Request: [WHAT'S BEING ASKED]
From: [WHO'S ASKING]
Relationship: [CONTEXT]
Why I want to say no: [REASON]
Concerns about declining: [WORRIES]

Decline framework:

1. Decision Validation
- Should I say no? (confirm)
- Impact of saying yes
- Impact of saying no
- Long-term considerations

2. Response Options

Firm No:
- Clear decline
- Brief reason (optional)
- No guilt

Soft No:
- Not right now
- Alternative timing
- Conditional yes

Deflection:
- Redirect to someone else
- Alternative solution
- Resource instead of time

3. Response Templates

Professional:
"Thank you for thinking of me for [request]. Unfortunately, I'm not able to [commit/participate/help] at this time due to [brief reason]. I hope [alternative/wish them well]."

[Provide 3-4 variations]

4. Delivery Tips
- Timing
- Medium (email/call/in-person)
- Tone
- Body language (if in-person)

5. Follow-Up
- If they push back
- If relationship repair needed
- Future considerations

6. Mental Preparation
- Self-permission
- Affirmations
- Values alignment
```

#### prod-036 - Mindful Productivity
- Placeholders: `DESCRIPTION, HIGH/MEDIUM/LOW, NONE/SOME/REGULAR`
- Prompt:

```text
Create a mindful productivity practice combining focus with wellbeing.

Current state:
- Productivity level: [HIGH/MEDIUM/LOW]
- Stress level: [HIGH/MEDIUM/LOW]
- Work-life balance: [DESCRIPTION]
- Mindfulness experience: [NONE/SOME/REGULAR]

Mindful productivity plan:

1. Intention Setting
- Daily intention ritual
- Priority clarity
- Purpose connection
- Gratitude integration

2. Mindful Work Blocks
- Single-tasking focus
- Breath awareness
- Body check-ins
- Mental noting

3. Transition Rituals
- Task completion pause
- Context shift breathing
- Physical movement
- Mental clearing

4. Mindful Breaks
- Micro-breaks (2 min)
- Short breaks (5-10 min)
- Long breaks (30+ min)
- Activities for each

5. Stress Integration
- Notice stress signals
- Pause and breathe
- Choose response
- Reset and continue

6. End-of-Day Ritual
- Work shutdown
- Day reflection
- Tomorrow preparation
- Transition activity

7. Weekly Reflection
- What worked well
- What was challenging
- Lessons learned
- Adjustments needed

8. Sustainability Practices
- Preventing burnout
- Energy renewal
- Boundary maintenance
- Joy integration
```

#### prod-037 - Remote Work Optimization
- Placeholders: `ALONE/FAMILY/ROOMMATES, DEDICATED/SHARED/NONE, DESCRIPTION, ISSUES`
- Prompt:

```text
Optimize my remote work setup and routine.

Current situation:
- Work type: [DESCRIPTION]
- Living situation: [ALONE/FAMILY/ROOMMATES]
- Workspace: [DEDICATED/SHARED/NONE]
- Main challenges: [ISSUES]

Remote work optimization:

1. Workspace Design
- Dedicated space setup
- Ergonomic requirements
- Tech setup
- Distraction barriers
- Lighting and environment

2. Work Boundaries
- Start time ritual
- End time ritual
- Physical separation
- Mental separation
- Household communication

3. Communication Protocols
- Availability signals
- Response time expectations
- Meeting preferences
- Async-first practices

4. Daily Structure
- Morning routine
- Core work hours
- Break schedule
- Transition activities
- Evening shutdown

5. Social Connection
- Team interactions
- Virtual coffee chats
- Video on/off policies
- Collaboration time

6. Focus Protection
- Deep work blocks
- Notification management
- Household coordination
- Emergency protocols

7. Physical Wellbeing
- Movement breaks
- Eye strain prevention
- Posture checks
- Outside time

8. Mental Health
- Isolation prevention
- Stress management
- Work-life boundaries
- Support resources
```

#### prod-038 - Sunday Reset Ritual
- Placeholders: `CONTEXT, DESCRIPTION, HOURS, LIFE AREAS`
- Prompt:

```text
Create a Sunday reset ritual to prepare for the week.

Life situation:
- Work type: [DESCRIPTION]
- Family situation: [CONTEXT]
- Available time: [HOURS]
- Priority areas: [LIFE AREAS]

Sunday reset ritual:

1. Life Admin Block (1-2 hours)
- Email cleanup
- Bill review/payments
- Appointment scheduling
- Errands planning
- Admin tasks

2. Home Reset
- Cleaning priorities
- Laundry
- Groceries/meal prep
- Space organization
- Supplies check

3. Week Planning
- Calendar review
- Priority setting
- Time blocking
- Commitment assessment
- Buffer planning

4. Mind Reset
- Weekly reflection
- Gratitude practice
- Intention setting
- Worry processing
- Mental preparation

5. Body Reset
- Sleep debt recovery
- Exercise planning
- Meal planning
- Health check-in
- Self-care activity

6. Relationship Check
- Family time
- Friend connections
- Relationship maintenance
- Social planning

7. Joy Integration
- Fun activity
- Hobby time
- Relaxation
- Energy restoration

8. Week Ahead Prep
- Clothes prepared
- Bags packed
- Meals prepped
- First-thing ready
```

#### prod-039 - Perfectionism Management
- Placeholders: `DELAYS/STRESS/QUALITY ISSUES, DESCRIPTION, HOW IT SHOWS UP, IF APPLICABLE, PROJECT/TASK`
- Prompt:

```text
Help me manage perfectionism on [PROJECT/TASK].

Task: [DESCRIPTION]
Perfectionism symptoms: [HOW IT SHOWS UP]
Impact: [DELAYS/STRESS/QUALITY ISSUES]
Deadline: [IF APPLICABLE]

Perfectionism management:

1. Perfectionism Audit
- Where it shows up
- Root causes
- Fear identification
- Cost calculation

2. Good Enough Definition
- Minimum viable outcome
- "Done" criteria
- Quality tiers
- Diminishing returns point

3. Constraint Setting
- Time box the task
- Version limits
- Revision caps
- Feedback gates

4. Progress Over Perfect
- First draft permission
- Iteration mindset
- Ship and improve
- Learn by doing

5. Fear Addressing
- What am I really afraid of?
- Worst case scenario
- Likely actual outcome
- Coping plan

6. Feedback Early
- Share imperfect work
- Get external input
- Reality check
- Course correct

7. Self-Compassion
- Acknowledge the struggle
- Common humanity
- Kind self-talk
- Celebrate progress

8. Practical Tactics
- Timer technique
- "Ship it" mantras
- Accountability partner
- Celebration ritual
```

#### prod-040 - Task Estimation
- Placeholders: `TASK 1, TASK 2, TASK 3, USUALLY OVER/UNDER, WORK ENVIRONMENT`
- Prompt:

```text
Help me estimate time for these tasks accurately:

Tasks to estimate:
1. [TASK 1]
2. [TASK 2]
3. [TASK 3]

Past estimation accuracy: [USUALLY OVER/UNDER]
Context: [WORK ENVIRONMENT]

Estimation framework:

1. Task Breakdown
For each task:
- Component steps
- Dependencies
- Decision points
- Unknown factors

2. Historical Data
- Similar past tasks
- Actual vs. estimated
- What caused variance
- Patterns identified

3. Three-Point Estimate
For each task:
- Optimistic (best case)
- Most likely (realistic)
- Pessimistic (worst case)
- PERT estimate calculation

4. Buffer Calculation
- Uncertainty level
- Risk factors
- Recommended buffer %
- Total estimated time

5. Common Pitfalls
- Planning fallacy traps
- Hidden work
- Interruption factor
- Learning curve

6. Confidence Levels
- High confidence estimates
- Medium confidence
- Low confidence (need more info)

7. Tracking for Improvement
- How to track actuals
- Review process
- Calibration approach

8. Final Estimates
- Task-by-task estimates
- Total project estimate
- Commitment vs. target
```

#### prod-041 - Focus Music/Environment
- Placeholders: `CHALLENGES, CREATIVE/ANALYTICAL/COMMUNICATION, HIGH/MEDIUM/LOW, OFFICE/HOME/COFFEE SHOP, RECOMMENDATION, WORK TYPE`
- Prompt:

```text
Create a focus environment prescription for [WORK TYPE].

Work context:
- Task type: [CREATIVE/ANALYTICAL/COMMUNICATION]
- Sensitivity to noise: [HIGH/MEDIUM/LOW]
- Work location: [OFFICE/HOME/COFFEE SHOP]
- Current focus issues: [CHALLENGES]

Focus environment design:

1. Auditory Environment

For focused work:
- Music genre recommendations
- Specific playlists/artists
- White/brown/pink noise options
- Nature sounds
- Binaural beats

For different tasks:
- Writing: [RECOMMENDATION]
- Analysis: [RECOMMENDATION]
- Creative: [RECOMMENDATION]
- Administrative: [RECOMMENDATION]

2. Visual Environment
- Screen setup
- Lighting optimization
- Color psychology
- Clutter management
- View/background

3. Physical Environment
- Temperature
- Air quality
- Scent/aromatherapy
- Comfort factors

4. Digital Environment
- Browser setup
- Desktop organization
- App arrangement
- Notification settings

5. Focus Tools
- Focus apps
- Website blockers
- Time trackers
- Ambient sound apps

6. Ritual Elements
- Focus trigger
- Start ritual
- Transition signals
- End ritual

7. Personalized Playlist
- Curated recommendations
- Duration matching
- Mood progression
```

#### prod-042 - Shutdown Routine
- Placeholders: `HARD TO STOP/LOOSE ENDS/ETC, HOW TO SPEND EVENINGS, TARGET, WHAT FOLLOWS WORK`
- Prompt:

```text
Create an end-of-workday shutdown routine.

Work situation:
- End of day time: [TARGET]
- Current challenges: [HARD TO STOP/LOOSE ENDS/ETC]
- Home situation: [WHAT FOLLOWS WORK]
- Evening goals: [HOW TO SPEND EVENINGS]

Shutdown routine:

1. Task Completion Check
- Review today's list
- Mark completions
- Capture loose ends
- Celebrate wins

2. Inbox Processing
- Final email check
- Urgent responses
- Everything else tomorrow
- Close email

3. Tomorrow Prep
- Top 3 priorities
- First task ready
- Calendar review
- Materials prepared

4. Capture Clearing
- Process notes
- File documents
- Clear inbox to zero
- Empty physical inbox

5. Workspace Reset
- Clean desk
- Close applications
- Physical organization
- Tomorrow-ready state

6. Mental Closure
- Day reflection (2 min)
- Gratitude moment
- Open loops documented
- Permission to stop

7. Transition Activity
- Physical movement
- Location change
- Outfit change
- Symbolic action

8. Shutdown Phrase
- Verbal declaration
- Mental signal
- Work is done
```

#### prod-043 - Task Triage System
- Placeholders: `DELEGATION OPTIONS, TASKS PER DAY/WEEK, TIMEFRAMES, WHERE TASKS COME FROM`
- Prompt:

```text
Create a task triage system for managing incoming requests.

Work context:
- Request sources: [WHERE TASKS COME FROM]
- Volume: [TASKS PER DAY/WEEK]
- Response expectations: [TIMEFRAMES]
- Support available: [DELEGATION OPTIONS]

Triage system:

1. Capture Protocol
- Single inbox
- Quick capture method
- Information to collect
- Don't process immediately

2. Triage Criteria

Urgency assessment:
- True emergency (now)
- Time-sensitive (today)
- Soon (this week)
- Eventually (someday)

Importance assessment:
- Critical (major impact)
- Important (significant value)
- Moderate (useful)
- Low (nice to have)

3. Decision Tree
- If < 2 min → Do now
- If delegatable → Delegate
- If schedulable → Calendar
- If actionable → Task list
- If reference → File
- If not needed → Delete

4. Processing Schedule
- Triage frequency
- Processing time blocks
- Batch decisions
- Clear inbox ritual

5. Communication Templates
- Acknowledge receipt
- Set expectations
- Decline gracefully
- Delegate handoff

6. Overflow Protocol
- When overwhelmed
- Renegotiation scripts
- Escalation path
- Emergency procedures

7. Tracking System
- Request log
- Status tracking
- Follow-up reminders
- Completion recording
```

#### prod-044 - Monthly Review Template
- Placeholders: `MONTH, SPECIFY`
- Prompt:

```text
Create a monthly review framework for personal and professional assessment.

Month: [MONTH]
Focus areas:
- Work/Career
- Health/Fitness
- Relationships
- Finances
- Personal Growth
- Other: [SPECIFY]

Monthly review:

1. Month Overview
- Highlights of the month
- Lowlights/challenges
- Unexpected events
- Overall satisfaction (1-10)

2. Goal Review
For each goal set:
- Target vs. actual
- Progress percentage
- Contributing factors
- Obstacles faced

3. Area-by-Area Review

For each area:
- Accomplishments
- Setbacks
- Lessons learned
- Next month focus

4. Habit Tracking
- Habits maintained
- Habits broken
- New habits formed
- Adjustments needed

5. Time Analysis
- How time was spent
- Well-invested time
- Wasted time
- Rebalancing needs

6. Learning Review
- Books/courses completed
- Skills developed
- Insights gained
- Knowledge applied

7. Relationship Check
- Connections strengthened
- Relationships neglected
- New connections
- Next month intentions

8. Next Month Planning
- Top 3 priorities
- Goals to set
- Habits to focus on
- Events to plan for
```

#### prod-045 - Constraint-Based Planning
- Placeholders: `FIXED COMMITMENTS, GOAL 1, GOAL 2, GOAL 3, HOURS/WEEK, LIMITATIONS, LOW/MEDIUM/HIGH`
- Prompt:

```text
Help me plan around constraints and limited resources.

Constraints:
- Time available: [HOURS/WEEK]
- Energy level: [LOW/MEDIUM/HIGH]
- Resources: [LIMITATIONS]
- Non-negotiables: [FIXED COMMITMENTS]

Goals to achieve:
1. [GOAL 1]
2. [GOAL 2]
3. [GOAL 3]

Constraint-based planning:

1. Constraint Mapping
- Fixed time blocks
- Energy windows
- Resource limitations
- Absolute priorities

2. Goal Prioritization
- Must achieve (non-negotiable)
- Should achieve (important)
- Could achieve (bonus)
- Won't achieve (accept)

3. Reality Check
- Hours needed vs. available
- Energy match
- Resource requirements
- Feasibility assessment

4. Creative Solutions
- Batching opportunities
- Delegation options
- Simplification possibilities
- Resource substitutions

5. Optimized Schedule
- Protected priority time
- Flexible buffer time
- Constraint-aware allocation
- Energy matching

6. Trade-Off Decisions
- What to sacrifice
- What to delay
- What to simplify
- What to delegate

7. Adjustment Triggers
- When to reassess
- Flexibility points
- Escalation criteria
- Recovery options

8. Realistic Plan
- Achievable outcomes
- Built-in buffers
- Clear priorities
- Acceptance of limits
```

#### prod-046 - Creative Work Scheduling
- Placeholders: `BEST TIMES, DESCRIPTION, WHEN CREATIVITY IS LOWEST, WRITING/DESIGN/MUSIC/ETC`
- Prompt:

```text
Design a schedule that optimizes for creative work.

Creative work type: [WRITING/DESIGN/MUSIC/ETC]
Current schedule: [DESCRIPTION]
Creative blocks: [WHEN CREATIVITY IS LOWEST]
Peak creative times: [BEST TIMES]

Creative schedule design:

1. Creative Rhythm Mapping
- Daily creative peaks
- Weekly patterns
- Monthly/seasonal cycles
- Energy correlations

2. Protected Creative Time
- Optimal time blocks
- Duration for deep work
- Frequency needed
- Protection strategies

3. Creative Rituals
- Warm-up activities
- Environmental triggers
- Mental preparation
- Transition rituals

4. Input vs. Output Balance
- Inspiration time
- Creation time
- Processing time
- Rest time

5. Administrative Batching
- Non-creative tasks
- Best times for admin
- Batching strategy
- Clear separation

6. Idea Capture
- Capture system
- Processing ritual
- Incubation time
- Development process

7. Block Breakers
- Unstuck techniques
- Creativity boosters
- Environment changes
- Cross-pollination

8. Weekly Creative Template
- Day-by-day structure
- Flexible vs. fixed blocks
- Review and planning time
- Rest and renewal
```

#### prod-047 - Workload Assessment
- Placeholders: `COMMITMENT 1, COMMITMENT 2, COMMITMENT 3, COMMITMENT 4, HOURS/WEEK, OVERWHELMED/MANAGEABLE/UNDERUTILIZED, POTENTIAL NEW COMMITMENT`
- Prompt:

```text
Assess my current workload and capacity.

Current commitments:
1. [COMMITMENT 1]: [HOURS/WEEK]
2. [COMMITMENT 2]: [HOURS/WEEK]
3. [COMMITMENT 3]: [HOURS/WEEK]
4. [COMMITMENT 4]: [HOURS/WEEK]

New request: [POTENTIAL NEW COMMITMENT]
Feeling: [OVERWHELMED/MANAGEABLE/UNDERUTILIZED]

Workload assessment:

1. Capacity Analysis
- Total available hours
- Current allocation
- Remaining capacity
- Buffer needed

2. Commitment Review
For each commitment:
- Hours required
- Energy required
- Flexibility
- Value/importance
- End date (if any)

3. Hidden Time Costs
- Transition time
- Communication overhead
- Meetings
- Administrative tasks
- Mental load

4. Energy Assessment
- High-energy tasks
- Low-energy tasks
- Energy balance
- Sustainability check

5. New Request Evaluation
- Time requirement
- Opportunity cost
- Strategic value
- Fit with capacity

6. Options Analysis
- Take it all on
- Negotiate scope
- Delay something else
- Decline

7. Recommendations
- Optimal decision
- What to adjust
- Communication needed
- Boundary setting

8. Sustainability Plan
- Workload monitoring
- Early warning signs
- Regular review
- Rebalancing triggers
```

#### prod-048 - Transition Period Planning
- Placeholders: `DATES, DESCRIPTION, START TO END, WORRIES`
- Prompt:

```text
Plan for a transition period in [SITUATION - job change, move, life change].

Transition details:
- What's changing: [DESCRIPTION]
- Timeline: [START TO END]
- Key milestones: [DATES]
- Concerns: [WORRIES]

Transition planning:

1. Transition Timeline
- Pre-transition phase
- Active transition phase
- Post-transition phase
- Key dates

2. Task Inventory
- Must complete before
- Must complete during
- Can wait until after
- Can delegate

3. Knowledge Transfer
- What to document
- Who to inform
- Training needed
- Handoff schedule

4. Emotional Preparation
- Anticipated challenges
- Support needed
- Self-care plan
- Celebration points

5. Logistics Checklist
- Administrative tasks
- Communications needed
- Resources to arrange
- Connections to maintain

6. First Week Plan
- Day 1 priorities
- Week 1 goals
- Early wins
- Learning focus

7. 30-60-90 Day Plan
- 30-day goals
- 60-day goals
- 90-day goals
- Success metrics

8. Support System
- Key contacts
- Resources available
- Check-in schedule
- Help to request
```

#### prod-049 - Interruption Protocol
- Placeholders: `HOW IT AFFECTS WORK, HOW OFTEN, OFFICE/HOME/HYBRID, PEOPLE/NOTIFICATIONS/ETC`
- Prompt:

```text
Create a protocol for handling interruptions at work.

Work environment: [OFFICE/HOME/HYBRID]
Interruption sources: [PEOPLE/NOTIFICATIONS/ETC]
Current frequency: [HOW OFTEN]
Impact: [HOW IT AFFECTS WORK]

Interruption protocol:

1. Interruption Categories
- True emergencies
- Urgent but not emergency
- Important but not urgent
- Low priority

2. Availability Signals
- Do not disturb indicators
- Open for quick questions
- Available for discussions
- Communication methods

3. Response Protocols

Emergency:
- Immediate response
- Drop everything
- Criteria for true emergency

Urgent:
- Acknowledge quickly
- Schedule response
- Time-box discussion

Important:
- Add to processing queue
- Scheduled response time
- Batch handling

Low priority:
- Defer or decline
- Redirect if needed
- Set expectations

4. Communication Scripts
- "I'm in deep work, can we..."
- "I have 2 minutes now..."
- "Let me add that to my list..."
- "Is this urgent or can it wait..."

5. Recovery Protocol
- Quick capture current state
- Handle interruption
- Return to task ritual
- Minimize restart time

6. Prevention Strategies
- Proactive communication
- Office hours
- Batch availability
- Environment design

7. Team Agreements
- Shared expectations
- Communication norms
- Respect for focus time
```

#### prod-050 - Year-End Review & New Year Planning
- Placeholders: `YEAR`
- Prompt:

```text
Conduct a comprehensive year-end review and new year planning session.

Year completing: [YEAR]
Life areas to review:
- Career/Work
- Health/Fitness
- Relationships
- Finances
- Personal Growth
- Fun/Adventure
- Contribution

Year-end review:

1. Year in Review
- Biggest accomplishments
- Biggest challenges
- Unexpected surprises
- Proudest moments
- Regrets or disappointments

2. Goal Assessment
- Goals achieved
- Goals partially met
- Goals abandoned
- Lessons about goal-setting

3. Life Area Scorecard
For each area (rate 1-10):
- Year start score
- Year end score
- Key events
- Lessons learned

4. Relationship Inventory
- Relationships strengthened
- Relationships that faded
- New connections made
- Relationship intentions

5. Growth Inventory
- Skills developed
- Knowledge gained
- Personal evolution
- Mindset shifts

6. Gratitude Reflection
- People to thank
- Opportunities received
- Lessons appreciated

7. New Year Vision
- Theme for the year
- Vision statement
- Word of the year
- How I want to feel

8. New Year Goals
For each life area:
- 1-3 specific goals
- Key habits to build
- Major projects
- Learning priorities

9. Quarterly Breakdown
- Q1 focus
- Q2 focus
- Q3 focus
- Q4 focus

10. Action Plan
- First week actions
- First month milestones
- Systems to implement
- Support to arrange
```

### 6. Learning & Research

#### learn-001 - Concept Explainer
- Placeholders: `CONCEPT`
- Prompt:

```text
Explain [CONCEPT] to me as if I'm a complete beginner. Break it down into:
1. Simple definition (one sentence)
2. Real-world analogy
3. Why it matters
4. 3 key components
5. Common misconceptions
6. How to learn more
```

#### learn-002 - Learning Path Creator
- Placeholders: `SKILL`
- Prompt:

```text
Create a complete learning path for mastering [SKILL]. Include:

1. Prerequisites (what I should know first)
2. Beginner phase (weeks 1-4)
3. Intermediate phase (months 2-3)
4. Advanced phase (months 4-6)

For each phase include:
- Specific topics to learn
- Best free resources
- Practice projects
- Milestones to hit

End with how to know when I've achieved competency.
```

#### learn-003 - Research Summary Generator
- Placeholders: `TOPIC`
- Prompt:

```text
I'm researching [TOPIC]. Provide a comprehensive summary including:

1. Overview and definition
2. Historical context/development
3. Current state of knowledge
4. Key debates or controversies
5. Major figures or contributors
6. Practical applications
7. Future directions
8. Recommended reading (books, papers, websites)

Present information objectively and note where expert opinions differ.
```

#### learn-004 - Study Guide Creator
- Placeholders: `SUBJECT/EXAM`
- Prompt:

```text
Create a comprehensive study guide for [SUBJECT/EXAM]. Include:

1. Key concepts (with brief explanations)
2. Important formulas/definitions to memorize
3. Common question types
4. Memory tricks and mnemonics
5. Practice questions with answers
6. Study schedule suggestion
7. Test-taking strategies specific to this subject
```

#### learn-005 - Socratic Teacher
- Placeholders: `CONCEPT`
- Prompt:

```text
Teach me [CONCEPT] using the Socratic method. Ask me thought-provoking questions that lead me to discover the answers myself. Start with a simple question, and based on my responses, guide me deeper into understanding. Don't give direct answers - help me reason my way there.
```

#### learn-006 - Flashcard Generator
- Placeholders: `TOPIC`
- Prompt:

```text
Create 20 flashcards for studying [TOPIC]. Format each as:

FRONT: [Question or term]
BACK: [Answer or definition]

Include a mix of:
- Definition cards
- Concept application cards
- Compare/contrast cards
- Example-based cards

Order from basic to advanced concepts.
```

#### learn-007 - Knowledge Gap Finder
- Placeholders: `CURRENT_KNOWLEDGE, GOAL, SUBJECT`
- Prompt:

```text
I'm learning [SUBJECT] and currently understand [CURRENT_KNOWLEDGE]. My goal is to [GOAL].

Identify:
1. Critical gaps in my knowledge
2. Concepts I likely misunderstand
3. What I should learn next (priority order)
4. Prerequisites I may have missed
5. Common plateaus at my level and how to overcome them
```

#### learn-008 - ELI5 Explainer
- Placeholders: `COMPLEX_TOPIC`
- Prompt:

```text
Explain [COMPLEX_TOPIC] like I'm 5 years old. Use:
- Simple words only
- Familiar everyday analogies
- A short story or example a child would understand
- No jargon whatsoever

Then explain it again at a high school level, then at an expert level. Show how the same concept scales in complexity.
```

#### learn-009 - Book Summary & Takeaways
- Placeholders: `AUTHOR, BOOK_TITLE`
- Prompt:

```text
Provide a comprehensive summary of the book '[BOOK_TITLE]' by [AUTHOR]. Include:

1. Main thesis in one sentence
2. Chapter-by-chapter key points
3. Top 10 actionable takeaways
4. Memorable quotes
5. Who should read this book
6. Related books to read next
7. Critiques or limitations of the book's arguments
```

#### learn-010 - Practice Problem Generator
- Placeholders: `DIFFICULTY_LEVEL, TOPIC/SKILL`
- Prompt:

```text
Generate 10 practice problems for [TOPIC/SKILL] at [DIFFICULTY_LEVEL] level. For each problem:

1. State the problem clearly
2. Provide hints (hidden, reveal if stuck)
3. Show step-by-step solution
4. Explain common mistakes to avoid
5. Suggest similar problems to try

Start with the easiest and progress to hardest.
```

#### learn-011 - Mental Model Teacher
- Placeholders: `MENTAL_MODEL`
- Prompt:

```text
Teach me the [MENTAL_MODEL] mental model. Explain:

1. What it is and where it came from
2. The core principle in one sentence
3. 3 real-world examples of it in action
4. When to use this model
5. When it fails or doesn't apply
6. How to practice thinking with this model
7. Related mental models to learn
```

#### learn-012 - Debate Both Sides
- Placeholders: `CONTROVERSIAL_TOPIC`
- Prompt:

```text
Present both sides of the debate on [CONTROVERSIAL_TOPIC].

Side A (For):
- Strongest 5 arguments
- Evidence and examples
- Values this side prioritizes

Side B (Against):
- Strongest 5 arguments
- Evidence and examples
- Values this side prioritizes

Conclusion:
- Where both sides agree
- The crux of the disagreement
- Questions that might resolve the debate
```

#### learn-013 - Historical Event Deep Dive
- Placeholders: `HISTORICAL_EVENT`
- Prompt:

```text
Provide an in-depth analysis of [HISTORICAL_EVENT]. Include:

1. Background and causes
2. Key players and their motivations
3. Timeline of events
4. Immediate consequences
5. Long-term impacts still felt today
6. Different historical interpretations
7. Lessons for the present
8. Primary sources to explore
```

#### learn-014 - Scientific Paper Explainer
- Placeholders: `PAPER_TOPIC/ABSTRACT`
- Prompt:

```text
Explain this scientific concept/paper in accessible terms:

[PAPER_TOPIC/ABSTRACT]

Provide:
1. Main finding in plain English
2. Why this matters
3. How the research was conducted
4. Limitations and caveats
5. What questions remain
6. Practical implications
7. How this fits into the broader field
```

#### learn-015 - Skill Breakdown
- Placeholders: `SKILL`
- Prompt:

```text
Break down [SKILL] into its component sub-skills. For each sub-skill:

1. Name and description
2. Why it's important
3. How to practice it in isolation
4. How long it typically takes to develop
5. How to know you've mastered it

Then explain how these sub-skills combine into overall competency.
```

#### learn-016 - Compare & Contrast Analysis
- Placeholders: `THING_A, THING_B`
- Prompt:

```text
Compare and contrast [THING_A] and [THING_B]. Analyze:

1. Key similarities
2. Key differences
3. Pros and cons of each
4. When to choose one over the other
5. Historical relationship between them
6. Common misconceptions about their differences
7. Hybrid or alternative options
```

#### learn-017 - Terminology Dictionary
- Placeholders: `FIELD/TOPIC`
- Prompt:

```text
Create a comprehensive glossary for [FIELD/TOPIC]. For each term include:

- Simple definition
- Etymology (word origin)
- Example in context
- Related terms
- Common misuse

Organize alphabetically and include at least 25 essential terms a beginner needs to know.
```

#### learn-018 - Learning From Failure
- Placeholders: `FIELD/INDUSTRY`
- Prompt:

```text
Analyze famous failures in [FIELD/INDUSTRY] and extract lessons:

1. List 5 notable failures
2. For each:
   - What happened
   - Root causes
   - Warning signs that were missed
   - How it could have been prevented
   - Key lesson

Conclude with universal principles for avoiding failure.
```

#### learn-019 - Expert Interview Questions
- Placeholders: `FIELD`
- Prompt:

```text
I'm going to interview an expert in [FIELD]. Generate:

1. 10 thoughtful questions to understand their work
2. 5 questions about their career journey
3. 5 questions about future trends
4. 3 contrarian questions that challenge assumptions
5. Questions to ask for resources and advice

Order from warm-up to deep-dive questions.
```

#### learn-020 - Misconception Buster
- Placeholders: `TOPIC`
- Prompt:

```text
List the top 10 misconceptions about [TOPIC]. For each:

1. The common misconception
2. The truth
3. Why this misconception persists
4. Evidence that disproves it
5. How to explain the truth to someone who believes the myth
```

#### learn-021 - Speed Learning System
- Placeholders: `SKILL, TIME_PERIOD`
- Prompt:

```text
Design a speed learning system to acquire [SKILL] in [TIME_PERIOD]. Include:

1. The 20% that gives 80% of results (focus areas)
2. Daily practice routine (with specific exercises)
3. Resources ranked by efficiency
4. Milestones and checkpoints
5. Common time-wasters to avoid
6. How to test your progress
7. What 'good enough' looks like vs. mastery
```

#### learn-022 - Question Generator
- Placeholders: `TOPIC`
- Prompt:

```text
I'm studying [TOPIC]. Generate 50 questions I should be able to answer to prove I understand it:

- 15 basic recall questions
- 15 comprehension questions
- 10 application questions
- 10 analysis/synthesis questions

Group by difficulty and topic area.
```

#### learn-023 - Theory to Practice Bridge
- Placeholders: `THEORY/CONCEPT`
- Prompt:

```text
I understand [THEORY/CONCEPT] theoretically but struggle to apply it. Create a practical application guide:

1. Why the theory-practice gap exists for this concept
2. 5 simple exercises to build intuition
3. 3 real-world scenarios to practice with
4. Common mistakes when applying this concept
5. Signs you've successfully bridged the gap
6. Advanced applications once basics are solid
```

#### learn-024 - Cross-Disciplinary Connections
- Placeholders: `SUBJECT`
- Prompt:

```text
I'm learning [SUBJECT]. Show me how it connects to other fields:

1. 5 connections to seemingly unrelated fields
2. How concepts from [SUBJECT] appear elsewhere
3. Insights from other fields that improve understanding of [SUBJECT]
4. Interdisciplinary career/project opportunities
5. Books/resources that explore these connections
```

#### learn-025 - Spaced Repetition Schedule
- Placeholders: `DATE, EXAM/MATERIAL, TOPICS`
- Prompt:

```text
Create a spaced repetition study schedule for [EXAM/MATERIAL]. Details:
- Exam date: [DATE]
- Material to cover: [TOPICS]

Provide:
1. Day-by-day schedule
2. What to review each day
3. When to introduce new material vs. review
4. Self-testing checkpoints
5. Buffer time for difficult concepts
6. Day-before-exam strategy
```

#### learn-026 - Expert vs. Novice Thinking
- Placeholders: `FIELD`
- Prompt:

```text
Describe how an expert in [FIELD] thinks differently from a novice:

1. What patterns do experts see that novices miss?
2. What do experts do automatically that novices must think about?
3. Common novice mistakes that mark someone as inexperienced
4. Mental shortcuts experts use
5. How experts approach problems differently
6. How to accelerate the novice-to-expert transition
```

#### learn-027 - Primary Source Finder
- Placeholders: `TOPIC`
- Prompt:

```text
I'm researching [TOPIC]. Help me find primary sources:

1. Types of primary sources available for this topic
2. Where to find them (databases, archives, etc.)
3. How to evaluate source credibility
4. Key primary sources I should definitely examine
5. How to cite and reference them properly
6. Secondary sources that analyze these primaries well
```

#### learn-028 - Learning Style Optimizer
- Placeholders: `LEARNING_STYLE, SUBJECT`
- Prompt:

```text
I learn best by [LEARNING_STYLE]. Optimize my approach to learning [SUBJECT]:

1. Study techniques that match my style
2. Resources in formats that work for me
3. How to adapt content that doesn't match my style
4. Exercises designed for my type of learner
5. Potential blindspots of my learning style
6. How to develop complementary learning approaches
```

#### learn-029 - Feynman Technique Application
- Placeholders: `CONCEPT`
- Prompt:

```text
Help me apply the Feynman Technique to [CONCEPT]:

1. Have me explain the concept simply (then critique my explanation)
2. Identify gaps in my understanding
3. Provide the information to fill those gaps
4. Suggest analogies I could use
5. Give me a final test: questions a child might ask
6. Provide a model simple explanation
```

#### learn-030 - Research Question Refiner
- Placeholders: `BROAD_TOPIC`
- Prompt:

```text
I want to research [BROAD_TOPIC]. Help me develop a focused research question:

1. Problems with researching the topic too broadly
2. 5 possible specific research questions
3. For each question:
   - Is it answerable?
   - Is it significant?
   - Is it original?
4. Recommended question and why
5. How to further narrow if needed
6. Keywords for database searches
```

#### learn-031 - Memory Palace Builder
- Placeholders: `INFORMATION`
- Prompt:

```text
Help me build a memory palace to memorize [INFORMATION]. 

1. Walk me through creating a mental location
2. Show how to place each piece of information
3. Create vivid, memorable associations
4. Provide a walkthrough of the completed palace
5. Tips for reviewing and maintaining the memory
6. How to expand the palace for more information
```

#### learn-032 - Literature Review Structure
- Placeholders: `RESEARCH_TOPIC`
- Prompt:

```text
Help me structure a literature review on [RESEARCH_TOPIC]:

1. Main themes/categories to organize around
2. Key authors and papers to include
3. How to show evolution of thinking over time
4. Where current debates and gaps lie
5. How to synthesize rather than just summarize
6. Transition phrases for academic writing
7. How to position my own research within the literature
```

#### learn-033 - Deliberate Practice Designer
- Placeholders: `SKILL`
- Prompt:

```text
Design a deliberate practice routine for improving [SKILL]. Include:

1. Specific sub-skills to isolate and practice
2. Exercises for each sub-skill
3. How to get immediate feedback
4. How to push just beyond current ability
5. Session structure (duration, breaks, frequency)
6. Progress tracking method
7. When to move to harder challenges
```

#### learn-034 - Curriculum Comparison
- Placeholders: `MY_SITUATION, SUBJECT`
- Prompt:

```text
Compare different ways to learn [SUBJECT]:

1. Self-study (books/online)
2. University courses
3. Bootcamps/intensive programs
4. Mentorship/apprenticeship
5. Project-based learning

For each: time investment, cost, effectiveness, credentials gained, best for whom. Recommend the best path for [MY_SITUATION].
```

#### learn-035 - Note-Taking System
- Placeholders: `SUBJECT`
- Prompt:

```text
Design an optimal note-taking system for learning [SUBJECT]. Consider:

1. Best method (Cornell, mind maps, outline, etc.) for this subject
2. What to capture vs. skip
3. How to organize notes for retrieval
4. Integration with spaced repetition
5. Digital vs. handwritten considerations
6. Review and refinement process
7. Template to use
```

#### learn-036 - Argument Analyzer
- Placeholders: `ARGUMENT, TOPIC`
- Prompt:

```text
Analyze this argument about [TOPIC]:

[ARGUMENT]

Provide:
1. Main claim and supporting premises
2. Logical structure (valid/invalid)
3. Hidden assumptions
4. Potential counterarguments
5. Evidence that would strengthen/weaken it
6. Logical fallacies present (if any)
7. Overall assessment of argument strength
```

#### learn-037 - Textbook Chapter Summary
- Placeholders: `CHAPTER_TOPIC`
- Prompt:

```text
I'm reading a textbook chapter on [CHAPTER_TOPIC]. Create a study summary:

1. Key terms and definitions
2. Main concepts explained simply
3. How concepts connect to each other
4. Important examples to remember
5. Likely exam questions
6. What to memorize vs. understand
7. Connections to previous/next chapters
```

#### learn-038 - Teach What You Learn
- Placeholders: `TOPIC`
- Prompt:

```text
I'm learning [TOPIC]. Create a lesson plan for me to teach it to someone else:

1. How to introduce the topic engagingly
2. Core concepts to cover (in order)
3. Analogies and examples to use
4. Interactive elements/exercises
5. Common questions students ask
6. How to check for understanding
7. Summary and key takeaways

Teaching is the best way to learn!
```

#### learn-039 - Academic Paper Structure
- Placeholders: `RESEARCH_TOPIC`
- Prompt:

```text
Help me structure an academic paper on [RESEARCH_TOPIC]:

1. Strong thesis statement options
2. Outline with section headings
3. What each section should accomplish
4. How to integrate sources
5. Transition strategies between sections
6. Introduction hook ideas
7. Conclusion strategies
8. Abstract template
```

#### learn-040 - Learning Accountability Partner
- Placeholders: `SUBJECT`
- Prompt:

```text
Act as my learning accountability partner for [SUBJECT]. Help me:

1. Set specific, measurable learning goals
2. Create a realistic schedule
3. Define checkpoints and milestones
4. Plan how to handle setbacks
5. Celebrate wins appropriately
6. Questions to ask myself for reflection
7. Signs I'm making real progress
```

#### learn-041 - Critical Reading Guide
- Placeholders: `SUBJECT`
- Prompt:

```text
Create a critical reading guide for texts about [SUBJECT]. Include:

1. Questions to ask before reading
2. What to look for while reading
3. How to identify author bias
4. Evaluating source credibility
5. Note-taking prompts
6. Post-reading reflection questions
7. How to synthesize with other readings
```

#### learn-042 - Visual Concept Map
- Placeholders: `TOPIC`
- Prompt:

```text
Create a text-based concept map for [TOPIC] showing:

1. Central concept
2. Main branches (major subtopics)
3. Sub-branches (details)
4. Connections between branches
5. Examples at the leaf nodes
6. Color/symbol key for different types of information

Format it clearly so I could redraw it visually.
```

#### learn-043 - Research Methodology Explainer
- Placeholders: `RESEARCH_METHOD`
- Prompt:

```text
Explain [RESEARCH_METHOD] methodology:

1. What it is and when to use it
2. Step-by-step process
3. Advantages and limitations
4. Famous studies using this method
5. Common mistakes to avoid
6. How to evaluate research using this method
7. Comparison to alternative methods
```

#### learn-044 - Skill Transfer Analysis
- Placeholders: `EXISTING_SKILL, NEW_SKILL`
- Prompt:

```text
I know [EXISTING_SKILL]. Analyze how to transfer this knowledge to learning [NEW_SKILL]:

1. Overlapping concepts and skills
2. What transfers directly
3. What needs to be unlearned or adjusted
4. Unique aspects of the new skill
5. Accelerated learning path based on my background
6. Pitfalls of assuming too much similarity
```

#### learn-045 - Learning Plateau Breaker
- Placeholders: `CURRENT_LEVEL, SKILL`
- Prompt:

```text
I've hit a plateau learning [SKILL]. I'm stuck at [CURRENT_LEVEL]. Help me break through:

1. Diagnose why plateaus happen at this level
2. Specific areas to focus on
3. New approaches to try
4. Drills to build weak areas
5. Mental blocks that might be limiting me
6. How long plateaus typically last
7. Signs I'm about to break through
```

### 7. Personal Development

#### personal-001 - Weekly Reflection
- Placeholders: `DATE`
- Prompt:

```text
Guide me through a deep weekly reflection for the week of [DATE]:

1. What were my 3 biggest wins this week?
2. What didn't go as planned and why?
3. What did I learn about myself?
4. Who did I help or connect with?
5. What am I grateful for?
6. What habits did I maintain/break?
7. What should I do differently next week?
8. What's my #1 focus for next week?
```

#### personal-002 - Goal Setting Framework
- Placeholders: `TIME_PERIOD`
- Prompt:

```text
Help me set effective goals for [TIME_PERIOD]. For each area of life (career, health, relationships, finances, personal growth):

1. What does success look like?
2. One specific, measurable goal
3. Why this goal matters to me
4. Potential obstacles
5. First action to take this week
6. How I'll track progress
7. Who can support me
```

#### personal-003 - Limiting Belief Challenger
- Placeholders: `LIMITING_BELIEF`
- Prompt:

```text
I have this limiting belief: '[LIMITING_BELIEF]'

Help me work through it:

1. Where might this belief have come from?
2. What evidence supports this belief?
3. What evidence contradicts it?
4. How has this belief held me back?
5. What would I do if I didn't believe this?
6. A new, empowering belief to replace it
7. Affirmations to reinforce the new belief
8. Small action to prove the old belief wrong
```

#### personal-004 - Habit Building System
- Placeholders: `HABIT`
- Prompt:

```text
Help me build the habit of [HABIT]. Create a complete system:

1. Make it obvious (cue design)
2. Make it attractive (temptation bundling)
3. Make it easy (reduce friction)
4. Make it satisfying (immediate reward)
5. Habit stack with existing habits
6. Tracking method
7. If-then contingency plans
8. 30-day progression schedule
```

#### personal-005 - Decision Making Framework
- Placeholders: `DECISION, OPTIONS`
- Prompt:

```text
I need to decide: [DECISION]

Options I'm considering: [OPTIONS]

Walk me through:
1. What's really at stake?
2. What are my core values relevant to this?
3. Pros and cons matrix for each option
4. What would I advise a friend in this situation?
5. What will matter most in 10 years?
6. What am I afraid of?
7. What does my gut say?
8. Recommended decision and why
```

#### personal-006 - Fear Analysis
- Placeholders: `FEAR`
- Prompt:

```text
I'm afraid of [FEAR]. Help me understand and overcome it:

1. What specifically am I afraid will happen?
2. What's the worst realistic outcome?
3. How likely is the worst case?
4. Could I recover from the worst case?
5. What's the cost of NOT taking action?
6. What would I do if I wasn't afraid?
7. Smallest step to face this fear
8. Exposure ladder (gradual steps)
```

#### personal-007 - Life Audit
- Placeholders: None
- Prompt:

```text
Conduct a comprehensive life audit. Rate each area 1-10 and analyze:

1. Health & Fitness
2. Career & Work
3. Finances
4. Relationships & Social
5. Family
6. Fun & Recreation
7. Personal Growth
8. Physical Environment
9. Contribution & Impact
10. Spiritual/Meaning

For the lowest-rated areas, identify specific improvements and first steps.
```

#### personal-008 - Morning Routine Designer
- Placeholders: `LIFESTYLE_DETAILS`
- Prompt:

```text
Design an optimal morning routine for me. Context: [LIFESTYLE_DETAILS]

Create a routine that:
1. Fits my available time
2. Energizes body and mind
3. Aligns with my goals
4. Is sustainable (not too ambitious)
5. Has flexibility built in
6. Includes keystone habits

Provide a detailed schedule with timing and explain why each element is included.
```

#### personal-009 - Procrastination Breaker
- Placeholders: `TASK`
- Prompt:

```text
I'm procrastinating on [TASK]. Help me:

1. Identify the real reason I'm avoiding it
2. Break it into tiny, non-threatening steps
3. Find my resistance points
4. Create artificial urgency
5. Set up accountability
6. Design the perfect environment
7. Use the 2-minute rule
8. Give me a pep talk to start RIGHT NOW
```

#### personal-010 - Values Clarification
- Placeholders: None
- Prompt:

```text
Help me clarify my core values through these exercises:

1. What 3 moments in life have made me happiest?
2. What makes me angry or frustrated?
3. Who do I admire and why?
4. What would I do with unlimited money?
5. What would I regret not doing?
6. What do I spend time on happily?

From this, identify my top 5 values and how to better align my life with them.
```

#### personal-011 - Difficult Conversation Prep
- Placeholders: `PERSON/RELATIONSHIP, SITUATION`
- Prompt:

```text
I need to have a difficult conversation about [SITUATION] with [PERSON/RELATIONSHIP].

Help me prepare:
1. What's my real objective?
2. What might their perspective be?
3. How to open the conversation
4. Key points to make (using 'I' statements)
5. How to listen effectively
6. Potential reactions and responses
7. Finding common ground
8. How to end constructively
```

#### personal-012 - Anger Management
- Placeholders: `SITUATION`
- Prompt:

```text
I'm struggling with anger about [SITUATION]. Help me process it:

1. Validate what I'm feeling
2. What unmet need is behind the anger?
3. What can I control vs. not control?
4. Healthy ways to express this feeling
5. Reframing the situation
6. Physical techniques to calm down
7. Long-term strategies
8. When it might indicate deeper work needed
```

#### personal-013 - Confidence Builder
- Placeholders: None
- Prompt:

```text
Help me build authentic confidence. Start with:

1. Inventory my genuine strengths and accomplishments
2. Identify where I feel least confident
3. Recognize distorted self-talk patterns
4. Create a personal 'wins' library
5. Body language adjustments
6. Confidence-building challenges for the week
7. Mantras and affirmations that don't feel fake
8. How to project confidence while still growing
```

#### personal-014 - Career Transition Advisor
- Placeholders: `CURRENT_CAREER, NEW_CAREER`
- Prompt:

```text
I'm considering transitioning from [CURRENT_CAREER] to [NEW_CAREER]. Analyze:

1. Transferable skills I already have
2. Skills I need to develop
3. Realistic timeline
4. Financial considerations
5. Steps to test this path before committing
6. How to position my background as an advantage
7. Networking strategy
8. Potential challenges and how to overcome them
```

#### personal-015 - Stress Management Plan
- Placeholders: `STRESSORS`
- Prompt:

```text
My current stressors: [STRESSORS]

Create a personalized stress management plan:

1. Categorize stressors (can change, can't change, can influence)
2. Immediate coping techniques
3. Daily stress-prevention habits
4. Weekly reset activities
5. Monthly check-in process
6. Warning signs that stress is too high
7. Emergency de-stress protocol
8. Long-term lifestyle changes
```

#### personal-016 - Personal SWOT Analysis
- Placeholders: `GOAL`
- Prompt:

```text
Conduct a personal SWOT analysis for my goal of [GOAL]:

Strengths:
- What advantages do I have?
- What am I good at?

Weaknesses:
- What could I improve?
- What do I avoid?

Opportunities:
- What trends could I leverage?
- Who could help me?

Threats:
- What obstacles exist?
- What could go wrong?

Then create an action plan leveraging strengths, addressing weaknesses.
```

#### personal-017 - Relationship Improvement
- Placeholders: `CHALLENGES, PERSON/RELATIONSHIP_TYPE`
- Prompt:

```text
I want to improve my relationship with [PERSON/RELATIONSHIP_TYPE]. Current challenges: [CHALLENGES]

Help me:
1. Understand their perspective
2. Identify my contribution to the dynamic
3. Find specific behaviors to change
4. Create connection opportunities
5. Improve communication patterns
6. Set healthy boundaries
7. Rebuild trust if needed
8. Measure improvement over time
```

#### personal-018 - Energy Audit
- Placeholders: None
- Prompt:

```text
Help me understand my energy patterns:

1. What activities drain my energy?
2. What activities energize me?
3. What people drain my energy?
4. What people energize me?
5. When in the day am I most energized?
6. How does food/sleep/exercise affect me?

Then design an ideal day that maximizes energy based on these insights.
```

#### personal-019 - Boundary Setting Guide
- Placeholders: `BOUNDARY_AREA, SITUATION`
- Prompt:

```text
Help me set better boundaries around [BOUNDARY_AREA]. Current situation: [SITUATION]

1. Why this boundary matters
2. What specifically needs to change
3. Scripts for communicating the boundary
4. How to handle pushback
5. Maintaining the boundary over time
6. When flexibility is appropriate
7. Self-care during the transition
8. Signs the boundary is working
```

#### personal-020 - Imposter Syndrome Coach
- Placeholders: `SITUATION`
- Prompt:

```text
I'm experiencing imposter syndrome about [SITUATION]. Help me:

1. Normalize what I'm experiencing
2. Examine the evidence objectively
3. Identify cognitive distortions
4. Create a 'proof file' of my competence
5. Reframe the situation
6. Turn anxiety into excitement
7. Prepare for the situation specifically
8. Build long-term imposter resistance
```

#### personal-021 - Life Purpose Exploration
- Placeholders: None
- Prompt:

```text
Guide me through discovering my life purpose:

1. What did I love doing as a child?
2. What would I do if money didn't matter?
3. What problems in the world bother me most?
4. When do I feel most alive?
5. What do people come to me for help with?
6. What would I like my legacy to be?
7. Ikigai analysis (love, good at, paid for, world needs)
8. Draft a personal mission statement
```

#### personal-022 - Habit Breaking Strategy
- Placeholders: `BAD_HABIT`
- Prompt:

```text
I want to break the habit of [BAD_HABIT]. Create a complete strategy:

1. Identify the cue that triggers it
2. What craving/reward am I really seeking?
3. Healthier alternatives that provide similar reward
4. Environmental changes to remove triggers
5. Replacement behaviors
6. If-then implementation intentions
7. Accountability structure
8. How to handle relapses
```

#### personal-023 - Self-Compassion Practice
- Placeholders: `SITUATION`
- Prompt:

```text
I'm being hard on myself about [SITUATION]. Help me practice self-compassion:

1. Acknowledge my suffering without minimizing
2. Remind me this is a common human experience
3. What would I say to a friend in this situation?
4. Identify the self-critical voice
5. Reframe with kindness
6. Physical self-soothing techniques
7. Affirmations for self-compassion
8. Long-term self-compassion practices
```

#### personal-024 - 10-Year Vision
- Placeholders: None
- Prompt:

```text
Help me create a compelling 10-year vision. In 10 years:

1. Where am I living?
2. What does a typical day look like?
3. What work am I doing?
4. Who is in my life?
5. How do I feel physically?
6. What have I accomplished?
7. What impact am I having?
8. What do I value most?

Then work backwards: 5-year milestone, 1-year milestone, 90-day first steps.
```

#### personal-025 - Perfectionism Overcomer
- Placeholders: `GOAL/AREA`
- Prompt:

```text
My perfectionism is getting in the way of [GOAL/AREA]. Help me:

1. Identify how perfectionism is disguised as 'high standards'
2. Calculate the cost of perfectionism
3. Distinguish between helpful and harmful striving
4. Practice 'good enough'
5. Embrace iteration and failure
6. Set realistic standards
7. Celebrate progress, not perfection
8. Affirmations for recovering perfectionists
```

#### personal-026 - Grief Processing
- Placeholders: `LOSS`
- Prompt:

```text
I'm grieving [LOSS]. Help me process this:

1. Validate all my feelings as normal
2. Explain grief isn't linear
3. Healthy ways to express grief
4. Self-care during this time
5. When to seek additional support
6. How to handle difficult days
7. Honoring what was lost
8. Finding meaning without 'moving on'
```

#### personal-027 - Personal Brand Builder
- Placeholders: `PROFESSION/ROLE`
- Prompt:

```text
Help me define my personal brand as a [PROFESSION/ROLE]. Explore:

1. What makes me unique?
2. My core message
3. How I want to be perceived
4. Key themes I want to be known for
5. My story and journey
6. Voice and communication style
7. Visual representation
8. Channels to share my brand
9. Personal brand statement
```

#### personal-028 - Work-Life Integration
- Placeholders: `SITUATION`
- Prompt:

```text
I'm struggling with work-life balance. Current situation: [SITUATION]

Help me design better integration:

1. Define what balance means to ME
2. Identify non-negotiable personal time
3. Create work boundaries
4. Batch and time-block strategies
5. Energy management vs. time management
6. Saying no gracefully
7. Quick recharge techniques
8. Sustainable long-term structure
```

#### personal-029 - Motivation Finder
- Placeholders: `GOAL/ACTIVITY`
- Prompt:

```text
I've lost motivation for [GOAL/ACTIVITY]. Help me reconnect with it:

1. Why did I start in the first place?
2. What's changed since then?
3. Is this still aligned with my values?
4. What's really blocking me?
5. Finding intrinsic motivation
6. Creating external motivation
7. Minimum viable commitment
8. Rekindling the fire (or permission to quit)
```

#### personal-030 - Mindfulness Beginner Guide
- Placeholders: `TIME_AVAILABLE`
- Prompt:

```text
Create a beginner's mindfulness practice guide for someone with [TIME_AVAILABLE] per day:

1. What mindfulness is (and isn't)
2. Benefits backed by science
3. Simple breathing exercise
4. Body scan instruction
5. Mindful daily activities
6. Handling wandering thoughts
7. Week-by-week progression
8. Common mistakes and solutions
```

#### personal-031 - Forgiveness Process
- Placeholders: `PERSON/SITUATION`
- Prompt:

```text
I'm struggling to forgive [PERSON/SITUATION]. Guide me through:

1. Acknowledge what happened and how it affected me
2. Understand forgiveness isn't condoning
3. Explore what forgiveness would give me
4. Release the need for apology or justice
5. Find meaning or growth from the experience
6. Set boundaries going forward
7. Practice compassion (for them and myself)
8. Rituals for letting go
```

#### personal-032 - Social Skills Builder
- Placeholders: `SPECIFIC_AREA`
- Prompt:

```text
I want to improve my social skills, especially [SPECIFIC_AREA]. Help me:

1. Understand the underlying principles
2. Observe good examples
3. Start small (specific exercises)
4. Handle awkwardness gracefully
5. Read social cues better
6. Become a better listener
7. Build genuine connections
8. Practice opportunities this week
```

#### personal-033 - Quarter-Life/Mid-Life Transition
- Placeholders: `FEELINGS, TYPE`
- Prompt:

```text
I'm going through a [TYPE] life transition. I'm feeling [FEELINGS].

Help me navigate this:

1. Normalize this experience
2. What questions should I be asking myself?
3. What old identities am I outgrowing?
4. What new possibilities are emerging?
5. How to sit with uncertainty
6. Resources and support
7. Red flags to watch for
8. How to emerge stronger
```

#### personal-034 - Financial Psychology
- Placeholders: `CURRENT_FEELINGS, MONEY_BACKGROUND`
- Prompt:

```text
Analyze my relationship with money. I grew up with [MONEY_BACKGROUND] and currently feel [CURRENT_FEELINGS] about finances.

1. Identify my money scripts (beliefs)
2. Where these beliefs came from
3. How they help and hurt me
4. Emotional patterns around spending/saving
5. Healthier money mindsets
6. Behavioral changes to try
7. Financial self-care practices
8. Affirmations for money wellness
```

#### personal-035 - Digital Wellness Plan
- Placeholders: None
- Prompt:

```text
Help me create a healthier relationship with technology:

1. Audit my current screen time and habits
2. Identify problematic patterns
3. What needs does tech overuse meet?
4. Create phone-free zones/times
5. Digital sunset routine
6. Apps and settings to change
7. Real-world activities to substitute
8. 30-day digital detox challenge
```

#### personal-036 - People-Pleasing Recovery
- Placeholders: None
- Prompt:

```text
I struggle with people-pleasing. Help me recover:

1. Why do I people-please? (root causes)
2. The cost of always saying yes
3. Recognizing people-pleasing in action
4. Distinguishing kindness from people-pleasing
5. Learning to say no (scripts)
6. Handling guilt after setting boundaries
7. Building identity outside of approval
8. Week-by-week recovery plan
```

#### personal-037 - Loneliness Navigator
- Placeholders: None
- Prompt:

```text
I'm experiencing loneliness. Help me address it:

1. Validate loneliness as a universal experience
2. Distinguish between alone and lonely
3. Identify what type of connection I'm missing
4. Quality vs. quantity of relationships
5. Small steps to increase connection
6. Places to meet like-minded people
7. Building depth in existing relationships
8. Self-companionship practices
```

#### personal-038 - Comparison Detox
- Placeholders: `COMPARISON_TARGETS`
- Prompt:

```text
I keep comparing myself to [COMPARISON_TARGETS]. Help me stop:

1. Understand why we compare (evolutionary)
2. The cost of comparison to my wellbeing
3. What the comparison is really about
4. Focus on my own journey
5. Gratitude practices
6. Curate my environment (social media, etc.)
7. Run my own race
8. Affirmations for self-acceptance
```

#### personal-039 - Anxiety Management Toolkit
- Placeholders: `TRIGGERS`
- Prompt:

```text
I experience anxiety around [TRIGGERS]. Build me a management toolkit:

1. Understand my anxiety patterns
2. Grounding techniques (5-4-3-2-1, etc.)
3. Breathing exercises
4. Cognitive reframing techniques
5. Physical interventions
6. Long-term anxiety reduction habits
7. When to seek professional help
8. Emergency calm-down protocol
```

#### personal-040 - Life Simplification
- Placeholders: `OVERWHELM_AREAS`
- Prompt:

```text
Help me simplify my life. Current overwhelm: [OVERWHELM_AREAS]

1. Identify what truly matters to me
2. What can I eliminate entirely?
3. What can I automate or delegate?
4. Physical decluttering priorities
5. Commitment audit (what to stop)
6. Decision fatigue reduction
7. Creating margin and white space
8. Maintaining simplicity long-term
```

#### personal-041 - Resilience Builder
- Placeholders: `CHALLENGE`
- Prompt:

```text
I want to build more resilience. Recent challenge: [CHALLENGE]

Help me develop:

1. Reframe this challenge as growth opportunity
2. What strengths got me through?
3. Build support systems
4. Develop problem-solving skills
5. Increase emotional regulation
6. Find meaning in adversity
7. Stress inoculation exercises
8. Resilience mantras and reminders
```

#### personal-042 - Personal Productivity System
- Placeholders: `CHALLENGES, WORK_STYLE`
- Prompt:

```text
Design a personal productivity system for me. Context: [WORK_STYLE] and [CHALLENGES]

1. Task capture system
2. Prioritization framework
3. Calendar blocking strategy
4. Focus techniques
5. Energy management
6. Weekly review process
7. Tools to use
8. How to maintain the system
```

#### personal-043 - Self-Sabotage Awareness
- Placeholders: `GOAL`
- Prompt:

```text
I keep sabotaging myself when it comes to [GOAL]. Help me understand:

1. Identify my sabotage patterns
2. What fear is driving this behavior?
3. Secondary gains from not succeeding
4. Upper limit problem exploration
5. Beliefs about what success would mean
6. Strategies to catch myself
7. Self-compassion when I slip
8. New patterns to replace the old
```

#### personal-044 - Personal Renaissance
- Placeholders: `SITUATION, VISION`
- Prompt:

```text
I want to reinvent myself. Current situation: [SITUATION], and I want to become [VISION].

1. What aspects of myself do I want to keep?
2. What needs to change?
3. New identity statement
4. Environment changes needed
5. New habits for new me
6. Who to spend time with
7. 90-day transformation plan
8. How to handle people who knew 'old me'
```

#### personal-045 - Gratitude Deep Dive
- Placeholders: None
- Prompt:

```text
Take me through a deep gratitude practice:

1. 10 things I take for granted but shouldn't
2. 5 people who've positively impacted me
3. 3 challenges that led to growth
4. What my body allows me to do
5. Privileges I may overlook
6. Small pleasures in my daily life
7. How to express gratitude to others
8. Sustainable daily gratitude practice
```

### 8. Creative & Design

#### creative-001 - Brand Identity Developer
- Placeholders: `BRAND_NAME, BUSINESS_TYPE, TARGET_AUDIENCE`
- Prompt:

```text
Create a complete brand identity for [BRAND_NAME], a [BUSINESS_TYPE] targeting [TARGET_AUDIENCE].

Deliver:
1. Brand personality (5 key traits)
2. Brand voice guidelines
3. Color palette (primary, secondary, accent with hex codes)
4. Typography recommendations (fonts for headers, body)
5. Visual style direction
6. Logo concept description
7. Tagline options (5 variations)
8. Brand story/origin narrative
```

#### creative-002 - Creative Brainstorm Facilitator
- Placeholders: `CHALLENGE/PROJECT`
- Prompt:

```text
Facilitate a creative brainstorming session for [CHALLENGE/PROJECT].

Use these techniques:
1. 'Yes, and...' building (5 ideas)
2. Reverse brainstorming (what would make it fail?)
3. Random word association
4. SCAMPER method
5. Worst possible idea → flip it
6. 'What would [famous person] do?'

Generate at least 20 unique ideas, then narrow to top 5 with rationale.
```

#### creative-003 - UI Design Critique
- Placeholders: `APP/WEBSITE_DESCRIPTION`
- Prompt:

```text
Provide a comprehensive UI design critique for [APP/WEBSITE_DESCRIPTION].

Analyze:
1. Visual hierarchy
2. Color usage and accessibility
3. Typography choices
4. Spacing and alignment
5. Call-to-action clarity
6. User flow logic
7. Mobile responsiveness considerations
8. Consistency issues

Provide specific, actionable improvements for each area.
```

#### creative-004 - Color Palette Generator
- Placeholders: `MOOD/FEELING, PROJECT_TYPE`
- Prompt:

```text
Create a color palette for [PROJECT_TYPE] with the mood of [MOOD/FEELING].

Provide:
1. Primary color (hex, use case)
2. Secondary color (hex, use case)
3. 2 accent colors (hex, use case)
4. Background color options
5. Text color options
6. Color psychology rationale
7. Accessibility contrast ratios
8. Example usage scenarios
9. Colors to avoid and why
```

#### creative-005 - Logo Concept Creator
- Placeholders: `COMPANY_DESCRIPTION, COMPANY_NAME`
- Prompt:

```text
Generate logo concepts for [COMPANY_NAME], a [COMPANY_DESCRIPTION].

Provide 5 distinct concepts, each including:
1. Concept name
2. Visual description (detailed enough to sketch)
3. Style (minimalist, vintage, modern, etc.)
4. Symbolism and meaning
5. Color recommendation
6. Where it would work best (digital, print, etc.)
7. Potential variations (icon, wordmark, combination)
```

#### creative-006 - Creative Brief Generator
- Placeholders: `PROJECT_DESCRIPTION, PROJECT_TYPE`
- Prompt:

```text
Create a comprehensive creative brief for [PROJECT_TYPE]:

Project: [PROJECT_DESCRIPTION]

Brief should include:
1. Project overview & objectives
2. Target audience profile
3. Key message to communicate
4. Tone and style guidelines
5. Mandatory elements
6. Things to avoid
7. Deliverables and specifications
8. Timeline and milestones
9. Success metrics
10. References and inspiration
```

#### creative-007 - Naming Convention Generator
- Placeholders: `INDUSTRY, PRODUCT/COMPANY/PROJECT`
- Prompt:

```text
Generate name options for [PRODUCT/COMPANY/PROJECT] in the [INDUSTRY] space.

Create names in these categories:
1. Descriptive names (5 options)
2. Abstract/invented names (5 options)
3. Metaphorical names (5 options)
4. Acronym-based names (3 options)
5. Founder/person-based names (3 options)

For each name include:
- Meaning/rationale
- Domain availability likelihood
- Pros and cons
- How it would sound in conversation
```

#### creative-008 - Mood Board Description
- Placeholders: `PROJECT, THEME`
- Prompt:

```text
Create a detailed mood board description for [PROJECT] with the theme of [THEME].

Include:
1. Overall visual direction
2. Color story
3. 5-7 image descriptions to source
4. Texture references
5. Typography style
6. Pattern/graphic element ideas
7. Emotional response to evoke
8. Reference brands/designers
9. What doesn't fit this mood
10. Key words to search for inspiration
```

#### creative-009 - Story Idea Generator
- Placeholders: `GENRE`
- Prompt:

```text
Generate story ideas in the [GENRE] genre. For each idea provide:

5 complete story concepts including:
1. Logline (one sentence hook)
2. Main character and their flaw
3. Central conflict
4. Setting/world
5. Unique twist or angle
6. Theme/message
7. Opening scene hook
8. Potential series potential

Make each concept distinctly different.
```

#### creative-010 - User Persona Creator
- Placeholders: `PRODUCT/SERVICE`
- Prompt:

```text
Create detailed user personas for [PRODUCT/SERVICE].

Generate 3 distinct personas, each including:
1. Name and photo description
2. Demographics (age, location, occupation)
3. Background and lifestyle
4. Goals and motivations
5. Pain points and frustrations
6. How they'd use the product
7. Preferred channels and behaviors
8. Quote that captures their mindset
9. Day-in-the-life scenario
10. What would make them choose a competitor
```

#### creative-011 - Presentation Design Guide
- Placeholders: `AUDIENCE, PRESENTATION_TOPIC`
- Prompt:

```text
Create a presentation design guide for [PRESENTATION_TOPIC] aimed at [AUDIENCE].

Include:
1. Recommended structure/flow
2. Opening hook ideas
3. Slide layout suggestions for different content types
4. Color scheme recommendation
5. Font pairing
6. Icon and visual style
7. Data visualization approaches
8. Closing/CTA design
9. Slides to definitely include
10. Common mistakes to avoid
```

#### creative-012 - Character Development
- Placeholders: `CHARACTER_TYPE, STORY_CONTEXT`
- Prompt:

```text
Develop a deep character profile for a [CHARACTER_TYPE] in [STORY_CONTEXT].

Explore:
1. Physical description
2. Personality (strengths, flaws, quirks)
3. Background and formative experiences
4. Core motivation and desires
5. Deepest fears
6. Speech patterns and vocabulary
7. Relationships and social dynamics
8. Internal conflict
9. Character arc potential
10. Secrets they keep
11. How they'd react in crisis
12. Their morning routine
```

#### creative-013 - Product Photography Direction
- Placeholders: `PRODUCT, TARGET_MARKET`
- Prompt:

```text
Create product photography direction for [PRODUCT] targeting [TARGET_MARKET].

Define:
1. Overall visual style
2. Background options
3. Lighting approach
4. Props and styling elements
5. Color coordination
6. Shot list (specific angles and compositions)
7. Lifestyle vs. studio balance
8. Mood and feeling to convey
9. Post-processing style
10. Platform-specific requirements (web, social, print)
```

#### creative-014 - Design System Starter
- Placeholders: `PRODUCT/BRAND`
- Prompt:

```text
Outline a design system for [PRODUCT/BRAND].

Define:
1. Design principles (5 guiding statements)
2. Color tokens (primary, secondary, semantic)
3. Typography scale
4. Spacing system
5. Core components needed
6. Icon style guidelines
7. Motion/animation principles
8. Accessibility requirements
9. Responsive breakpoints
10. Documentation structure
11. Naming conventions
```

#### creative-015 - Video Content Concept
- Placeholders: `BRAND/PRODUCT, OBJECTIVE`
- Prompt:

```text
Create a video content concept for [BRAND/PRODUCT] to [OBJECTIVE].

Develop:
1. Video format/length recommendation
2. Core message/story
3. Opening hook (first 3 seconds)
4. Shot-by-shot breakdown
5. Music/audio direction
6. On-screen text/graphics
7. Call-to-action placement
8. Talent/casting needs
9. Location requirements
10. Platform optimization notes
```

#### creative-016 - Illustration Style Guide
- Placeholders: `BRAND/PROJECT`
- Prompt:

```text
Define an illustration style guide for [BRAND/PROJECT].

Specify:
1. Overall style (flat, isometric, hand-drawn, etc.)
2. Line weight and quality
3. Color palette usage
4. Level of detail
5. Character style (if applicable)
6. Perspective and dimension
7. Textures and patterns
8. Icon style
9. Do's and don'ts with examples
10. Reference artists/styles
11. Use cases and applications
```

#### creative-017 - Creative Writing Prompt
- Placeholders: `THEME`
- Prompt:

```text
Generate 10 creative writing prompts themed around [THEME]. For each prompt:

1. The prompt/scenario
2. Suggested genre
3. Point of view to try
4. Word count recommendation
5. Challenge element (constraint to make it interesting)
6. Emotional core to explore
7. Opening line to spark inspiration

Vary difficulty and style across the 10 prompts.
```

#### creative-018 - Event Theme Designer
- Placeholders: `EVENT_TYPE, NUMBER`
- Prompt:

```text
Design a theme for [EVENT_TYPE] with [NUMBER] guests.

Create:
1. Theme name and concept
2. Color scheme
3. Decor elements and setup
4. Invitation design direction
5. Food and drink tie-ins
6. Music and entertainment
7. Guest experience journey
8. Photo opportunity setups
9. Party favor ideas
10. Budget-friendly alternatives
11. DIY elements possible
```

#### creative-019 - App Feature Ideation
- Placeholders: `APP_TYPE`
- Prompt:

```text
Generate innovative feature ideas for [APP_TYPE] app.

Brainstorm:
1. Core feature improvements (5 ideas)
2. Engagement features (5 ideas)
3. Social/community features (3 ideas)
4. Monetization features (3 ideas)
5. Accessibility features (3 ideas)
6. 'Delight' features (unexpected value)

For each, include: description, user benefit, implementation complexity (low/med/high), and differentiation potential.
```

#### creative-020 - Packaging Design Brief
- Placeholders: `INDUSTRY, PRODUCT`
- Prompt:

```text
Create a packaging design brief for [PRODUCT] in the [INDUSTRY] market.

Define:
1. Packaging format/structure
2. Primary design elements
3. Information hierarchy
4. Material recommendations
5. Sustainability considerations
6. Shelf presence strategy
7. Unboxing experience
8. Required regulatory elements
9. Print/production specifications
10. Competitive differentiation
```

#### creative-021 - World Building Framework
- Placeholders: `STORY_TYPE`
- Prompt:

```text
Build a fictional world for [STORY_TYPE].

Develop:
1. Physical geography and climate
2. History (key events that shaped now)
3. Political structure
4. Economy and resources
5. Culture and customs
6. Technology level
7. Magic/science system (if applicable)
8. Social hierarchy
9. Conflicts and tensions
10. Daily life of ordinary people
11. Unique details that make it memorable
12. Rules that can't be broken
```

#### creative-022 - Typography Pairing
- Placeholders: `PROJECT_TYPE, STYLE`
- Prompt:

```text
Recommend typography pairings for [PROJECT_TYPE] with [STYLE] aesthetic.

Provide 5 pairings, each including:
1. Header font (name, style, where to get it)
2. Body font (name, style, where to get it)
3. Accent font if needed
4. Why they work together
5. Optimal sizes and weights
6. Line height and spacing recommendations
7. Use case examples
8. Free alternatives if fonts are paid
```

#### creative-023 - Social Media Visual Strategy
- Placeholders: `BRAND, PLATFORM`
- Prompt:

```text
Develop a visual content strategy for [BRAND] on [PLATFORM].

Define:
1. Visual theme/aesthetic
2. Content pillars (categories of posts)
3. Grid/feed layout strategy
4. Post templates (5 types)
5. Color and filter consistency
6. Typography for graphics
7. Image vs. video mix
8. Stories/ephemeral content style
9. Reusable design elements
10. Tools to use
11. Posting cadence recommendations
```

#### creative-024 - Interactive Experience Design
- Placeholders: `AUDIENCE, PURPOSE`
- Prompt:

```text
Design an interactive experience for [PURPOSE] targeting [AUDIENCE].

Conceptualize:
1. Core interaction mechanic
2. User journey flow
3. Gamification elements
4. Reward/feedback loops
5. Personalization opportunities
6. Social sharing moments
7. Accessibility considerations
8. Technical requirements
9. Success metrics
10. Emotional arc of the experience
```

#### creative-025 - Book Cover Concept
- Placeholders: `BOOK_TITLE, BRIEF_DESCRIPTION, GENRE`
- Prompt:

```text
Create book cover concepts for '[BOOK_TITLE]', a [GENRE] book about [BRIEF_DESCRIPTION].

Provide 3 distinct concepts:
1. Concept description
2. Visual elements
3. Typography treatment
4. Color palette
5. Mood and tone
6. How it stands out in genre
7. Spine and back cover notes
8. eBook thumbnail considerations
```

#### creative-026 - Creative Block Breaker
- Placeholders: `PROJECT`
- Prompt:

```text
I'm experiencing creative block on [PROJECT]. Help me break through:

1. Diagnose the type of block
2. Quick exercises to get unstuck (5)
3. New constraints to try
4. Random inspiration prompts
5. Change of perspective techniques
6. Physical/environment changes to make
7. Questions to ask myself
8. Permission slips (what I'm allowed to do)
9. 15-minute sprint challenge
10. When to walk away vs. push through
```

#### creative-027 - Website Layout Structure
- Placeholders: `WEBSITE_PURPOSE`
- Prompt:

```text
Create a website layout structure for [WEBSITE_PURPOSE].

Define:
1. Page hierarchy and sitemap
2. Homepage sections and order
3. Navigation structure
4. Above-the-fold priorities
5. Content blocks for each page type
6. Call-to-action placement strategy
7. Mobile adaptation notes
8. Footer structure
9. User flow paths
10. Conversion optimization elements
```

#### creative-028 - Dialogue Writing Coach
- Placeholders: `CHARACTERS, SCENE_CONTEXT`
- Prompt:

```text
Help me write better dialogue for [SCENE_CONTEXT] between [CHARACTERS].

Provide:
1. Character voice differentiation tips
2. Subtext and what's NOT said
3. Conflict in conversation
4. Realistic speech patterns
5. Avoiding 'on-the-nose' dialogue
6. Beat/action integration
7. Sample dialogue exchange
8. Common mistakes to avoid
9. How to read dialogue aloud effectively
10. Revision checklist
```

#### creative-029 - Interior Design Direction
- Placeholders: `ROOM/SPACE, STYLE`
- Prompt:

```text
Create an interior design direction for [ROOM/SPACE] with [STYLE] aesthetic.

Include:
1. Overall concept and mood
2. Color scheme
3. Key furniture pieces
4. Lighting approach
5. Textiles and textures
6. Accent decor items
7. Layout suggestions
8. Statement piece recommendation
9. Budget-friendly tips
10. DIY opportunities
11. Shopping recommendations
```

#### creative-030 - Plot Structure Developer
- Placeholders: `STORY_PREMISE, STRUCTURE_TYPE`
- Prompt:

```text
Develop a plot structure for [STORY_PREMISE] using [STRUCTURE_TYPE] (three-act, hero's journey, etc.).

Outline:
1. Hook/opening
2. Inciting incident
3. Key plot points
4. Midpoint shift
5. Rising complications
6. Climax
7. Resolution
8. Subplots to weave in
9. Scene sequence suggestions
10. Pacing recommendations
11. Emotional beats to hit
```

#### creative-031 - Music Mood Direction
- Placeholders: `MOOD, PROJECT`
- Prompt:

```text
Create music direction for [PROJECT] with [MOOD] feeling.

Define:
1. Genre and style
2. Tempo and energy level
3. Instrumentation
4. Reference tracks (5 examples)
5. Key moments needing music
6. Lyrics or instrumental preference
7. Emotional arc
8. Licensing considerations
9. How to find/commission music
10. Sound effects to complement
```

#### creative-032 - Infographic Concept
- Placeholders: `TOPIC/DATA`
- Prompt:

```text
Design an infographic concept to explain [TOPIC/DATA].

Provide:
1. Main message/headline
2. Visual metaphor/concept
3. Information hierarchy
4. Section breakdown
5. Data visualization types to use
6. Icon concepts
7. Color coding strategy
8. Reading flow
9. Size and format
10. Key statistics to highlight
11. Call-to-action
```

#### creative-033 - Animation Concept
- Placeholders: `PURPOSE`
- Prompt:

```text
Create an animation concept for [PURPOSE].

Define:
1. Animation style
2. Duration and pacing
3. Scene-by-scene breakdown
4. Character/element designs
5. Color palette
6. Motion principles to use
7. Transitions between scenes
8. Audio/music sync points
9. Text/typography treatment
10. Deliverable formats needed
```

#### creative-034 - Game Mechanic Designer
- Placeholders: `GAME_TYPE, THEME`
- Prompt:

```text
Design core mechanics for a [GAME_TYPE] game about [THEME].

Develop:
1. Core gameplay loop
2. Player objectives
3. Challenge/difficulty progression
4. Reward systems
5. Player agency/choices
6. Feedback mechanisms
7. Failure states
8. Social/multiplayer elements
9. Unique selling point
10. Reference games for inspiration
```

#### creative-035 - Photo Editing Style
- Placeholders: `PHOTOGRAPHY_TYPE`
- Prompt:

```text
Define a photo editing style for [PHOTOGRAPHY_TYPE] content.

Specify:
1. Overall mood and feel
2. Exposure approach
3. Color grading
4. Contrast and tone curve
5. Saturation and vibrance
6. Highlight/shadow treatment
7. Grain/texture
8. Specific color adjustments
9. Preset settings (Lightroom/similar)
10. Before/after visualization description
```

#### creative-036 - Fashion Lookbook Concept
- Placeholders: `BRAND/COLLECTION`
- Prompt:

```text
Create a lookbook concept for [BRAND/COLLECTION].

Design:
1. Theme and narrative
2. Model casting direction
3. Location/backdrop concepts
4. Styling approach
5. Hair and makeup direction
6. Photography style
7. Layout and format
8. Shot types needed
9. Props and accessories
10. Mood and atmosphere
11. How to tell the collection story
```

#### creative-037 - Metaphor Generator
- Placeholders: `AUDIENCE, CONCEPT`
- Prompt:

```text
Generate creative metaphors and analogies to explain [CONCEPT] to [AUDIENCE].

Provide:
1. 10 different metaphors/analogies
2. Why each works
3. Which audiences each suits
4. Visual representations of each
5. Extended metaphor opportunity
6. Metaphors to avoid
7. How to test if a metaphor lands
8. Top 3 recommendations ranked
```

#### creative-038 - Pitch Deck Design
- Placeholders: `STARTUP/PROJECT`
- Prompt:

```text
Create a pitch deck design framework for [STARTUP/PROJECT].

Structure:
1. Cover slide concept
2. Problem slide visualization
3. Solution presentation
4. Market opportunity graphics
5. Product demo/screenshots
6. Business model visualization
7. Traction/metrics display
8. Team slide layout
9. Ask/use of funds
10. Closing slide
11. Design consistency elements
```

#### creative-039 - Theatrical Set Design
- Placeholders: `PLAY/PRODUCTION`
- Prompt:

```text
Design a theatrical set concept for [PLAY/PRODUCTION].

Visualize:
1. Overall aesthetic approach
2. Main set pieces
3. Scene changes strategy
4. Lighting design direction
5. Color and material palette
6. Symbolic elements
7. Practical requirements
8. Actor movement space
9. Budget considerations
10. Technical requirements
```

#### creative-040 - Icon Set Designer
- Placeholders: `APPLICATION/BRAND`
- Prompt:

```text
Design an icon set for [APPLICATION/BRAND].

Define:
1. Style (line, filled, duotone, etc.)
2. Grid and sizing system
3. Stroke weight
4. Corner radius
5. Color usage
6. Icon list (30 essential icons)
7. Metaphor approach for abstract concepts
8. Consistency rules
9. File format deliverables
10. Usage guidelines
```

#### creative-041 - Creative Constraint Challenge
- Placeholders: `PROJECT_TYPE`
- Prompt:

```text
Create creative constraints for [PROJECT_TYPE] to spark innovation.

Generate:
1. Time constraints (5 variations)
2. Resource constraints (5 variations)
3. Format constraints (5 variations)
4. Audience constraints (5 variations)
5. Style constraints (5 variations)
6. Combination challenges (3 multi-constraint)

Explain how each constraint drives creativity and provide an example outcome.
```

#### creative-042 - Signage and Wayfinding
- Placeholders: `SPACE/VENUE`
- Prompt:

```text
Design a signage and wayfinding system for [SPACE/VENUE].

Develop:
1. Signage hierarchy
2. Typography selection
3. Icon/pictogram style
4. Color coding system
5. Material recommendations
6. Mounting and placement
7. Accessibility compliance
8. Digital signage integration
9. Temporary vs. permanent signage
10. Brand integration
```

#### creative-043 - Newsletter Design Template
- Placeholders: `BRAND/PUBLICATION`
- Prompt:

```text
Create a newsletter design template for [BRAND/PUBLICATION].

Define:
1. Header design
2. Section layouts (3-5 types)
3. Typography hierarchy
4. Color scheme
5. Image treatment
6. CTA button styles
7. Footer structure
8. Mobile optimization
9. Content block modules
10. Personalization opportunities
11. A/B testing elements
```

#### creative-044 - Exhibit Design Concept
- Placeholders: `TOPIC/SUBJECT, VENUE_TYPE`
- Prompt:

```text
Design an exhibit concept for [TOPIC/SUBJECT] at [VENUE_TYPE].

Conceptualize:
1. Visitor journey/narrative
2. Entry experience
3. Interactive elements
4. Visual displays
5. Audio elements
6. Tactile experiences
7. Information hierarchy
8. Space flow
9. Focal points
10. Exit experience
11. Accessibility considerations
```

#### creative-045 - Creative Portfolio Structure
- Placeholders: `CREATIVE_FIELD`
- Prompt:

```text
Structure a creative portfolio for [CREATIVE_FIELD].

Define:
1. Opening/about section
2. Project categorization
3. Case study format
4. What to include for each project
5. Visual presentation
6. Platform/medium
7. Navigation structure
8. Contact/CTA placement
9. What to exclude
10. How to tell your story
11. Portfolio update schedule
```

#### creative-046 - Menu Design Concept
- Placeholders: `RESTAURANT_TYPE`
- Prompt:

```text
Create a menu design concept for [RESTAURANT_TYPE] restaurant.

Develop:
1. Format and size
2. Visual theme
3. Typography choices
4. Color palette
5. Section organization
6. Item descriptions approach
7. Pricing presentation
8. Photography direction
9. Material and finish
10. Brand integration
11. Seasonal update strategy
```

#### creative-047 - Podcast Branding
- Placeholders: `PODCAST_NAME, TOPIC`
- Prompt:

```text
Create branding for [PODCAST_NAME], a podcast about [TOPIC].

Develop:
1. Logo/artwork concept
2. Cover art design direction
3. Color scheme
4. Typography
5. Episode thumbnail template
6. Social media assets
7. Intro/outro music direction
8. Audiogram template
9. Website design direction
10. Merchandise potential
```

#### creative-048 - Data Storytelling
- Placeholders: `DATA_DESCRIPTION`
- Prompt:

```text
Transform this data into a compelling visual story: [DATA_DESCRIPTION]

Create:
1. Narrative arc for the data
2. Key insights to highlight
3. Visualization types for each insight
4. Headline for each section
5. Color coding for meaning
6. Annotations and callouts
7. Comparison frameworks
8. Opening hook
9. Closing takeaway
10. What NOT to show
```

#### creative-049 - Product Naming Workshop
- Placeholders: `PRODUCT_DESCRIPTION`
- Prompt:

```text
Facilitate a product naming session for [PRODUCT_DESCRIPTION].

Generate names using:
1. Portmanteau method (blend words)
2. Foreign language inspiration
3. Mythology/history references
4. Onomatopoeia
5. Acronym creation
6. Abstract sounds
7. Descriptive compounds
8. Evocative words

For final 10 candidates: check domain viability, trademark concerns, global meanings, and memorability.
```

#### creative-050 - Seasonal Campaign Concept
- Placeholders: `BRAND, SEASON/HOLIDAY`
- Prompt:

```text
Create a seasonal marketing campaign for [BRAND] during [SEASON/HOLIDAY].

Develop:
1. Campaign theme and name
2. Visual concept
3. Key messaging
4. Content calendar
5. Channel-specific adaptations
6. User-generated content opportunity
7. Influencer angle
8. Email sequence
9. In-store/digital experience
10. Measurement plan
11. Timeline
```

### 9. Data & Analysis

#### data-001 - Data Interpretation Framework
- Placeholders: `DATA_DESCRIPTION`
- Prompt:

```text
Analyze this data and provide insights:

[DATA_DESCRIPTION]

Provide:
1. Summary of what the data shows
2. Key patterns and trends
3. Notable outliers or anomalies
4. Possible explanations for patterns
5. What questions this data raises
6. Limitations of this data
7. Recommended next analyses
8. Actionable insights for decision-making
```

#### data-002 - Executive Report Generator
- Placeholders: `DATA_CONTEXT, REPORT_TOPIC`
- Prompt:

```text
Create an executive summary report for [REPORT_TOPIC].

Data/Context: [DATA_CONTEXT]

Format the report with:
1. Executive Summary (3-5 key takeaways)
2. Key Metrics Dashboard description
3. Performance vs. Goals
4. Trend Analysis
5. Risk Factors
6. Opportunities Identified
7. Recommended Actions (prioritized)
8. Next Steps and Timeline

Keep it concise - executives should grasp the key points in under 2 minutes.
```

#### data-003 - Survey Analysis Template
- Placeholders: `SURVEY_DATA, SURVEY_TOPIC`
- Prompt:

```text
Analyze survey results for [SURVEY_TOPIC].

Results: [SURVEY_DATA]

Provide:
1. Response rate and sample quality
2. Demographic breakdown
3. Key findings by question/section
4. Quantitative summaries (averages, distributions)
5. Qualitative theme analysis (open-ended responses)
6. Segment comparisons
7. Statistical significance notes
8. Recommendations based on findings
9. Suggested follow-up questions
10. Data visualization recommendations
```

#### data-004 - KPI Dashboard Designer
- Placeholders: `DEPARTMENT/FUNCTION`
- Prompt:

```text
Design a KPI dashboard for [DEPARTMENT/FUNCTION].

Define:
1. Primary KPIs (5-7 most critical)
2. Secondary metrics
3. Leading vs. lagging indicators
4. Benchmark/target for each
5. Data source for each metric
6. Visualization type for each
7. Update frequency
8. Drill-down capabilities
9. Alert thresholds
10. Dashboard layout
11. User-specific views
```

#### data-005 - Trend Identification
- Placeholders: `DATA, DATA_TYPE, TIME_PERIOD`
- Prompt:

```text
Identify and analyze trends in [DATA_TYPE] over [TIME_PERIOD].

Data points: [DATA]

Analyze:
1. Overall trend direction
2. Rate of change
3. Seasonal patterns
4. Cyclical patterns
5. Inflection points
6. Trend drivers (likely causes)
7. Correlation with other factors
8. Forecast projection
9. Confidence level
10. Actions suggested by trend
```

#### data-006 - Competitive Analysis Matrix
- Placeholders: `COMPANY/PRODUCT, COMPETITORS`
- Prompt:

```text
Create a competitive analysis for [COMPANY/PRODUCT] vs [COMPETITORS].

Analyze:
1. Feature comparison matrix
2. Pricing comparison
3. Market positioning map
4. Strengths/weaknesses of each
5. Customer segment focus
6. Marketing approach
7. Technology/innovation comparison
8. Financial health (if available)
9. Competitive advantages
10. Market share estimates
11. Strategic recommendations
```

#### data-007 - Funnel Analysis
- Placeholders: `FUNNEL_DATA, FUNNEL_TYPE`
- Prompt:

```text
Analyze this conversion funnel for [FUNNEL_TYPE]:

[FUNNEL_DATA]

Provide:
1. Conversion rate at each stage
2. Drop-off points and magnitude
3. Comparison to industry benchmarks
4. Segment-specific performance
5. Bottleneck identification
6. Root cause hypotheses
7. A/B test suggestions for each stage
8. Priority improvements (effort vs. impact)
9. Projected impact of improvements
10. Tracking recommendations
```

#### data-008 - Financial Metrics Explainer
- Placeholders: `COMPANY/PROJECT, FINANCIAL_DATA`
- Prompt:

```text
Explain and analyze these financial metrics for [COMPANY/PROJECT]:

[FINANCIAL_DATA]

Provide:
1. What each metric means in plain English
2. Is each metric healthy? (benchmark comparison)
3. How metrics relate to each other
4. Red flags to watch
5. Positive indicators
6. Trend direction for each
7. Industry context
8. Recommendations for improvement
9. Metrics to add to tracking
10. Executive summary
```

#### data-009 - A/B Test Results Analyzer
- Placeholders: `TEST_DESCRIPTION, VARIANT_A_RESULTS, VARIANT_B_RESULTS`
- Prompt:

```text
Analyze these A/B test results:

Test: [TEST_DESCRIPTION]
Variant A: [VARIANT_A_RESULTS]
Variant B: [VARIANT_B_RESULTS]

Provide:
1. Statistical significance calculation
2. Winner declaration (or not)
3. Effect size and confidence interval
4. Segment breakdown
5. Secondary metric impacts
6. Potential biases or issues
7. What we learned
8. Recommended next test
9. Implementation recommendation
10. Lessons for future tests
```

#### data-010 - Customer Segmentation
- Placeholders: `BUSINESS/PRODUCT, DATA_AVAILABLE`
- Prompt:

```text
Create a customer segmentation analysis for [BUSINESS/PRODUCT].

Data available: [DATA_AVAILABLE]

Develop:
1. Segmentation criteria and methodology
2. Segment profiles (4-6 segments)
3. Size and value of each segment
4. Behavioral patterns per segment
5. Needs and pain points per segment
6. Channel preferences
7. Product/service fit
8. Growth potential
9. Targeting recommendations
10. Personalization opportunities
```

#### data-011 - Root Cause Analysis
- Placeholders: `CONTEXT, PROBLEM/ISSUE`
- Prompt:

```text
Perform root cause analysis for [PROBLEM/ISSUE].

Context: [CONTEXT]

Use multiple frameworks:
1. 5 Whys analysis
2. Fishbone diagram categories
3. Pareto analysis (if applicable)
4. Timeline of events
5. Contributing factors
6. Root cause identification
7. Evidence supporting each cause
8. Immediate fixes
9. Long-term solutions
10. Prevention measures
11. Success metrics for solutions
```

#### data-012 - Cohort Analysis
- Placeholders: `COHORT_TYPE, DATA, METRIC`
- Prompt:

```text
Perform cohort analysis for [METRIC] across [COHORT_TYPE] cohorts.

Data: [DATA]

Analyze:
1. Cohort definition and grouping
2. Retention/behavior curves
3. Week-over-week or month-over-month changes
4. Best and worst performing cohorts
5. What differentiates high performers
6. Trend across cohorts over time
7. Seasonality effects
8. LTV implications
9. Recommendations for improving cohorts
10. Future cohort predictions
```

#### data-013 - Data Quality Assessment
- Placeholders: `DATASET_DESCRIPTION`
- Prompt:

```text
Assess data quality for [DATASET_DESCRIPTION].

Evaluate:
1. Completeness (missing values)
2. Accuracy (validation checks)
3. Consistency (format, duplicates)
4. Timeliness (freshness)
5. Validity (within expected ranges)
6. Uniqueness (duplicate records)
7. Data lineage
8. Documentation quality
9. Issues found and severity
10. Remediation recommendations
11. Ongoing quality monitoring plan
```

#### data-014 - Predictive Model Explanation
- Placeholders: `MODEL_DESCRIPTION, MODEL_PURPOSE, PREDICTION`
- Prompt:

```text
Explain this predictive model's outputs for [MODEL_PURPOSE].

Model info: [MODEL_DESCRIPTION]
Prediction: [PREDICTION]

Provide:
1. Plain English explanation of prediction
2. Key factors driving the prediction
3. Confidence level interpretation
4. Feature importance
5. Comparison to baseline
6. Potential biases
7. Edge cases to watch
8. How to use this prediction
9. When to override the model
10. Model limitations
```

#### data-015 - Market Research Summary
- Placeholders: `MARKET/INDUSTRY, RESEARCH_DATA`
- Prompt:

```text
Summarize market research findings for [MARKET/INDUSTRY].

Research data: [RESEARCH_DATA]

Structure:
1. Market size and growth
2. Key players and market share
3. Customer segments
4. Trends shaping the market
5. Opportunities identified
6. Threats and challenges
7. Regulatory landscape
8. Technology developments
9. Entry barriers
10. Strategic recommendations
11. Data gaps to fill
```

#### data-016 - Performance Benchmarking
- Placeholders: `BENCHMARKS, ENTITY, METRICS_DATA`
- Prompt:

```text
Benchmark [ENTITY]'s performance against [BENCHMARKS].

Metrics: [METRICS_DATA]

Analyze:
1. Metrics comparison table
2. Above/below benchmark for each
3. Gap analysis
4. Best practice identification
5. Quick wins (easy improvements)
6. Strategic priorities
7. Resource requirements
8. Timeline to close gaps
9. Risk of not improving
10. Recommended targets
```

#### data-017 - Scenario Analysis
- Placeholders: `CONTEXT, DECISION/SITUATION`
- Prompt:

```text
Conduct scenario analysis for [DECISION/SITUATION].

Context: [CONTEXT]

Develop:
1. Base case scenario
2. Best case scenario
3. Worst case scenario
4. Key variables and assumptions
5. Probability estimates for each
6. Financial/outcome projections
7. Sensitivity analysis
8. Risk mitigation for each scenario
9. Decision recommendation
10. Trigger points to monitor
11. Contingency plans
```

#### data-018 - User Behavior Analysis
- Placeholders: `BEHAVIORAL_DATA, PRODUCT/FEATURE`
- Prompt:

```text
Analyze user behavior for [PRODUCT/FEATURE].

Data: [BEHAVIORAL_DATA]

Examine:
1. Usage patterns and frequency
2. User journey mapping
3. Feature adoption rates
4. Time-on-task analysis
5. Drop-off points
6. Power user behaviors
7. Struggling user patterns
8. Session analysis
9. Device/platform differences
10. Recommendations for UX improvement
11. Metrics to track going forward
```

#### data-019 - Cost-Benefit Analysis
- Placeholders: `PROJECT/INITIATIVE, PROJECT_DETAILS`
- Prompt:

```text
Perform cost-benefit analysis for [PROJECT/INITIATIVE].

Details: [PROJECT_DETAILS]

Analyze:
1. All costs (initial, ongoing, hidden)
2. All benefits (quantifiable, intangible)
3. Timeline of costs and benefits
4. NPV calculation
5. ROI projection
6. Payback period
7. Risk-adjusted returns
8. Sensitivity analysis
9. Opportunity costs
10. Recommendation (proceed/don't/modify)
11. Key assumptions and uncertainties
```

#### data-020 - Churn Analysis
- Placeholders: `BUSINESS/PRODUCT, CHURN_DATA`
- Prompt:

```text
Analyze customer churn for [BUSINESS/PRODUCT].

Data: [CHURN_DATA]

Investigate:
1. Overall churn rate and trend
2. Churn by segment
3. Time-to-churn analysis
4. Churn predictors
5. Customer health indicators
6. Pre-churn behavior patterns
7. Reasons for churn (if known)
8. Churn cost calculation
9. At-risk customer identification
10. Intervention strategies
11. Retention program recommendations
```

#### data-021 - Pricing Analysis
- Placeholders: `PRICING_CONTEXT, PRODUCT/SERVICE`
- Prompt:

```text
Analyze pricing strategy for [PRODUCT/SERVICE].

Context: [PRICING_CONTEXT]

Evaluate:
1. Current pricing structure
2. Competitor pricing comparison
3. Price elasticity estimate
4. Value-based pricing analysis
5. Customer willingness to pay
6. Margin analysis
7. Pricing by segment opportunity
8. Bundle/unbundle options
9. Recommended pricing changes
10. Implementation approach
11. Expected revenue impact
```

#### data-022 - Capacity Planning
- Placeholders: `CURRENT_DATA, DEMAND_PROJECTION, RESOURCE/SYSTEM`
- Prompt:

```text
Create capacity analysis for [RESOURCE/SYSTEM].

Current data: [CURRENT_DATA]
Projected demand: [DEMAND_PROJECTION]

Analyze:
1. Current capacity utilization
2. Peak vs. average usage
3. Growth trajectory
4. When capacity will be exceeded
5. Bottleneck identification
6. Scaling options
7. Cost of each option
8. Lead time requirements
9. Recommendation and timeline
10. Monitoring and triggers
11. Buffer requirements
```

#### data-023 - Attribution Analysis
- Placeholders: `CONVERSION_DATA, MARKETING/SALES`
- Prompt:

```text
Perform attribution analysis for [MARKETING/SALES] efforts.

Data: [CONVERSION_DATA]

Analyze:
1. First-touch attribution
2. Last-touch attribution
3. Linear attribution
4. Time-decay attribution
5. Model comparison
6. Channel performance
7. Cross-channel journeys
8. Recommended attribution model
9. Budget reallocation suggestions
10. Data gaps affecting analysis
11. Next steps for better attribution
```

#### data-024 - Anomaly Detection Report
- Placeholders: `ANOMALY_DESCRIPTION, DATA_TYPE`
- Prompt:

```text
Investigate anomalies in [DATA_TYPE].

Anomaly detected: [ANOMALY_DESCRIPTION]

Investigate:
1. Anomaly characterization
2. When it started
3. Magnitude and scope
4. Affected segments/areas
5. Potential causes (ranked)
6. Rule out false positive
7. Impact assessment
8. Immediate actions needed
9. Investigation steps
10. Monitoring enhancement
11. Documentation for future reference
```

#### data-025 - LTV Analysis
- Placeholders: `BUSINESS, CUSTOMER_DATA`
- Prompt:

```text
Calculate and analyze Customer Lifetime Value for [BUSINESS].

Data: [CUSTOMER_DATA]

Provide:
1. LTV calculation methodology
2. Average LTV
3. LTV by segment
4. LTV:CAC ratio
5. LTV trend over time
6. Factors driving LTV
7. High-LTV customer profile
8. LTV prediction model inputs
9. Strategies to increase LTV
10. LTV-based prioritization
11. Limitations of analysis
```

#### data-026 - Inventory Analysis
- Placeholders: `BUSINESS/CATEGORY, INVENTORY_DATA`
- Prompt:

```text
Analyze inventory performance for [BUSINESS/CATEGORY].

Data: [INVENTORY_DATA]

Evaluate:
1. Inventory turnover rate
2. Days of inventory
3. Stock-out frequency
4. Overstock analysis
5. ABC categorization
6. Seasonal patterns
7. Slow-moving inventory
8. Reorder point analysis
9. Working capital implications
10. Optimization recommendations
11. Forecasting improvements needed
```

#### data-027 - Social Media Analytics
- Placeholders: `BRAND/ACCOUNT, SOCIAL_DATA`
- Prompt:

```text
Analyze social media performance for [BRAND/ACCOUNT].

Data: [SOCIAL_DATA]

Review:
1. Follower growth trend
2. Engagement rate by platform
3. Top performing content
4. Worst performing content
5. Best posting times
6. Audience demographics
7. Sentiment analysis
8. Competitor comparison
9. Share of voice
10. ROI of social efforts
11. Recommendations for improvement
```

#### data-028 - Website Analytics Review
- Placeholders: `ANALYTICS_DATA, TIME_PERIOD, WEBSITE`
- Prompt:

```text
Review website analytics for [WEBSITE].

Data period: [TIME_PERIOD]
Data: [ANALYTICS_DATA]

Analyze:
1. Traffic overview and trends
2. Source/medium breakdown
3. Top pages performance
4. User flow analysis
5. Bounce rate by page type
6. Conversion analysis
7. Mobile vs. desktop
8. Site speed impact
9. SEO performance
10. Quick wins identified
11. Strategic recommendations
```

#### data-029 - Regression Analysis Interpretation
- Placeholders: `ANALYSIS_PURPOSE, REGRESSION_OUTPUT`
- Prompt:

```text
Interpret this regression analysis for [ANALYSIS_PURPOSE].

Results: [REGRESSION_OUTPUT]

Explain:
1. What the model is predicting
2. Coefficient interpretations
3. Statistical significance
4. R-squared meaning
5. Key predictors
6. Practical significance
7. Assumptions and violations
8. Prediction examples
9. Limitations
10. Business implications
11. Next steps for model improvement
```

#### data-030 - NPS Analysis
- Placeholders: `COMPANY/PRODUCT, NPS_DATA`
- Prompt:

```text
Analyze Net Promoter Score data for [COMPANY/PRODUCT].

Data: [NPS_DATA]

Provide:
1. Overall NPS and trend
2. Promoter/Passive/Detractor breakdown
3. NPS by segment
4. Drivers of promoter scores
5. Drivers of detractor scores
6. Verbatim analysis themes
7. Benchmark comparison
8. Correlation with other metrics
9. Action plan for improvement
10. Priority focus areas
11. Follow-up program design
```

#### data-031 - Supply Chain Analysis
- Placeholders: `COMPANY/PRODUCT, SUPPLY_CHAIN_DATA`
- Prompt:

```text
Analyze supply chain performance for [COMPANY/PRODUCT].

Data: [SUPPLY_CHAIN_DATA]

Evaluate:
1. Lead time analysis
2. Supplier performance
3. On-time delivery rate
4. Cost breakdown
5. Quality metrics
6. Risk assessment
7. Bottleneck identification
8. Demand-supply alignment
9. Optimization opportunities
10. Technology improvements
11. Resilience recommendations
```

#### data-032 - Employee Survey Analysis
- Placeholders: `COMPANY/DEPARTMENT, SURVEY_RESULTS`
- Prompt:

```text
Analyze employee survey results for [COMPANY/DEPARTMENT].

Data: [SURVEY_RESULTS]

Examine:
1. Overall engagement score
2. Category breakdowns
3. Demographic differences
4. Trend vs. previous surveys
5. Benchmark comparison
6. Strength areas
7. Improvement areas
8. Verbatim theme analysis
9. Priority actions
10. Communication plan
11. Follow-up survey design
```

#### data-033 - Geographic Analysis
- Placeholders: `BUSINESS_METRIC, GEOGRAPHIC_DATA`
- Prompt:

```text
Perform geographic analysis for [BUSINESS_METRIC].

Data: [GEOGRAPHIC_DATA]

Analyze:
1. Performance by region
2. Hot spots and cold spots
3. Market penetration by area
4. Demographic correlations
5. Competitive density
6. Growth opportunities
7. Underperforming markets
8. Expansion recommendations
9. Resource allocation
10. Localization needs
11. Territory optimization
```

#### data-034 - Feature Adoption Analysis
- Placeholders: `ADOPTION_DATA, FEATURE_NAME, PRODUCT`
- Prompt:

```text
Analyze feature adoption for [PRODUCT].

Feature: [FEATURE_NAME]
Data: [ADOPTION_DATA]

Investigate:
1. Adoption rate over time
2. User segments adopting
3. Time to first use
4. Frequency of use
5. Stickiness metrics
6. Feature correlation with retention
7. Non-adopter analysis
8. Barrier identification
9. In-app messaging effectiveness
10. Improvement recommendations
11. Success metrics
```

#### data-035 - Revenue Analytics
- Placeholders: `BUSINESS, PERIOD, REVENUE_DATA`
- Prompt:

```text
Create revenue analysis for [BUSINESS].

Data: [REVENUE_DATA]
Time period: [PERIOD]

Analyze:
1. Total revenue and growth
2. Revenue by product/service
3. Revenue by customer segment
4. Revenue by channel
5. Recurring vs. one-time
6. Average deal size
7. Revenue concentration risk
8. Seasonality patterns
9. Pipeline and forecast
10. Revenue optimization opportunities
11. Key metrics to track
```

#### data-036 - Experiment Design
- Placeholders: `CONTEXT, HYPOTHESIS`
- Prompt:

```text
Design an experiment to test [HYPOTHESIS].

Context: [CONTEXT]

Define:
1. Clear hypothesis statement
2. Test and control groups
3. Sample size calculation
4. Randomization approach
5. Primary and secondary metrics
6. Test duration
7. Success criteria
8. Risk mitigation
9. Data collection plan
10. Analysis plan
11. Roll-out decision framework
```

#### data-037 - Dashboard Storytelling
- Placeholders: `AUDIENCE, METRICS`
- Prompt:

```text
Transform this dashboard data into a narrative for [AUDIENCE]:

Dashboard metrics: [METRICS]

Create:
1. Opening headline/summary
2. The story arc
3. Key insight #1 with context
4. Key insight #2 with context
5. Key insight #3 with context
6. What to watch going forward
7. Action recommendations
8. Questions this raises
9. Data visualization suggestions
10. Executive summary version
```

#### data-038 - Correlation Investigation
- Placeholders: `DATA, VARIABLE_A, VARIABLE_B`
- Prompt:

```text
Investigate the correlation between [VARIABLE_A] and [VARIABLE_B].

Data: [DATA]

Analyze:
1. Correlation coefficient
2. Scatter plot description
3. Strength of relationship
4. Direction of relationship
5. Correlation vs. causation
6. Potential confounding variables
7. Subset analysis
8. Time-lagged relationships
9. Practical implications
10. Further investigation needed
11. Recommendations
```

#### data-039 - Operations Metrics Review
- Placeholders: `OPERATION/TEAM, OPERATIONS_DATA`
- Prompt:

```text
Review operational metrics for [OPERATION/TEAM].

Metrics: [OPERATIONS_DATA]

Assess:
1. Throughput and efficiency
2. Quality metrics
3. Cycle time analysis
4. Capacity utilization
5. Error/rework rates
6. SLA performance
7. Trend analysis
8. Benchmark comparison
9. Bottleneck identification
10. Improvement opportunities
11. Resource optimization
```

#### data-040 - Forecast Accuracy Assessment
- Placeholders: `ACTUAL_DATA, FORECAST_DATA, FORECAST_TYPE`
- Prompt:

```text
Assess forecast accuracy for [FORECAST_TYPE].

Forecasted: [FORECAST_DATA]
Actual: [ACTUAL_DATA]

Evaluate:
1. Overall accuracy metrics (MAPE, bias, etc.)
2. Over/under prediction tendency
3. Accuracy by segment
4. Accuracy over time
5. Outlier analysis
6. Root cause of errors
7. Forecast process review
8. Model improvement suggestions
9. Data input improvements
10. Process improvements
11. New accuracy targets
```

#### data-041 - Risk Assessment Matrix
- Placeholders: `CONTEXT, PROJECT/INITIATIVE`
- Prompt:

```text
Create a risk assessment for [PROJECT/INITIATIVE].

Context: [CONTEXT]

Develop:
1. Risk identification (10+ risks)
2. Probability rating for each
3. Impact rating for each
4. Risk priority score
5. Risk categories
6. Mitigation strategies
7. Contingency plans
8. Risk owners
9. Monitoring approach
10. Risk register template
11. Escalation triggers
```

#### data-042 - Customer Journey Analytics
- Placeholders: `BUSINESS/PRODUCT, JOURNEY_DATA`
- Prompt:

```text
Analyze customer journey for [BUSINESS/PRODUCT].

Data: [JOURNEY_DATA]

Map and analyze:
1. Key touchpoints
2. Conversion at each stage
3. Time between stages
4. Drop-off points
5. Multi-channel behavior
6. Pain points identified
7. Moments of delight
8. Segment variations
9. Journey optimization opportunities
10. Measurement improvements
11. Priority actions
```

#### data-043 - Variance Analysis
- Placeholders: `COMPARISON, METRIC/BUDGET, VARIANCE_DATA`
- Prompt:

```text
Perform variance analysis for [METRIC/BUDGET] vs. [COMPARISON].

Data: [VARIANCE_DATA]

Analyze:
1. Total variance calculation
2. Favorable vs. unfavorable
3. Variance breakdown by component
4. Root causes
5. Controllable vs. uncontrollable
6. Trend of variances
7. Impact significance
8. Corrective actions
9. Forecast adjustment needed
10. Process improvements
11. Reporting recommendations
```

#### data-044 - Cluster Analysis Interpretation
- Placeholders: `ANALYSIS_PURPOSE, CLUSTER_DATA`
- Prompt:

```text
Interpret cluster analysis results for [ANALYSIS_PURPOSE].

Results: [CLUSTER_DATA]

Explain:
1. Number of clusters and why
2. Profile of each cluster
3. Size of each cluster
4. Key differentiating factors
5. Cluster naming suggestions
6. Actionable insights per cluster
7. Strategy recommendations
8. Targeting approaches
9. Validation methods
10. Limitations
11. Next steps
```

#### data-045 - Data Request Specification
- Placeholders: `ANALYSIS_NEED, PURPOSE`
- Prompt:

```text
Create a data request specification for [ANALYSIS_NEED].

Purpose: [PURPOSE]

Specify:
1. Business questions to answer
2. Data fields required
3. Granularity needed
4. Time period
5. Filters and segments
6. Data source(s)
7. Delivery format
8. Refresh frequency
9. Access requirements
10. Quality expectations
11. Timeline and priority
```

### 10. Communication & HR

#### comm-001 - Professional Email Writer
- Placeholders: `CONTEXT, EMAIL_PURPOSE, FORMAL/FRIENDLY/URGENT, RECIPIENT_TYPE`
- Prompt:

```text
Write a professional email for [EMAIL_PURPOSE].

Context: [CONTEXT]
Tone: [FORMAL/FRIENDLY/URGENT]
Recipient: [RECIPIENT_TYPE]

Provide:
1. Subject line options (3)
2. Email body
3. Appropriate greeting
4. Clear call-to-action
5. Professional sign-off
6. Follow-up timing suggestion
```

#### comm-002 - Meeting Agenda Creator
- Placeholders: `DURATION, MEETING_TYPE, OBJECTIVE, PARTICIPANTS`
- Prompt:

```text
Create a meeting agenda for [MEETING_TYPE].

Participants: [PARTICIPANTS]
Duration: [DURATION]
Objective: [OBJECTIVE]

Provide:
1. Meeting title
2. Pre-meeting preparation requirements
3. Detailed agenda with time allocations
4. Discussion questions for each topic
5. Decision points needed
6. Action item template
7. Follow-up process
```

#### comm-003 - Performance Review Template
- Placeholders: `ACCOMPLISHMENTS, AREAS, EMPLOYEE_ROLE, PERIOD`
- Prompt:

```text
Create a performance review for [EMPLOYEE_ROLE].

Review period: [PERIOD]
Key accomplishments: [ACCOMPLISHMENTS]
Areas for improvement: [AREAS]

Structure:
1. Summary of performance
2. Strengths demonstrated
3. Areas for development
4. Specific examples for each point
5. Goals for next period
6. Development plan
7. Compensation discussion framework
8. Employee self-reflection questions
```

#### comm-004 - Interview Question Generator
- Placeholders: `LEVEL, POSITION, SKILLS`
- Prompt:

```text
Generate interview questions for [POSITION].

Level: [LEVEL]
Key skills needed: [SKILLS]

Provide:
1. Ice-breaker questions (3)
2. Experience/background questions (5)
3. Technical/skill questions (5)
4. Behavioral questions with STAR prompts (5)
5. Culture fit questions (3)
6. Red flag indicators to watch for
7. Questions for candidate to ask
8. Scoring rubric
```

#### comm-005 - Feedback Delivery Framework
- Placeholders: `CONTEXT, PERSON/RELATIONSHIP, SITUATION`
- Prompt:

```text
Help me deliver feedback about [SITUATION].

Recipient: [PERSON/RELATIONSHIP]
Context: [CONTEXT]

Provide:
1. Opening that creates safety
2. Specific behavior to address
3. Impact of the behavior
4. What you'd like to see instead
5. Collaborative discussion prompts
6. How to handle pushback
7. Commitment and follow-up
8. Practice script
```

#### comm-006 - Slack/Teams Message Optimizer
- Placeholders: `CONTEXT, MESSAGE, PLATFORM`
- Prompt:

```text
Improve this workplace message for [PLATFORM]:

Original: [MESSAGE]
Context: [CONTEXT]

Optimize for:
1. Clarity and conciseness
2. Appropriate tone
3. Actionable next steps
4. Proper formatting for the platform
5. Emoji/reaction appropriateness
6. Threading recommendations
7. Alternative versions for different audiences
```

#### comm-007 - Job Description Writer
- Placeholders: `COMPANY_DESCRIPTION, LEVEL, POSITION, RESPONSIBILITIES`
- Prompt:

```text
Write a job description for [POSITION].

Company: [COMPANY_DESCRIPTION]
Level: [LEVEL]
Key responsibilities: [RESPONSIBILITIES]

Include:
1. Compelling opening hook
2. About the company
3. Role overview
4. Key responsibilities (8-10)
5. Required qualifications
6. Preferred qualifications
7. Benefits and perks
8. Inclusive language check
9. Call-to-action
10. SEO-optimized title
```

#### comm-008 - Difficult Message Drafting
- Placeholders: `AUDIENCE, DIFFICULT_TOPIC, KEY_MESSAGE`
- Prompt:

```text
Help me draft a message about [DIFFICULT_TOPIC].

Audience: [AUDIENCE]
Key message: [KEY_MESSAGE]

Provide:
1. Empathetic opening
2. Clear statement of facts
3. Rationale/explanation
4. Impact acknowledgment
5. What happens next
6. Resources/support available
7. Q&A preparation
8. Multiple delivery format versions (written, verbal)
```

#### comm-009 - One-on-One Meeting Guide
- Placeholders: `CHALLENGES, FREQUENCY, RELATIONSHIP_TYPE`
- Prompt:

```text
Create a one-on-one meeting framework for [RELATIONSHIP_TYPE].

Frequency: [FREQUENCY]
Current challenges: [CHALLENGES]

Provide:
1. Check-in questions
2. Progress review questions
3. Obstacle discussion prompts
4. Development conversation starters
5. Feedback exchange format
6. Career growth discussion
7. Action item tracking
8. Meeting cadence and structure
9. When to escalate concerns
```

#### comm-010 - Team Announcement Writer
- Placeholders: `ANNOUNCEMENT_TOPIC, TEAM/DEPARTMENT, TONE`
- Prompt:

```text
Write a team announcement about [ANNOUNCEMENT_TOPIC].

Audience: [TEAM/DEPARTMENT]
Tone: [TONE]

Include:
1. Attention-grabbing subject/headline
2. Key message upfront
3. Context and background
4. What this means for the team
5. Timeline and next steps
6. Who to contact with questions
7. FAQ section
8. Version for different channels
```

#### comm-011 - Onboarding Plan Creator
- Placeholders: `NEW_HIRE_ROLE, START_DATE, TEAM`
- Prompt:

```text
Create an onboarding plan for [NEW_HIRE_ROLE].

Team: [TEAM]
Start date: [START_DATE]

Develop:
1. Pre-start preparation
2. Day 1 schedule
3. Week 1 milestones
4. 30-day goals
5. 60-day goals
6. 90-day goals
7. Key people to meet
8. Training resources
9. Check-in schedule
10. Success metrics
11. Buddy/mentor assignment
```

#### comm-012 - Conflict Resolution Script
- Placeholders: `CONFLICT_TOPIC, CONTEXT, PARTIES`
- Prompt:

```text
Help me resolve a conflict between [PARTIES] regarding [CONFLICT_TOPIC].

Context: [CONTEXT]

Provide:
1. Pre-conversation preparation
2. Opening that establishes neutrality
3. Questions to understand each side
4. Identifying common ground
5. Brainstorming solutions together
6. Agreement documentation
7. Follow-up plan
8. Escalation path if needed
```

#### comm-013 - Reference Letter Writer
- Placeholders: `DURATION, PERSON_NAME, POSITION/PURPOSE, RELATIONSHIP, STRENGTHS`
- Prompt:

```text
Write a reference letter for [PERSON_NAME] applying for [POSITION/PURPOSE].

Relationship: [RELATIONSHIP]
Time known: [DURATION]
Key strengths: [STRENGTHS]

Include:
1. Strong opening endorsement
2. Context of relationship
3. Specific examples of excellence (3-4)
4. Character and work style
5. Growth demonstrated
6. Comparison to peers
7. Confident closing
8. Contact information offer
```

#### comm-014 - Presentation Script Developer
- Placeholders: `AUDIENCE, DURATION, OBJECTIVE, PRESENTATION_TOPIC`
- Prompt:

```text
Develop a presentation script for [PRESENTATION_TOPIC].

Audience: [AUDIENCE]
Duration: [DURATION]
Objective: [OBJECTIVE]

Create:
1. Hook/opening (first 30 seconds)
2. Agenda overview
3. Main points with transitions
4. Stories/examples to include
5. Audience engagement moments
6. Handling Q&A
7. Strong closing and call-to-action
8. Speaker notes
9. Backup points if running long/short
```

#### comm-015 - Policy Documentation
- Placeholders: `ORGANIZATION_TYPE, POLICY_TOPIC, SCOPE`
- Prompt:

```text
Write a policy document for [POLICY_TOPIC].

Organization: [ORGANIZATION_TYPE]
Scope: [SCOPE]

Include:
1. Policy statement
2. Purpose and scope
3. Definitions
4. Roles and responsibilities
5. Procedures
6. Compliance requirements
7. Exceptions process
8. Related policies
9. Review cycle
10. Approval and effective date
11. FAQ for common questions
```

#### comm-016 - Resignation Letter Helper
- Placeholders: `NOTICE, POSITION, REASON, RELATIONSHIP`
- Prompt:

```text
Help me write a resignation letter.

Current position: [POSITION]
Reason (optional): [REASON]
Notice period: [NOTICE]
Relationship with manager: [RELATIONSHIP]

Provide:
1. Professional resignation letter
2. How to handle exit interview
3. Transition plan outline
4. Knowledge transfer checklist
5. Relationship maintenance tips
6. LinkedIn recommendation request
7. What NOT to say
8. Timeline of notifications
```

#### comm-017 - Team Building Activity Designer
- Placeholders: `BUDGET, IN_PERSON/REMOTE/HYBRID, OBJECTIVE, TEAM_SIZE, TIME`
- Prompt:

```text
Design team building activities for [TEAM_SIZE] people.

Context: [IN_PERSON/REMOTE/HYBRID]
Objective: [OBJECTIVE]
Time available: [TIME]
Budget: [BUDGET]

Provide:
1. Activity options (5+)
2. Detailed instructions for top 3
3. Materials needed
4. How it supports the objective
5. Debrief questions
6. Accessibility considerations
7. Backup plans
8. Success metrics
```

#### comm-018 - Salary Negotiation Script
- Placeholders: `LEVERAGE, ROLE, SALARY, TARGET`
- Prompt:

```text
Prepare me for salary negotiation.

Current/offered salary: [SALARY]
Target salary: [TARGET]
Role: [ROLE]
Leverage points: [LEVERAGE]

Provide:
1. Research framework
2. Opening statement
3. Justification talking points
4. Counter-offer responses
5. Non-salary negotiables
6. How to handle 'no'
7. When to walk away
8. Practice scenarios
9. Follow-up email templates
```

#### comm-019 - Remote Team Communication
- Placeholders: `SIZE, TEAM_TYPE, TIMEZONES, TOOLS`
- Prompt:

```text
Create a remote team communication guide for [TEAM_TYPE].

Team size: [SIZE]
Time zones: [TIMEZONES]
Tools used: [TOOLS]

Define:
1. Communication norms
2. Response time expectations
3. Meeting guidelines
4. Async vs. sync decisions
5. Documentation standards
6. Overlap hours and usage
7. Video on/off norms
8. Status indicators
9. Escalation paths
10. Team rituals
11. Inclusion practices
```

#### comm-020 - Recognition Message Writer
- Placeholders: `ACCOMPLISHMENT, CONTEXT, PERSON/TEAM`
- Prompt:

```text
Write a recognition message for [PERSON/TEAM].

Accomplishment: [ACCOMPLISHMENT]
Context: [CONTEXT]
Channel: [CHANNEL - email/slack/public/private]

Provide:
1. Opening that grabs attention
2. Specific behaviors/actions to recognize
3. Impact of their work
4. Company values alignment
5. Personal touch
6. Closing that motivates
7. Versions for different audiences
8. Award/reward suggestions if applicable
```

#### comm-021 - Rejection Letter Template
- Placeholders: `REASON, RECIPIENT, REJECTION_TYPE, RELATIONSHIP_IMPORTANCE`
- Prompt:

```text
Write a rejection letter for [REJECTION_TYPE].

Recipient: [RECIPIENT]
Reason: [REASON]
Relationship to maintain: [RELATIONSHIP_IMPORTANCE]

Provide:
1. Respectful opening
2. Clear but kind decision statement
3. Brief reasoning (without over-explaining)
4. Positive elements to acknowledge
5. Future possibility (if appropriate)
6. Closing that maintains dignity
7. Timing recommendations
8. Alternative versions by channel
```

#### comm-022 - Project Update Email
- Placeholders: `PROJECT, STAKEHOLDERS, STATUS, UPDATES`
- Prompt:

```text
Write a project status update for [PROJECT].

Audience: [STAKEHOLDERS]
Current status: [STATUS]
Key updates: [UPDATES]

Structure:
1. TL;DR summary
2. Progress since last update
3. Key milestones hit
4. Current blockers/risks
5. Upcoming milestones
6. Help needed
7. Metrics dashboard
8. Next update timing
```

#### comm-023 - Apology Letter Professional
- Placeholders: `OUTCOME, RECIPIENT, ROLE, SITUATION`
- Prompt:

```text
Help me write a professional apology for [SITUATION].

Recipient: [RECIPIENT]
My role in situation: [ROLE]
Desired outcome: [OUTCOME]

Provide:
1. Sincere acknowledgment
2. Taking responsibility (without excuses)
3. Understanding their perspective
4. What I'll do differently
5. Making it right
6. Request to move forward
7. Appropriate tone calibration
8. Follow-up actions
```

#### comm-024 - Meeting Minutes Template
- Placeholders: `ATTENDEES, DETAILS, DISCUSSIONS, MEETING_TYPE`
- Prompt:

```text
Create meeting minutes for [MEETING_TYPE].

Meeting details: [DETAILS]
Attendees: [ATTENDEES]
Key discussions: [DISCUSSIONS]

Format:
1. Meeting header (date, time, attendees)
2. Agenda items covered
3. Discussion summaries
4. Decisions made
5. Action items with owners and deadlines
6. Open items/parking lot
7. Next meeting details
8. Distribution list
```

#### comm-025 - Career Development Plan
- Placeholders: `CURRENT_ROLE, SKILLS, TARGET_ROLE, TIMEFRAME`
- Prompt:

```text
Create a career development plan for [CURRENT_ROLE] aspiring to [TARGET_ROLE].

Timeframe: [TIMEFRAME]
Current skills: [SKILLS]

Develop:
1. Skills gap analysis
2. Short-term goals (6 months)
3. Medium-term goals (1-2 years)
4. Long-term goals (3-5 years)
5. Learning resources
6. Experiences to seek
7. Mentorship needs
8. Networking strategy
9. Milestone checkpoints
10. Success metrics
11. Manager discussion guide
```

#### comm-026 - Termination Script
- Placeholders: `CIRCUMSTANCES, REASON, ROLE`
- Prompt:

```text
Prepare a termination conversation script.

Role: [ROLE]
Reason: [REASON]
Circumstances: [CIRCUMSTANCES]

Provide:
1. Pre-meeting preparation
2. Who should be present
3. Opening statement
4. Delivering the message
5. Handling reactions
6. Logistics to cover
7. What NOT to say
8. Transition information
9. Documentation requirements
10. Team communication after
11. Legal considerations reminder
```

#### comm-027 - Delegation Communication
- Placeholders: `DEADLINE, LEVEL, PERSON, TASK/PROJECT`
- Prompt:

```text
Help me delegate [TASK/PROJECT] effectively.

Delegate to: [PERSON]
Their level: [LEVEL]
Deadline: [DEADLINE]

Provide:
1. Task overview
2. Why I'm choosing them
3. Clear expectations
4. Authority level granted
5. Resources available
6. Check-in schedule
7. Definition of done
8. How to handle questions
9. What success looks like
10. Handoff meeting agenda
```

#### comm-028 - Change Communication Plan
- Placeholders: `CHANGE, GROUPS, TIMELINE`
- Prompt:

```text
Create a change communication plan for [CHANGE].

Impacted groups: [GROUPS]
Timeline: [TIMELINE]

Develop:
1. Key messages by audience
2. Communication timeline
3. Channels to use
4. Spokesperson assignments
5. FAQ document
6. Objection handling
7. Feedback mechanism
8. Success indicators
9. Escalation path
10. Follow-up communications
```

#### comm-029 - Networking Message Template
- Placeholders: `CONNECTION_TYPE, CONTEXT, PLATFORM, PURPOSE`
- Prompt:

```text
Write networking messages for [PURPOSE].

Context: [CONTEXT]
Connection type: [CONNECTION_TYPE]
Platform: [PLATFORM]

Provide:
1. Initial outreach message
2. Follow-up if no response
3. Thank you after meeting
4. Staying in touch template
5. Asking for introduction
6. Offering value message
7. Reconnecting after time
8. LinkedIn-specific versions
```

#### comm-030 - Meeting Facilitation Guide
- Placeholders: `CHALLENGES, MEETING_TYPE, OUTCOME, PARTICIPANTS`
- Prompt:

```text
Create a facilitation guide for [MEETING_TYPE].

Participants: [PARTICIPANTS]
Challenges expected: [CHALLENGES]
Outcome needed: [OUTCOME]

Include:
1. Pre-meeting setup
2. Opening and ground rules
3. Facilitation techniques
4. Keeping discussion on track
5. Encouraging participation
6. Managing dominant voices
7. Handling conflict
8. Decision-making process
9. Closing and action items
10. Post-meeting follow-through
```

#### comm-031 - Employee Survey Design
- Placeholders: `AUDIENCE, PURPOSE, SURVEY_TOPIC`
- Prompt:

```text
Design an employee survey about [SURVEY_TOPIC].

Purpose: [PURPOSE]
Audience: [AUDIENCE]

Create:
1. Survey objectives
2. Question types mix
3. 15-20 well-crafted questions
4. Rating scale design
5. Open-ended questions
6. Demographic questions
7. Survey introduction
8. Anonymity statement
9. Estimated completion time
10. Analysis plan
11. Action planning framework
```

#### comm-032 - Promotion Request Builder
- Placeholders: `ACCOMPLISHMENTS, CURRENT_ROLE, TARGET_ROLE, TIME`
- Prompt:

```text
Help me build a case for promotion from [CURRENT_ROLE] to [TARGET_ROLE].

Time in role: [TIME]
Key accomplishments: [ACCOMPLISHMENTS]

Provide:
1. Self-assessment framework
2. Evidence collection guide
3. Metrics to highlight
4. Skills demonstration
5. 'Promotion document' structure
6. Meeting request approach
7. Presentation of case
8. Handling objections
9. Timeline discussion
10. Alternative outcomes to propose
11. Follow-up strategy
```

#### comm-033 - 360 Review Questions
- Placeholders: `FOCUS_AREAS, PEER/MANAGER/REPORT, ROLE_TYPE`
- Prompt:

```text
Create 360-degree feedback questions for [ROLE_TYPE].

Focus areas: [FOCUS_AREAS]
Relationships: [PEER/MANAGER/REPORT]

Provide:
1. Leadership/management questions
2. Communication questions
3. Collaboration questions
4. Technical competency questions
5. Strategic thinking questions
6. Rating scale questions
7. Open-ended questions
8. Relationship-specific versions
9. How to interpret results
10. Action planning template
```

#### comm-034 - Town Hall Script
- Placeholders: `COMPANY/DEPARTMENT, DURATION, MESSAGES, TOPIC`
- Prompt:

```text
Write a town hall presentation script for [TOPIC].

Audience: [COMPANY/DEPARTMENT]
Duration: [DURATION]
Key messages: [MESSAGES]

Include:
1. Opening hook
2. Company update structure
3. Wins to celebrate
4. Challenges to address
5. Strategy/vision section
6. Q&A facilitation guide
7. Closing inspiration
8. Visual/slide recommendations
9. Pre-town hall communication
10. Post-town hall summary
```

#### comm-035 - Mentorship Program Design
- Placeholders: `GOALS, ORGANIZATION, PARTICIPANTS`
- Prompt:

```text
Design a mentorship program for [ORGANIZATION].

Program goals: [GOALS]
Participant type: [PARTICIPANTS]

Create:
1. Program structure
2. Matching criteria
3. Mentor responsibilities
4. Mentee responsibilities
5. Meeting guidelines
6. Conversation starters
7. Progress tracking
8. Program timeline
9. Success metrics
10. Training for mentors
11. Program launch communication
```

#### comm-036 - Cross-Team Collaboration
- Placeholders: `CHALLENGES, GOAL, TEAM_A, TEAM_B`
- Prompt:

```text
Create a collaboration framework between [TEAM_A] and [TEAM_B].

Collaboration goal: [GOAL]
Current challenges: [CHALLENGES]

Develop:
1. Shared objectives definition
2. Roles and responsibilities
3. Communication cadence
4. Decision-making process
5. Conflict resolution protocol
6. Shared tools and spaces
7. Success metrics
8. Kickoff meeting agenda
9. Stakeholder alignment
10. Continuous improvement process
```

#### comm-037 - Upward Feedback Script
- Placeholders: `CONTEXT, DESIRED_OUTCOME, RELATIONSHIP_QUALITY, TOPIC`
- Prompt:

```text
Help me give upward feedback to my manager about [TOPIC].

Context: [CONTEXT]
Relationship: [RELATIONSHIP_QUALITY]
Goal: [DESIRED_OUTCOME]

Provide:
1. How to request the conversation
2. Setting the right tone
3. Framing the feedback positively
4. Specific examples to use
5. Impact statements
6. Suggestions (not demands)
7. Handling defensiveness
8. Follow-up approach
9. What to avoid saying
10. Building on the conversation
```

#### comm-038 - PIP Communication
- Placeholders: `GAPS, IMPROVEMENTS, ROLE, SITUATION`
- Prompt:

```text
Create a Performance Improvement Plan communication for [SITUATION].

Role: [ROLE]
Performance gaps: [GAPS]
Improvement needed: [IMPROVEMENTS]

Include:
1. Meeting preparation
2. Opening the conversation
3. Specific expectations document
4. Timeline and milestones
5. Support to be provided
6. Check-in schedule
7. Consequences if not improved
8. Documentation requirements
9. Employee response handling
10. Success criteria
11. HR partnership points
```

#### comm-039 - Client Communication Template
- Placeholders: `DETAILS, RELATIONSHIP, SITUATION_TYPE`
- Prompt:

```text
Create client communication for [SITUATION_TYPE].

Client relationship: [RELATIONSHIP]
Situation details: [DETAILS]

Provide templates for:
1. Project kickoff
2. Progress update
3. Delay notification
4. Scope change discussion
5. Deliverable presentation
6. Issue escalation
7. Success celebration
8. Project close
9. Ongoing relationship maintenance
10. Difficult news delivery
```

#### comm-040 - Workplace Boundaries Script
- Placeholders: `BOUNDARY_AREA, CONTEXT, PERSON/GROUP`
- Prompt:

```text
Help me set workplace boundaries around [BOUNDARY_AREA].

Context: [CONTEXT]
With whom: [PERSON/GROUP]

Provide:
1. Self-clarity on what I need
2. How to introduce the boundary
3. Scripts for common situations
4. Handling pushback
5. Maintaining the boundary over time
6. When to involve HR
7. Documentation approach
8. Protecting relationships while setting limits
9. Signs the boundary is working
10. Adjustment strategies
```

#### comm-041 - Exit Interview Questions
- Placeholders: `DEPARTING_ROLE, DEPARTMENT, TENURE`
- Prompt:

```text
Create exit interview questions for [DEPARTING_ROLE].

Department: [DEPARTMENT]
Tenure: [TENURE]

Design questions about:
1. Reason for leaving
2. Job satisfaction
3. Management feedback
4. Team dynamics
5. Career development opportunities
6. Compensation and benefits
7. Work environment
8. Company culture
9. Suggestions for improvement
10. Would they return/recommend
11. Analysis framework for responses
```

#### comm-042 - Remote Check-In Framework
- Placeholders: `CONCERNS, FREQUENCY, TEAM_TYPE`
- Prompt:

```text
Create a remote employee check-in framework.

Team type: [TEAM_TYPE]
Check-in frequency: [FREQUENCY]
Concerns to address: [CONCERNS]

Include:
1. Check-in question bank
2. Video vs. voice guidance
3. Duration recommendations
4. Emotional check-in approaches
5. Work progress discussion
6. Obstacle identification
7. Connection and belonging
8. Development conversations
9. When to escalate concerns
10. Documentation needs
11. Rotation of approaches
```

#### comm-043 - Stakeholder Management Plan
- Placeholders: `DURATION, PROJECT/INITIATIVE, STAKEHOLDERS`
- Prompt:

```text
Create a stakeholder management plan for [PROJECT/INITIATIVE].

Key stakeholders: [STAKEHOLDERS]
Project duration: [DURATION]

Develop:
1. Stakeholder mapping (influence/interest)
2. Communication preferences by stakeholder
3. Update frequency by stakeholder
4. Key concerns to address
5. Engagement strategies
6. Escalation triggers
7. Meeting cadence
8. Decision involvement matrix
9. Risk mitigation
10. Relationship building activities
11. Success metrics
```

#### comm-044 - Internal Presentation Deck
- Placeholders: `AUDIENCE, OBJECTIVE, TIME, TOPIC`
- Prompt:

```text
Outline an internal presentation about [TOPIC].

Audience: [AUDIENCE]
Objective: [OBJECTIVE]
Time: [TIME]

Provide:
1. Slide-by-slide outline
2. Key message per slide
3. Data/visuals to include
4. Story arc
5. Executive summary slide
6. Appendix suggestions
7. Handout recommendation
8. Q&A preparation
9. Follow-up materials
10. Presentation tips for this audience
```

#### comm-045 - Workplace Conflict De-escalation
- Placeholders: `CONFLICT, LEVEL, PARTIES, ROLE`
- Prompt:

```text
Help me de-escalate a workplace conflict about [CONFLICT].

Parties involved: [PARTIES]
Current tension level: [LEVEL]
My role: [ROLE]

Provide:
1. Immediate cooling-off strategies
2. Active listening techniques
3. Neutral language phrases
4. Finding common ground
5. Reframing statements
6. When to take a break
7. Involving third parties
8. Documentation approach
9. Resolution pathways
10. Preventing recurrence
11. When to escalate to HR
```
