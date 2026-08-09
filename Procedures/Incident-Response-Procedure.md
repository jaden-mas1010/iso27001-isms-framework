# Incident Response Procedure

## Purpose
To ensure NovaPay can detect, respond to, contain, and recover from information security incidents in a structured and effective manner.

## Scope
All employees, contractors, systems, applications, and data assets managed by NovaPay.

## Roles & Responsibilities
- **Incident Manager** – Leads the response effort.
- **SOC / Security Team** – Performs technical investigation and containment.
- **IT Operations** – Supports recovery and system restoration.
- **Communications Lead** – Handles internal and external notifications.
- **Data Protection Officer (DPO)** – Assesses regulatory reporting requirements.

---

## 1. Identification
- Detect incidents via:
  - SOC alerts  
  - SIEM logs  
  - EDR notifications  
  - User reports  
- Classify severity:
  - **Low** – Minor disruption  
  - **Medium** – Noticeable impact  
  - **High** – Major system impact  
  - **Critical** – Data breach or service outage  

---

## 2. Containment
- Isolate affected systems (network segmentation, quarantine).
- Disable compromised accounts.
- Block malicious IPs or domains.
- Capture forensic evidence (logs, memory snapshots).

---

## 3. Eradication
- Remove malware or malicious files.
- Patch exploited vulnerabilities.
- Reset credentials.
- Validate that no persistence mechanisms remain.

---

## 4. Recovery
- Restore systems from backups if needed.
- Validate system integrity and functionality.
- Monitor systems for recurrence.
- Re-enable services gradually.

---

## 5. Lessons Learned
- Conduct a post‑incident review within 5 business days.
- Document root cause.
- Update controls, policies, and procedures.
- Add corrective actions to the ISMS improvement log.

---

## 6. Reporting
- Internal reporting to management within 24 hours.
- Regulatory reporting (GDPR/DPA 2018) within **72 hours** if personal data is involved.
- Customer or supplier notification if required by contract.

---

## Review
This procedure must be reviewed annually or after any major incident.
