---
name: b2b-career-due-diligence
description: Deeply research and evaluate B2B SaaS, AI, enterprise software, digital transformation, and complex enterprise-service roles. Use when a candidate provides a company, job description, recruiter message, website, or resume and wants to judge whether the company and role are worth pursuing, what the role really does, how the business model works, how well the candidate fits, what gaps or risks exist, and how to prepare for interviews. Best for customer success, strategic CSM, account management, solution consulting/pre-sales, implementation/delivery, enterprise sales, business consulting, customer operations, and business-facing AI/FDE roles.
---

# B2B Career Due Diligence

## Purpose

Perform evidence-based career due diligence for B2B enterprise-service roles. Do more than summarize a job description or company profile. Determine:

1. Why the company can credibly win in its market.
2. Why customers pay, continue paying, or expand.
3. What the product or service actually changes in the customer's workflow.
4. What the advertised role really owns in that commercial model.
5. Whether the candidate can do the job, wants the job, and has evidence to prove fit.
6. What must still be verified in interviews before making a career decision.

The core reasoning chain is:

**company → business model → product value → role reality → candidate evidence → career decision**

## Scope

### Best-fit roles

Use this skill primarily for roles in B2B SaaS, AI, enterprise software, enterprise digitalization, and complex enterprise services, especially:

- Customer Success Manager / Enterprise CSM / Strategic CSM
- AI Customer Success / customer AI success / business-facing AI adoption roles
- Account Manager / Key Account Manager
- Solution Consultant / Pre-sales / Solution Architect with strong business-facing scope
- Implementation / Delivery / Enterprise Project Manager
- Business Consultant / Digital Transformation Consultant
- Enterprise Sales when the user wants to understand solution complexity and account ownership
- Customer Operations / Customer Value Management
- Forward-deployed or FDE-like roles where business discovery and adoption matter as much as technical execution

### Do not present as a universal career framework

This skill is not optimized for pure software engineering, algorithm research, academic research, clinical practice, traditional legal practice, visual design, public-sector examinations, or other occupations where the main success model is not B2B customer value delivery.

If the user asks about one of those roles, you may still research the company, but explicitly state that the role-fit framework is outside the skill's strongest scope.

## Inputs

Possible inputs include:

- company name
- company website
- job description
- screenshots of recruiter / hiring-manager conversations
- candidate resume or LinkedIn-style work history
- candidate preferences and constraints
- prior interview notes
- competing offers or roles

Do not require all inputs. Work with what is available and clearly mark missing evidence.

## Operating modes

Infer the mode from the user's request. If unclear, default to **Deep** when enough company/job information exists and **Quick** when information is sparse.

### Quick

Use when the user asks whether a role is worth pursuing or wants a fast fit check.

Output:
- one-line verdict
- company / role classification
- 3 strongest fit points
- 3 biggest risks or unknowns
- 3 interview validation questions
- pursue priority: A / B / C / D

### Deep

Use for full company + role due diligence.

Follow the complete workflow below and use `templates/deep-analysis.md`.

### Interview

Use after an interview is scheduled or when the user wants to prepare for a recruiter, hiring manager, or executive conversation.

Focus on:
- candidate positioning
- strongest evidence cases
- likely challenge questions
- role-specific answers
- interviewer-specific reverse questions
- unknowns to validate

Use `templates/interview-prep.md`.

### Resume Fit

Use when the user provides a resume and a target role and asks for fit or resume improvements.

Use `templates/resume-fit.md`.

## Workflow

### Step 1 — Build the candidate profile first when a resume is available

Do not jump straight to job matching.

Extract:
- years and trajectory of experience
- industries and product categories
- customer segments and account complexity
- customer portfolio size where available
- sales / renewal / expansion / implementation / delivery ownership
- discovery and business-process analysis experience
- solution design experience
- project and cross-functional execution experience
- customer enablement / training / workshop experience
- product feedback / product iteration experience
- commercial outcomes and metrics
- management experience
- strongest 3–5 evidence cases
- transferable capabilities
- explicit career preferences and exclusions, only if provided by the user

