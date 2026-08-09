# Network Security Policy
## ISO/IEC 27001:2022 Information Security Management System

### 1. Purpose
This Network Security Policy defines the requirements for securing organisational 
networks, preventing unauthorised access, and protecting systems from network‑based 
threats. It ensures compliance with ISO/IEC 27001:2022 Annex A network security controls.

---

### 2. Scope
This policy applies to:
- All organisational networks, firewalls, routers, switches, and wireless systems  
- All cloud, on‑premises, and hybrid network environments  
- All employees, contractors, and third‑party providers  
- All systems transmitting or receiving organisational data  

---

### 3. Network Security Principles

#### **Defense in Depth**
Multiple layers of security must protect network infrastructure.

#### **Least Privilege**
Network access must be restricted to the minimum required.

#### **Segmentation**
Critical systems must be isolated from general user networks.

#### **Secure Configuration**
Network devices must follow hardened configuration standards.

---

### 4. Network Segmentation & Zoning
Networks must be segmented into zones such as:
- Public / DMZ  
- Internal corporate network  
- Restricted / sensitive systems  
- Production vs. development environments  

Traffic between zones must be controlled using firewalls and access control lists (ACLs).

---

### 5. Firewall & Gateway Requirements

#### **5.1 Configuration**
- Firewalls must deny all traffic by default (“default deny”).  
- Only approved ports, protocols, and IP ranges may be allowed.  
- Rules must be documented and reviewed at least quarterly.

#### **5.2 Monitoring**
- Firewall logs must be collected and monitored.  
- Alerts must be generated for suspicious or blocked activity.

#### **5.3 Change Control**
Firewall changes must follow the Change Management Policy.

---

### 6. Secure Network Configuration

- Network devices must use secure management protocols (SSH, HTTPS).  
- Default credentials must be changed before deployment.  
- Unused services and ports must be disabled.  
- Network time must be synchronised using NTP.  
- Configuration backups must be encrypted and stored securely.

---

### 7. Wireless Network Security

- Wireless networks must use WPA3 or equivalent strong encryption.  
- Guest Wi‑Fi must be isolated from internal networks.  
- Hidden SSIDs must be used for sensitive environments.  
- Wireless access must require authentication and follow least privilege.

---

### 8. Remote Access Security

- Remote access must use VPN or encrypted tunnels.  
- MFA must be enforced for all remote connections.  
- Remote sessions must be logged and monitored.  
- Split tunneling must be disabled unless approved.

---

### 9. Network Monitoring & Detection

- IDS/IPS or equivalent monitoring must be deployed for critical systems.  
- Network traffic must be monitored for anomalies.  
- Alerts must be integrated with incident response workflows.  
- Logs must be retained for audit and investigation.

---

### 10. Protection Against Network Threats

- Anti‑malware and endpoint protection must be deployed.  
- Network‑based attacks (DDoS, scanning, brute force) must be detected and mitigated.  
- Rate limiting and throttling must be used where appropriate.  
- Cloud networks must use security groups and network ACLs.

---

### 11. Third‑Party & Cloud Networks

- Cloud network configurations must follow the same security principles.  
- Third‑party connections must be approved, documented, and monitored.  
- Supplier networks must meet contractual security requirements.

---

### 12. Incident Response Integration
Network security incidents must be handled under the Incident Response Policy, including:
- Suspicious traffic  
- Unauthorised access  
- Firewall breaches  
- Wireless compromise  

---

### 13. Compliance
Non‑compliance may result in:
- Revocation of network access  
- Disciplinary action  
- Contract termination (for third parties)

---

### 14. Review
This policy will be reviewed annually or after major changes to network infrastructure.

---

### 15. Approval
Approved by senior management as part of the ISMS governance framework.
