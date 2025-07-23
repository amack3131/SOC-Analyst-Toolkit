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
- [🚀 Features & Usage](#-features--usage)

---

## 🧠 Analyst Mindset

Insight into how I approach incidents, from alert triage to threat hunting and post-incident reporting.

- 📌 Alert Prioritization Framework (CVSS + TTPs)
- 🧭 Triage Flowchart
- 🔄 Escalation & Closure Protocol

---

## 🔍 Investigation Tools

| Tool | Purpose | Link |
|------|---------|------|
| Wireshark | Packet analysis | [Docs](https://www.wireshark.org/docs/) |
| Sysmon | Endpoint logging | [Sysmon Config](https://github.com/SwiftOnSecurity/sysmon-config) |
| Velociraptor | Threat hunting | [GitHub](https://github.com/Velocidex/velociraptor) |

---

## ⚙️ Automation & Scripts

- `soc-toolkit.py` – A Python utility that includes:
  - ✅ IP reputation checking
  - ✅ WHOIS lookups
  - ✅ File hash analysis via VirusTotal
  - ✅ Email header parsing

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

- 🚨 Phishing Email Response
- 🐚 Reverse Shell Detection
- 🔐 Privilege Escalation Investigation

---

## 🧪 Labs & Projects

- **Incident Response Simulation**: [Lab1-IncidentResponse.md](labs/Lab1-IncidentResponse.md)
- **SIEM Threat Hunting**: Splunk dashboards from internship
- **Detection Engineering**: Custom alerts for lateral movement

---

## 📎 Reference Materials

- 🧾 Josh Madakor – Professional Reference (Image in `/reference`)
- 🧠 [MITRE ATT&CK Navigator](https://mitre-attack.github.io/attack-navigator/)
- 📄 Resume + Interview Prep [Coming Soon]

---

## 🚀 Features & Usage

### 🔧 Features

| Function   | Description |
|------------|-------------|
| `--ip`     | Checks IP reputation using AbuseIPDB |
| `--whois`  | Performs WHOIS lookup on a domain or IP |
| `--hash`   | Queries VirusTotal to check if a file hash is malicious |
| `--email`  | Parses raw email headers and extracts useful investigation info |

---

### 📌 Usage Examples

```bash
# IP reputation check
python soc-toolkit.py --ip 8.8.8.8

# WHOIS lookup
python soc-toolkit.py --whois google.com

# Hash check
python soc-toolkit.py --hash 44d88612fea8a8f36de82e1278abb02f

# Email header parser
python soc-toolkit.py --email "C:\Users\You\Documents\sample-header.txt"
