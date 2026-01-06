# Risk Assessment

## Overview
Current security posture at Botium Toys shows inadequate asset management and gaps in controls and compliance. Risk to critical assets is significant due to the lack of controls, proper encryption, access policies, and disaster recovery plans.

## Identified Risks

| Risk | Likelihood | Impact | Risk Score | Notes |
|------|------------|--------|------------|-------|
| Unauthorized access to customer PII/SPII and cardholder data | High | High | 8 | All employees currently have access to sensitive data; lack of least privilege enforcement. |
| Weak password policies and lack of centralized management | Medium | Medium | 6 | Nominal password complexity; recovery process affects productivity. |
| Lack of encryption for stored cardholder data | High | High | 8 | Customer payment info is stored locally without encryption. |
| No intrusion detection system (IDS) | High | Medium | 7 | No automated detection of potential attacks. |
| Lack of disaster recovery and backups | High | High | 9 | No schedule or plans for critical system recovery. |
| Legacy system monitoring inconsistencies | Medium | Medium | 6 | Monitoring occurs but schedule and methods unclear. |
| Partial compliance with GDPR and PCI DSS | Medium | High | 7 | Notification plan exists, but other controls are missing or insufficient. |

## Comments
- Potential business impact is medium for individual asset loss, high for regulatory fines.  
- Controls exist in some areas (firewall, antivirus, physical security), but significant gaps remain.  
