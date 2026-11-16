# Week 2: Network Discovery and Footprinting

**Intern:** COLLINS ASHIME JR |  **Batch:** B084 |  Networkwalks Cybersecurity Internship

Host discovery on my own lab network with Zenmap, and footprinting of the authorized target `networkwalks.com` using whois, whatweb, nslookup, curl, wafw00f, dnsrecon and Maltego.

## Key results

- **Zenmap ping scan** (`nmap -sn 10.0.0.2/24`): 3 live hosts (10.0.0.1, 10.0.0.2, 10.0.0.3).
- **networkwalks.com:** server IP 192.232.216.135, Apache with WordPress, behind a ModSecurity WAF, one public e-mail found (info@networkwalks.com).

## Files
View Repository files for detail results


> All testing was done with written authorization and was limited to reconnaissance and scanning. For educational use only.
