# 🛡️ Andon Mack's SOC Analyst Toolkit

![Status](https://img.shields.io/badge/Active-Yes-brightgreen) ![Role](https://img.shields.io/badge/Role-SOC_Analyst-blue)

Welcome to my Security Operations Center (SOC) Analyst Toolkit. This repository contains practical tools, scripts, processes, and resources I’ve used to investigate, triage, and remediate real-world cyber threats.

> 🔐 “Security isn’t just a job — it’s a mindset.” — Andon Mack

---

## 📚 Table of Contents

- [🧠 Analyst Mindset](#-analyst-mindset)
- [🔍 Investigation Tools](#-investigation-tools)
- [⚙️ Automation & Scripts](#️-automation--scripts)
- [📈 SIEM Queries (Splunk, ELK)](#-siem-queries)
- [📓 Playbooks](#-playbooks)
- [🧪 Labs & Projects](#-labs--projects)
- [📎 Reference Materials](#-reference-materials)

---

## 🧠 Analyst Mindset

Insight into how I approach incidents, from alert triage to threat hunting and post-incident reporting.

- 📌 Alert Prioritization Framework (CVSS + TTPs)
- 🧭 Triage Flowchart
- 🔄 Escalation & Closure Protocol

---

## 🔍 Investigation Tools

A list of the tools I use and how I use them.

| Tool | Purpose | Link |
|------|---------|------|
| Wireshark | Packet analysis | [Docs](https://www.wireshark.org/docs/) |
| Sysmon | Endpoint logging | [Sysmon Config](https://github.com/SwiftOnSecurity/sysmon-config) |
| Velociraptor | Threat hunting | [GitHub](https://github.com/Velocidex/velociraptor) |

---

## ⚙️ Automation & Scripts

- `log_parser.py` – Parses Windows event logs for lateral movement indicators
- `ip_reputation_checker.sh` – Bash script that pulls IP info from AbuseIPDB
- `hash_lookup.py` – Automates hash lookups across VirusTotal, Hybrid Analysis, and more

---

## 📈 SIEM Queries

- 🔍 **Splunk Queries**
  - Suspicious PowerShell
  - RDP Brute Force
  - Credential Dumping
- 📦 **ELK Stack Dashboards**
  - Suricata Logs
  - Sysmon Events

---

## 📓 Playbooks

Step-by-step remediation guides.

- 🚨 Phishing Email Response
- 🐚 Reverse Shell Detection
- 🔐 Privilege Escalation Investigation

---

## 🧪 Labs & Projects

Projects based on hands-on labs and real-world investigations.

- **Incident Response Simulation**: [Lab1-IncidentResponse.md](labs/Lab1-IncidentResponse.md)
- **SIEM Threat Hunting**: Splunk dashboards used during internship
- **Detection Engineering**: Custom alerts for lateral movement

---

## 📎 Reference Materials

- 🧾 Josh Madakor – Professional Reference (Image will be in `/reference`)
- 🧠 [MITRE ATT&CK Navigator Layers](https://mitre-attack.github.io/attack-navigator/)
- 📄 Sample Resume + Interview Prep [Coming Soon]

---

## 📬 Contact

📧 andonmack96@gmail.com  
📍 Based in [Your City], Available for Remote & On-Site Work  
🔗 [LinkedIn](https://www.linkedin.com/in/your-profile) | [Twitter](https://twitter.com/yourhandle)

---

> _Security is a journey, not a destination._  
> — Thanks for visiting.
