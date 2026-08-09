# Cryptography Policy
## ISO/IEC 27001:2022 Information Security Management System

### 1. Purpose
This Cryptography Policy defines the requirements for the use, management, and protection 
of cryptographic controls to ensure confidentiality, integrity, and authenticity of 
information in accordance with ISO/IEC 27001:2022 and ISO/IEC 27002:2022.

---

### 2. Scope
This policy applies to:
- All systems, applications, and services using cryptographic mechanisms  
- All employees, contractors, and third parties handling encrypted data  
- All cryptographic keys, certificates, tokens, and secrets  
- All environments (on‑premises, cloud, hybrid)

---

### 3. Cryptographic Principles

#### **Confidentiality**
Sensitive data must be encrypted at rest and in transit.

#### **Integrity**
Cryptographic hashing must be used to detect unauthorised modification.

#### **Authenticity**
Digital certificates and secure protocols must verify identity and trust.

#### **Key Protection**
Keys must be stored securely and rotated regularly.

---

### 4. Encryption Requirements

#### **4.1 Data in Transit**
All data transmitted over networks must use secure protocols:
- TLS 1.2+  
- SSH v2  
- IPSec  
- HTTPS with strong ciphers  

Unencrypted protocols (FTP, Telnet, HTTP) are prohibited unless encapsulated in secure tunnels.

#### **4.2 Data at Rest**
Sensitive or regulated data must be encrypted using:
- AES‑256 or equivalent  
- FIPS‑approved algorithms where required  

Cloud storage must use provider‑managed or customer‑managed encryption keys.

---

### 5. Key Management

- Keys must be generated using approved cryptographic algorithms.  
- Keys must be stored in secure vaults or Hardware Security Modules (HSMs).  
- Keys must be rotated at least annually or after suspected compromise.  
- Keys must never be hard‑coded in applications or stored in plaintext.  
- Access to keys must follow least privilege and MFA requirements.  

---

### 6. Certificate Management

- Certificates must be issued by trusted Certificate Authorities (CAs).  
- Expiry dates must be monitored to prevent service disruption.  
- Self‑signed certificates are prohibited except for approved internal testing.  
- Private keys must never be shared or transmitted insecurely.  

---

### 7. Hashing Requirements

Approved hashing algorithms:
- SHA‑256  
- SHA‑384  
- SHA‑512  

MD5 and SHA‑1 are prohibited for security‑critical functions.

---

### 8. Secure Protocols

The following protocols must be used for secure communication:
- HTTPS  
- TLS 1.2+  
- SSH  
- SFTP  
- VPN with strong encryption  

Deprecated protocols must be disabled unless required for legacy systems with compensating controls.

---

### 9. Secret & Token Management

- API keys, tokens, and secrets must be stored in secure vaults.  
- Secrets must not be stored in code repositories.  
- Secrets must be rotated regularly.  
- Access to secrets must be logged and monitored.  

---

### 10. Monitoring & Logging

- Cryptographic operations must be logged where feasible.  
- Key access events must be monitored for anomalies.  
- Certificate expiry alerts must be enabled.  

---

### 11. Compliance
Non‑compliance may result in:
- Disciplinary action  
- Revocation of access  
- Contract termination  
- Legal consequences  

---

### 12. Review
This policy will be reviewed annually or after major changes to cryptographic standards or systems.

---

### 13. Approval
Approved by senior management as part of the ISMS governance framework.
