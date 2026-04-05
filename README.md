# 🔍 OFind

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux%20%2F%20Windows-informational?style=flat-square&logo=linux&logoColor=white&color=0a0c10"/>
  <img src="https://img.shields.io/badge/Category-ORec%20%2F%20OSINT-cyan?style=flat-square"/>
  <img src="https://img.shields.io/badge/Dependencies-requests-yellow?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-Proprietary-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-v1.0-cyan?style=flat-square"/>
</p>

> **OFind** is a fast username reconnaissance tool that checks the existence of a username across **100+ platforms** including social media, developer sites, gaming, forums, creative communities, and more.

**Instant OSINT for digital footprint mapping and identity investigation.**

---

## 📌 Overview

OFind performs parallel checks on a large database of platforms using HTTP status codes and content-based detection. It supports full scans, category-specific searches, and exports results to JSON.

Clean colored output with live results and detailed summary.

---

## 🖥️ Modules

| # | Module                  | Description |
|---|-------------------------|-------------|
| **[1]** | **Search Username**     | Full scan across all 100+ platforms |
| **[2]** | **Search by Category**  | Scan only a specific category |
| **[H]** | **Help**                | Usage guide and platform information |

---

## 📊 Key Features

- **100+ Platforms** — Social Media, Developer, Gaming, Forums, Creative, Security, Professional
- **Parallel Scanning** — Threaded checks for fast results
- **Smart Detection** — Combines HTTP status + page content keywords
- **Category Filtering** — Scan only Social, Developer, Gaming, etc.
- **Live Results** — Real-time colored output ([✔ FOUND] or [✘])
- **Summary Statistics** — Total platforms, found/not found, average response time
- **JSON Export** — Structured results with full details
- **Pure & Lightweight** — Minimal dependencies

---

## ⚙️ Requirements

- **requests**
  ```bash
  pip install requests
  chmod +x OFind
  ./OFind


  📁 Output

Live Terminal — Colored real-time results showing platform, status, URL, and response time
Summary — Total platforms scanned, number found, average time
Export — ofind_<username>_<timestamp>.json containing all results with metadata


📦 Part of OwlSec Toolkit
This tool is part of the OwlSec suite — a collection of 300+ security and privacy tools.
🔗 owlsec.org

©️ License
Proprietary — © Khaled S. Haddad
Tools are distributed as pre-built executables. Source code is proprietary.
AUTHORISED SECURITY TESTING / OSINT USE ONLY
