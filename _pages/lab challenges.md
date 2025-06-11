---
layout: single
title: "Lab Challenges"
permalink: /labchallenges/
author_profile: true
---

## Lab Challenges

Explore real-world cybersecurity tasks based on hands-on training and analysis labs. Each challenge below reflects a scenario solved using industry tools and techniques.

---

### 🧪 Challenge: Network Traffic Analysis (HTB Academy)

**Platform**: [Hack The Box Academy](https://academy.hackthebox.com/)  
**Badge**: 🏅 [View Badge](https://academy.hackthebox.com/achievement/1918558/81)

**Focus Areas**:  
OSI & TCP/IP, Packet Filtering, RDP Decryption, Protocol Analysis

**Tools Used**:  
Tcpdump, Wireshark, TShark, `.pcap` files

**Approach**:  
- Captured live traffic with `tcpdump` and analyzed with Wireshark  
- Applied display filters (e.g., `ftp`, `http`, `dns`)  
- Reconstructed TCP streams and extracted transferred files (e.g., `Rise-Up.jpg`)  
- Detected suspicious activity involving user "Bob" and RDP logins (user: Bucky)

**Key Outcomes**:  
- Identified user creation events (e.g., user: Hacker) and port 4444 traffic  
- Practiced end-to-end traffic decryption and anomaly detection

---

### 🌐 Challenge: DNS in Detail (TryHackMe)

**Platform**: [TryHackMe – DNS in Detail](https://tryhackme.com/room/dnsindetail)

**Tools Used**:  
`dig`, `nslookup`, DNSDumpster

**Focus Areas**:  
- DNS Protocol Hierarchy  
- Record Types (A, CNAME, MX, TXT)  
- OSINT-based DNS Enumeration

**Approach**:  
- Queried A, MX, TXT records using `dig` and `nslookup`  
- Traced DNS resolution paths (root > TLD > subdomain)  
- Applied OSINT with DNSDumpster to identify related infrastructure

**Key Outcomes**:  
- Built strong understanding of DNS resolution and misconfig risks  
- Learned how DNS data aids enumeration during recon phases

---

### 🔗 Challenge: Web Requests and APIs (HTB Academy)

**Platform**: [Hack The Box Academy](https://academy.hackthebox.com/)

**Badge**: 🏅 [View Badge](https://academy.hackthebox.com/achievement/badge/cb163662-43a1-11f0-bcfdbea50ffe6cb4)

**Tools Used**:  
`curl`, Browser DevTools, API Endpoints

**Focus Areas**:  
- HTTP Methods & Responses  
- Header Manipulation  
- API-based CRUD Operations

**Approach**:  
- Crafted and intercepted GET/POST/DELETE requests  
- Modified headers (e.g., `User-Agent`, `Authorization`)  
- Authenticated API requests and analyzed response codes (200, 403, 500)

**Key Outcomes**:  
- Practiced safe interaction with REST APIs  
- Gained insights into API testing, web app security, and endpoint exposure

---

> These lab challenges demonstrate hands-on problem solving in core cybersecurity areas including network forensics, DNS analysis, and API security testing.
