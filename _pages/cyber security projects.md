---
title: "Cyber Security Projects"
permalink: /cybersecurityprojects/
layouts: posts
author_profile: true
---

## 🏆 Completed CTF Challenges

### 🌐 **Intro to Network Traffic Analysis (Tier 0)**
**🛠️ Tools Used:** Wireshark | TCPdump  
**📌 Skills Demonstrated:**
- Network traffic analysis principles
- Tcpdump fundamentals
- Working with Wireshark
- Wireshark filterson

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
