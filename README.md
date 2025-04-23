## 🛡️ DNS in Detail

**Room:** [DNS in Detail — TryHackMe](https://tryhackme.com/room/dnsindetail)  
**Status:** ✅ Completed  
**Date:** *(22nd April 2025)*

### 🎯 Objective  
To understand how DNS works behind the scenes, including how domain names resolve into IP addresses, the structure of domain names, and how different DNS records serve specific roles in communication.

---

### 🗝️ Key Concepts  
- DNS – Translates human-friendly domain names into IP addresses that computers understand.  
- Domain hierarchy – Root, TLDs, second-level domains, and subdomains that structure how names are organised.  
- A & AAAA records – Map domain names to IPv4 (A) or IPv6 (AAAA) addresses.  
- CNAME records – Point one domain name to another, acting like an alias.  
- MX records – Tell mail servers where to deliver emails for a domain, with priorities for backup handling.  
- TXT records – Store readable data like verification info or SPF rules for email security.  
- Recursive DNS servers – Perform lookups on behalf of users, caching results for speed.  
- Authoritative DNS servers – Hold the official records for a domain and respond with accurate DNS info.  
- TTL (Time To Live) – Sets how long DNS info is cached before a new lookup is needed.  

---

### 🛠️ Tools Used  
- Online DNS lookup tools — used to simulate and view DNS queries and responses  

---

### ⚠️ Challenges Faced  
- Initially found it tricky to understand how the query flows between different servers (root, TLD, authoritative).  
- Visualising the full DNS resolution path made it clearer, especially how recursive DNS servers cache responses to save time.

---

### 🧠 What I Learned  
- Gained a strong foundational understanding of how DNS supports internet browsing.  
- Learned how to identify and interpret various DNS record types.  
- Understood how DNS caching improves performance but can also affect changes taking effect.

---

### 🌐 Real-World Application:  
> DNS is a vital part of web infrastructure. Knowing how it works helps in both offensive and defensive security — attackers may exploit subdomains, and defenders can monitor DNS traffic for threats.

---

### 💭 Reflections:  
- It was interesting to see how something as simple as typing a URL kicks off a complex behind-the-scenes process.  
- I won’t forget the difference between authoritative and recursive DNS servers — that cleared up a lot for me!

