# 🔍 VulnScanner

A modular and extensible **Python-based vulnerability scanner** designed for recon, enumeration, and CVE detection. Built for red teamers, bug bounty hunters, and cybersecurity learners.

---

## 🚀 Features

- ✅ Custom TCP Port Scanner (with optional Nmap support)
- 🌐 Subdomain Brute-Forcing using wordlists
- 🔐 HTTP Header & Security Header Analyzer
- 🧠 CMS Detection (WordPress, Joomla, etc.)
- 📡 Real-time CVE Lookup via NVD API
- 📝 Generates scan reports (JSON, Markdown, and PDF)

---

## 🧱 Project Structure

See a breakdown of the main components:

| Folder/File          | Purpose |
|----------------------|---------|
| `scanner/`           | Core scanning modules (port, subdomains, headers, CMS, CVEs) |
| `utils/`             | Helper scripts: logger, API clients, report writer |
| `reports/`           | Output folder for all scan result files |
| `wordlists/`         | Custom wordlists for bruteforce modules |
| `main.py`            | Main entry point to run full scan |
| `config.py`          | Global configuration like ports, timeouts, API keys |
| `requirements.txt`   | Python dependencies |
| `.gitignore`         | Ignored files like cache, venv, logs |
| `README.md`          | Project documentation |
| `LICENSE`            | Open-source license (MIT by default) |

---
### Usage

python main.py --target example.com --full-scan

## Output Reports 
 - reports/scan_report.json
 - reports/scan_report.md
 - reports/scan_report.pdf

## Wordlists 
 - wordlists/subdomain.txt

## 🔧 Setup Instructions

### 1. Clone the Repository & Install Dependencies

```bash
git clone https://github.com/arun-khatwe/vulnscanner.git
cd vulnscanner









