# 🛡️ SOC Analyst & Cybersecurity Investigation Portfolio

![Role](https://img.shields.io/badge/Target_Role-SOC_Analyst_L1-0078D4?style=for-the-badge)
![Focus](https://img.shields.io/badge/Focus-Blue_Team_%26_Incident_Response-2EA44F?style=for-the-badge)
![Labs](https://img.shields.io/badge/Completed_Investigations-Hands--on_Labs-orange?style=for-the-badge)

**Oputa Chinazar Ernestina** | Cybersecurity & SOC Operations Practitioner  

Welcome to my central security operations portfolio. This repository serves as an executive index of my hands-on security investigations[span_0](start_span)[span_0](end_span). Every lab demonstrates practical Tier-1/Tier-2 defensive workflows—including SIEM log ingestion, endpoint telemetry correlation, threat hunting, malware triage, phishing header forensics, and actionable remediation mapping[span_1](start_span)[span_1](end_span).

---

## 🛠️ SOC Core Competencies & Technical Matrix

| Security Domain | Operational Capabilities & Telemetry | Tools & Frameworks |
| :--- | :--- | :--- |
| **SIEM & Log Monitoring** | Agent deployment, alert rule validation, Windows Security & PowerShell log correlation (`Event IDs 1, 4624, 4625, 4104, 4720`) | Wazuh SIEM, Windows Event Viewer, Sysmon |
| **Threat Hunting & IR** | Process lineage inspection, brute-force attack tracking, cross-timezone log normalization (`UTC` vs `WAT`) | Wazuh Threat Hunting, MITRE ATT&CK |
| **Phishing & Threat Intel** | SMTP header hop analysis, SPF/DMARC validation, URL detonation, IOC extraction & defanging | VirusTotal, AbuseIPDB, WHOIS, URLScan.io, MXToolbox |
| **Malware Triage** | Static hash verification, dynamic sandbox behavioral telemetry, shadow copy & persistence detection | ANY.RUN, Hybrid Analysis, VirusTotal |
| **Web & App Defense** | Vulnerability validation, CVSS v3.1 risk scoring, WAF rule & defensive detection engineering[span_2](start_span)[span_2](end_span)[span_3](start_span)[span_3](end_span)[span_4](start_span)[span_4](end_span) | Burp Suite, OWASP Top 10, bWAPP[span_5](start_span)[span_5](end_span) |

---

## 📂 Master Investigation Index (Hands-On Labs)

| # | Investigation / Lab Title | SOC Focus Area | Primary Tools & Telemetry | Report |
| :--- | :--- | :--- | :--- | :--- |
| **01** | **Wazuh SIEM Deployment & Brute-Force Detection** | SIEM Engineering & Alerting | Wazuh SIEM, Windows Agent, Rule `60122` | [View Report](https://github.com/oputaernestina321-netizen/Wazuh_SIEM_Home_Lab) |
| **02** | **SOC Incident Response: Brute-Force Attack** | Incident Response & Forensics | Wazuh SIEM, Windows Event Logs (`4625`/`4624`) | [View Report](https://github.com/oputaernestina321-netizen/soc-incident-response-bruteforce-analysis) |
| **03** | **Sysmon & Wazuh Threat Hunting Lab** | Endpoint Threat Hunting | Sysmon (`Event ID 1`), Wazuh SIEM, PowerShell | [View Report](https://github.com/oputaernestina321-netizen/sysmon_threat_hunting_siem) |
| **04** | **Windows Event Log & PowerShell SIEM Lab** | Windows Endpoint Forensics | Event Viewer (`4624, 4625, 4104, 4720`), PowerShell | [View Report](https://github.com/oputaernestina321-netizen/SIEM-Home-Lab) |
| **05** | **WannaCry Ransomware Malware Triage SOP** | Malware Analysis & IOCs | VirusTotal, ANY.RUN, Hybrid Analysis | [View Report](https://github.com/oputaernestina321-netizen/malware-analysis-wannacry) |
| **06** | **Phishing Email Header & OSINT Investigation** | Email Security & Blue Team Triage | MXToolbox, VirusTotal, URLScan.io, SPF/DMARC | [View Report](https://github.com/oputaernestina321-netizen/phishing_email_analysis) |
| **07** | **Threat Intelligence & Phishing Triage Lab** | Threat Intel & Reputation Triage | VirusTotal, WHOIS, AbuseIPDB, Kaspersky | [View Report](https://github.com/oputaernestina321-netizen/Threat-Intel-Phishing-Analysis) |
| **08** | **RDP Brute-Force Simulation & Detection** | Attack Emulation & Alerting | Kali Linux (Hydra), Wazuh SIEM, Windows Logs | [View Report](https://github.com/oputaernestina321-netizen/Brute_Force_Attack_Detection) |
| **09** | **bWAPP Web Vulnerability Assessment** | Web App Security & WAF Defense[span_6](start_span)[span_6](end_span)[span_7](start_span)[span_7](end_span) | Burp Suite, OWASP Top 10, CVSS v3.1[span_8](start_span)[span_8](end_span) | [View Report](https://github.com/oputaernestina321-netizen/bWAPP-Web-Vulnerability-Assessment) |

---

## 📋 Documentation Standard Across All Reports
Every repository linked above follows a standardized SOC reporting structure:
* **Executive Summary & Incident Scope:** Clear business and technical context[span_9](start_span)[span_9](end_span).
* **Verified Visual Evidence:** High-resolution screenshots of SIEM dashboards, raw event logs, packet/header traces, and sandbox detonations[span_10](start_span)[span_10](end_span).
* **Extracted IOCs & Telemetry:** Defanged URLs, hashes (`SHA-256`/`MD5`), IP addresses, and Windows Event IDs.
* **Actionable SOC Remediation:** Defensive containment, SIEM/WAF detection rules, and hardening recommendations[span_11](start_span)[span_11](end_span).
