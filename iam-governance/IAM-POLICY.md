# Identity and Access Management Policy
**Policy ID NX-SEC-004 | Version 1.0 | Simulated approval: 2026-10-12 | Owner: Noah Williams, IT Director | Approver: Olivia Reed, CISO | Next review: 2027-10-12**

## Purpose and scope
Control workforce, contractor and service access to Nexora AWS, Entra ID, SaaS applications and systems processing ePHI. This fictional approved-style policy is not evidence of actual approval or implementation.

## Requirements
1. **Identity:** Every human user receives a unique identity; shared human accounts are prohibited. HR is authoritative for employment status.
2. **Joiners:** Managers request role-based access in the IT service desk; system owner approves before IT provisions. Standard access must be based on job duties.
3. **Movers:** HR role changes trigger an access reassessment within 2 business days; unneeded permissions must be removed within 5 business days.
4. **Leavers:** HR notifies IT immediately upon confirmed departure; interactive access is disabled no later than termination effective time for involuntary exits and within 4 hours of effective time for routine exits. Tokens and sessions are revoked where supported.
5. **Authentication:** Phishing-resistant MFA is required for privileged users where technically supported; MFA is mandatory for all workforce remote and cloud access. Break-glass accounts are separately controlled, monitored and tested quarterly.
6. **Privilege:** Standing production admin access requires documented CISO exception. Prefer time-bound elevation, separate admin identities and least privilege.
7. **Reviews:** System owners review privileged access monthly and all in-scope workforce access quarterly; reviewers record retain/remove decisions, rationales and evidence of completed revocation.
8. **Service accounts:** Assign named owners, use short-lived credentials where supported, prohibit interactive login and review at least quarterly.
9. **Monitoring:** Log privileged role assignments, access changes and authentication events; send security-relevant events to Sentinel or equivalent.
10. **Exceptions:** A documented business justification, compensating controls, expiry date and CISO approval are required; no permanent exceptions.

## Accountability and enforcement
IT operates provisioning; HR supplies lifecycle events; application owners approve entitlements; Security monitors exceptions; GRC samples review evidence and reports exceptions to the CISO. Noncompliance requires a tracked remediation item and risk escalation.

## Control alignment (illustrative)
HIPAA 45 CFR §164.312(a) access control; §164.308(a)(3) workforce security; §164.308(a)(4) information access management. SOC 2 Security CC6 family. Exact applicability and criterion wording must be verified during formal scoping.
