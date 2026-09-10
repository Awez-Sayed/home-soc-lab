# Home SOC Lab

A self-built, isolated lab environment for practicing detection and analysis 
of attacker behavior, using tools common in real SOC environments.

## Environment
- **Attacker:** Kali Linux
- **Target:** Windows 10
- **Network:** Isolated VirtualBox Host-only network
- **Logging:** Sysmon, Windows Security Auditing
- **SIEM:** Splunk Enterprise (free tier) + Splunk Universal Forwarder

## Reports
- [SMB Port Scan Detection](reports/01-smb-port-scan-detection.md)

## Purpose
Built to gain hands-on experience with log analysis, SIEM tooling, and 
attacker pattern recognition ahead of an entry-level SOC Analyst role.
