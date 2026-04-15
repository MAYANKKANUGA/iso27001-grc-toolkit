# Statement of Applicability (SoA)

**Organisation:** ABC India Pvt. Ltd.
**Version:** 1.0
**Date:** March 2025
**Author:** Mayank Kanuga
**Standard:** ISO/IEC 27001:2022 — Clause 6.1.3

---

## 1. Introduction

This Statement of Applicability documents the selection and 
justification of ISO 27001:2022 Annex A controls for 
ABC India Pvt. Ltd. Each control is assessed for applicability 
based on risk assessment results, legal requirements, and 
business objectives.

---

## 2. Control Selection Legend

| Symbol | Meaning |
|--------|---------|
| YES | Control is applicable and implemented |
| PARTIAL | Control is applicable but partially implemented |
| NO | Control is not applicable — with justification |

---

## 3. Annex A Controls — SoA

### Theme 1 — Organisational Controls (A.5)

| Control | Title | Applicable | Justification | Implementation Status |
|---------|-------|------------|---------------|----------------------|
| A.5.1 | Policies for IS | YES | Required for ISMS foundation | PARTIAL |
| A.5.2 | IS roles and responsibilities | YES | Required for accountability | NOT STARTED |
| A.5.3 | Segregation of duties | YES | Prevents fraud in payment processing | PARTIAL |
| A.5.4 | Management responsibilities | YES | Required for leadership commitment | NOT STARTED |
| A.5.5 | Contact with authorities | YES | Required for incident response | NOT STARTED |
| A.5.6 | Contact with interest groups | YES | Required for threat intelligence | NOT STARTED |
| A.5.7 | Threat intelligence | YES | Required for proactive security | NOT STARTED |
| A.5.8 | IS in project management | YES | Required for secure development | NOT STARTED |
| A.5.9 | Asset inventory | YES | Required for risk assessment | PARTIAL |
| A.5.10 | Acceptable use | YES | Required for all staff | PARTIAL |
| A.5.11 | Return of assets | YES | Required for HR process | IMPLEMENTED |
| A.5.12 | Information classification | YES | Required for data protection | NOT STARTED |
| A.5.13 | Labelling | YES | Required after classification | NOT STARTED |
| A.5.14 | Information transfer | YES | Required for data sharing | PARTIAL |
| A.5.15 | Access control | YES | Critical for payment systems | PARTIAL |
| A.5.16 | Identity management | YES | Critical for all systems | PARTIAL |
| A.5.17 | Authentication information | YES | Required for password management | PARTIAL |
| A.5.18 | Access rights | YES | Required for least privilege | PARTIAL |
| A.5.19 | Supplier IS | YES | Third-party payment gateways | NOT STARTED |
| A.5.20 | Supplier agreements | YES | Required for contracts | NOT STARTED |
| A.5.21 | ICT supply chain | YES | Required for cloud providers | NOT STARTED |
| A.5.22 | Supplier monitoring | YES | Required for ongoing assurance | NOT STARTED |
| A.5.23 | IS for cloud services | YES | AWS is primary infrastructure | NOT STARTED |
| A.5.24 | IS incident management | YES | Required for response capability | PARTIAL |
| A.5.25 | Assessment of IS events | YES | Required for triage | PARTIAL |
| A.5.26 | Response to incidents | YES | Required for containment | PARTIAL |
| A.5.27 | Learning from incidents | YES | Required for improvement | NOT STARTED |
| A.5.28 | Collection of evidence | YES | Required for forensics | NOT STARTED |
| A.5.29 | IS during disruption | YES | Required for continuity | NOT STARTED |
| A.5.30 | ICT readiness for BC | YES | Required for recovery | NOT STARTED |
| A.5.31 | Legal requirements | YES | RBI and PDPB compliance | PARTIAL |
| A.5.32 | Intellectual property | YES | Source code protection | IMPLEMENTED |
| A.5.33 | Protection of records | YES | Required for audit trail | PARTIAL |
| A.5.34 | Privacy and PII | YES | Customer data protection | NOT STARTED |
| A.5.35 | Independent IS review | YES | Required for assurance | NOT STARTED |
| A.5.36 | Compliance with policies | YES | Required for governance | NOT STARTED |
| A.5.37 | Documented procedures | YES | Required for operations | PARTIAL |

### Theme 2 — People Controls (A.6)

| Control | Title | Applicable | Justification | Status |
|---------|-------|------------|---------------|--------|
| A.6.1 | Screening | YES | Required for all new hires | PARTIAL |
| A.6.2 | Terms of employment | YES | Security responsibilities in contracts | PARTIAL |
| A.6.3 | Awareness and training | YES | Required for all staff | PARTIAL |
| A.6.4 | Disciplinary process | YES | Required for policy violations | IMPLEMENTED |
| A.6.5 | Termination responsibilities | YES | Required for offboarding | PARTIAL |
| A.6.6 | NDA agreements | YES | Required for confidentiality | IMPLEMENTED |
| A.6.7 | Remote working | YES | Staff work remotely post-COVID | NOT STARTED |
| A.6.8 | IS event reporting | YES | Required for incident detection | NOT STARTED |

