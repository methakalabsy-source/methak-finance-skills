# Financial Closure AI Skills

> A modular enterprise skill framework for AI-assisted financial closure, donor compliance, audit readiness, and financial governance.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## Overview

**Financial Closure AI Skills** is a structured library of professional AI skill specifications for donor-funded project financial closure. It is designed to help finance, grants, compliance, audit-preparation, and management teams organize evidence-based financial analysis, reconciliation, closure readiness, donor-reporting preparation, audit defense, and enterprise financial governance.

The framework is built on four operating principles:

- **Evidence first** : conclusions should be linked to reliable source data and supporting evidence.
- **Professional skepticism** : transactions, reports, balances, and explanations require validation.
- **Traceability** : findings should be traceable from conclusion to analysis, transaction, and evidence.
- **Human accountability** : material financial, compliance, approval, and submission decisions remain with authorized professionals.

## Intended Users

- NGO and INGO finance teams
- Project accountants and financial controllers
- Grant managers and donor-compliance specialists
- Finance directors and senior management
- Internal audit and external audit-preparation teams
- Financial systems, AI workflow, and governance professionals

## Core Architecture

The framework contains one governance skill and eight executive skills.

| No. | Skill | Primary purpose |
|---:|---|---|
| 00 | Master Governance & Orchestration | Coordinates skill use, quality expectations, workflow routing, professional principles, and output standards. |
| 01 | General Ledger Intelligence | Assesses GL integrity, transaction quality, classifications, journals, balances, and closure-related risks. |
| 02 | Financial Reconciliation Intelligence | Reconciles accounting records, donor reports, partner reports, budgets, and final settlement information. |
| 03 | Project Closure Readiness Assessment | Assesses financial completion, evidence readiness, controls, outstanding obligations, and closure status. |
| 04 | Final Donor Reporting Intelligence | Prepares and reviews final donor reporting and the supporting evidence package. |
| 05 | Audit Defense Intelligence | Simulates donor and audit challenge procedures and prepares evidence-linked management responses. |
| 06 | Continuous Learning Intelligence | Converts validated lessons, findings, and feedback into controlled improvement recommendations. |
| 07 | AI Financial Closure Agent | Defines controlled AI-assisted automation, monitoring, alerts, report drafting, and human review. |
| 08 | Enterprise Financial Governance Intelligence | Aggregates project-level information into portfolio oversight, risk intelligence, and executive decision support. |

## Downloadable Skill Packages

Each package is a standard ZIP archive containing exactly one root-level file:

```text
SKILL.md
```

Each `SKILL.md` begins with YAML metadata containing a skill `name` and `description`.

| No. | Downloadable package |
|---:|---|
| 00 | [Master Governance & Orchestration](packages/financial-closure-ai-00-master-governance-orchestration.zip) |
| 01 | [General Ledger Intelligence](packages/financial-closure-ai-01-general-ledger-intelligence.zip) |
| 02 | [Financial Reconciliation Intelligence](packages/financial-closure-ai-02-financial-reconciliation-intelligence.zip) |
| 03 | [Project Closure Readiness Assessment](packages/financial-closure-ai-03-project-closure-readiness-assessment.zip) |
| 04 | [Final Donor Reporting Intelligence](packages/financial-closure-ai-04-final-donor-reporting-intelligence.zip) |
| 05 | [Audit Defense Intelligence](packages/financial-closure-ai-05-audit-defense-intelligence.zip) |
| 06 | [Continuous Learning Intelligence](packages/financial-closure-ai-06-continuous-learning-intelligence.zip) |
| 07 | [AI Financial Closure Agent](packages/financial-closure-ai-07-ai-financial-closure-agent.zip) |
| 08 | [Enterprise Financial Governance Intelligence](packages/financial-closure-ai-08-enterprise-financial-governance-intelligence.zip) |

## How to Use a Skill Package

1. Download the required ZIP package.
2. Extract the archive.
3. Confirm that `SKILL.md` is located at the root of the extracted package.
4. Review the YAML metadata and the skill scope.
5. Use the skill only with authorized, relevant, and appropriately protected information.
6. Retain human review and approval for material accounting, donor-compliance, audit, reporting, and closure decisions.

### Recommended Lifecycle Sequence

```text
00 Master Governance
        ↓
01 General Ledger Intelligence
        ↓
02 Financial Reconciliation Intelligence
        ↓
03 Project Closure Readiness Assessment
        ↓
04 Final Donor Reporting Intelligence
        ↓
05 Audit Defense Intelligence
        ↓
06 Continuous Learning Intelligence
        ↓
07 AI Financial Closure Agent
        ↓
08 Enterprise Financial Governance Intelligence
```

Not every engagement requires every skill at the same depth. The Master Governance Skill should be used to determine the appropriate scope, sequence, limitations, and required professional review.

## Important Professional Boundaries

This repository provides a **methodology and AI decision-support framework**. It does not:

- Replace professional accounting, management, legal, donor, or audit judgment.
- Issue an independent audit opinion or expenditure-verification conclusion.
- Certify donor eligibility without the applicable agreement, evidence, and authorized review.
- Post accounting journals, approve payments, sign reports, submit donor reports, or close projects autonomously.
- Guarantee donor acceptance, audit outcomes, compliance, or financial recovery avoidance.

Applicable law, the executed grant agreement and amendments, authorized donor instructions, and entity-approved accounting policies take precedence over generic framework content.

## Data Protection and Confidentiality

Do **not** upload confidential, personal, or sensitive information to this public repository, including:

- General Ledger exports, bank statements, payroll, invoices, or payment records
- Grant agreements, amendments, partner reports, or donor correspondence that are confidential
- Personal data, credentials, API keys, access tokens, or internal audit materials

Use sanitized, synthetic, or properly authorized data for testing and demonstrations. Maintain organization-specific donor rules, policies, and project evidence in an appropriate private and access-controlled environment.

## Current Scope and Future Development

The current release contains the core governance skill and eight executive skills. A future optional shared reference layer may be maintained separately by users or organizations for controlled donor requirements, accounting policies, reporting templates, terminology, and other organization-specific resources.

Potential future development may include:

- Readable source folders for each `SKILL.md`
- Implementation guides and use cases
- Sanitized demonstration datasets and testing scenarios
- Controlled templates and dashboards
- Release notes and formal version tags
- Organization-specific private knowledge resources

## Contributing

Suggestions, issue reports, and improvement proposals are welcome. Please do not submit confidential financial data, unverified donor rules, proprietary documents, or changes that remove human-approval and evidence requirements.

Material changes should explain:

1. The affected skill and section
2. The purpose and professional rationale
3. The impact on evidence, financial control, audit readiness, donor compliance, or AI governance
4. Any required review, testing, or approval

## Version Status

**Current repository status:** Public sanitized core skill library prepared.  
**Current release:** `v1.0.1 — Financial Closure AI Core Skills Release`.

## License

This repository is distributed under the [MIT License](LICENSE).

## Disclaimer

This project is provided for informational, methodological, and decision-support purposes. Users are responsible for validating all requirements against their applicable laws, grant agreements, donor instructions, accounting policies, and organizational controls. Use of this framework does not create an audit, legal, consulting, fiduciary, or donor-approval relationship.
