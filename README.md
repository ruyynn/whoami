<div align="center">
  <img src="whoami-banner.svg" alt="whoami banner" width="100%"/>
</div>

<div align="center">

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python)](https://python.org)
[![Platform](https://img.shields.io/badge/Platform-Termux%20|%20Linux%20|%20Windows%20|%20macOS-green?style=for-the-badge)](https://github.com/ruyynn)
[![Version](https://img.shields.io/badge/Version-1.3-red?style=for-the-badge)](https://github.com/ruyynn)
[![License](https://img.shields.io/badge/License-GNU%20GPL%20v3-yellow?style=for-the-badge)](LICENSE)
[![Stars](https://img.shields.io/github/stars/ruyynn/whoami?style=for-the-badge)](https://github.com/ruyynn)

</div>

---

> ⚠️ **Disclaimer:** This tool is for **educational and authorized penetration testing only**. Using it against systems without explicit permission is illegal. The author is **not responsible** for any misuse or damage caused by this tool. You are solely responsible for your own actions.

---

## 📌 About

**whoami** is a powerful, all-in-one penetration testing suite built in Python. Designed for security researchers, ethical hackers, and cybersecurity students who need a comprehensive toolkit that works across multiple platforms — including Android via Termux.

---

## ✨ Features

| Category | Tools |
|----------|-------|
| 📡 Information Gathering | Whois Lookup, DNS Enumeration, Subdomain Finder, HTTP Header Grabber, IP Geolocation |
| 🌐 Network Scanning | Port Scanner, ARP Scanner, Ping Sweep, Traceroute |
| 🔍 Vulnerability Scanner | SQL Injection Scanner, XSS Scanner |
| 🌍 Web Application Testing | HTTP Header Grabber, SQLi, XSS |
| 🔑 Password Attacks | FTP Bruteforce, SSH Bruteforce, Telnet Bruteforce, HTTP Bruteforce, MD5 Hash Cracker |
| 📶 Wireless Attacks | *(Coming in v2.0)* |
| 🎯 Post Exploitation | *(Coming in v2.0)* |
| 📊 Reporting | *(Coming in v2.0)* |

---

## 🖥️ Supported Platforms

- 📱 **Termux** (Android)
- 🐧 **Linux** (Ubuntu / Debian / Kali / Arch)
- 🪟 **Windows** (10/11)
- 🍎 **macOS**

---

## ⚙️ Installation

### 🐧 Linux / macOS
```bash
git clone https://github.com/ruyynn/whoami
cd whoami
pip install -r requirements.txt
python3 whoami.py
```

### 📱 Termux (Android)
```bash
pkg update && pkg upgrade
pkg install python git
git clone https://github.com/ruyynn/whoami
cd whoami
pip install -r requirements.txt
python whoami.py
```

### 🪟 Windows
```bash
git clone https://github.com/ruyynn/whoami
cd whoami
pip install -r requirements.txt
python whoami.py
```

---

## 📦 Requirements

```
colorama
requests
paramiko
scapy
dnspython
python-whois
beautifulsoup4
telnetlib3
```

Install semua sekaligus:
```bash
pip install -r requirements.txt
```

---

## 🚀 Usage

```bash
python3 whoami.py
```

## 📸 Preview

<div align="center">
  <img src="assets/preview.png" alt="whoami main menu preview" width="80%"/>
</div>

---

## 🗺️ Roadmap

- [x] v1.0 — Initial release
- [x] v1.3 — Multi-platform support, bruteforce modules, vuln scanner
- [ ] v2.0 — Wireless attacks, post exploitation, reporting (PDF/JSON/HTML), improved scanner payloads

---

## 👨‍💻 Author

**ruyynn**

- 🐙 GitHub: [Github](https://github.com/ruyynn)
- 📧 Gmail: [Gmail](mailto:ruyynn25@gmail.com)
- 📘 Facebook: [Facebook](https://facebook.com)

---

## 🤝 Contributing

Kontribusi sekecil apapun sangat dihargai! Kamu bisa membantu dengan cara:

- ⭐ **Star** repo ini
- 🍴 **Fork** dan kembangkan fitur baru
- 🐛 **Laporkan bug** via [GitHub Issues](https://github.com/ruyynn/whoami/issues)
- 💡 **Request fitur** baru lewat Issues
- 📬 **Hubungi langsung** via Gmail atau Facebook di atas

> Setiap kontribusi, sekecil apapun, sangat berarti untuk perkembangan whoami! 🙏

---

## 🐛 Bug Report & Pertanyaan

Ada bug atau pertanyaan? Hubungi saya lewat:

| Platform | Link |
|----------|------|
| 🐙 GitHub Issues | [Buka Issue](https://github.com/ruyynn/whoami/issues) |
| 📧 Gmail | [Gmail](mailto:ruyynn25@gmail.com) |
| 📘 Facebook | [Facebook](https://facebook.com) |

---

## ☕ Dukung Pengembangan

Kalau tool ini bermanfaat dan kamu ingin mendukung pengembangan **whoami v2.0**, kamu bisa donasi lewat Saweria:

<p align="center">
  <a href="https://saweria.co/Ruyynn">
    <img src="https://user-images.githubusercontent.com/26188697/180601310-e82c63e4-412b-4c36-b7b5-7ba713c80380.png" width="200" />
  </a>
</p>

> Donasi tidak diwajibkan, tapi sangat membantu! 🙏

---

<div align="center">
  <b>whoami v1.3 — by ruyynn</b><br>
  <i>v2.0 coming soon 👀</i><br><br>
  Kalau tool ini bermanfaat, jangan lupa kasih ⭐ <b>star</b> ya!
</div>
