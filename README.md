# B2B Career Due Diligence

An open Agent Skill for deeply evaluating **B2B SaaS, AI, enterprise software, digital-transformation, and complex enterprise-service roles**.

It is designed for candidates considering roles such as:

- Customer Success / Strategic CSM / Enterprise CSM
- AI Customer Success
- Account Management / Key Account Management
- Solution Consulting / Pre-sales
- Implementation / Delivery / Enterprise Project Management
- Business / Digital Transformation Consulting
- Enterprise Sales
- Customer Operations / Customer Value Management
- Business-facing AI / FDE-style roles

## Why this skill exists

Most job analysis stops at “JD keyword match”. That is often insufficient for B2B roles, where the same title can mean very different work depending on the company's business model and organizational boundaries.

This skill asks deeper questions:

1. Why does the company have the right to win?
2. Why do customers buy and keep paying?
3. What does the product actually change in the customer's workflow?
4. What does the role really own: sales, pre-sales, implementation, adoption, renewal, expansion, or several of them?
5. Does the candidate have evidence of fit, not just similar keywords?
6. Is the role attractive to the candidate, not merely executable by them?

Core reasoning chain:

> **company → business model → product value → role reality → candidate evidence → career decision**

## What it can do

- Analyze a resume into a structured B2B capability profile
- Research founders, funding, company stage, business model, product, and competitors
- Identify the business model's most diagnostic metrics
- Translate a JD into the real job behind the title
- Audit role boundaries across sales / pre-sales / delivery / success / expansion
- Build a person-job evidence matrix
- Separate direct fit, transferable fit, weak evidence, and real gaps
- Generate interview validation questions by interviewer type
- Score the opportunity and recommend pursuit priority
- Prepare role-specific interview positioning

## What it is not

This is **not** a universal career skill. It is intentionally optimized for B2B enterprise-service and commercial/solution roles.

It is not the best primary framework for pure software engineering, academic research, clinical practice, traditional legal practice, visual design, or public-sector examination roles.

## Skill structure

```text
b2b-career-due-diligence/
├── SKILL.md
├── README.md
├── LICENSE
├── CHANGELOG.md
├── references/
│   ├── candidate-profile-schema.md
│   ├── interview-evidence-framework.md
│   ├── research-framework.md
│   ├── research-standards.md
│   ├── role-taxonomy.md
│   └── scoring-rubric.md
├── templates/
│   ├── deep-analysis.md
│   ├── interview-prep.md
│   ├── quick-analysis.md
│   └── resume-fit.md
└── examples/
    ├── example-input.md
    └── example-output-outline.md
```

## Usage examples

### Example 1 — full due diligence

> Here is my resume, the company website, and the JD. Use the B2B career due diligence framework to tell me whether this role is worth pursuing and what I need to verify in the interview.

### Example 2 — company + job only

> Research this AI startup and translate this customer-success JD into what the job probably does in practice.

### Example 3 — interview preparation

> I have a 30-minute conversation with the CHO tomorrow. Based on my resume and this JD, prepare my positioning, likely questions, and the 5 best questions I should ask.

### Example 4 — resume fit

> Compare my resume to this Solution Consultant role. Separate direct matches, transferable matches, evidence gaps, and genuine capability gaps.

## Installation

This repository follows the open Agent Skills format: a skill directory containing a `SKILL.md` manifest plus supporting files.

Copy the `b2b-career-due-diligence` folder into the skill directory used by your agent, or mount the repository in an environment that supports Agent Skills.

Always review third-party skill instructions before enabling them in an agent with powerful tools.

## Design principles

- **Evidence over encouragement** — do not inflate fit.
- **Business model before title** — role meaning depends on how the company makes money and delivers value.
- **Role boundaries matter** — broad responsibility is fine; unbounded accountability is not.
- **Can do ≠ want to do** — capability fit and preference fit are separate.
- **Interview questions are diligence** — each question should test a specific risk or hypothesis.
- **AI is not automatically a moat** — examine real workflow integration and business outcomes.

## License

MIT. See [LICENSE](LICENSE).

## Version

Current version: **1.0.0**
