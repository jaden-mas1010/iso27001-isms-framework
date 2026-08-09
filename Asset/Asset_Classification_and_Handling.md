# Asset Classification and Handling  
## ISO/IEC 27001:2022 – Annex A.5.12

---

# 1. Purpose  
To ensure NovaPay’s information assets are classified according to sensitivity and handled appropriately throughout their lifecycle.

---

# 2. Scope  
This document applies to:

- All information assets listed in the Asset Inventory  
- All employees, contractors, and third‑party service providers  
- All data stored, processed, or transmitted by NovaPay  

---

# 3. Classification Levels  

NovaPay uses four classification levels:

### 3.1 Public  
Information intended for public release.  
**Examples:** Marketing materials, public website content.

### 3.2 Internal  
Information for internal use only.  
**Examples:** Internal documentation, non-sensitive operational data.

### 3.3 Confidential  
Sensitive business information requiring protection.  
**Examples:** Source code, financial reports, internal system configurations.

### 3.4 Highly Confidential  
Information that could cause severe harm if disclosed.  
**Examples:** Customer PII, authentication secrets, payment data.

---

# 4. Classification Criteria  

Assets are classified based on:

- Sensitivity  
- Regulatory requirements  
- Business impact  
- Confidentiality, integrity, and availability needs  
- Risk of unauthorized disclosure  

---

# 5. Handling Requirements  

## 5.1 Public  
- No special handling required  
- Must be approved before release  

## 5.2 Internal  
- Store in internal systems only  
- Access restricted to employees  
- No external sharing without approval  

## 5.3 Confidential  
- Must be encrypted at rest and in transit  
- Access granted on a need‑to‑know basis  
- Must be stored in secure systems  
- Sharing requires manager approval  

## 5.4 Highly Confidential  
- Strong encryption required  
- MFA required for access  
- Logging and monitoring mandatory  
- Must not be stored on personal devices  
- Sharing prohibited unless contractually required  
- Must follow secure deletion procedures  

---

# 6. Handling by Asset Type  

### 6.1 Hardware  
- Laptops must be encrypted  
- Servers must be in secure environments  
- Devices must be wiped before disposal  

### 6.2 Software  
- Access controlled via IAM  
- Secrets stored in secure vaults  
- Updates applied regularly  

### 6.3 Cloud Assets  
- Follow cloud security baseline  
- Enforce encryption and IAM policies  
- Enable logging and monitoring  

### 6.4 Information/Data  
- Classified according to sensitivity  
- Protected according to classification level  
- Backed up according to DR requirements  

### 6.5 Third‑Party Services  
- Must meet NovaPay’s security requirements  
- Must have continuity and recovery capabilities  
- Must be included in supplier risk assessments  

---

# 7. Storage Requirements  

| Classification | Storage Requirements |
|----------------|-----------------------|
| Public | Standard storage |
| Internal | Internal systems only |
| Confidential | Encrypted storage |
| Highly Confidential | Encrypted + access logging + MFA |

---

# 8. Transmission Requirements  

- Use TLS 1.2+ for all data transfers  
- Highly Confidential data must use secure channels only  
- No sending sensitive data via personal email  

---

# 9. Access Control Requirements  

- Access must follow the Access Control Policy  
- Owners approve access  
- Privileged access must be monitored  
- Access must be removed during offboarding  

---

# 10. Retention & Disposal  

- Retention must follow legal and business requirements  
- Highly Confidential data must use secure deletion  
- Backups must follow DR retention rules  

---

# 11. Review  
This document must be reviewed:

- Annually  
- After major organisational changes  
- Before certification audits  

---

# 12. Approval  

**ISMS Manager:**  
Name: ____________________  
Signature: ________________  
Date: _____________________  

**CTO / Senior Management:**  
Name: ____________________  
Signature: ________________  
Date: _____________________  
