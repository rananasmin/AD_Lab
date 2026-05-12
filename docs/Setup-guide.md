## AD Lab Setup Guide

### Objective

This lab simulates an enterprise Active Directory environment with centralized logging and attack simulation capabilities.

The lab was built to:
- Practice Active Directory administration 
- Simulate attacks 
- Forward logs into Splunk SIEM
- Create detection rules
- Perform incident investigation


### Systems Overview

| System | IP Address | Purpose |
|--------|-------------|---------|
| Splunk Server | 192.168.10.10 | SIEM and log analysis |
| Domain Controller | 192.168.10.7 | Active Directory |
| Windows 10 Client | DHCP | Endpoint workstation |
| Kali Linux | 192.168.10.250 | Attack simulation |


### Network Configuration

Network:
192.168.10.0/24

Gateway:
192.168.10.1

DNS:
192.168.10.7

Static IPs:
- Splunk: 192.168.10.10
- Domain Controller: 192.168.10.7
- Kali Linux: 192.168.10.250

