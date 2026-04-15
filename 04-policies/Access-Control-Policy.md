# Access Control Policy

**Organisation:** ABC India Pvt. Ltd.
**Version:** 1.0
**Date:** March 2025
**Author:** Mayank Kanuga
**Standard:** ISO/IEC 27001:2022 — A.5.15, A.5.16, A.5.18, A.8.2, A.8.3, A.8.5

---

## 1. Purpose
Define rules for granting, reviewing, and revoking access to 
ABC India Pvt. Ltd. information systems and data.

---

## 2. Principles

- **Least Privilege** — Users receive minimum access required
- **Need to Know** — Access granted only when business need exists
- **Separation of Duties** — Critical tasks require two people
- **Default Deny** — Access is denied unless explicitly granted

---

## 3. User Access Management

### 3.1 Access Request
All access requests must be submitted via IT helpdesk with 
manager approval before access is granted.

### 3.2 Provisioning
IT team provisions access within 2 business days of approved request.

### 3.3 Access Review
All user access rights must be reviewed every 90 days by system owners.

### 3.4 Revocation
Access must be revoked within 24 hours of employee termination 
or role change.

---

## 4. Password Requirements

| Requirement | Standard |
|-------------|----------|
| Minimum length | 14 characters |
| Complexity | Uppercase, lowercase, number, special character |
| Maximum age | 90 days |
| History | Last 24 passwords cannot be reused |
| MFA | Mandatory for all systems |

---

## 5. Privileged Access

- Privileged accounts must be separate from standard user accounts
- Privileged access must be logged and monitored via CloudTrail
- Shared admin accounts are prohibited
- Privileged sessions must be recorded where possible

---

## 6. Remote Access

- All remote access must use VPN or AWS Systems Manager
- MFA is mandatory for all remote access
- Remote sessions must be encrypted using TLS 1.2 or higher

---

## 7. Document Control

| Field | Details |
|-------|---------|
| Version | 1.0 |
| Author | Mayank Kanuga |
| Review Date | March 2026 |
| Classification | Internal |