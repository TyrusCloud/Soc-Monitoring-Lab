# 🛡️ Linux SOC Monitoring Lab & Incident Response 



## 📌 Project Overview
This project simulates a Security Operations Center (SOC) investigation using two Linux virtual machines without SIEM tools.  
An Ubuntu system functions as the SOC monitoring workstation while a RHEL system acts as the compromised endpoint.

The objective was to detect, investigate, and respond to simulated attacks using native Linux logging and analysis tools.

---

## 🎯 Project Objectives
- Simulate reconnaissance and exploitation activity
- Detect brute-force authentication attempts
- Identify unauthorized access
- Detect attacker persistence mechanisms
- Investigate suspicious processes and open ports
- Perform containment and incident response actions
- Conduct manual log analysis without SIEM platforms

---

## 🧱 Lab Architecture

| Role | Operating System | Purpose |
|------|-----------------|---------|
| SOC Server | Ubuntu | Monitoring & Investigation |
| Victim Host | RHEL | Simulated Compromised Endpoint |

Network Setup:
- Both VMs connected to same virtual network
- SSH enabled for remote access simulation

---

## 🛠️ Tools Used
- SSH
- Nmap
- ss
- ps
- grep
- journalctl
- tcpdump
- netstat / ss
- iptables
- Linux authentication logs

---

## 📸 Lab Setup

### Network Verification

Commands Used:
```bash
ip a
ping <rhel-ip>
