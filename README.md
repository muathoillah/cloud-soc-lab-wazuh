# Cloud SOC Lab with Wazuh

## Overview
This project demonstrates a cloud-hosted SOC (Security Operations Center) lab built using Wazuh SIEM on an Ubuntu VPS.

The lab was designed for:
- Threat monitoring
- Security event analysis
- Endpoint monitoring
- Authentication failure detection
- Threat hunting

---

## Technologies Used
- Wazuh SIEM
- Ubuntu Server
- Docker
- VPS Infrastructure

---

## Features
- Real-time log monitoring
- SSH brute-force detection
- PAM authentication monitoring
- Threat Hunting dashboard
- MITRE ATT&CK mapping
- Security event visualization

---

## Simulated Attacks
### SSH Brute Force Simulation
```bash
for i in {1..20}; do ssh fakeuser@localhost; done
```

### Privilege Escalation Activity
```bash
sudo su
```

---

## Detection Results
Wazuh successfully detected:
- Failed SSH login attempts
- Non-existent user login attempts
- PAM authentication failures
- Privilege escalation activity

---
---
## Screenshots

### Wazuh Dashboard
![Dashboard](screenshots/dashboard.png)

### Threat Hunting
![Threat Hunting](screenshots/threat-hunting.png)

### Security Alerts
![Alerts](screenshots/alerts.png)

### SSH Brute Force Detection
![SSH Bruteforce](screenshots/ssh-bruteforce.png)

## Skills Demonstrated
- SIEM deployment
- SOC monitoring workflow
- Threat hunting
- Log analysis
- Linux administration
- Security event investigation
