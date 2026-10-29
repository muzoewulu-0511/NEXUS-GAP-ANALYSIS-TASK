# Nexus Financial Services | GRC Assessment & ISO 27001 Gap Analysis

![Project type](https://img.shields.io/badge/Project-Case%20Study-blue)
![Focus](https://img.shields.io/badge/Focus-GRC-005A9C)
![Standard](https://img.shields.io/badge/Reference-ISO%2FIEC%2027001%3A2022-008080)
![Deliverables](https://img.shields.io/badge/Deliverables-Documentation-grey)

A documentation-based portfolio project assessing governance, risk, compliance, and information security management gaps at Nexus Financial Services.

The project brings together an introductory GRC assessment and an ISO/IEC 27001:2022 gap analysis. It translates organizational weaknesses into categorized findings, proposed controls, an Information Security Management System (ISMS) scope, and a prioritized remediation roadmap.

> This repository presents an educational case-study assessment—not a deployed application, completed control implementation, formal certification audit, or claim of ISO 27001 certification.

## Contents

- [Project Purpose](#project-purpose)
- [Problem Statement](#problem-statement)
- [Case-Study Environment](#case-study-environment)
- [Key Deliverables](#key-deliverables)
- [Assessment Approach](#assessment-approach)
- [Key Findings](#key-findings)
- [Proposed ISMS Scope](#proposed-isms-scope)
- [PDCA Assessment](#pdca-assessment)
- [Remediation Roadmap](#remediation-roadmap)
- [Tools, Formats, and Technologies](#tools-formats-and-technologies)
- [Repository Structure](#repository-structure)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Skills Demonstrated](#skills-demonstrated)
- [Limitations](#limitations)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [Author](#author)
- [References](#references)
- [License](#license)

## Project Purpose

Demonstrate how a GRC analyst can connect business challenges with governance structures, security requirements, control recommendations, and practical remediation priorities.

The project addresses two complementary questions:

1. How can an organization establish a basic governance, risk, and compliance framework?
2. What information security management gaps should it address as it prepares for ISO/IEC 27001 certification?

## Problem Statement

Nexus Financial Services has grown faster than its governance and security management practices.

Its case-study challenges include:

- No clear process for approving or enforcing policies
- No consistent approach to assessing risk before business decisions
- No assigned responsibility for tracking regulatory requirements and deadlines
- No formal ISMS governance or established information security objectives
- Independent control implementation across departments
- Incomplete identification and classification of critical assets
- Limited organization-wide risk visibility

These weaknesses create potential exposure to unauthorized access, data breaches, inconsistent protection, regulatory failures, operational disruption, and certification delays.

## Case-Study Environment

The ISO 27001 assessment describes the following organizational and technical scope:

| Area | Scenario Details |
|---|---|
| Organization | Nexus Financial Services |
| Workforce and locations | 250 employees across three offices |
| Business functions | IT & Operations; Finance & Compliance; Human Resources |
| Cloud environment | AWS-hosted customer data |
| Business systems | Payment-processing systems and a mobile banking application |
| Integrations | Third-party APIs |
| Identity infrastructure | On-premises Active Directory |
| Information assets | Customer, transaction, employee, contractor, operational, security, and regulatory-reporting information |

These technologies form the environment being assessed. They are not software components built or deployed by this project.

## Key Deliverables

| Document | Purpose | Included Analysis |
|---|---|---|
| `Intro-to-GRC-Assignment.docx` | Assess foundational GRC weaknesses | GRC definitions, three categorized issues, business implications, and a recommendation for a board-sponsored GRC framework |
| `NEXUS-GAP-ANALYSIS-TASK.docx` | Assess ISO 27001 readiness gaps | Five security gaps, control mappings, recommendations, ISMS scope, PDCA assessment, and phased remediation priorities |

The project’s central strength is its progression from business-level accountability issues to a structured information security improvement plan.

## Assessment Approach

The documents use a qualitative, scenario-based approach:

1. Review the case-study business context and stated challenges.
2. Classify foundational issues under governance, risk management, or compliance.
3. Identify five major information security gaps.
4. Associate findings with relevant ISO/IEC 27001:2022 requirements and Annex A control areas.
5. Recommend controls and explain their business rationale.
6. Define the proposed ISMS boundary.
7. Assess the current Plan–Do–Check–Act lifecycle.
8. Prioritize remediation based on foundational dependencies and protection needs.

No live-system testing, configuration review, automated scanning, or control-effectiveness validation is documented.

## Key Findings

### Foundational GRC Issues

| Issue | GRC Pillar | Proposed Response |
|---|---|---|
| Policies lack clear approval and enforcement processes | Governance | Define policy ownership, approval authority, decision rights, and oversight |
| Business decisions lack a standard risk-assessment method | Risk Management | Establish a repeatable assessment process, risk ownership, and a central risk register |
| Regulatory requirements and deadlines lack an accountable owner | Compliance | Assign responsibility and maintain a regulatory obligations calendar |

The introductory assessment recommends a board-sponsored GRC framework supported by a charter, accountable owners, core registers, and at least quarterly leadership reporting.

### ISO 27001 Gap Analysis

| Identified Gap | Priority in Assessment | Proposed Response |
|---|---|---|
| No formal ISMS governance, policy, accountability, or executive oversight | Critical | Establish an ISMS owner, approved security policy, defined responsibilities, and recurring oversight |
| No consistent information security risk-assessment and treatment process | Critical | Define risk criteria, ownership, treatment options, acceptance thresholds, and review intervals |
| Incomplete asset identification, ownership, and classification | High | Maintain a central asset register with owners and information classifications |
| Inconsistent identity, access, and privileged-access practices | High | Standardize role-based access, MFA, joiner–mover–leaver workflows, and access reviews |
| Insufficient cloud, supplier, and API risk governance | High | Introduce supplier due diligence, security requirements, contractual safeguards, and periodic reviews |

The detailed report associates findings with control areas covering policy, security responsibilities, asset inventory, information classification, identity and access management, supplier relationships, and cloud services.

The risk-management finding also references clauses 6.1.2 and 6.1.3. Control mappings should be validated against the applicable standard before operational or audit use.

## Proposed ISMS Scope

The proposed ISMS covers the people, processes, information, applications, infrastructure, and third-party interfaces supporting IT & Operations, Finance & Compliance, and Human Resources across Nexus’s three offices.

It includes AWS-hosted customer information, payment-processing systems, the mobile banking application, third-party API integrations, on-premises Active Directory, and the related customer, transaction, employee, contractor, operational, security, and regulatory-reporting information.

## PDCA Assessment

The analysis uses Plan–Do–Check–Act (PDCA) to describe the maturity of the scenario’s security management practices.

| Stage | Assessed State | Basis in the Case Study |
|---|---|---|
| Plan | Immature | Governance, policy, objectives, risk processes, and asset ownership are not fully established |
| Do | Fragmented | Departments implement controls independently |
| Check | Not evidenced | The scenario does not demonstrate consistent monitoring, internal audit, control testing, or management review |
| Act | Not evidenced | The scenario does not describe a formal corrective-action or continual-improvement process |

“Not evidenced” means the supplied scenario does not demonstrate the activity; it does not establish that the activity is definitively absent.

## Remediation Roadmap

The following phases are recommendations, not completed implementations.

### Phase 1 — Establish the ISMS Foundation

- Secure executive sponsorship.
- Assign ISMS, risk, asset, and control ownership.
- Approve the ISMS scope, security policy, governance charter, and reporting structure.
- Establish risk-assessment and risk-treatment methods.
- Create a central risk register.
- Develop a Statement of Applicability (SoA) documenting selected controls, implementation status, and inclusion or exclusion rationale.

Intended outcome: governed, risk-based, documented security decisions with clear accountability.

### Phase 2 — Protect Critical Information and Systems

- Complete the asset inventory and information-classification scheme.
- Assign owners to critical information assets.
- Standardize identity, access, and privileged-access practices.
- Formalize cloud, supplier, and API security requirements.
- Establish incident-management procedures, escalation paths, and evidence requirements.

Intended outcome: clearer visibility of critical assets and more consistent protection across systems and suppliers.

### Phase 3 — Demonstrate and Improve Effectiveness

- Define measurable security objectives and performance indicators.
- Establish monitoring, vulnerability management, and backup testing.
- Deliver employee and contractor security awareness training.
- Conduct internal audits and management reviews.
- Track corrective actions and reassess readiness.

Intended outcome: evidence that selected controls operate effectively and support continual improvement.

## Tools, Formats, and Technologies

### Project Artifacts

| Item | Role |
|---|---|
| DOCX | Format of the two assessment reports |
| Markdown | Repository overview and navigation |
| GRC analysis | Classification of organizational issues and accountability gaps |
| ISO/IEC 27001:2022 | Reference framework for the security gap analysis |
| PDCA | Structure for assessing management-system maturity |

The document-authoring application is not confirmed in the supplied materials.

### Technologies Discussed in the Scenario

- Amazon Web Services (AWS)
- On-premises Active Directory
- Payment-processing systems
- Mobile banking application
- Third-party API integrations

No programming language, package manager, application runtime, CI/CD pipeline, or deployed GRC platform is documented.

## Repository Structure

Expected layout when the supplied reports and this README are added to the repository:

```text
.
├── README.md
├── Intro-to-GRC-Assignment.docx
└── NEXUS-GAP-ANALYSIS-TASK.docx
```

## Getting Started

### Prerequisites

- A DOCX-compatible document viewer or editor
- Git, only if cloning the repository locally

### Option 1 — Review Through GitHub

1. Locate the report you want to review.
2. Download the DOCX file.
3. Open it in a compatible document viewer.

### Option 2 — Clone Locally

Replace the placeholders with the repository’s actual details:

```bash
git clone [https://github.com/](https://github.com/)<github-username>/<repository-name>.git
cd <repository-name>
```

Open either assessment document to review the full analysis.

There are no project dependencies to install, build commands to run, or application services to start.

## Usage

### For Recruiters and Hiring Managers

1. Review the key findings for a concise summary of the analyst’s reasoning.
2. Open the introductory GRC report to assess issue classification and business communication.
3. Open the gap-analysis report to review scope definition, control recommendations, prioritization, and readiness planning.

### For Learners and Reviewers

1. Compare each finding with the scenario evidence.
2. Review the distinction between management-system requirements and security controls.
3. Examine why governance and risk methodology precede later remediation activities.
4. Use the recommendations as a starting point for creating supporting templates.

Do not treat the reports as evidence that controls have been implemented, tested, or certified.

## Skills Demonstrated

- Governance, risk, and compliance issue classification
- Business-impact analysis
- ISO 27001 gap-analysis documentation
- Control mapping and recommendation development
- ISMS scope definition
- Qualitative remediation prioritization
- PDCA maturity assessment
- Executive-summary writing and stakeholder communication

## Limitations

- Findings are based on the supplied case-study narrative, not an independently verified organizational assessment.
- No live infrastructure access, interviews, audit evidence, or technical testing is documented.
- Priority ratings are qualitative; no numerical scoring model is supplied.
- Recommended registers, policies, dashboards, and the SoA are not included as completed artifacts.
- No jurisdiction-specific regulatory assessment is documented.
- The introductory report includes “Nexus Health Services” in some headings, while its body and the gap-analysis report describe Nexus Financial Services. This README uses Nexus Financial Services consistently.
- ISO control mappings and certification-readiness conclusions require further validation before professional audit use.

## Future Enhancements

Potential additions—not currently included—are:

- GRC charter and responsibility matrix
- Risk register and documented scoring criteria
- Asset inventory and classification template
- Policy register and regulatory obligations calendar
- Statement of Applicability
- Remediation tracker with owners, target dates, and evidence requirements
- Quarterly GRC dashboard
- PDF versions of the reports for easier review
- Screenshots or diagrams of completed supporting artifacts

## Contributing

To propose an improvement:

1. Open an issue describing the correction or proposed addition.
2. Explain the supporting evidence or rationale.
3. Submit a pull request with focused changes.

Please:

- Keep scenario facts separate from assumptions and recommendations.
- Validate any changes to ISO references or control mappings.
- Do not describe proposed controls as implemented.
- Avoid adding confidential, personal, or proprietary organizational information.
- Respect applicable copyright and licensing restrictions.

## Author

Maureen Uzoewulu  
GRC Analyst — Case-Study Portfolio

- GitHub: <GitHub profile URL>
- LinkedIn: <LinkedIn profile URL>
- Contact: <optional professional email>

## References

The supplied reports cite:

- Bello-Abubakar, A. (n.d.). Enterprise GRC framework integration. Course presentation, 10Alytics.
- ISO/IEC 27001:2022, Information security, cybersecurity and privacy protection — Information security management systems — Requirements.
- ISO 27001 implementation and gap-analysis course materials.

Consult the reports for their reference details.

## License

<Add the selected license and a LICENSE file, or specify the intended reuse permissions.>

Any repository license should distinguish original project content from third-party course materials and standards.
