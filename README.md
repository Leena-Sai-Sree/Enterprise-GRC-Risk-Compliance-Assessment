# Nexora Health Technologies | Enterprise GRC Portfolio

**Simulation | Assessment as of October 17, 2026 | All organizations, people, events, evidence and decisions are fictional.**

## Executive overview
Nexora Health Technologies is a fictional Dallas-based healthcare SaaS business with 450 employees, 75 healthcare customers and $65M annual revenue. Its AWS-hosted platform supports scheduling, clinical documentation and billing workflows, and processes electronic protected health information (ePHI) for covered-entity customers under business associate agreements (BAAs). Microsoft 365/Entra ID supports workforce identity; AWS hosts EC2, RDS and S3; Sentinel, CloudTrail and Tenable provide security telemetry.

**Assessment result:** 12 scenario-based enterprise risks were evaluated. Three risks are rated Critical and nine High on an inherent basis; after assumed current controls, four remain High. An access recertification weakness and incomplete vendor assurance create the most immediate treatment priorities. See [management briefing](05-management-reporting/BOARD-BRIEF.md).

> **Interpretation:** All findings and scores are constructed educational scenarios, not verified operating evidence. No real audit, penetration test, SOC 2 examination, HIPAA compliance determination, or ISO 27001 certification occurred. Control effectiveness is an assumption for training purposes.

## Business priorities and scope
- Protect ePHI confidentiality, integrity and availability.
- Support 99.9% customer-facing platform uptime (internal target, not verified achievement).
- Meet contractual customer security assurance expectations and prepare for a possible SOC 2 Type II examination.
- Establish repeatable vendor oversight and access governance.
- Build an ISO/IEC 27001:2022-aligned ISMS roadmap, using NIST CSF 2.0 for risk organization.

**Assessment boundary:** AWS production environment, Entra ID workforce identities, critical vendor relationships and supporting security operations. Excludes customers' own systems, physical clinics and payment-card data environments; payment handling is outsourced, and PCI DSS applicability needs separate scoping.

## Framework interpretation
| Source | Nexora's use | Status |
|---|---|---|
| HIPAA Security Rule / applicable Breach Notification Rule | Business associate regulatory and BAA duties, assuming ePHI processing | Applicable obligations; scenario-specific legal analysis required |
| SOC 2 Trust Services Criteria | Customer-requested assurance; Security with Availability and Confidentiality considered for scope | Voluntary independent attestation goal, not certification |
| ISO/IEC 27001:2022 | ISMS and risk treatment roadmap | Optional certification goal |
| NIST CSF 2.0 | Organizing cybersecurity governance and control outcomes | Voluntary framework |

## Four portfolio deliverables
1. [Risk assessment methodology](01-risk-management/RISK-METHODOLOGY.md) and [12-risk register](01-risk-management/RISK-REGISTER.csv), with [treatment tracker](01-risk-management/RISK-TREATMENT-PLAN.csv).
2. [IAM policy](02-iam-governance/IAM-POLICY.md) and [quarterly access review](02-iam-governance/Q3-ACCESS-REVIEW.csv), with [review decisions](02-iam-governance/ACCESS-REVIEW-SUMMARY.md).
3. [Vendor due diligence assessment](03-third-party-risk/VENDOR-ASSESSMENT.md), [questionnaire](03-third-party-risk/VENDOR-QUESTIONNAIRE.csv) and [vendor actions](03-third-party-risk/VENDOR-REMEDIATION.csv).
4. [HIPAA/SOC 2 control gap assessment](04-compliance-gap-assessment/CONTROL-GAP-MATRIX.csv), [assessment report](04-compliance-gap-assessment/GAP-ASSESSMENT.md) and [corrective action plan](04-compliance-gap-assessment/CORRECTIVE-ACTIONS.csv).

Also see the [evidence catalog](evidence/EVIDENCE-INDEX.csv), [board-level briefing](05-management-reporting/BOARD-BRIEF.md), and [LinkedIn copy](LINKEDIN-POST.md).

## How the simulation was assessed
1. Defined scope and plausible assets/threats.
2. Scored inherent likelihood and impact (1–5) and documented assumed controls.
3. Scored residual likelihood and impact after assumed controls, without treating missing evidence as proof of operation.
4. Assigned accountable risk owners, dated treatment plans and acceptance authorities.
5. Performed a synthetic IAM sample review and vendor due diligence review.
6. Mapped a **selected subset**, not the entirety, of HIPAA and SOC 2 requirements to simulated control design and evidence gaps.
7. Summarized decision points for executive management.

## Repository integrity
All names, customer counts, findings, meeting outcomes and sample evidence identifiers are fabricated. **Simulated evidence is not auditor-validated evidence.** Cross-references are for internal case-study traceability. Ratings and deadlines are scenario assumptions, not observations about any actual organization.

## References
- [HHS HIPAA Security Rule](https://www.hhs.gov/hipaa/for-professionals/security/index.html)
- [HHS Business Associates](https://www.hhs.gov/hipaa/for-professionals/covered-entities/business-associates/index.html)
- [NIST CSF 2.0](https://www.nist.gov/cyberframework)
- [AICPA SOC 2](https://www.aicpa-cima.com/resources/landing/system-and-organization-controls-soc-suite-of-services)
- [ISO/IEC 27001 overview](https://www.iso.org/standard/27001)

**Prepared by:** Independent GRC portfolio author | **Version:** 1.0 | **Scenario date:** 2026-10-17

## Quality-control note (2026-10-17)
The treatment plan and risk register have been reconciled to the three removal decisions in the six-record IAM sample. Monthly privileged reviews and quarterly certification are distinguished. Evidence is simulated or missing; residual risk scores are provisional. Vendor contractual and assurance approval gates are documented separately.