Use `references/candidate-profile-schema.md`.

Important:
- A job title is not a capability. Infer capability from responsibilities and evidence.
- Do not invent metrics or results.
- Do not infer protected or sensitive traits.
- Separate **can do** from **wants to do**.

### Step 2 — Verify company identity

Before researching:
- confirm the exact legal or operating entity when names are ambiguous
- confirm product / brand names
- distinguish similarly named companies
- use official sources where possible

If identity remains uncertain, explicitly state the uncertainty rather than merging information from different entities.

### Step 3 — Analyze company foundations

Research:
- founding date and stage
- founders and founder-market fit
- core leadership team
- ownership / parent-subsidiary relationships when material
- financing rounds and investors
- strategic or industrial backing
- current hiring / expansion signals

The question is not “who invested?” but:

**Why is this team structurally credible to solve this problem?**

For early-stage companies, founder-market fit matters heavily.

### Step 4 — Reconstruct the business model

Answer five questions:

1. Who buys?
2. Why do they buy?
3. What exactly do they buy?
4. How does it create measurable value?
5. Why would they renew, expand, or keep using it?

Express the value loop as:

**customer → problem → product/service → usage → business outcome → continued spend**

If one link is unclear, flag it as a business-model risk.

### Step 5 — Identify the business-model “kill metric”

Find the smallest set of metrics that would most strongly validate or falsify the model.

Examples:
- marketplace: repeat transaction rate, supply-side repeat participation, GMV retention, disintermediation rate
- SaaS: activation, time-to-value, retention, NRR, expansion, measurable business outcome
- AI Agent: POC-to-production rate, sustained usage, production task volume, scenario expansion, validated ROI
- enterprise services: ARR, renewal, delivery cycle, implementation cost, gross margin, utilization

Do not ask generic questions such as “How is the business doing?” when a more diagnostic metric exists.

### Step 6 — Explain how the product actually works

Use this chain:

**input → product/AI action → output → user → changed business action**

For AI companies, explicitly classify whether the product is primarily:
- AI assistance
- workflow automation
- agentic task execution
- human-delivered service with AI support

Do not accept labels such as “AI Agent”, “copilot”, “digital employee”, or “platform” at face value.

### Step 7 — Map the competitive landscape

Separate:
- direct competitors
- adjacent competitors
- incumbents adding the same capability
- internal/manual substitutes

Then answer:

**Why would a customer choose this company instead?**

Evaluate possible moats:
- proprietary data
- domain know-how
- workflow embedding
- integrations
- network effects
- distribution / ecosystem
- switching costs
- technical advantage
- delivery capability

Use `references/research-framework.md` and `references/research-standards.md`.

### Step 8 — Translate the JD into the real job

Do not trust the title alone.

Classify the actual role by ownership across:
- discovery / business diagnosis
- new-logo sales
- demos / POC / pre-sales
- solution design
- onboarding / implementation
- project management
- training / enablement
- adoption / usage growth
- renewal
- expansion / upsell
- executive relationship management
- product feedback and roadmap influence
- technical troubleshooting

Then classify the role as one or more of:
- customer success
- strategic customer success
- account management
- solution consulting / pre-sales
- implementation / delivery
- enterprise sales
- business consulting
- business-facing AI / FDE
- hybrid

When 3 or more major responsibility domains are combined without clear support functions, flag **role-boundary risk**.

Use `references/role-taxonomy.md`.

### Step 9 — Audit role boundaries

For B2B enterprise roles, explicitly verify:
- Who owns new-logo signing?
- Does this role carry new-logo quota?
- Who owns renewal?
- Who owns expansion?
- Who owns pre-sales and POC?
- Who owns implementation?
- Who designs the technical solution?
- Who handles product / engineering escalations?
- How many customers / projects does one person manage?
- What are the role's success metrics?

A broad role is not automatically bad. The risk is **unbounded accountability without organizational support**.

### Step 10 — Build the person-job evidence matrix

Use these columns:

| Job requirement | Candidate capability | Evidence / case | Match type | Gap / risk |

