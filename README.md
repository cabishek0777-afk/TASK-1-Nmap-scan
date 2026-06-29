# Task 1 - Nmap Local Network Scan

## Objective
To discover open ports on devices in the local network using Nmap.

## Tool Used
- Nmap

## Command Used
bash
nmap -sS 10.0.2.0/24 -oN scan.txt


## Open Ports Found
- 80/tcp - HTTP
- 135/tcp - MSRPC
- 445/tcp - Microsoft-DS
- 53/tcp - DNS

## Security Risks
- HTTP is not encrypted.
- SMB (445) should not be exposed unnecessarily.
- Unused open ports should be closed.

## Conclusion
Successfully scanned the local network and identified open ports and their services.