### Theme 3 — Physical Controls (A.7)

| Control | Title | Applicable | Justification | Status |
|---------|-------|------------|---------------|--------|
| A.7.1 | Physical perimeters | YES | Office security required | IMPLEMENTED |
| A.7.2 | Physical entry | YES | Access control required | IMPLEMENTED |
| A.7.3 | Securing offices | YES | Required for asset protection | IMPLEMENTED |
| A.7.4 | Physical monitoring | YES | CCTV required | PARTIAL |
| A.7.5 | Physical threats | YES | Fire, flood protection required | PARTIAL |
| A.7.6 | Secure areas | YES | Server room security | PARTIAL |
| A.7.7 | Clear desk | YES | Required for confidentiality | NOT STARTED |
| A.7.8 | Equipment siting | YES | Required for protection | IMPLEMENTED |
| A.7.9 | Off-premises assets | YES | Laptops taken offsite | NOT STARTED |
| A.7.10 | Storage media | YES | USB and media control | NOT STARTED |
| A.7.11 | Supporting utilities | YES | UPS and power protection | IMPLEMENTED |
| A.7.12 | Cabling security | YES | Network cabling protection | IMPLEMENTED |
| A.7.13 | Equipment maintenance | YES | Required for availability | PARTIAL |
| A.7.14 | Secure disposal | YES | Hard drive wiping required | NOT STARTED |

### Theme 4 — Technological Controls (A.8)

| Control | Title | Applicable | Justification | Status |
|---------|-------|------------|---------------|--------|
| A.8.1 | User endpoint devices | YES | Laptops and mobiles | PARTIAL |
| A.8.2 | Privileged access | YES | Admin accounts on AWS | NOT STARTED |
| A.8.3 | Information access restriction | YES | Role-based access required | PARTIAL |
| A.8.4 | Access to source code | YES | Code repository access | IMPLEMENTED |
| A.8.5 | Secure authentication | YES | MFA required for all systems | PARTIAL |
| A.8.6 | Capacity management | YES | AWS resource monitoring | PARTIAL |
| A.8.7 | Protection against malware | YES | Endpoint protection required | PARTIAL |
| A.8.8 | Technical vulnerabilities | YES | Patch management required | NOT STARTED |
| A.8.9 | Configuration management | YES | AWS Config required | NOT STARTED |
| A.8.10 | Information deletion | YES | Data retention policy required | NOT STARTED |
| A.8.11 | Data masking | YES | PII masking in test environments | NOT STARTED |
| A.8.12 | Data leakage prevention | YES | Customer data protection | NOT STARTED |
| A.8.13 | Information backup | YES | Critical for recovery | PARTIAL |
| A.8.14 | Redundancy | YES | HA required for payments | PARTIAL |
| A.8.15 | Logging | YES | CloudTrail and audit logs | PARTIAL |
| A.8.16 | Monitoring | YES | GuardDuty and Security Hub | NOT STARTED |
| A.8.17 | Clock synchronisation | YES | Required for log correlation | IMPLEMENTED |
| A.8.18 | Privileged utility programs | YES | Admin tools control | NOT STARTED |
| A.8.19 | Software installation | YES | Unauthorised software control | PARTIAL |
| A.8.20 | Network security | YES | VPC and firewall required | PARTIAL |
| A.8.21 | Network services security | YES | AWS network controls | NOT STARTED |
| A.8.22 | Network segregation | YES | Dev/Prod separation | NOT STARTED |
| A.8.23 | Web filtering | YES | Internet access control | NOT STARTED |
| A.8.24 | Cryptography | YES | Encryption for data at rest | NOT STARTED |
| A.8.25 | Secure development | YES | SDLC security required | NOT STARTED |
| A.8.26 | Application security | YES | API security required | NOT STARTED |
| A.8.27 | Secure architecture | YES | AWS architecture review | NOT STARTED |
| A.8.28 | Secure coding | YES | Developer training required | NOT STARTED |
| A.8.29 | Security testing | YES | Pentest required | NOT STARTED |
| A.8.30 | Outsourced development | NO | All development in-house | N/A |
| A.8.31 | Dev/test/prod separation | YES | Environment separation | PARTIAL |
| A.8.32 | Change management | YES | Change control required | PARTIAL |
| A.8.33 | Test information | YES | Test data management | NOT STARTED |
| A.8.34 | IS during audit | YES | Audit protection required | NOT STARTED |

---

## 4. Document Control

| Field | Details |
|-------|---------|
| Version | 1.0 |
| Author | Mayank Kanuga |
| Review Date | March 2026 |
| Classification | Confidential |