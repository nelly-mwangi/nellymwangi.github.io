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

---

---

### 🔎 **DNS in Detail**  

🎯 **Platform**: [TryHackMe – DNS in Detail](https://tryhackme.com/room/dnsindetail)  
📚 **Module Summary**:  
Hands-on room focused on understanding DNS mechanics, hierarchy, and exploitation in cybersecurity contexts. Covered how DNS queries are made, record types used, and tools for enumeration and information gathering.

---

### 🛠️ Tools Used
- 🧪 `dig` – DNS query tool  
- 🧾 `nslookup` – Resolve names to IPs  
- 🌐 [DNSDumpster](https://dnsdumpster.com) – Passive DNS recon  

---

### 📌 Skills Demonstrated
- ✅ Understanding the **DNS Protocol** and its role in networking  
- ✅ Exploring the **Domain Hierarchy** (Root > TLD > Subdomain)  
- ✅ Identifying common **Record Types** (A, CNAME, MX, TXT)  
- ✅ Executing **DNS Requests** and interpreting responses  
- ✅ Using OSINT tools to enumerate domain information

---

### 🧠 Practical Examples

```bash
# Lookup A record
dig A tryhackme.com

# Find mail servers (MX record)
dig MX tryhackme.com

# Reverse lookup an IP address
dig -x 10.10.10.10

# nslookup to resolve name
nslookup tryhackme.com

# Subdomain brute-force with DNSDumpster or external tools
  

### 🛠️ Tooling Implementation
```bash
# cURL examples from CTF
curl -X POST -H "User-Agent: CTF-Agent" -d "username=admin" http://target.site/login
curl -i -H "Authorization: Bearer token123" https://api.ctf.site/data

---
---

## 🌐 HTB Academy: Web Requests Module

🎲 **Platform**: [Hack The Box Academy](https://academy.hackthebox.com/)  
🏅 **Achievement Badge**:  
[![HTB Web Requests Badge](https://academy.hackthebox.com/images/badges/web-requests.svg)](https://academy.hackthebox.com/achievement/badge/cb163662-43a1-11f0-bcfdbea50ffe6cb4)  
🔗 [Click to view full certificate](https://academy.hackthebox.com/achievement/badge/cb163662-43a1-11f0-bcfdbea50ffe6cb4)

---

### 📝 Module Overview

This module provided a deep dive into the **HTTP protocol** and how web applications handle requests and responses. I explored the structure of HTTP headers, methods, and payloads — both in theory and practice — and performed hands-on interaction with RESTful APIs.

---

### 🔍 Skills Demonstrated
- 🌐 **Understanding HTTP Protocol**: Request/response cycles and status codes  
- 🧾 **Crafting Web Requests**: Using `curl` and browser developer tools  
- 🔐 **Header Manipulation**: User-Agent, Authorization, Content-Type  
- 🔄 **CRUD API Operations**: GET, POST, PUT, DELETE  
- 🕵️‍♀️ **Web Traffic Inspection**: Analyzing client-server communications  

---

### 🛠️ Tooling Implementation

```bash
# GET request
curl -X GET https://api.example.com/data

# POST request with form data
curl -X POST -d "username=admin&password=1234" https://api.example.com/login

# PUT request to update a resource
curl -X PUT -H "Content-Type: application/json" -d '{"city":"Nairobi"}' https://api.example.com/cities/1

# DELETE request to remove a city
curl -X DELETE https://api.example.com/cities/1
