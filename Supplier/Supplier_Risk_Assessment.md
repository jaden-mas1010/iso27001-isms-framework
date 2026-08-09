# Supplier Risk Assessment  
## ISO/IEC 27001:2022 – Annex A.5.19 – A.5.22

This assessment evaluates the security, continuity, and compliance risks associated with suppliers providing services to NovaPay.

---

# 1. Purpose  
To identify, evaluate, and document risks associated with suppliers and ensure appropriate controls are applied before onboarding and throughout the supplier lifecycle.

---

# 2. Scope  
This assessment covers:

- All suppliers providing services to NovaPay  
- All SaaS platforms, cloud providers, and third‑party tools  
- All outsourced operational, technical, or security functions  

---

# 3. Supplier Risk Categories  

### 3.1 Critical Supplier  
Provides essential services required for NovaPay’s core operations.  
Examples: Cloud provider, payment gateway, authentication provider.

### 3.2 High‑Risk Supplier  
Processes sensitive data or impacts security.  
Examples: SIEM, logging platforms, email provider.

### 3.3 Medium‑Risk Supplier  
Supports internal operations but does not process sensitive data.  
Examples: HR tools, documentation platforms.

### 3.4 Low‑Risk Supplier  
Minimal operational or security impact.  
Examples: Training platforms, non‑technical services.

---

# 4. Risk Assessment Criteria  

Each supplier is evaluated across:

| Category | Description |
|----------|-------------|
| Security Controls | Encryption, access control, monitoring |
| Compliance | ISO 27001, SOC 2, GDPR, PCI‑DSS |
| Data Sensitivity | Type of data processed |
| Operational Impact | Dependency level |
| Continuity & DR | Backup, failover, resilience |
| Incident History | Past breaches or outages |
| Contractual Strength | Security clauses, SLAs |

---

# 5. Supplier Assessment Table

| Supplier | Service Provided | Risk Level | Data Sensitivity | Security Certifications | DR Capability | Final Rating |
|----------|------------------|------------|-------------------|--------------------------|---------------|--------------|
| AWS | Cloud Infrastructure | Critical | Highly Confidential | ISO 27001, SOC 2 | Multi‑region | High |
| Stripe | Payment Gateway | Critical | Financial Data | PCI‑DSS | High | High |
| Auth0 | Authentication | High | PII | ISO 27001 | High | High |
| Microsoft 365 | Email & Docs | High | Internal/Confidential | ISO 27001 | Medium | Medium |
| Slack | Internal Comms | Medium | Internal | SOC 2 | Medium | Medium |
| Notion | Documentation | Low | Internal | SOC 2 | Low | Low |

---

# 6. Risk Scoring Matrix  

| Score | Description |
|--------|-------------|
| 1 | Low Risk |
| 2 | Medium Risk |
| 3 | High Risk |
| 4 | Critical Risk |

Suppliers scoring **3 or 4** require additional controls.

---

# 7. Required Controls Based on Risk Level  

### Critical  
- Contractual security clauses  
- Annual security review  
- DR capability validation  
- Incident reporting requirements  

### High  
- Security certification validation  
- Access control review  
- Monitoring of incidents  

### Medium  
- Basic security review  
- SLA validation  

### Low  
- Standard onboarding checks  

---

# 8. Approval Workflow  

1. Supplier identified  
2. Risk assessment performed  
3. ISMS Manager reviews  
4. Senior management approves  
5. Supplier added to Supplier Register  

---

# 9. Review  
Supplier risk assessments must be reviewed:

- Annually  
- After major supplier changes  
- After incidents involving the supplier  

---

# 10. Approval  

**ISMS Manager:**  
Name: ____________________  
Signature: ________________  
Date: _____________________  

**Senior Management:**  
Name: ____________________  
Signature: ________________  
Date: _____________________  
