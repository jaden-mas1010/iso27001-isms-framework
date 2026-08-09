# Asset Inventory  
## ISO/IEC 27001:2022 – Annex A.5.9, A.5.10, A.5.11, A.5.12

This inventory lists all information assets owned, used, or managed by NovaPay. It includes asset type, owner, classification, location, and protection requirements.

---

# 1. Purpose  
To maintain a complete and accurate inventory of NovaPay’s information assets and ensure they are protected according to their classification and business value.

---

# 2. Scope  
This inventory covers:

- Hardware assets  
- Software assets  
- Cloud resources  
- Databases  
- Network devices  
- Information assets (data)  
- Third‑party services  
- Documentation  

---

# 3. Asset Categories  

### Hardware  
- Laptops  
- Servers  
- Network devices  
- Storage devices  

### Software  
- Internal applications  
- SaaS platforms  
- Security tools  

### Cloud  
- Compute instances  
- Storage buckets  
- Databases  
- Load balancers  

### Information  
- Customer data  
- Employee data  
- Financial data  
- Logs  

### Third‑Party Services  
- Payment gateway  
- Email provider  
- Cloud provider  

---

# 4. Asset Inventory Table

| Asset Name | Type | Owner | Location | Classification | Criticality | Notes |
|------------|------|--------|-----------|----------------|-------------|--------|
| Payment Processing System | Application | CTO | Cloud (AWS) | Confidential | Critical | Handles customer transactions |
| Authentication Service | Application | DevOps Lead | Cloud (AWS) | Confidential | Critical | MFA & login |
| Customer Database | Database | DBA | Cloud (AWS RDS) | Highly Confidential | Critical | Stores customer PII |
| SOC SIEM Platform | SaaS | SOC Lead | Cloud | Confidential | High | Security monitoring |
| Employee Laptops | Hardware | IT Ops | Office | Internal | Medium | Encrypted devices |
| Cloud Infrastructure | Cloud | Cloud Architect | AWS | Internal | High | Core compute/storage |
| Email Provider | Third‑Party | IT Ops | SaaS | Internal | Medium | External dependency |
| Internal Documentation | Information | ISMS Manager | SharePoint | Internal | Low | Policies & procedures |

---

# 5. Asset Ownership  
Each asset must have:

- A designated owner  
- Defined responsibilities  
- Classification level  
- Protection requirements  

Asset owners must review their assets annually.

---

# 6. Classification Levels  

| Level | Description |
|--------|-------------|
| Public | No harm if disclosed |
| Internal | Internal use only |
| Confidential | Sensitive business data |
| Highly Confidential | PII, financial data, regulated data |

---

# 7. Protection Requirements  
All assets must follow:

- Access control policies  
- Encryption requirements  
- Backup requirements  
- Logging & monitoring  
- Supplier security controls (if applicable)  

---

# 8. Review  
This inventory must be reviewed:

- Quarterly  
- After major changes  
- Before certification audits  

---

# 9. Approval  

**ISMS Manager:**  
Name: ____________________  
Signature: ________________  
Date: _____________________  

**CTO / Senior Management:**  
Name: ____________________  
Signature: ________________  
Date: _____________________  
