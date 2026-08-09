# Risk Register  
## ISO/IEC 27001:2022 – Clause 6.1

This register documents all identified information security risks, their assessment, treatment, and current status.

---

# 1. Risk Scoring Model  
Risk Score = Likelihood × Impact  
(Scale: 1–5 each)

| Score | Level |
|-------|--------|
| 1–5 | Low |
| 6–12 | Medium |
| 13–25 | High |

---

# 2. Risk Register Table

| ID | Asset | Threat | Vulnerability | Likelihood (1–5) | Impact (1–5) | Risk Score | Risk Level | Treatment | Owner | Status | Evidence |
|----|--------|---------|---------------|------------------|--------------|------------|------------|-----------|--------|---------|----------|
| R‑001 | Customer Data | Phishing | Weak email filtering | 4 | 5 | 20 | High | Reduce | SOC Lead | In Progress | Email Filter Logs |
| R‑002 | Production Servers | Malware | Outdated patches | 3 | 5 | 15 | High | Reduce | IT Ops | In Progress | Patch Reports |
| R‑003 | Admin Accounts | Privilege Abuse | Excessive permissions | 4 | 4 | 16 | High | Reduce | CTO | Planned | IAM Review |
| R‑004 | Cloud Infrastructure | Misconfiguration | Lack of IaC validation | 3 | 4 | 12 | Medium | Reduce | DevOps | In Progress | Terraform Scan |
| R‑005 | Supplier Systems | Data Breach | Weak supplier controls | 3 | 5 | 15 | High | Transfer/Reduce | Procurement | In Progress | Supplier Audit |
| R‑006 | Employee Devices | Data Loss | No encryption | 2 | 4 | 8 | Medium | Reduce | IT Ops | Completed | Device Encryption Logs |
| R‑007 | Source Code | Unauthorized Access | Weak repo permissions | 3 | 3 | 9 | Medium | Reduce | Dev Lead | In Progress | GitHub Audit |
| R‑008 | Network | DoS Attack | No rate limiting | 2 | 5 | 10 | Medium | Reduce | Network Team | Planned | Firewall Config |
| R‑009 | HR Data | Insider Threat | Excessive access | 2 | 5 | 10 | Medium | Reduce | HR Manager | Planned | Access Review |
| R‑010 | Backups | Ransomware | Backup not isolated | 3 | 5 | 15 | High | Reduce | IT Ops | In Progress | Backup Audit |

---

# 3. Risk Treatment Summary  
High risks require immediate treatment.  
Medium risks require planned treatment.  
Low risks may be accepted.

---

# 4. Review  
This risk register must be reviewed:

- Quarterly  
- After major incidents  
- After major changes  
- Before certification audits  
