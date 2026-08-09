# Backup & Restore Procedure

## Purpose
To ensure NovaPay can maintain data availability, integrity, and recoverability through secure and reliable backup processes.

## Scope
All production systems, databases, applications, cloud services, and critical business data.

## Roles & Responsibilities
- **IT Operations** – Performs backups and restores.
- **ISMS Manager** – Ensures compliance with ISO 27001 requirements.
- **System Owners** – Validate backup completeness and recovery success.

---

## 1. Backup Schedule
NovaPay follows a structured backup schedule:

### Daily
- Incremental backups of all critical systems.

### Weekly
- Full backups of servers, databases, and cloud storage.

### Monthly
- Encrypted offsite backups stored in secure cloud vaults.

### Retention
- Daily backups retained for 14 days.
- Weekly backups retained for 8 weeks.
- Monthly backups retained for 12 months.

---

## 2. Backup Storage Requirements
- All backups must be **encrypted at rest** (AES‑256).
- Backup repositories must enforce **access control** and **MFA**.
- Backup storage must be isolated from production systems.
- Backup logs must be retained for **12 months**.

---

## 3. Backup Monitoring
- Automated alerts for failed backups.
- Daily review of backup status dashboard.
- Monthly reporting to ISMS Manager.

---

## 4. Restore Testing
Restore tests must be performed **quarterly**:

### Testing Requirements
- Select a random system or dataset.
- Perform a full restore in a test environment.
- Validate:
  - Data integrity  
  - Application functionality  
  - No corruption  
- Document results in the Restore Test Log.

---

## 5. Restore Process
When a restore is required:

### Step 1 — Identify Backup
- Determine the correct backup version.
- Validate timestamp and integrity.

### Step 2 — Prepare Environment
- Isolate affected system.
- Notify stakeholders.

### Step 3 — Perform Restore
- Restore data from backup repository.
- Validate system functionality.
- Reconnect system to production environment.

### Step 4 — Post‑Restore Validation
- Confirm data accuracy.
- Monitor for anomalies.
- Document the restore event.

---

## 6. Security Requirements
- Backup encryption keys stored in secure key vault.
- No backups stored on personal devices.
- No unencrypted backups permitted.
- Backup access restricted to authorised personnel only.

---

## Review
This procedure must be reviewed annually or after any major incident involving data loss.
