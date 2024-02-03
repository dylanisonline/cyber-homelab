# 🥼🧪 Cybersecurity Homelab

One of the most imporant things that any cybersecurity professional should have (or know how to setup) is a homelab. This makes testing configurations and learning new skills more convenient, safe, and inexpensive.

<br>

### Network Topology
---
<br>


### Machines
---
| Machine      | CPU | Ram | Network | Storage | Description |
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| OPNsense      | 2  | 4 | Nat | 20 | Firewall software solution | 
| Metasploitable   | 1 | 1 | 2 | 1 | Vulnerable Linux Server for testing  |
| Kali   | 4        | 40 | 4 | 80 | Threat Actor machine |
| Ubuntu Server   | 2        | 4 | 2 | 100 | Splunk Server |
| Ubuntu Desktop   | 2       | 1 | 2 | | Used as Linux Based workstation
| Windows Desktop   | 2      | 2 | 2 | 60 | Windows Workstation Operating systems | 
| Windows Server   | 2        | 2 | 2 | 60 | Domain Controller Server for active directory |

<br>

### Hardware Setup
----
- AMD Ryzen 9 5900HX
- AMD Radeon RX 6800M
- 16 GB DDR4 ram (Most imporant component)
- 1 TB SSD

<br>

### Components
---
These are going to be the main features that this lab will include. The components were picked based on industry standards and principals.

1. Attacking machine (Kali Linux)
2. Software Firewall (Pfsense)
3. Intrusion Detection System (Suricata)
4. Security Information and Event Management Tool (Splunk)
5. Vulnerable Linux Server (Metasploitable)
6. Domain Controller (Windows Active Directory Server)
7. VMware Workstation Pro 17 (Virtualization Environment)

<br>

### Steps
---
1. [Setup Images and Machines](Step1.md)
2. Configuring opnsense firewall interfaces
3. Setup Snort
4. Configuring Splunk Server
5. Configuring Active Directory Environment

<br>

### Inspirations 
---
[Cyberwox Cybersecurity Lab](youtube.com)

