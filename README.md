# Course Capture-The-Flag (Ethical Hacking)
Project URL: https://andrewb1998.github.io/CTF-Ethical-Hacking/

This repository contains a detailed report of a Capture the Flag (CTF) challenge for the course Ethical Hacking at University of Turku. 
The challenge was completed under supervised conditions within a 2-hour timeframe. The task was completed with full points.

CTF Description:
- 4 distinct challenges that represent key concepts and techniques learned during the course, such as active reconnaissance, SSRF, and privilege escalation.
- The challenges involved finding a hidden flag, which was then entered into the challenge page's input box to redeem points.
- Each challenge is documented and includes technical findings, evidence, and recommended remediation.

Challenges:
- OSINT: Flag found in style.css file.
- Nmap: Discovered open HTTP service on port 10111 using Nmap. base64-encoded message extracted.
- SSRF: Exploited SSRF vulnerability to reveal internal resources.
- File Upload & Privilege Escalation: Reverse shell executed via file upload and privilege escalation using a crafted command.
