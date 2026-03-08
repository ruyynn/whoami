<div align="center">
  <img src="whoami-banner.svg" alt="whoami banner" width="100%"/>
</div>

<div align="center">

[![Python](https://img.shields.io/badge/Python-3.8%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Version](https://img.shields.io/badge/Version-1.3-FF0000?style=for-the-badge)](https://github.com/ruyynn/whoami)
[![License](https://img.shields.io/badge/License-GPL%20v3-gold?style=for-the-badge&logo=gnu&logoColor=black)](LICENSE)
[![Stars](https://img.shields.io/github/stars/ruyynn/whoami?style=for-the-badge&logo=github&color=yellow)](https://github.com/ruyynn/whoami)
[![Forks](https://img.shields.io/github/forks/ruyynn/whoami?style=for-the-badge&logo=github&color=blue)](https://github.com/ruyynn/whoami/forks)
[![Issues](https://img.shields.io/github/issues/ruyynn/whoami?style=for-the-badge&logo=github&color=red)](https://github.com/ruyynn/whoami/issues)

[![Platform](https://img.shields.io/badge/Termux-Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://github.com/ruyynn)
[![Platform](https://img.shields.io/badge/Linux-Supported-FCC624?style=for-the-badge&logo=linux&logoColor=black)](https://github.com/ruyynn)
[![Platform](https://img.shields.io/badge/Windows-Supported-0078D4?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/ruyynn)
[![Platform](https://img.shields.io/badge/macOS-Supported-000000?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/ruyynn)

[![Maintenance](https://img.shields.io/badge/Maintained-Yes-brightgreen?style=for-the-badge)](https://github.com/ruyynn/whoami)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)](https://github.com/ruyynn/whoami)
[![Open Source](https://img.shields.io/badge/Open%20Source-Yes-brightgreen?style=for-the-badge&logo=opensourceinitiative&logoColor=white)](https://github.com/ruyynn/whoami)
[![Contributions](https://img.shields.io/badge/Contributions-Welcome-orange?style=for-the-badge)](https://github.com/ruyynn/whoami/issues)
[![Saweria](https://img.shields.io/badge/Donate-Saweria-FF69B4?style=for-the-badge)](https://saweria.co/Ruyynn)

</div>

---

## ⚠️ Disclaimer

**whoami** is developed strictly for **educational purposes** and **authorized penetration testing** only.

- You **must have explicit written permission** from the system owner before using this tool against any target.
- Using this tool against systems, networks, or devices **without authorization is illegal** and may violate laws including the Computer Fraud and Abuse Act (CFAA), the EU Directive on Attacks Against Information Systems, and equivalent laws in your country.
- The author (**ruyynn**) takes **absolutely no responsibility** for any damage, data loss, legal consequences, or misuse arising from the use of this tool.
- This tool is provided **"as is"** without warranty of any kind.
- **You are solely and fully responsible for your own actions.**

By downloading or using whoami, you agree to these terms.

---

## About

**whoami** is a multi-platform, all-in-one penetration testing suite written in Python. Built with simplicity and functionality in mind, it brings together the most commonly used tools in a single, easy-to-navigate terminal interface — no complex setup, no scattered scripts.

Whether you're a security researcher conducting authorized audits, a student learning the fundamentals of ethical hacking, or a developer testing your own infrastructure, whoami provides a practical and accessible starting point. It runs natively across Termux (Android), Linux, Windows, and macOS, making it flexible enough for both field and lab environments.

The project is still actively developed, with more advanced modules planned for v2.0.

---

## Features

| Category | Tools |
|----------|-------|
| Information Gathering | Whois Lookup, DNS Enumeration, Subdomain Finder, HTTP Header Grabber, IP Geolocation |
| Network Scanning | Port Scanner, ARP Scanner, Ping Sweep, Traceroute |
| Vulnerability Scanner | SQL Injection Scanner, XSS Scanner |
| Web Application Testing | HTTP Header Grabber, SQLi, XSS |
| Password Attacks | FTP Bruteforce, SSH Bruteforce, Telnet Bruteforce, HTTP Bruteforce, MD5 Hash Cracker |
| Wireless Attacks | *(Coming in v2.0)* |
| Post Exploitation | *(Coming in v2.0)* |
| Reporting | *(Coming in v2.0)* |

---

## Supported Platforms

- Termux (Android)
- Linux (Ubuntu / Debian / Kali / Arch)
- Windows (10/11)
- macOS

---

## Installation

### Linux / macOS
```bash
git clone https://github.com/ruyynn/whoami
cd whoami
pip install -r requirements.txt
python3 whoami.py
```

### Termux (Android)
```bash
pkg update && pkg upgrade
pkg install python git
git clone https://github.com/ruyynn/whoami
cd whoami
pip install -r requirements.txt
python whoami.py
```

### Windows
```bash
git clone https://github.com/ruyynn/whoami
cd whoami
pip install -r requirements.txt
python whoami.py
```

---

## Usage

```bash
python3 whoami.py
```

Once launched, select your platform and navigate through the interactive menu.

---

## Preview

<!-- Replace 'assets/preview.png' with your actual screenshot path after uploading to the repo -->
<div align="center">
  <img src="assets/preview.png" alt="whoami main menu preview" width="80%"/>
</div>

---

## Roadmap

- [x] v1.0 — Initial release
- [x] v1.3 — Multi-platform support, bruteforce modules, vuln scanner
- [ ] v2.0 — Wireless attacks, post exploitation, reporting (PDF/JSON/HTML), improved scanner payloads

---

## Author

**ruyynn**

- GitHub: [github.com/ruyynn](https://github.com/ruyynn)
- Gmail: [ruyynn25@gmail.com](mailto:ruyynn25@gmail.com)
- Facebook: [Facebook](https://facebook.com)

---

## Contributing

All contributions are welcome, no matter how small. Here's how you can help:

- Star this repo
- Fork and develop new features
- Report bugs via [GitHub Issues](https://github.com/ruyynn/whoami/issues)
- Request features through Issues
- Contact directly via Gmail or Facebook above

Every contribution means a lot to the continued development of whoami.

---

## Bug Reports & Questions

Found a bug or have a question? Reach out via:

| Platform | Link |
|----------|------|
| GitHub Issues | [Open an Issue](https://github.com/ruyynn/whoami/issues) |
| Gmail | [ruyynn25@gmail.com](mailto:ruyynn25@gmail.com) |
| Facebook | [Facebook](https://facebook.com) |

---

## Support Development

If this tool has been useful and you'd like to support the development of **whoami v2.0**, donations are available via Saweria:

<p align="center">
  <a href="https://saweria.co/Ruyynn">
    <img src="https://user-images.githubusercontent.com/26188697/180601310-e82c63e4-412b-4c36-b7b5-7ba713c80380.png" width="200" />
  </a>
</p>

Donations are never required, but always appreciated.

---

<div align="center">
  <b>whoami v1.3 — by ruyynn</b><br>
  <i>v2.0 coming soon</i><br><br>
  If this tool has been helpful, a ⭐ star goes a long way.
</div>
