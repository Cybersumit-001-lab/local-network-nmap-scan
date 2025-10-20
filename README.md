# Task 1: Scan Your Local Network for Open Ports

## Objective
To discover open ports and running services in the local network using Nmap.

## Tools Used
- Nmap
- Wireshark (optional)

## Steps Performed
1. Installed Nmap.
2. Found my local IP range using `ipconfig`.
3. Ran `nmap -sS 192.168.***.0/24`.
4. Noted down IPs and open ports.
5. Analyzed packets with Wireshark.
6. Researched the services running on open ports.
7. Identified potential security risks.
8. Saved results and uploaded to GitHub.

## Results
| IP Address | Open Ports | Services |
|-------------|-------------|-----------|
| 192.168.***.136 | 22      | SSH |
| 192.168.***.2   | 53      | domain|

## Security Insights
- SSH open to everyone may lead to brute-force attacks.
- An open DNS (port 53) can be abused for amplification DDoS, zone-transfer leaks, DNS tunneling/exfiltration, and cache‑poisoning—leading to outages, data exposure, and compromised DNS integrity.

## Files
- `scan_results.txt` – Nmap output
- `screenshots/` – Screenshots of Nmap and Wireshark
