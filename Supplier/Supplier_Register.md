# Supplier Register  
## ISO/IEC 27001:2022 – Annex A.5.19 – A.5.22

This register lists all suppliers providing services to NovaPay, including their classification, risk level, security posture, and review status.

---

# 1. Purpose  
To maintain a complete and accurate register of all suppliers and ensure they meet NovaPay’s security, compliance, and continuity requirements.

---

# 2. Scope  
This register includes:

- All third‑party service providers  
- All SaaS platforms  
- All cloud providers  
- All outsourced operational or security services  

---

# 3. Supplier Register Table

| Supplier | Service Provided | Classification | Risk Level | Data Sensitivity | Security Certifications | Contract Status | Last Review | Next Review |
|----------|------------------|----------------|------------|-------------------|--------------------------|------------------|-------------|-------------|
| AWS | Cloud Infrastructure | Critical | High | Highly Confidential | ISO 27001, SOC 2 | Active | Jan 2026 | Jan 2027 |
| Stripe | Payment Gateway | Critical | High | Financial Data | PCI‑DSS | Active | Jan 2026 | Jan 2027 |
| Auth0 | Authentication | High | High | PII | ISO 27001 | Active | Jan 2026 | Jan 2027 |
| Microsoft 365 | Email & Docs | High | Medium | Internal/Confidential | ISO 27001 | Active | Feb 2026 | Feb 2027 |
| Slack | Internal Comms | Medium | Medium | Internal | SOC 2 | Active | Feb 2026 | Feb 2027 |
| Notion | Documentation | Low | Low | Internal | SOC 2 | Active | Mar 2026 | Mar 2027 |
| Cloudflare | DNS/WAF | High | High | Public/Internal | ISO 27001 | Active | Jan 2026 | Jan 2027 |
| SendGrid | Email Delivery | Medium | Medium | Internal | SOC 2 | Active | Mar 2026 | Mar 2027 |

---

# 4. Supplier Classification Definitions  

### Critical  
Essential for NovaPay’s core operations. Failure impacts business continuity.

### High  
Processes sensitive data or impacts security posture.

### Medium  
Supports internal operations; limited security impact.

### Low  
Minimal operational or security impact.

---

# 5. Review Requirements  
Suppliers must be reviewed:

- Annually  
- After major incidents  
- After contract changes  
- After significant service outages  

Critical suppliers may require **quarterly** reviews.

---

# 6. Contract Requirements  
All supplier contracts must include:

- Security obligations  
- Data protection clauses  
- Breach notification timelines  
- SLA commitments  
- Right to audit (for critical suppliers)

---

# 7. Evidence Storage  
Supplier documentation must be stored in the ISMS evidence repository:

- Contracts  
- Security certifications  
- Risk assessments  
- Review reports  
- Incident records  

---

# 8. Approval  

**ISMS Manager:**  
Name: ____________________  
Signature: ________________  
Date: _____________________  

**Senior Management:**  
Name: ____________________  
Signature: ________________  
Date: _____________________  
