# Security_Audit
Botium Toys Security Audit
# Botium Toys security audit

This repository contains a scope, goals, and risk assessment for Botium Toys, plus a controls and compliance checklist mapped to administrative, technical, and physical control categories.

## Contents
- Scope, goals, and risk assessment report — [DOCX](./Botium-Toys-Scope-goals-and-risk-assessment-report.docx)
- Control categories and types — [DOCX](./Control-categories.docx)
- Controls and compliance checklist — [DOCX](./Controls%20and%20compliance%20checklist.docx) | [PDF](./Controls%20and%20compliance%20checklist.pdf)

## Executive summary
- Risk score: 8/10 due to inadequate asset management and missing controls.
- Key gaps: Least privilege, separation of duties, IDS, encryption, backups, disaster recovery, password management.
- Strengths: Firewall, antivirus, legacy system monitoring, physical security (locks, CCTV, fire detection), GDPR breach notification plan.

## Controls status (snapshot)
| Control | Status |
|---|---|
| Firewall | Yes |
| Antivirus | Yes |
| Legacy system monitoring | Yes |
| Locks / CCTV / Fire detection | Yes |
| Least privilege | No |
| Separation of duties | No |
| Password policy (current) | No (nominal requirements) |
| Password management system | No |
| IDS | No |
| Backups | No |
| Encryption | No |
| Disaster recovery plans | No |

## Compliance snapshot
- PCI DSS: Not compliant (access controls, encryption, secure environment, password management).
- GDPR: Partially aligned (privacy, 72-hour breach notice, data classification, policies enforced).
- SOC 1/2: Data integrity and availability present; user access and confidentiality controls missing.
