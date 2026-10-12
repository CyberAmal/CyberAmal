
# Hello, I'm Amal

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Amal%20Varghese-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/amalbuilds/)

MSc Cyber Security graduate focused on **SOC Operations, Threat Detection, Incident Investigation, Cloud Security, Network Security, and Security Engineering**.

I build hands-on cybersecurity labs to develop practical experience with **SIEM, detection engineering, KQL, IDS/IPS, network traffic analysis, security-event correlation, and defensive security controls**.

My portfolio includes both **on-premises enterprise SOC infrastructure** and **Microsoft Azure cloud SIEM monitoring**, with ten completed security investigations across two projects.

---

## Career Objective

My goal is to build a career in **SOC Analysis, Cyber Security Analysis, and Security Engineering**, with a long-term interest in cloud security.

I focus on designing security environments, generating controlled attack simulations, analysing telemetry, developing detections, investigating incidents, and validating defensive controls.

---

## Featured Projects

### 01 - Enterprise SOC & Network Security Lab

**Status: Completed**

An enterprise-style SOC and network security environment designed for **security monitoring, threat detection, incident investigation, network segmentation, and defensive security validation**.

**Technologies**

`Splunk` `Wazuh` `Zeek` `Suricata` `pfSense` `Proxmox` `MITRE ATT&CK` `Tailscale`

**Implemented**

- pfSense firewall and inter-VLAN security policies
- VLAN-based network segmentation
- Dedicated network IDS sensor with SPAN/port mirroring
- Zeek network security monitoring
- Suricata IDS/IPS and custom detection rules
- Splunk SIEM and Wazuh endpoint monitoring
- Wazuh-to-Splunk alert integration
- Centralised SOC monitoring dashboards
- Secure remote access using Tailscale
- Controlled security simulations and incident investigations

**Completed Investigations**

| Investigation | Focus |
|---|---|
| 01 — Phishing | Phishing analysis and investigation |
| 02 — SSH Brute Force | Authentication attack detection |
| 03 — Network Reconnaissance | Network scanning and traffic analysis |
| 04 — Cross-VLAN Access | Firewall policy and segmentation validation |
| 05 — Suricata IDS/IPS | Intrusion detection and prevention validation |

