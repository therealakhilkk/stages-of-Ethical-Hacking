Reconnaissance (Information Gathering)

Reconnaissance is the first phase of ethical hacking, where hackers collect as much information as possible about the target before launching an attack. 
This phase is crucial as it helps in identifying weak points and planning further penetration attempts.

Types of Reconnaissance
Passive reconnaissance 
Active Reconnaissance

Passive Reconnaissance (Indirect)
Indirect passive reconnaissance involves collecting publicly available data without directly interacting with the target organization's infrastructure. 
Instead of scanning or probing the target’s network, this method relies on third-party sources.

Methods of Indirect Passive Reconnaissance
Search Engines (Google Dorking)
Using advanced search operators to find sensitive information indexed by search engines.
Example: site:example.com filetype:pdf confidential.

Public Databases & Archives
WHOIS lookup for domain information.
DNS records from services like VirusTotal, SecurityTrails, or Shodan.
Archive.org (Wayback Machine) for historical snapshots of websites.

Social Media & OSINT (Open-Source Intelligence)
Collecting information from LinkedIn, Twitter, Facebook, etc.
Monitoring job postings that reveal technology stacks.

Active Reconnaissance (Direct)
Active reconnaissance is the process of directly interacting with a target system to gather information. 
Unlike passive reconnaissance, this method involves sending requests, scanning networks, and probing systems, 
which increases the risk of detection by security measures like IDS (Intrusion Detection Systems) and firewalls.

Types of Active Reconnaissance
Network Scanning
Identifies live hosts, open ports, and services running on a target.
Tools: Nmap, Masscan, Angry IP Scanner

Port Scanning
Detects open ports and services that might be vulnerable.
Common scan types:
SYN Scan (-sS) – Stealthy, doesn’t complete handshake.
TCP Connect Scan (-sT) – Complete handshake, easier to detect.
UDP Scan (-sU) – Finds open UDP ports (e.g., DNS, SNMP).

Service Enumeration
Retrieves detailed information about running services (e.g., version numbers, configurations).
Tools: Nmap, Netcat, Metasploit

Web Application Scanning
Analyzes web applications for vulnerabilities (SQL injection, XSS, misconfigurations).
Tools: Burp Suite, Nikto, Dirb, OWASP ZAP

Wireless Reconnaissance
Identifies and analyzes Wi-Fi networks for weaknesses.
Tools: Kismet, Aircrack-ng, Wireshark
