# Erdal Kilic

### Senior SDET | QA Automation Engineer

I build automation frameworks for web applications and APIs, integrate tests into CI/CD pipelines, and investigate failures across UI, service, and database layers.

**9+ years in software quality engineering** across financial services, healthcare, and media. Based in **New Jersey, USA**, and seeking **fully remote Senior SDET / QA Automation Engineer roles**.

[Website](https://www.eai.engineering) · [LinkedIn](https://www.linkedin.com/in/erdalkilic/) · [Email](mailto:erdal@eai.engineering)

**For a quick review:** [Take the five-minute project tour](https://www.eai.engineering/engineering/tour) through checkout retries, claim redelivery, and settlement controls, with source links and evidence scope.

## Selected engineering work

| Project | What it demonstrates | Explore |
| --- | --- | --- |
| [Playwright AI Automation](https://github.com/kilicerdal/playwright-ai-automation) | TypeScript UI/API automation and PostgreSQL commerce. The [November 17 release verification](https://github.com/kilicerdal/playwright-ai-automation/releases/tag/mutation-showcase-2026-11-17) records **322 local test executions**, plus detection of **6/6 inventory and 6/6 pricing source mutations** in a separate campaign. | [Watch mutation walkthrough](https://github.com/kilicerdal/playwright-ai-automation/releases/download/mutation-showcase-2026-11-17/mutation-walkthrough.webm) · [Evidence and reproduction](https://github.com/kilicerdal/playwright-ai-automation/blob/main/docs/local-mutation-testing.md) |
| [SettlementLab](https://github.com/kilicerdal/settlementlab) | Python financial assurance: matching, maker/checker approval, settlement, and reconciliation. Reuses one assurance engine against an independent collateral API and detects an injected replay defect. | [Watch demo](https://github.com/kilicerdal/settlementlab/releases/download/v3.0.0/settlementlab-walkthrough.webm) · [Case study](https://www.eai.engineering/engineering/settlementlab) |
| [Healthcare Quality Platform](https://github.com/kilicerdal/ai-healthcare-quality-platform) | Playwright API, contract, PostgreSQL, and simulated S3/SQS testing, including message redelivery and idempotency controls. Focus: service and event integration. | [Watch walkthrough](https://github.com/kilicerdal/ai-healthcare-quality-platform/blob/main/docs/media/walkthrough.webm?raw=true) · [Sample report](https://github.com/kilicerdal/ai-healthcare-quality-platform/blob/main/docs/samples/ai-validation-report.zip?raw=true) |
| [Healthcare Quality Lab](https://github.com/kilicerdal/healthcare-quality-lab) | Python, pytest and Playwright. **665 deterministic tests**; business-rule correctness, concurrent payment protection, interrupted-worker recovery, independently checked AI expectations, and recorded OpenAI/Ollama evaluation. | [Watch walkthrough](https://github.com/kilicerdal/healthcare-quality-lab/releases/download/v5.8.0/healthcare-showcase.webm) · [Case study and evidence](https://github.com/kilicerdal/healthcare-quality-lab/blob/main/docs/CASE_STUDY.md) |
| [eAI Engineering](https://github.com/kilicerdal/eai-engineering) | A deployed Next.js platform with an engineering assistant, AI learning tools, server-side integrations, and regression checks. | [Live website](https://www.eai.engineering) · [Architecture and checks](https://github.com/kilicerdal/eai-engineering#architecture-and-boundaries) |

**Evidence scope:** Playwright results are recorded local runs. The twelve targeted source mutations are counted separately from test executions and do not establish exhaustive defect coverage. That project's hosted workflows and live model calls are disabled. Healthcare Quality Platform uses Moto to simulate AWS; its sample AI report covers eight deterministic checks. Healthcare Quality Lab's OpenAI and Ollama measurements use a small development cohort with differing runtime settings; its deterministic CI uses offline provider doubles. AI examples, recordings, and test results are labeled in each repository.

## Engineering judgment

- [From a surviving mutation to a detected defect](https://github.com/kilicerdal/playwright-ai-automation/blob/main/docs/local-mutation-testing.md#follow-a-survivor-through-an-assertion-improvement): a status-only test passes with stock deduction removed; adding a persisted-stock assertion detects expected **6** / observed **8** against the same mutated source. Both healthy controls pass.
- [Atomic settlement and rollback](https://github.com/kilicerdal/settlementlab/blob/main/docs/decisions/001-atomic-settlement.md): keeping financial state and journal evidence consistent.
- [Replay identity and stale writes](https://github.com/kilicerdal/settlementlab/blob/main/docs/decisions/002-replay-and-stale-writes.md): separating duplicate requests from concurrent changes.
- [Healthcare failure cases](https://github.com/kilicerdal/ai-healthcare-quality-platform/blob/main/docs/ENGINEERING.md): queue retries, persistence, and validation decisions.

- [Independently checking AI-created expectations](https://github.com/kilicerdal/healthcare-quality-lab/blob/main/docs/CASE_STUDY.md): separating a plausible generated case from a reviewed test that detects a wrong business result.

## Skills

**Automation:** Playwright, Selenium, Cypress · **API:** REST Assured, Postman, Karate, contract testing  
**Languages:** Java, TypeScript, JavaScript, Python, SQL · **Delivery:** GitHub Actions, Jenkins, GitLab CI/CD  
**Quality engineering:** regression strategy, database validation, failure investigation · **Cloud and AI:** AWS, LLM integration, AI-assisted testing

These repositories contain personal engineering projects with synthetic data. I set the direction and priorities and use AI assistance for implementation, test development, and documentation. Public source and dated verification records make the results inspectable. Employer source code and confidential data are excluded.

For remote SDET and QA automation opportunities: **[erdal@eai.engineering](mailto:erdal@eai.engineering)**.
