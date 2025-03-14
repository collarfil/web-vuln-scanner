# Web Vulnerability Scanner
A Python tool to scan websites for basic security flaws—open ports, missing headers, and exposed directories.

## Features
- Scans web ports (80, 443, 8080).
- Checks for missing security headers (e.g., X-Frame-Options).
- Tests for exposed directories (e.g., /admin).
- Outputs in Pidgin + saves to vuln_report.txt.

## Requirements
- Python 3.8+
- `pip install requests`

## Usage
1. Edit `target_url` (e.g., "http://testphp.vulnweb.com").
2. Run `python web_vuln_scanner.py`.

## Sample Output
