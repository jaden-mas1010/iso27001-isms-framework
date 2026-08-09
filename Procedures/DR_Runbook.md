# Disaster Recovery Runbook  
## ISO/IEC 27001:2022 – Annex A.5.30

This runbook provides step-by-step technical instructions for restoring NovaPay’s systems, applications, and cloud infrastructure during a disaster.

---

# 1. Activation

**Trigger:** DRP activated by Disaster Recovery Manager.

**Immediate Actions:**
1. Notify IT Ops, DevOps, DBA, SOC teams.
2. Freeze all production deployments.
3. Enable DR communication channel (Slack/Teams/Email).
4. Begin logging all actions in DR Activation Log.

---

# 2. Infrastructure Failover (Cloud)

## 2.1 Switch to Secondary Region
