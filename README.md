# Ramdoot Solutions — Compliance & Security Documentation Suite

## Overview

This directory contains a comprehensive compliance documentation suite covering:

- **SOC 2 Readiness Documentation** — Trust Services Criteria mapping, control matrix, evidence register
- **SOC 1 Readiness Documentation** — Internal controls framework for ICFR
- **NISP** — Network & Information Security Policy (overarching security policy)
- **24 Security Policies** — Covering access control, encryption, incident response, SDLC, and more
- **10 Operational Procedures** — Step-by-step procedures for onboarding, offboarding, change management, etc.
- **11 Governance Registers** — Risk register, vendor register, asset register, policy register, etc.
- **3 Evidence Documents** — Evidence index, request list, and cross-framework mapping
- **Gap Analysis** — Current state assessment against SOC 2, SOC 1, and NISP requirements
- **Management Decisions** — 32 unresolved decisions requiring management input

## Important Disclaimers

1. **These documents do NOT constitute SOC 1 or SOC 2 certification, attestation, or audit reports.** They are internal readiness documentation prepared for Ramdoot Solutions' compliance program.

2. **All documents are in Draft status** and require management review, completion of placeholder items (marked as `[TO BE COMPLETED BY RAMDOOT SOLUTIONS]`), and formal approval.

3. **No evidence has been fabricated.** Where evidence is required but not available, it is marked as `REQUIRED` with placeholder links.

4. **The Secureframe SOC 2 Evidence Collection Spreadsheet** was used as a reference for evidence requirements. Secureframe is credited as the source of the reference template, not as the owner of these documents.

## Directory Structure

```
compliance/
├── index.html                          # Main compliance library home page
├── gap-analysis.html                   # Control & evidence readiness assessment
├── management-decisions-required.html  # 32 pending management decisions
├── README.md                           # This file
│
├── assets/
│   ├── compliance.css                  # Shared stylesheet
│   ├── print.css                       # A4 print-optimized stylesheet
│   └── logo-placeholder.svg           # Logo placeholder (replace with actual)
│
├── soc2/
│   ├── index.html                      # SOC 2 document index
│   ├── soc2-readiness-report.html      # RS-SOC2-001 — Readiness assessment
│   ├── system-description.html         # RS-SOC2-002 — System description
│   ├── trust-services-criteria.html    # RS-SOC2-003 — TSC mapping
│   ├── control-matrix.html             # RS-SOC2-004 — Control matrix (40+ controls)
│   └── evidence-register.html          # RS-SOC2-005 — Evidence register (80+ items)
│
├── soc1/
│   ├── index.html                      # SOC 1 document index
│   ├── soc1-readiness-report.html      # RS-SOC1-001 — Readiness report
│   ├── internal-controls-framework.html # RS-SOC1-002 — COSO-aligned framework
│   └── control-matrix.html             # RS-SOC1-003 — SOC 1 control matrix
│
├── nisp/
│   └── nisp.html                       # RS-NISP-001 — Overarching security policy
│
├── security/                           # 24 security policies (RS-POL-001 through RS-POL-024)
│   ├── information-security-policy.html
│   ├── access-control-policy.html
│   ├── password-authentication-policy.html
│   ├── acceptable-use-policy.html
│   ├── asset-management-policy.html
│   ├── data-classification-policy.html
│   ├── data-retention-policy.html
│   ├── encryption-policy.html
│   ├── vulnerability-management-policy.html
│   ├── patch-management-policy.html
│   ├── secure-development-policy.html
│   ├── change-management-policy.html
│   ├── logging-monitoring-policy.html
│   ├── incident-response-policy.html
│   ├── business-continuity-policy.html
│   ├── disaster-recovery-policy.html
│   ├── backup-policy.html
│   ├── vendor-management-policy.html
│   ├── risk-management-policy.html
│   ├── privacy-data-protection-policy.html
│   ├── physical-security-policy.html
│   ├── remote-work-policy.html
│   ├── employee-security-policy.html
│   └── termination-offboarding-policy.html
│
├── governance/                         # 11 governance documents
│   ├── code-of-conduct.html            # RS-GOV-001
│   ├── compliance-policy.html          # RS-GOV-002
│   ├── roles-responsibilities.html     # RS-GOV-003
│   ├── risk-register.html              # RS-REG-001
│   ├── vendor-register.html            # RS-REG-002
│   ├── asset-register.html             # RS-REG-003
│   ├── access-review-register.html     # RS-REG-004
│   ├── incident-register.html          # RS-REG-005
│   ├── change-register.html            # RS-REG-006
│   ├── training-register.html          # RS-REG-007
│   └── policy-register.html            # RS-REG-008
│
├── procedures/                         # 10 operational procedures
│   ├── employee-onboarding.html        # RS-PRO-001
│   ├── employee-offboarding.html       # RS-PRO-002
│   ├── access-request-procedure.html   # RS-PRO-003
│   ├── privileged-access-procedure.html # RS-PRO-004
│   ├── incident-response-procedure.html # RS-PRO-005
│   ├── vulnerability-remediation-procedure.html # RS-PRO-006
│   ├── change-release-procedure.html   # RS-PRO-007
│   ├── backup-restore-procedure.html   # RS-PRO-008
│   ├── vendor-onboarding-procedure.html # RS-PRO-009
│   └── annual-risk-assessment-procedure.html # RS-PRO-010
│
└── evidence/                           # Evidence management
    ├── evidence-index.html             # RS-EV-IDX-001
    ├── evidence-request-list.html      # RS-EV-REQ-001
    └── evidence-mapping.html           # RS-EV-MAP-001
```

