# 🦉 ONetX

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OForensics-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0-cyan?style=flat-square"/>
</p>

> **ONetX** — Network forensics and PCAP analyzer

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

ONetX is a network forensic and traffic analysis suite covering live connections, packet sniffing, DNS, port scanning, ARP discovery, banner grabbing, and PCAP analysis. CLI supports offline PCAP analysis and an authorised-use `--agree` flag; the fuller interactive workflow provides geo-IP, protocol stats, and JSON/TXT/HTML forensic reports.

---

## ✨ Features

- Live connection listing with process mapping and Geo-IP context
- Raw packet sniffer with PCAP capture and SHA-256 integrity
- DNS resolver / reverse lookup, port scanner, ARP discovery, and banner grabbing
- Traffic statistics, protocol analysis, and Ethernet/IP/TCP/UDP/ICMP packet decoder
- Forensic report generation (JSON / TXT / HTML) and interface monitor
- Non-interactive offline PCAP analysis via `--pcap` with optional `--agree` to skip the authorised-use prompt

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./ONetX --pcap capture.pcap --agree
./ONetX --agree
./ONetX --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
