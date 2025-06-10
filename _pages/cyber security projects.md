---
title: "Cyber Security Projects"
permalink: /cybersecurityprojects/
layouts: posts
author_profile: true
---

## 🏆 Completed CTF Challenges


### 🌐 HTB Academy: Network Traffic Analysis Module

🎲 **Platform**: [Hack The Box Academy](https://academy.hackthebox.com/)  
🏅 **Achievement Badge**: [![Badge Link](https://academy.hackthebox.com/images/badges/network-traffic-analysis.svg)](https://academy.hackthebox.com/achievement/1918558/81)  
🧠 **Focus Areas**:  
- 🔄 OSI & TCP/IP Models  
- 📊 Packet Filtering & Analysis  
- 🔐 Session Decryption  
- 🧰 Practical Traffic Analysis  

🛠️ **Tools Used**:  
- 🖥️ `Tcpdump` – CLI packet capture  
- 🌐 `Wireshark` – GUI protocol analyzer  
- 🔧 `TShark` – Wireshark CLI  
- 📁 `.pcap` Files – Offline inspection

---

### 📝 Summary
**📌 Skills Demonstrated:**
- Network traffic analysis principles
- Tcpdump fundamentals
- Working with Wireshark
- Wireshark filterson

This module introduced me to packet analysis and traffic monitoring. I learned to capture, filter, and interpret network data using industry-standard tools. I also practiced applying filters, identifying protocol behaviors, and decrypting RDP sessions.

---

### 🔍 Key Practical Labs

#### 🧪 Tcpdump Fundamentals
- Captured traffic using `tcpdump -i eth0 -nvXc 100`
- Parsed `.pcap` files with hex/ASCII output via `-Xr`
- Applied filters like `host`, `port`, `not icmp`

#### 🕸️ Wireshark Traffic Analysis
- Used display filters (`http`, `dns`, `ftp-data`)
- Followed TCP streams to extract `Rise-Up.jpg`
- Identified malicious actor: **Bob**

#### 🔐 RDP Decryption & Threat Hunt
- Discovered suspicious RDP session by user: **Bucky**
- Found unauthorized user creation: **Hacker**
- Flagged suspicious port usage: `4444`

---

### 🧠 Key Takeaways

- 💡 Stronger understanding of networking layers and protocols  
- 🧵 Traced sessions and reconstructed traffic streams  
- 🔎 Enhanced ability to recognize traffic anomalies  
- 🛡️ Strengthened foundation in network forensics

---

📌 **View Certificate**: [Click to Open Badge](https://academy.hackthebox.com/achievement/1918558/81)


📸 [Certificate Preview](#) | 📝 [Full Writeup](#)

---

### 🔎 **DNS in Detail**  
**🛠️ Tools Used:** `dig` | `nslookup` | DNSDumpster  
**📌 Skills Demonstrated:**  
- What is DNS
- Domain Hierarchy
- Record Types
- Making a Request

## 🌍 Web Requests 

**Performed comprehensive HTTP protocol analysis through hands-on challenges:**  

### 🔍 Skills Demonstrated
- **HTTP Method Mastery** (GET/POST/PUT/DELETE)  
- **Header Manipulation** (User-Agent, Cookies, Referer)  
- **Status Code Analysis** (200, 301, 403, 500)  
- **Form Data Handling** (URL-encoded vs multipart)  
- **API Endpoint Testing** (RESTful services inspection)  

### 🛠️ Tooling Implementation
```bash
# cURL examples from CTF
curl -X POST -H "User-Agent: CTF-Agent" -d "username=admin" http://target.site/login
curl -i -H "Authorization: Bearer token123" https://api.ctf.site/data
