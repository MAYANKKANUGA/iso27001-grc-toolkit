# Multiframework Control Mapping

**Organisation:** ABC India Pvt. Ltd.
**Version:** 1.0
**Date:** March 2025
**Author:** Mayank Kanuga

---

## Overview

This document maps ISO 27001:2022 Annex A controls to NIST 
Cybersecurity Framework (CSF) and SOC 2 Trust Services Criteria, 
demonstrating how a single control implementation can satisfy 
multiple framework requirements simultaneously.

---

## Framework Overview

| Framework | Purpose | Audience |
|-----------|---------|----------|
| ISO 27001:2022 | ISMS certification standard | Global organisations |
| NIST CSF | Cybersecurity risk framework | US government and industry |
| SOC 2 | Service organisation controls | SaaS and cloud companies |

---

## Control Mapping Table

| ISO 27001 Control | ISO Title | NIST CSF | SOC 2 Criteria |
|-------------------|-----------|----------|----------------|
| A.5.1 | IS Policies | ID.GV-1 | CC1.3 |
| A.5.2 | IS Roles | ID.GV-2 | CC1.2 |
| A.5.9 | Asset Inventory | ID.AM-1 | CC6.1 |
| A.5.12 | Information Classification | ID.AM-5 | CC6.1 |
| A.5.15 | Access Control | PR.AC-1 | CC6.2 |
| A.5.16 | Identity Management | PR.AC-6 | CC6.2 |
| A.5.17 | Authentication | PR.AC-7 | CC6.3 |
| A.5.19 | Supplier Security | ID.SC-1 | CC9.2 |
| A.5.23 | Cloud Security | PR.AC-3 | CC6.6 |
| A.5.24 | Incident Management | RS.RP-1 | CC7.3 |
| A.5.26 | Incident Response | RS.MI-1 | CC7.4 |
| A.5.29 | Business Continuity | RC.RP-1 | A1.2 |
| A.6.3 | Security Awareness | PR.AT-1 | CC2.2 |
| A.6.7 | Remote Working | PR.AC-3 | CC6.6 |
| A.7.1 | Physical Perimeters | PR.AC-2 | CC6.4 |
| A.8.2 | Privileged Access | PR.AC-4 | CC6.3 |
| A.8.5 | Secure Authentication | PR.AC-7 | CC6.3 |
| A.8.7 | Malware Protection | DE.CM-4 | CC6.8 |
| A.8.8 | Vulnerability Management | ID.RA-1 | CC7.1 |
| A.8.9 | Configuration Management | PR.IP-1 | CC6.1 |
| A.8.12 | Data Leakage Prevention | PR.DS-5 | CC6.7 |
| A.8.13 | Backup | PR.IP-4 | A1.2 |
| A.8.15 | Logging | DE.CM-1 | CC7.2 |
| A.8.16 | Monitoring | DE.CM-7 | CC7.2 |
| A.8.20 | Network Security | PR.AC-5 | CC6.6 |
| A.8.24 | Cryptography | PR.DS-1 | CC6.1 |
| A.8.25 | Secure Development | PR.IP-2 | CC8.1 |
| A.8.29 | Security Testing | DE.CM-8 | CC4.1 |
| A.8.32 | Change Management | PR.IP-3 | CC8.1 |

---

## Key Mapping Insights

### 1. Access Control — Triple Coverage
ISO A.5.15 + A.5.16 + A.5.17 maps to NIST PR.AC-1/6/7 
and SOC 2 CC6.2/6.3 — implementing these three controls 
satisfies access requirements across all three frameworks.

### 2. Incident Response — Triple Coverage
ISO A.5.24 + A.5.26 maps to NIST RS.RP-1 + RS.MI-1 
and SOC 2 CC7.3 + CC7.4 — one IR procedure satisfies all.

### 3. Logging and Monitoring — Triple Coverage
ISO A.8.15 + A.8.16 maps to NIST DE.CM-1 + DE.CM-7 
and SOC 2 CC7.2 — CloudTrail + GuardDuty satisfies all three.

---

## Conclusion

Organisations implementing ISO 27001:2022 gain approximately 
70% coverage of NIST CSF and 65% coverage of SOC 2 Trust 
Services Criteria as a by-product — significantly reducing 
the effort required to achieve multiple framework compliance.

---

## Document Control

| Field | Details |
|-------|---------|
| Version | 1.0 |
| Author | Mayank Kanuga |
| Review Date | March 2026 |
| Classification | Internal |