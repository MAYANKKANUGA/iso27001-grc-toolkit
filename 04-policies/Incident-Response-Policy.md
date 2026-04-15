# Incident Response Policy

**Organisation:** ABC India Pvt. Ltd.
**Version:** 1.0
**Date:** March 2025
**Author:** Mayank Kanuga
**Standard:** ISO/IEC 27001:2022 — A.5.24, A.5.25, A.5.26, A.5.27, A.5.28

---

## 1. Purpose
Define the process for detecting, reporting, and responding to 
information security incidents at ABC India Pvt. Ltd.

---

## 2. Incident Classification

| Severity | Definition | Response Time |
|----------|------------|---------------|
| P1 — Critical | Data breach, ransomware, system down | 1 hour |
| P2 — High | Malware, unauthorised access | 4 hours |
| P3 — Medium | Policy violation, phishing attempt | 24 hours |
| P4 — Low | Suspicious activity, minor violation | 72 hours |

---

## 3. Incident Response Lifecycle

### Phase 1 — Preparation
- Maintain incident response team contacts
- Ensure logging enabled on all systems
- Test incident response plan annually

### Phase 2 — Detection and Analysis
- Monitor alerts from GuardDuty, Wazuh, and Splunk
- Triage and classify incident severity
- Document initial findings in incident ticket

### Phase 3 — Containment
- Isolate affected systems immediately
- Preserve evidence before making changes
- Notify senior management for P1 and P2 incidents

### Phase 4 — Eradication
- Remove threat from environment
- Patch vulnerability that was exploited
- Verify threat is fully removed

### Phase 5 — Recovery
- Restore systems from clean backups
- Monitor systems closely post-recovery
- Verify normal operations resumed

### Phase 6 — Lessons Learned
- Conduct post-incident review within 5 days
- Document findings and recommendations
- Update controls and procedures accordingly

---

## 4. Incident Reporting

| Incident Type | Report To | Timeframe |
|--------------|-----------|-----------|
| Data breach | CISO + CEO + RBI | Within 6 hours |
| Ransomware | CISO + CEO | Within 1 hour |
| Unauthorised access | IT Security team | Within 4 hours |
| Phishing attempt | IT Security team | Within 24 hours |

---

## 5. Evidence Collection

All evidence must be collected following forensic best practices:
- Create forensic image before any changes
- Maintain chain of custody documentation
- Store evidence in secure, access-controlled location

---

## 6. Document Control

| Field | Details |
|-------|---------|
| Version | 1.0 |
| Author | Mayank Kanuga |
| Review Date | March 2026 |
| Classification | Confidential |