👋 About This Repository

This repository documents my 6-week practical training in Cyber Security and Ethical Hacking. Each of the 18 tasks is written up as a report with objectives, methodology, commands and tools used, screenshots, findings, and lessons learned.

The work follows the structure of a real penetration test:

Foundations → Lab Setup → Reconnaissance → Scanning & Enumeration → Vulnerability Assessment → Web Exploitation → System Exploitation → Reporting

All testing was performed only in isolated, intentionally vulnerable lab environments that I built and own (VirtualBox, Kali Linux, Metasploitable, DVWA). No real-world systems were targeted.

🎯 Key Skills Demonstrated
Area	What I Did
Networking	IP addressing, ports, protocols, OSI model, subnetting, network tools
Linux	Command line, file system, permissions, working daily in Kali Linux
Reconnaissance	Passive footprinting and OSINT
Scanning & Enumeration	Nmap scanning, service enumeration, vulnerability scanning
Web Security	HTTP fundamentals, Burp Suite, OWASP Top 10, SQL injection, XSS
Attacks & Exploitation	Brute-force attacks with Hydra, exploitation with Metasploit
Password Security	Hash cracking with John the Ripper / Hashcat
Reporting	Full pentest with a professional-grade report (Capstone)

🧰 Tools & Technologies

Kali Linux · VirtualBox · Metasploitable · DVWA · Nmap · Burp Suite · Metasploit Framework · Hydra · John the Ripper · Hashcat · Linux CLI · OSINT techniques

⭐ Featured: Capstone Project

Week 6 · Task 18 — Full Penetration Test + Professional Report

The capstone brings everything together: reconnaissance, scanning, enumeration, exploitation, and post-exploitation findings, documented in a professional pentest report that includes an executive summary, methodology, findings with severity ratings, evidence, and remediation recommendations.

👉 Recruiters short on time: start here.

📚 Report Index
Week 1 — Foundations
#	Task	Focus
1	Cyber Security & Ethical Hacking: Introduction	Core concepts, the CIA triad, types of hackers, legal and ethical boundaries
2	Networking Basics: IP, Ports, Protocols & OSI Model	How data moves across networks and where attacks occur
3	Lab Setup: VirtualBox + Kali Linux	Building a safe, isolated testing environment
Week 2 — Tools & Practice Targets
#	Task	Focus
4	Linux Fundamentals: Commands, Files & Permissions	Command-line fluency and permission models
5	Networking Tools & Subnetting Basics	Network utilities and subnet calculations
6	Vulnerable Lab Setup: Metasploitable / DVWA	Deploying intentionally vulnerable targets
Week 3 — Reconnaissance & Enumeration
#	Task	Focus
7	Footprinting & OSINT (Passive Recon)	Gathering intelligence without touching the target
8	Network Scanning with Nmap	Host discovery, port scanning, service and version detection
9	Enumeration: Digging Deeper into Services	Extracting detailed information from discovered services
Week 4 — Vulnerability Assessment & Web Foundations
#	Task	Focus
10	Vulnerability Scanning Basics	Identifying and prioritizing known weaknesses
11	How the Web Works + Burp Suite Intro	HTTP requests/responses and intercepting traffic
12	OWASP Top 10: Web Vulnerabilities Overview	The most critical web application risks
Week 5 — Web Exploitation
#	Task	Focus
13	SQL Injection (Hands-on with DVWA)	Exploiting and understanding database injection flaws
14	Cross-Site Scripting (XSS): DVWA	Reflected and stored XSS attacks
15	Brute Force & Authentication Attacks (Hydra)	Attacking weak login mechanisms
Week 6 — Exploitation, Cracking & Reporting
#	Task	Focus
16	Metasploit: Exploit a Vulnerable Machine	Gaining access with the Metasploit Framework
17	Password Cracking: Hashes (John / Hashcat)	Understanding hash types and cracking weak passwords
18	CAPSTONE: Full Pentest + Professional Report	End-to-end assessment with a client-style report
🗂️ Repository Structure
.
├── Week-1/   # Intro, networking, lab setup
├── Week-2/   # Linux, network tools, vulnerable labs
├── Week-3/   # OSINT, Nmap, enumeration
├── Week-4/   # Vuln scanning, Burp Suite, OWASP Top 10
├── Week-5/   # SQLi, XSS, brute force
├── Week-6/   # Metasploit, password cracking, capstone
└── README.md
⚖️ Ethical Statement

Everything in this repository was done for education and defensive learning, in a controlled lab I set up myself. I follow the principles of ethical hacking: get authorization first, stay within scope, do no harm, and report responsibly. The techniques shown must never be used against systems without explicit written permission.

