# Information Security Risk Register

**Organisation:** ABC India Pvt. Ltd.
**Version:** 1.0
**Date:** March 2025
**Author:** Mayank Kanuga
**Standard:** ISO/IEC 27001:2022 — Clause 6.1.2

---

## 1. Risk Assessment Methodology

### Likelihood Scale
| Score | Level | Definition |
|-------|-------|------------|
| 1 | Rare | Less than once in 5 years |
| 2 | Unlikely | Once in 2 to 5 years |
| 3 | Possible | Once per year |
| 4 | Likely | Multiple times per year |
| 5 | Almost Certain | Weekly or monthly |

### Impact Scale
| Score | Level | Definition |
|-------|-------|------------|
| 1 | Negligible | No operational impact |
| 2 | Minor | Minor disruption, quickly resolved |
| 3 | Moderate | Significant disruption, hours to resolve |
| 4 | Major | Serious impact, days to resolve |
| 5 | Critical | Business-threatening, regulatory breach |

### Risk Score = Likelihood x Impact
| Score | Rating |
|-------|--------|
| 1 to 4 | Low |
| 5 to 9 | Medium |
| 10 to 14 | High |
| 15 to 25 | Critical |

---

## 2. Asset Inventory

| Asset ID | Asset Name | Type | Owner | Classification |
|----------|-----------|------|-------|----------------|
| A001 | Payment Processing API | Software | CTO | Confidential |
| A002 | Customer Database (RDS) | Data | DBA | Restricted |
| A003 | AWS S3 Buckets | Infrastructure | IT Manager | Confidential |
| A004 | Employee Laptops | Hardware | HR | Internal |
| A005 | Source Code Repository | Software | CTO | Confidential |
| A006 | AWS IAM Credentials | Data | IT Manager | Restricted |
| A007 | Network Infrastructure | Hardware | IT Manager | Internal |
| A008 | Email System | Software | IT Manager | Internal |
| A009 | Backup Systems | Infrastructure | IT Manager | Confidential |
| A010 | Physical Server Room | Physical | Facilities | Internal |

---

## 3. Risk Register

| Risk ID | Asset | Threat | Vulnerability | Likelihood | Impact | Score | Rating | Treatment |
|---------|-------|--------|---------------|------------|--------|-------|--------|-----------|
| R001 | A002 | Unauthorised database access | Weak IAM policies | 4 | 5 | 20 | Critical | Implement least privilege IAM |
| R002 | A003 | S3 bucket public exposure | Misconfigured bucket ACL | 4 | 5 | 20 | Critical | Enable S3 Block Public Access |
| R003 | A006 | AWS credential theft | Hardcoded keys in code | 3 | 5 | 15 | Critical | Implement Secrets Manager |
| R004 | A001 | API brute force attack | No rate limiting | 4 | 4 | 16 | Critical | Implement WAF rate rules |
| R005 | A004 | Ransomware infection | No endpoint protection | 3 | 5 | 15 | Critical | Deploy EDR solution |
| R006 | A002 | Data exfiltration | No DLP controls | 3 | 5 | 15 | Critical | Implement DLP policy |
| R007 | A005 | Source code theft | No MFA on repo access | 3 | 4 | 12 | High | Enforce MFA on GitHub |
| R008 | A001 | SQL injection attack | Unvalidated input | 3 | 4 | 12 | High | Implement input validation |
| R009 | A009 | Backup failure | No backup testing | 3 | 4 | 12 | High | Monthly backup restore test |
| R010 | A007 | Network intrusion | No IDS/IPS deployed | 3 | 4 | 12 | High | Deploy network monitoring |
| R011 | A008 | Phishing attack | No email filtering | 4 | 3 | 12 | High | Implement email security |
| R012 | A004 | Device loss or theft | No disk encryption | 3 | 4 | 12 | High | Enable BitLocker/FileVault |
| R013 | A006 | Insider threat | No access monitoring | 2 | 5 | 10 | High | Enable CloudTrail logging |
| R014 | A003 | Unencrypted data at rest | No S3 encryption | 3 | 4 | 12 | High | Enable SSE-KMS on all buckets |
| R015 | A001 | DDoS attack | No Shield protection | 3 | 4 | 12 | High | Enable AWS Shield Standard |
| R016 | A007 | Unauthorised network access | No network segmentation | 2 | 4 | 8 | Medium | Implement VPC segmentation |
| R017 | A004 | Malware infection | Outdated antivirus | 3 | 3 | 9 | Medium | Update and automate AV |
| R018 | A010 | Unauthorised physical access | Weak access control | 2 | 4 | 8 | Medium | Implement badge access |
| R019 | A005 | Accidental code deletion | No version control policy | 2 | 3 | 6 | Medium | Enforce branching policy |
| R020 | A008 | Email data breach | Unencrypted email | 2 | 3 | 6 | Medium | Implement TLS for email |

---

## 4. Risk Treatment Plan

| Risk ID | Treatment Option | Control Reference | Owner | Target Date | Status |
|---------|-----------------|-------------------|-------|-------------|--------|
| R001 | Mitigate — enforce least privilege | A.5.15, A.8.2 | IT Manager | 30 days | Open |
| R002 | Mitigate — Block Public Access | A.5.23, A.8.20 | IT Manager | 7 days | Open |
| R003 | Mitigate — Secrets Manager | A.8.24 | CTO | 14 days | Open |
| R004 | Mitigate — WAF rate rules | A.8.20, A.8.21 | IT Manager | 14 days | Open |
| R005 | Mitigate — deploy EDR | A.8.7 | IT Manager | 30 days | Open |
| R006 | Mitigate — DLP controls | A.8.12 | IT Manager | 60 days | Open |
| R007 | Mitigate — enforce MFA | A.8.5 | CTO | 7 days | Open |
| R008 | Mitigate — input validation | A.8.26 | CTO | 30 days | Open |
| R009 | Mitigate — backup testing | A.8.13 | IT Manager | 30 days | Open |
| R010 | Mitigate — IDS deployment | A.8.16 | IT Manager | 45 days | Open |

---

## 5. Document Control

| Field | Details |
|-------|---------|
| Version | 1.0 |
| Author | Mayank Kanuga |
| Review Date | March 2026 |
| Classification | Confidential |