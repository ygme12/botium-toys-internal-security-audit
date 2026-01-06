# Controls Assessment Checklist

| Control | Category | Type | Present (Yes/No) | Notes / Recommendation |
|---------|---------|------|-----------------|----------------------|
| Least Privilege | Administrative | Preventative | No | Employees currently have full access to sensitive data. Implement role-based access control. |
| Disaster recovery plans | Administrative / Operational | Corrective | No | No plans or backups exist. Recommend developing DR plan and regular backup schedule. |
| Password policies | Administrative | Preventative | Partial | Policy exists but does not meet modern complexity standards; implement enforcement. |
| Separation of duties | Administrative | Preventative | No | Not implemented. Recommend defining clear responsibilities to reduce risk. |
| Firewall | Technical | Preventative | Yes | Firewall blocks traffic per security rules. |
| Intrusion Detection System (IDS) | Technical | Detective | No | IDS not installed. Recommend deploying IDS for real-time threat detection. |
| Backups | Operational | Corrective | No | Critical data not backed up. Implement regular backup schedule. |
| Antivirus software | Technical | Preventative | Yes | Installed and monitored regularly. |
| Manual monitoring/maintenance for legacy systems | Operational | Detective | Partial | Monitoring occurs but lacks schedule and clear methods. |
| Encryption | Technical | Preventative | No | Cardholder data and sensitive info unencrypted. Recommend full encryption. |
| Password management system | Technical / Administrative | Preventative | No | No centralized system; implement to enforce policy and improve productivity. |
| Locks (office, storefront, warehouse) | Physical | Preventative | Yes | Proper physical security measures in place. |
| CCTV surveillance | Physical | Detective | Yes | Functioning and up-to-date CCTV system. |
| Fire detection/prevention | Physical | Preventative | Yes | Fire alarms and sprinklers installed and functional. |

# Compliance Checklist

| Regulation | Best Practice | Present (Yes/No) | Notes / Recommendation |
|------------|---------------|-----------------|----------------------|
| PCI DSS | Only authorized users have access to customers’ credit card information | No | Restrict access to cardholder data. |
| PCI DSS | Credit card info is securely stored, accepted, processed, transmitted internally | No | Data not encrypted; implement full PCI-compliant environment. |
| PCI DSS | Implement data encryption procedures for transactions and storage | No | Encryption missing; implement AES-256 encryption. |
| PCI DSS | Adopt secure password management policies | Partial | Password policy weak; implement centralized enforcement. |
| GDPR | E.U. customers’ data is kept private/secured | Partial | Privacy policies exist; ensure enforcement. |
| GDPR | Notify E.U. customers within 72 hours if data compromised | Yes | Plan exists. |
| GDPR | Ensure data is properly classified and inventoried | No | Full data inventory and classification recommended. |
| GDPR | Enforce privacy policies, procedures, and processes | Partial | Policies exist; ensure enforcement and training. |
| SOC Type 1/2 | User access policies are established | Partial | Policies exist but not fully enforced; implement audit trail. |
| SOC Type 1/2 | Sensitive data (PII/SPII) is confidential/private | Partial | Encryption missing; restrict access. |
| SOC Type 1/2 | Data integrity is ensured | Yes | Controls in place to validate accuracy and completeness. |
| SOC Type 1/2 | Data is available to authorized users | Yes | Availability maintained for authorized personnel. |

