# Case-Study-Evading-IDS-Firewalls-and-Honeypots-IDS-Firewall-Evasion-Lab
# IDS, Firewall & Evasion Case Study

## Objective
To analyze firewall behavior and test evasion techniques using Nmap and web-based attacks.

## Tools Used
- Nmap
- Burp Suite
- Firefox

## Steps Performed
1. Performed port scanning using Nmap
2. Observed all ports filtered (Firewall active)
3. Attempted evasion using slow scan
4. Shifted to web application testing
5. Intercepted HTTP traffic using Burp Suite
6. Tested input parameters for vulnerabilities

## Findings
- Strong firewall blocked network scans
- Application layer remained accessible
- Input fields may allow injection attacks

## Conclusion
When network-level attacks fail, attackers pivot to application-level exploitation.

## Countermeasures
- Input validation
- Web Application Firewall (WAF)
- IDS tuning
