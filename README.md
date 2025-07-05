#VulnScanner - Python-Based Vulnerability Scanner

A modular and extensible vulnerability scanner built in Python for recon, enumeration, and CVE detection. Inspired by tools like Nmap, Nikto, and WhatWeb.

##Features

- Port Scanner (manual + nmap)
- Subdomain Finder
- HTTP Header & Security Header Analyzer
- CMS Detector (WordPress, Joomla, etc.)
- CVE Lookup & Threat Intelligence
- JSON, Markdown & PDF Reports

## Project Structure

vulnscanner/
├── scanner/                 # Core vulnerability scanner modules
│   ├── __init_.py
│   ├── port_scanner.py
│   ├── subdomain_finder.py
│   ├── header_analyzer.py
│   ├── cms_detector.py
│   └── cve_checker.py

├── utils/                   # Helper modules (APIs, logger, common utils)
│   ├── __init_.py
│   ├── logger.py
│   ├── api_helpers.py
│   └── output_writer.py

├── reports/                 # Output reports saved here
│   ├── scan_report.json
│   ├── scan_report.md
│   └── scan_report.pdf

├── wordlists/               # For subdomain brute-force, tech fingerprinting
│   └── subdomains.txt

├── main.py                  # Entry point – runs all modules
├── config.py                # Settings (ports, URLs, API keys, etc.)
├── requirements.txt         # All Python dependencies
├── README.md                # Full usage, features, setup guide
├── .gitignore               # Ignore logs, venv,
etc.
└── LICENSE                  # Add MIT license or your choice

