<div align="center">

<img src="https://img.shields.io/badge/Python-3.12-blue?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Flask-3.0.3-black?style=for-the-badge&logo=flask&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-Ready-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Modules-30-orange?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Auth-None_(Open)-red?style=for-the-badge"/>
<img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge"/>

<br/><br/>

<h1>🛡️ CyberScan Pro — v2 (Open Edition)</h1>
<h3>All-in-One Cybersecurity Intelligence Platform · No Auth Required</h3>

<p><strong>30 offensive & defensive security modules. No login. Instant access. Self-hosted.</strong></p>

<a href="https://anshul2414.github.io/cyberscan-pro-v2">🌐 Live Demo</a> •
<a href="#-quick-start">🚀 Quick Start</a> •
<a href="#-modules">📦 Modules</a> •
<a href="#-docker">🐳 Docker</a>

> ⚠️ **v2 = Open Edition** — No authentication. For **local/lab use only**. Use [cyberscan-pro](https://github.com/anshul2414/cyberscan-pro) for the authenticated production version.

</div>

---

## ✨ Overview

**CyberScan Pro v2** is the open, authentication-free edition of the CyberScan Pro platform — a self-hosted cybersecurity dashboard with **30 active security scanning modules**. Designed for **penetration testers**, **security researchers**, and **ethical hackers** running in isolated lab environments.

> Built by [Anshul](https://anshul2414.github.io) — Penetration Tester & Certified Ethical Hacker (CEH)

---

## 📦 Modules

### 🔵 Core Reconnaissance (16 modules)

| # | Module | Description |
|---|--------|-------------|
| 1 | **URL Check** | Analyze URL safety, redirects & response metadata |
| 2 | **Port Scan** | TCP port scanning with service detection |
| 3 | **DNS Lookup** | Full DNS enumeration (A, MX, NS, TXT, AAAA) |
| 4 | **SSL Inspector** | Certificate chain, expiry, cipher suite analysis |
| 5 | **WHOIS Lookup** | Domain registration & ownership data |
| 6 | **Tech Detect** | Identify web technologies, frameworks & CMS |
| 7 | **Email Security** | SPF, DKIM, DMARC validation & analysis |
| 8 | **Security Headers** | HTTP security header audit (HSTS, CSP, X-Frame) |
| 9 | **CORS Analyzer** | Cross-Origin Resource Sharing misconfiguration check |
| 10 | **WAF Detect** | Web Application Firewall fingerprinting |
| 11 | **Subdomain Enum** | Passive subdomain discovery & enumeration |
| 12 | **IP Geolocation** | IP intelligence — ASN, ISP, geo, threat classification |
| 13 | **Hash Tools** | MD5, SHA-1, SHA-256/512 generation & comparison |
| 14 | **Password Analyzer** | Strength scoring, entropy calculation |
| 15 | **Robots.txt Parser** | Hidden paths and disallowed resource discovery |
| 16 | **CVE Search** | Search CVE database for vulnerability intelligence |

### 🔴 Advanced Offensive Modules (14 modules)

| # | Module | Description |
|---|--------|-------------|
| 17 | **Traceroute** | Network path tracing & hop latency analysis |
| 18 | **Dir Fuzzer** | Directory & endpoint brute-force enumeration |
| 19 | **XSS / SQLi / LFI Scanner** | Automated injection vulnerability scanner |
| 20 | **Open Redirect** | Open redirect chain detection & verification |
| 21 | **Cookie Analyzer** | Cookie flags — HttpOnly, Secure, SameSite audit |
| 22 | **JWT Analyzer** | JWT decode, algorithm audit, key-confusion detection |
| 23 | **TLS Deep Scan** | TLS version, cipher strength & certificate pinning |
| 24 | **Firewall Detect** | Active firewall & IDS/IPS detection techniques |
| 25 | **Email Header Forensics** | Full email header trace & spoofing analysis |
| 26 | **CIDR Scanner** | Bulk IP range scanning & host discovery |
| 27 | **Banner Grabber** | Service banner collection for fingerprinting |
| 28 | **API Security Tester** | REST/GraphQL endpoint enumeration & auth testing |
| 29 | **Network Fingerprinter** | OS & service stack fingerprinting |
| 30 | **SSRF / Cloud Probe** | SSRF detection & cloud metadata exposure testing |

---

## 🚀 Quick Start

```bash
git clone https://github.com/anshul2414/cyberscan-pro-v2.git
cd cyberscan-pro-v2
pip install -r requirements.txt
python app.py
```
Open **http://localhost:5000** — no login required.

---

## 🐳 Docker

```bash
docker-compose up -d
# Open → http://localhost:8080
```

---

## ⚠️ vs Authenticated Version

| Feature | v2 (This Repo) | v3 Auth Edition |
|---------|---------------|-----------------|
| Login Required | ❌ No | ✅ Yes |
| Scan History | ✅ Yes | ✅ Yes |
| Docker Support | ✅ Yes | ✅ Yes |
| Best For | Local Labs | Production / Shared |
| Repo | [cyberscan-pro-v2](https://github.com/anshul2414/cyberscan-pro-v2) | [cyberscan-pro](https://github.com/anshul2414/cyberscan-pro) |

---

## ⚠️ Legal Disclaimer

> For **authorized security testing and educational purposes only**.
> Never scan systems without explicit written permission.

---

## 📬 Contact

**Anshul** — Penetration Tester & Ethical Hacker

- 💼 LinkedIn: [linkedin.com/in/anshul-9800a3275](https://linkedin.com/in/anshul-9800a3275)
- 🐙 GitHub: [github.com/anshul2414](https://github.com/anshul2414)
- 🎯 TryHackMe: [tryhackme.com/p/anshul28054](https://tryhackme.com/p/anshul28054)

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.

---

<div align="center">⭐ Star this repo if you find it useful! · Made with ❤️ by <a href="https://github.com/anshul2414">Anshul</a></div>