Match type must be one of:
- Direct match
- Transferable match
- Adjacent evidence
- Clear gap

Do not convert weak evidence into a strong match just to be encouraging.

For each gap, distinguish:
- learnable product / domain gap
- structural experience gap
- preference mismatch
- evidence gap (candidate may have done it but resume does not prove it)

### Step 11 — Separate ability fit from preference fit

Assess two different questions:

**Can the candidate do it?**
- capability
- evidence
- complexity handled before
- learning curve

**Would the candidate want to do it?**
- industry interest
- work content
- customer type
- role boundaries
- travel / intensity / location / compensation constraints, only if supplied

Never treat strong historical performance in a responsibility as proof the candidate wants to continue doing it.

### Step 12 — Surface risks and unknowns

Group them into:
- company risk
- business-model risk
- product risk
- role-boundary risk
- candidate-fit risk
- career-direction risk

Mark each as:
- confirmed concern
- plausible risk
- unknown to verify

### Step 13 — Convert unknowns into interview validation questions

Every interview question should test a specific hypothesis.

Bad:
- “How does the team collaborate?”

Better:
- “I saw the role covers discovery, solution design and adoption. In a typical customer project, where does the CSM stop and where do solution/FDE and implementation teams take over?”

Split questions by interviewer:

#### Recruiter / HR
- reason for headcount
- team size
- reporting line
- KPI structure
- travel
- compensation structure
- process

#### Hiring manager
- customer lifecycle
- portfolio size
- role boundaries
- success metrics
- standard vs customized delivery
- renewal / expansion ownership
- typical customer case

#### Executive / founder / CHO
- strategic thesis
- why customers keep paying
- productization vs services tradeoff
- 1–2 year priorities
- why this role matters now

### Step 14 — Prepare candidate positioning when requested

Build a concise narrative around:
- strongest transferable capability
- role-specific evidence
- honest gap
- why the transition is logical

Avoid generic claims such as “fast learner” when evidence can be used instead.

### Step 15 — Score the opportunity

Use six scores from 1–10:
- Company / business model
- Product / market space
- Candidate-role fit
- Career growth value
- Industry / work-content interest
- Role boundary / sustainability

Then assign:
- **A — Prepare seriously**
- **B — Worth exploring; validate key unknowns**
- **C — Useful for practice or information gathering**
- **D — Low priority / do not invest heavily**

Also include **confidence: high / medium / low** based on evidence quality.

Use `references/scoring-rubric.md`.

## Research standards

When current public information matters, research before concluding.

Source priority:
1. company official website, documentation, investor relations, regulatory filings
2. founder / executive interviews and first-party product material
3. reputable business / technology media
4. financing databases and company databases
5. secondary commentary and social media

For financing, customer scale, revenue, and market claims:
- cross-check important claims where possible
- distinguish confirmed disclosure from database-only records
- write “not publicly disclosed” when evidence is absent
- never convert marketing language into a fact

Always distinguish:
- **Fact** — supported by source
- **Inference** — reasoned interpretation
- **Unknown** — needs verification

See `references/research-standards.md`.

## Output principles

- Lead with judgment, not data dumping.
- Explain why a fact matters for the career decision.
- Use tables when comparing role responsibilities, candidate evidence, or competitors.
- Keep “company quality” separate from “candidate preference”.
- Treat interview questions as diligence tools, not a generic list.
- Be candid when a role is a disguised sales, implementation, or catch-all position.
- Do not overrate “AI” merely because the market is fashionable.
- Do not underrate a candidate solely because the product category is new if the underlying capability is transferable.
- Do not fabricate candidate achievements, company metrics, customers, or funding details.

## Supporting files

Read the relevant files when needed:
- `references/research-framework.md`
- `references/candidate-profile-schema.md`
- `references/role-taxonomy.md`
- `references/scoring-rubric.md`
- `references/research-standards.md`
- `references/interview-evidence-framework.md`
- `templates/quick-analysis.md`
- `templates/deep-analysis.md`
- `templates/resume-fit.md`
- `templates/interview-prep.md`