## How to Open Documents

1. Open `compliance/index.html` in any modern web browser (Chrome, Firefox, Edge, Safari)
2. Navigate using the card-based interface to any document
3. Each document includes a navigation bar with links back to the home page and related sections

## How to Export HTML to PDF

1. Open the desired document in a web browser
2. Press `Ctrl+P` (Windows/Linux) or `Cmd+P` (Mac)
3. Select "Save as PDF" as the destination
4. The print stylesheet automatically formats for A4 paper with:
   - Professional page margins (18mm top/bottom, 16mm sides)
   - Confidentiality footer on every page
   - Page numbers (where browser CSS supports it)
   - Table header repetition across page breaks
   - Navigation elements hidden
   - Black-and-white readable output

## Which Documents Require Management Approval

**All documents** are currently in Draft status. Before they become effective:

1. Review and complete all `[TO BE COMPLETED BY RAMDOOT SOLUTIONS]` placeholders
2. Management must review and approve each policy document
3. The Information Security Officer (to be appointed) must own the security policies
4. Board/management committee must review the SOC 2 scope and SOC 1 applicability decisions

See `management-decisions-required.html` for the full list of 32 pending decisions.

## What Evidence Remains Missing

**All evidence items** are marked as `REQUIRED`. No operating evidence has been collected yet. Before engaging an auditor:

1. Complete the management decisions (scope, categories, audit period)
2. Implement critical gap remediation items (see `gap-analysis.html`)
3. Begin operating controls for the defined audit period (minimum 3 months for Type II)
4. Collect evidence per the `evidence/evidence-request-list.html`
5. Store evidence with version control and access tracking

## Why These Documents Do Not Constitute SOC Certification

- SOC 1 and SOC 2 reports can only be issued by a licensed CPA firm performing an independent attestation engagement
- These documents represent Ramdoot Solutions' internal readiness preparation
- Having comprehensive documentation is a prerequisite for, but does not replace, an independent audit
- The readiness documentation demonstrates intent and framework alignment, not attested compliance

## What Is Required Before Engaging an Auditor

1. **Management decisions resolved** — Complete all 32 decisions in the management decisions document
2. **Policies approved** — All 24 security policies reviewed, completed, and formally approved
3. **Critical gaps remediated** — At minimum: MFA implemented, data-at-rest encryption enabled, centralized logging deployed, incident response plan operational
4. **Evidence collection period** — Minimum 3 months (for Type II) of operating evidence collected
5. **Internal readiness review** — Self-assessment confirming all controls are operating as designed
6. **Audit firm selected** — CPA firm with SOC attestation experience engaged
7. **Scope confirmed** — System boundaries, Trust Services Categories, and audit period finalized with the audit firm

## Document ID Scheme

| Prefix | Category | Example |
|--------|----------|---------|
| RS-SOC2-xxx | SOC 2 Documents | RS-SOC2-001 |
| RS-SOC1-xxx | SOC 1 Documents | RS-SOC1-001 |
| RS-NISP-xxx | NISP | RS-NISP-001 |
| RS-POL-xxx | Security Policies | RS-POL-001 |
| RS-PRO-xxx | Procedures | RS-PRO-001 |
| RS-GOV-xxx | Governance Documents | RS-GOV-001 |
| RS-REG-xxx | Registers | RS-REG-001 |
| RS-EV-xxx | Evidence Items | RS-EV-001 |
| RS-GAP-xxx | Gap Analysis | RS-GAP-001 |
| RS-MGT-xxx | Management Documents | RS-MGT-001 |

## Reference

The SOC 2 evidence requirements in this suite are based on the *SOC 2 Evidence Collection Spreadsheet* provided by Secureframe as a reference template. Secureframe is credited as the source of the evidence checklist framework; all resulting documents are authored by and for Ramdoot Solutions.
