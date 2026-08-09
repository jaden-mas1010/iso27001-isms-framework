# Business Continuity Procedure  
## ISO/IEC 27001:2022 – Annex A.5.29 & A.5.30

This procedure defines how NovaPay activates, manages, and restores business operations during and after disruptive incidents.

---

# 1. Purpose  
To ensure NovaPay can maintain or quickly restore critical business operations following cyberattacks, outages, disasters, or other major disruptions.

---

# 2. Scope  
This procedure applies to:

- All critical business processes  
- All NovaPay systems and applications  
- All cloud environments (AWS/Azure)  
- All employees and contractors  
- All third‑party services supporting critical operations  

---

# 3. Roles & Responsibilities  

### Business Continuity Manager  
- Declares BCP activation  
- Coordinates all continuity activities  
- Communicates with senior management  

### IT Operations  
- Restores systems and infrastructure  
- Executes disaster recovery actions  
- Validates system integrity  

### Communications Lead  
- Manages internal and external communication  
- Approves customer and regulatory notifications  

### ISMS Manager  
- Ensures alignment with ISO 27001  
- Records evidence and updates ISMS documentation  

### System Owners  
- Validate recovery of their systems  
- Support manual fallback operations  

---

# 4. Activation Criteria  
The Business Continuity Plan (BCP) is activated when any of the following occur:

- Critical systems unavailable for **>30 minutes**  
- Cyberattack disrupts operations  
- Major outage affecting customer‑facing services  
- Disaster impacting NovaPay facilities or cloud regions  
- Senior management requests activation  

**Activation must be formally declared by the Business Continuity Manager.**

---

# 5. Communication Procedure  

## 5.1 Internal Communication  
- Notify employees via email, Slack, or emergency channels  
- Provide clear instructions and status updates  
- Restrict unauthorized communication  

## 5.2 External Communication  
- Notify customers if services are impacted  
- Notify suppliers if dependencies are affected  
- Regulatory notification (GDPR 72‑hour rule) if required  
- All communication must be approved by the Communications Lead  

---

# 6. Recovery Actions  

## 6.1 System Recovery  
- Switch to backup systems or failover environments  
- Prioritize restoration of critical services:  
  - Payment processing  
  - Authentication services  
  - Customer portal  
  - SOC monitoring  
- Validate system integrity before returning to production  

## 6.2 Manual Workarounds  
If systems are unavailable:

- Use documented manual processes  
- Log all manual transactions for later reconciliation  
- Assign staff to critical manual functions  

## 6.3 Resource Allocation  
- Reassign staff to critical operations  
- Relocate operations if physical facilities are affected  
- Ensure availability of required tools and communication channels  

---

# 7. Return to Normal Operations  
Once systems are stable:

1. Restore primary systems  
2. Validate full functionality  
3. Reconcile manual work performed  
4. Notify employees and customers  
5. Close BCP activation formally  

---

# 8. Post‑Incident Review  
Within **5 business days**, NovaPay must:

- Conduct a full review of the disruption  
- Identify root cause  
- Document lessons learned  
- Update BCP, DR plans, and related procedures  
- Add corrective actions to the ISMS Improvement Log  

---

# 9. Testing Requirements  
NovaPay must test the Business Continuity Plan:

- **Annually** – full BCP simulation  
- **Quarterly** – partial or tabletop exercises  

Test results must be:

- Documented  
- Reviewed by the ISMS Manager  
- Stored in the ISMS evidence repository  

---

# 10. Review  
This procedure must be reviewed:

- Annually  
- After major disruptions  
- Before certification audits  