**[View Enterprise SOC & Network Security Lab](https://github.com/CyberAmal/enterprise-soc-security-lab)**

---

### 02 - Microsoft Sentinel Cloud SOC & Threat Detection Lab

**Status: Completed — 5 Security Investigations**

A hybrid cloud SOC project integrating a **Proxmox-hosted Windows 11 endpoint with Microsoft Azure** using Azure Arc and Azure Monitor Agent.

Developed custom KQL detection rules, collected Windows security telemetry, and validated automatic alert and incident generation in Microsoft Sentinel.

**Technologies**

`Microsoft Sentinel` `Azure Arc` `Azure Monitor Agent` `Log Analytics` `KQL` `Microsoft Defender` `Windows 11` `Proxmox`

**Implemented**

- Microsoft Sentinel and Azure Log Analytics
- Azure Arc integration for a non-Azure Windows endpoint
- Azure Monitor Agent and Data Collection Rules
- Windows Security, PowerShell, and Defender event collection
- Custom KQL scheduled analytics rules
- Windows security event correlation
- SID-based correlation of account creation and privileged group membership events
- Automatic security alert and incident generation
- Host entity mapping and incident validation
- Troubleshooting Windows audit policies, Data Collection Rules, and Sentinel detection issues
- MITRE ATT&CK technique mapping

**Completed Investigations**

| Investigation | Event IDs | MITRE ATT&CK |
|---|---|---|
| 01 — Repeated Windows Failed Logons | 4625 | T1110 |
| 02 — Suspicious PowerShell Activity | 4104 | T1059.001 |
| 03 — Microsoft Defender Malware Detection | 1116, 1117 | Endpoint Detection |
| 04 — Account Creation & Privilege Escalation | 4720, 4732 | T1136.001, T1098 |
| 05 — Scheduled Task Persistence | 4698 | T1053.005 |

**Results:** Five detection scenarios validated, with Microsoft Sentinel incidents generated automatically and the monitored endpoint identified through Host entity mapping.

**[View Microsoft Sentinel Cloud SOC Lab](https://github.com/CyberAmal/microsoft-sentinel-cloud-soc)**

---

## SOC Lab Architecture Overview

```mermaid
flowchart TB
    A["Cybersecurity Home Lab"]

    A --> B["Project 01<br/>Enterprise SOC"]
    A --> C["Project 02<br/>Microsoft Sentinel Cloud SOC"]

    subgraph P1["On-Premises Security Monitoring"]
        D["Proxmox VE"]
        E["pfSense / VLANs"]
        F["Zeek / Suricata"]
        G["Wazuh / Splunk"]
        D --> E
        E --> F
        F --> G
    end

    subgraph P2["Azure Cloud Security Monitoring"]
        H["Windows 11 - Thor"]
        I["Azure Arc / AMA"]
        J["Log Analytics"]
        K["Microsoft Sentinel"]
        L["KQL Analytics Rules"]
        M["Security Incidents"]
        H --> I
        I --> J
        J --> K
        K --> L
        L --> M
    end

    B --> D
    C --> H
```

*The diagram summarises two separate portfolio projects and their monitoring architectures.*

---

## Technical Skills

| Category | Technologies & Skills |
|---|---|
| SIEM & SOC | Microsoft Sentinel, Splunk, Wazuh |
| Detection Engineering | KQL, Security Analytics Rules, Event Correlation |
| Cloud Security | Microsoft Azure, Azure Arc, Azure Monitor, Log Analytics |
| Endpoint Security | Microsoft Defender, Windows Event Logs, PowerShell Logging |
| Network Security | pfSense, VLANs, Zeek, Suricata, Wireshark |
| Incident Response | Alert Triage, Threat Detection, Incident Investigation |
| Security Frameworks | MITRE ATT&CK |
| Systems & Virtualisation | Windows, Linux, Proxmox VE |
| Scripting | Python, PowerShell |

---

## Tools & Technologies

### SIEM & Cloud Security

![Microsoft Sentinel](https://img.shields.io/badge/Microsoft%20Sentinel-Cloud%20SIEM-0078D4?style=for-the-badge)
![Microsoft Azure](https://img.shields.io/badge/Microsoft%20Azure-0078D4?style=for-the-badge)
![KQL](https://img.shields.io/badge/KQL-Detection%20Engineering-5C2D91?style=for-the-badge)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=for-the-badge&logo=splunk&logoColor=white)
![Wazuh](https://img.shields.io/badge/Wazuh-005571?style=for-the-badge)

### Network Security

![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
![Suricata](https://img.shields.io/badge/Suricata-EF3B2D?style=for-the-badge)
![Zeek](https://img.shields.io/badge/Zeek-Network%20Monitoring-6C63A8?style=for-the-badge)
![pfSense](https://img.shields.io/badge/pfSense-Firewall-212121?style=for-the-badge)

### Detection & Analysis

![MITRE ATT&CK](https://img.shields.io/badge/MITRE%20ATT%26CK-Threat%20Analysis-C8102E?style=for-the-badge)
![Microsoft Defender](https://img.shields.io/badge/Microsoft%20Defender-Endpoint%20Security-0078D4?style=for-the-badge)

### Systems & Infrastructure

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Windows](https://img.shields.io/badge/Windows-0078D4?style=for-the-badge&logo=windows&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=for-the-badge&logo=proxmox&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)

### Scripting

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white)

---

## Certifications

![CompTIA Security+](https://img.shields.io/badge/CompTIA-Security%2B-EA1D25?style=for-the-badge)
![CompTIA A+](https://img.shields.io/badge/CompTIA-A%2B-EA1D25?style=for-the-badge)

- **CompTIA Security+**
- **CompTIA A+**
- **Microsoft MTA - Introduction to Programming Using Python**

---

## Hands-On Training

### TryHackMe - SOC Level 1

- Completed **40+ hands-on SOC labs**
- Investigated **15 simulated security incidents**
- Practised SIEM operations, threat detection, and incident response
- Investigated phishing, Windows/Linux security events, and network activity
- Applied MITRE ATT&CK during security investigations

---

## Project Roadmap

| Project | Focus | Status |
|---|---|---|
| 01 - Enterprise SOC & Network Security Lab | SIEM, IDS/IPS, network security, investigations | Completed |
| 02 - Microsoft Sentinel Cloud SOC Lab | Azure monitoring, KQL, detection engineering | Completed |
| 03 - Azure Cloud Security | Identity, network security, monitoring, hardening | Planned |

---

## Education

**MSc Cyber Security with Advanced Research**  
University of Hertfordshire, United Kingdom

**BSc Computer Science**  
University of Calicut, India

---

## Connect With Me

I'm building my career in **SOC Operations, Cyber Security Analysis, and Security Engineering**, supported by practical blue-team and cloud security projects.

[![LinkedIn](https://img.shields.io/badge/Connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/amalbuilds/)
[![GitHub](https://img.shields.io/badge/View%20My%20Projects-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/CyberAmal)
