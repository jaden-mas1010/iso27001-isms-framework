# Risk Treatment Plan  
## ISO/IEC 27001:2022 – Clause 6.1.3

This plan defines how NovaPay will treat identified information security risks and which controls will be applied.

---

# 1. Treatment Options  
NovaPay uses four treatment options:

- **Reduce** – Implement controls to lower risk  
- **Avoid** – Stop the risky activity  
- **Transfer** – Use insurance or suppliers  
- **Accept** – Approve residual risk  

---

# 2. Risk Treatment Table

| Risk ID | Risk Description | Treatment | Annex A Controls Applied | Owner | Deadline | Status | Evidence |
|---------|------------------|-----------|---------------------------|--------|----------|---------|----------|
| R‑001 | Phishing due to weak email filtering | Reduce | A.8.7, A.8.16 | SOC Lead | 30 days | In Progress | Email Filter Config |
| R‑002 | Malware due to outdated patches | Reduce | A.8.8, A.8.9 | IT Ops | 14 days | In Progress | Patch Logs |
| R‑003 | Privilege abuse from excessive admin rights | Reduce | A.8.2, A.8.3 | CTO | 45 days | Planned | IAM Review |
| R‑004 | Cloud misconfigurations | Reduce | A.8.9, A.8.10 | DevOps | 30 days | In Progress | Terraform Scan |
| R‑005 | Supplier breach risk | Transfer + Reduce | A.5.19–A.5.23 | Procurement | 60 days | In Progress | Supplier Audit |
| R‑006 | Unencrypted employee devices | Reduce | A.8.11 | IT Ops | Completed | Completed | Encryption Logs |
| R‑007 | Unauthorized access to source code | Reduce | A.8.2, A.8.3 | Dev Lead | 30 days | In Progress | GitHub Audit |
| R‑008 | DoS attack due to no rate limiting | Reduce | A.8.20 | Network Team | 45 days | Planned | Firewall Config |
| R‑009 | Insider threat to HR data | Reduce | A.8.2, A.8.3 | HR Manager | 30 days | Planned | Access Review |
| R‑010 | Ransomware risk due to non‑isolated backups | Reduce | A.8.13 | IT Ops | 30 days | In Progress | Backup Audit |

---

# 3. Control Mapping  
Each treatment action must map to Annex A controls.

Examples:

- **A.8.7** – Protection against malware  
- **A.8.2** – Identity and access management  
- **A.8.3** – Privileged access management  
- **A.8.11** – Secure device configuration  
- **A.5.19–A.5.23** – Supplier security  
- **A.8.20** – Network security  
- **A.8.13** – Backup security  

---

# 4. Approval  
High‑risk treatments require CEO approval.  
Medium‑risk treatments require ISMS Manager approval.

---

# 5. Review  
This plan must be reviewed:

- Quarterly  
- After major incidents  
- Before certification audits  
