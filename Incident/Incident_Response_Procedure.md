# Incident Response Procedure  
## ISO/IEC 27001:2022 – Annex A.5.24

This procedure defines the step-by-step actions NovaPay must take to detect, contain, eradicate, and recover from information security incidents.

---

# 1. Purpose  
To provide a structured and repeatable process for responding to security incidents.

---

# 2. Scope  
Applies to all NovaPay systems, employees, contractors, cloud environments, and third-party services.

---

# 3. Incident Response Phases  

## 3.1 Identification  
- SOC detects alert via SIEM/EDR/WAF/IAM  
- Validate if the event is a true incident  
- Record initial details (time, system, user, logs)  
- Assign Incident Severity (Low/Medium/High/Critical)

**Outputs:**  
- Incident Ticket Created  
- Initial Evidence Collected  

---

## 3.2 Containment  

### Short-Term Containment  
- Block malicious IPs  
- Disable compromised accounts  
- Isolate infected devices  
- Stop harmful processes  

### Long-Term Containment  
- Apply firewall rules  
- Patch vulnerable systems  
- Strengthen authentication  
- Restrict access  

**Outputs:**  
- Spread of incident stopped  
- Systems stabilized  

---

## 3.3 Eradication  
- Remove malware  
- Delete malicious files  
- Revoke unauthorized access  
- Fix misconfigurations  
- Apply security patches  

**Outputs:**  
- Root cause removed  
- Vulnerabilities eliminated  

---

## 3.4 Recovery  
- Restore systems from clean backups  
- Validate system integrity  
- Monitor for recurrence  
- Re-enable services gradually  

**Outputs:**  
- Systems fully operational  
- Monitoring active  

---

## 3.5 Lessons Learned  
Conduct a post-incident review within 7 days:

- What happened?  
- What worked well?  
- What failed?  
- What controls need improvement?  
- Update policies, procedures, and training  

**Outputs:**  
- Incident Report  
- Updated controls  
- Improved processes  

---

# 4. Severity Levels  

| Level | Description | Examples |
|-------|-------------|----------|
| Low | Minimal impact | Single failed login |
| Medium | Limited impact | Malware blocked by EDR |
| High | Major impact | Successful phishing attack |
| Critical | Severe impact | Ransomware, data breach |

---

# 5. Communication & Escalation  

### Internal  
- SOC → Incident Manager  
- Incident Manager → IT Ops  
- High/Critical → Senior Management  

### External  
- Customers (if affected)  
- Regulators (GDPR 72-hour rule)  
- Suppliers (if involved)  

---

# 6. Evidence Handling  
- Preserve logs  
- Capture screenshots  
- Export SIEM alerts  
- Maintain chain of custody  
- Store evidence securely  

---

# 7. Documentation  
Every incident must include:

- Incident Ticket  
- Timeline  
- Evidence  
- Actions taken  
- Final report  
- Lessons learned  

---

# 8. Review  
This procedure must be reviewed:

- Annually  
- After major incidents  
- Before certification audits  
