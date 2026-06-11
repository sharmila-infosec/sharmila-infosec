# Hi there, I'm Sharmila! 👋
🔐 Aspiring Cybersecurity Professional  
📚 Currently completing Google Cybersecurity Certificate  
🌍 Passionate about protecting people and data online  

---

## 🚀 About Me
- 🎯 Currently learning **Security Auditing, Risk Assessment & Compliance**
- 🌱 Growing my skills in **Linux, SQL, Python & Network Security**
- 💼 Building a professional cybersecurity portfolio
- 🤝 Open to **entry level cybersecurity opportunities**

---

## 🛠️ Skills & Tools
![Security Auditing](https://img.shields.io/badge/-Security%20Auditing-blue)
![NIST CSF](https://img.shields.io/badge/-NIST%20CSF-green)
![PCI DSS](https://img.shields.io/badge/-PCI%20DSS-red)
![GDPR](https://img.shields.io/badge/-GDPR-orange)
![Linux](https://img.shields.io/badge/-Linux-yellow)
![SQL](https://img.shields.io/badge/-SQL-lightblue)
![Python](https://img.shields.io/badge/-Python-purple)
![tcpdump](https://img.shields.io/badge/-tcpdump-darkblue)
![Network Security](https://img.shields.io/badge/-Network%20Security-teal)

---

## 📂 Featured Projects

| Project | Description |
|---------|-------------|
| [🔍 Botium Toys Security Audit](https://github.com/sharmila-infosec/cybersecurity-portfolio/blob/main/security-audits/botium-toys-audit.md) | Internal IT audit using NIST CSF framework |
| [🌐 Network Traffic Analysis — DNS & ICMP Incident](https://github.com/sharmila-infosec/cybersecurity-incident-report) | Analyzed tcpdump logs to identify DNS/UDP port 53 failure causing website outage |

---

## 🌐 Network Traffic Analysis — DNS & ICMP Incident Report

### 📋 Overview
Analyzed a real-world style cybersecurity incident where users were unable 
to access **www.yummyrecipesforme.com** due to a DNS service failure.
Captured and interpreted network traffic logs using **tcpdump** to identify 
the root cause.

### 🔍 What Was Analyzed
- Captured UDP/DNS requests sent from client to DNS server
- Identified repeated ICMP error messages: **"udp port 53 unreachable"**
- Traced the failure back to the DNS server at IP **203.0.113.2**

### 🛠️ Tools & Protocols Used
- **tcpdump** — Network packet capture and analysis
- **UDP** — Protocol used for DNS requests
- **ICMP** — Protocol that returned the error responses
- **DNS** — Service affected (Port 53)

### 📌 Key Findings
- DNS requests from `192.51.100.15` to `203.0.113.2` failed repeatedly
- UDP port 53 was unreachable on the DNS server
- ICMP returned the same error 3 times confirming the outage
- Website was completely inaccessible due to DNS resolution failure

### 🔎 Possible Root Causes
- DNS service was down or misconfigured on the server
- Firewall rule blocking inbound traffic to UDP port 53
- DNS server was overwhelmed or unresponsive

### 💡 What I Learned
- How to read and interpret **tcpdump** network logs
- How **DNS and ICMP protocols** interact in the TCP/IP model
- How to identify, analyze and document cybersecurity incidents
- How to write a professional **cybersecurity incident report**

---

## 📊 GitHub Stats
![Sharmila's GitHub Stats](https://github-readme-stats.vercel.app/api?username=sharmila-infosec&show_icons=true&theme=dark)

---

## 📬 Connect With Me
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-blue?logo=linkedin)](your-linkedin-url)

---

⭐ *"Security is not a product, but a process"* — Bruce Schneier
