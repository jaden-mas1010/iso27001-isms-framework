# Incident Classification Matrix  
## ISO/IEC 27001:2022 – Annex A.5.24

This matrix defines how NovaPay classifies information security incidents based on impact, likelihood, and business disruption.

---

# 1. Classification Levels

NovaPay uses four severity levels:

| Level | Description | Business Impact | Required Response |
|-------|-------------|-----------------|-------------------|
| **Low** | Minor event, no damage | No disruption | Handled by SOC |
| **Medium** | Noticeable issue | Limited disruption | SOC + IT Ops |
| **High** | Significant incident | Major disruption | Incident Manager + Senior Mgmt |
| **Critical** | Severe incident | Full outage / regulatory impact | Executive Team + Legal + External Reporting |

---

# 2. Classification Criteria

### 2.1 Impact Categories  
Incidents are evaluated across:

- **Confidentiality** – Data exposure  
- **Integrity** – Unauthorized modification  
- **Availability** – System downtime  
- **Regulatory** – GDPR/DPA implications  
- **Financial** – Monetary loss  
- **Reputational** – Customer trust impact  

---

# 3. Incident Classification Table

| Severity | Example Incidents | Indicators | Required Actions |
|----------|-------------------|------------|------------------|
| **Low** | Failed login attempts, blocked malware | No data impact | SOC handles, log only |
| **Medium** | Malware detected & contained, minor misconfigurations | Limited data exposure | SOC + IT Ops, containment within 4 hours |
| **High** | Successful phishing, unauthorized access, partial outage | Data accessed or modified | Incident Manager leads, notify senior management |
| **Critical** | Ransomware, full outage, data breach, GDPR violation | Major data loss or exposure | Executive team involved, legal notified, 72‑hour GDPR reporting |

---

# 4. Response Time Requirements

| Severity | Initial Response | Containment | Full Resolution |
|----------|------------------|-------------|------------------|
| Low | 24 hours | 48 hours | 5 days |
| Medium | 4 hours | 24 hours | 3 days |
| High | 1 hour | 4 hours | 48 hours |
| Critical | Immediate | Immediate | As fast as possible |

---

# 5. Escalation Path

### Low  
SOC → Incident Ticket

### Medium  
SOC → IT Ops → Incident Manager

### High  
SOC → Incident Manager → Senior Management

### Critical  
SOC → Incident Manager → CEO → Legal → External Regulators

---

# 6. Review  
This matrix must be reviewed:

- Annually  
- After major incidents  
- Before certification audits  
