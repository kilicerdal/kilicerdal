# Erdal Kilic

### Senior SDET | QA Automation Engineer

I build automation frameworks for web applications and APIs, integrate tests into CI/CD pipelines, and investigate failures across UI, service, and database layers.

**9+ years in software quality engineering** across financial services, healthcare, and media. Based in **New Jersey, USA**, and seeking **fully remote Senior SDET / QA Automation Engineer roles**.

[Website](https://www.eai.engineering) · [LinkedIn](https://www.linkedin.com/in/erdalkilic/) · [Email](mailto:erdal@eai.engineering)

## Selected engineering work

| Project | What it demonstrates | Explore |
| --- | --- | --- |
| [Playwright AI Automation](https://github.com/kilicerdal/playwright-ai-automation) | TypeScript UI/API automation, PostgreSQL commerce, cross-browser checks, and controlled defect detection. V5 records **223 distinct scenarios across 301 local test executions**. | [Watch demo](https://github.com/kilicerdal/playwright-ai-automation/releases/download/v5.0.0/v5-showcase-demo.webm) · [Results and scope](https://github.com/kilicerdal/playwright-ai-automation/blob/main/docs/verification.md) |
| [SettlementLab](https://github.com/kilicerdal/settlementlab) | Python financial assurance: matching, maker/checker approval, settlement, and reconciliation. Reuses one assurance engine against an independent collateral API and detects an injected replay defect. | [Watch demo](https://github.com/kilicerdal/settlementlab/releases/download/v3.0.0/settlementlab-walkthrough.webm) · [Case study](https://www.eai.engineering/engineering/settlementlab) |
| [Healthcare Quality Platform](https://github.com/kilicerdal/ai-healthcare-quality-platform) | Playwright API, contract, PostgreSQL, and simulated S3/SQS testing, including message redelivery and idempotency controls. | [Watch walkthrough](https://github.com/kilicerdal/ai-healthcare-quality-platform/blob/main/docs/media/walkthrough.webm?raw=true) · [Sample report](https://github.com/kilicerdal/ai-healthcare-quality-platform/blob/main/docs/samples/ai-validation-report.zip?raw=true) |
| [eAI Engineering](https://github.com/kilicerdal/eai-engineering) | A deployed Next.js platform with an engineering assistant, AI learning tools, server-side integrations, and regression checks. | [Live website](https://www.eai.engineering) · [Architecture and checks](https://github.com/kilicerdal/eai-engineering#architecture-and-boundaries) |

**Evidence scope:** Playwright V5 results are recorded local runs; its hosted workflows and live model calls are disabled. Healthcare uses Moto to simulate AWS; its sample AI report covers eight deterministic checks. AI examples, recordings, and test results are labeled in each repository.

## Engineering judgment

- [Atomic settlement and rollback](https://github.com/kilicerdal/settlementlab/blob/main/docs/decisions/001-atomic-settlement.md): keeping financial state and journal evidence consistent.
- [Replay identity and stale writes](https://github.com/kilicerdal/settlementlab/blob/main/docs/decisions/002-replay-and-stale-writes.md): separating duplicate requests from concurrent changes.
- [Healthcare failure cases](https://github.com/kilicerdal/ai-healthcare-quality-platform/blob/main/docs/ENGINEERING.md): queue retries, persistence, and validation decisions.

## Skills

**Automation:** Playwright, Selenium, Cypress · **API:** REST Assured, Postman, Karate, contract testing  
**Languages:** Java, TypeScript, JavaScript, Python, SQL · **Delivery:** GitHub Actions, Jenkins, GitLab CI/CD  
**Quality engineering:** regression strategy, database validation, failure investigation · **Cloud and AI:** AWS, LLM integration, AI-assisted testing

These repositories contain personal engineering work with synthetic data. Employer source code and confidential data are excluded.

For remote SDET and QA automation opportunities: **[erdal@eai.engineering](mailto:erdal@eai.engineering)**.
