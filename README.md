# 🛡️ Red Team Recon – Major Project

## 📌 Overview
**Red Team Recon** is an advanced cybersecurity project designed to simulate real-world reconnaissance as part of a penetration testing workflow.  
The goal is to identify publicly available information about a target, map its attack surface, and collect data for further security analysis — all within a **safe, fictional environment**.

> ⚠️ **Disclaimer:** This project is for **educational purposes only**.  
> The target domain (`example.com`) is a placeholder for safe testing.  
> Never run these tools against real systems without permission.

---

## 🚀 Features
- Automated **Subdomain Enumeration** using `Amass` and `Subfinder`
- **WHOIS Lookup** for domain registration details
- **Web Fingerprinting** using `WhatWeb`
- **Email Harvesting** with `theHarvester`
- **Port Scanning** via `Nmap`
- Organized results in `.txt` format and screenshots

---

## 🛠 Tools Used
| Tool | Purpose |
|------|---------|
| **Amass** | Passive & active subdomain enumeration |
| **Subfinder** | High-speed passive subdomain discovery |
| **Nmap** | Network scanning & service enumeration |
| **WhatWeb** | Website fingerprinting |
| **theHarvester** | Email and host information gathering |
| **WHOIS** | Domain registration details |

---

## 📂 Project Structure
red_team_recon/
│── all_subdomains.txt # Combined results from Amass & Subfinder
│── amass_subdomains.txt # Amass output
│── subfinder_subdomains.txt # Subfinder output
│── nmap_results.txt # Nmap scan results
│── whatweb.txt # Web fingerprinting details
│── theharvester_results.txt # Emails & hosts from theHarvester
│── whois.txt # WHOIS lookup details
│── images/ # Screenshots of execution & results
│── README.md # This documentation

## ⚙ Installation

**1️⃣ Clone the repository**
```bash
git clone https://github.com/balaramdas2004/red-team-recon-major-project.git
cd red-team-recon-major-project

Notice here:
- The first triple backticks should be **\`\`\`bash** (not yaml).
- The last triple backticks should **close immediately after commands**, with no extra indentation.
- There must be a blank line before and after the code block.

3. Save (CTRL + O, Enter) and exit (CTRL + X).

4. Push to GitHub:
```bash
git add README.md
git commit -m "Fixed code block formatting"
git push
