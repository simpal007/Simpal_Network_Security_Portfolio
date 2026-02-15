# 01 - Enterprise Network Security Lab 🏢🔐

## 📌 Objective

The goal of this project is to build a realistic enterprise-style network security lab to simulate, monitor, and defend against network attacks.

This lab will serve as the foundation for future projects such as:

- Firewall Hardening  
- IDS/IPS Detection  
- SIEM Monitoring  
- Incident Response  

---

## 🏗 Lab Architecture

The lab environment includes

- **Windows Server 2019** (Domain Controller + AD Services)
- **Windows 10 Client** (Domain-joined machine)
- **Kali Linux** (Attacker VM)
- **pfSense Firewall** (Network perimeter security)
- **Splunk SIEM** (Log monitoring and alerting)

---

## 🌐 Network Design

| Device | Role | Example IP |
|--------|------|------------|
| pfSense Firewall | Gateway + Filtering | 192.168.1.1 |
| Windows Server | Domain Controller | 192.168.1.10 |
| Windows Client | Employee Workstation | 192.168.1.20 |
| Kali Linux | Attacker Machine | 192.168.1.30 |
| Splunk Server | Monitoring System | 192.168.1.40 |

---

## 🔧 Tools & Technologies Used

- VirtualBox / VMware  
- pfSense Firewall  
- Windows Server + Active Directory  
- Kali Linux  
- Wireshark  
- Snort IDS (future integration)  
- Splunk SIEM (future integration)

---

## ✅ Planned Security Use Cases

This lab will be used to simulate and detect:

- Port scanning (Nmap)
- Brute-force attacks
- Malware traffic analysis
- Kerberoasting attack detection
- Firewall rule enforcement
- Incident response workflows

---

## 📸 Evidence & Documentation

Screenshots, logs, and configuration files will be added in:

- `screenshots/`
- `configs/`
- `reports/`

---

## 🚧 Project Status

✅ Lab setup started  
🔄 Currently in progress  

---

## 📚 Key Learning Outcomes

Through this lab, I am improving skills in:

- Enterprise network design  
- Security monitoring and logging  
- Network attack detection  
- Defensive security engineering  
