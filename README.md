# 🥼🧪 Cybersecurity Homelab

One of the most imporant things that any cybersecurity professional should have (or know how to setup) is a homelab. This makes testing configurations and learning new skills more convenient, safe, and inexpensive.

<br>

### Network Topology
---

192.168.1.x : Engineering Network. Where a machine will be placed for configuring the Pfsense firewall.

192.168.2.x : Security Onion machine and Analyst Machine

192.168.3.x : Where our vulnerable server is going to be

192.168.4.x : Where our Linux Workstations will be

192.168.5.x: Where our attack machine will be

<br>

### Hardware Setup
----
- AMD Ryzen 9 5900HX
- AMD Radeon RX 6800M
- 32 GB DDR4 ram (Most imporant component)
- 1 TB SSD

<br>

### Components
---
These are going to be the main features that this lab will include. The components were picked based on industry standards and principals.

1. VMware Workstation Pro (Virtualization Solution)
2. Pfsense (Firewall and Routing solution)
3. Security Onion (IDS / IPS solution)
4. Metasploitable (Deliberately vulnerable server)
5. Kali Linux (Threat Actor)

<br>

### Steps
---
1. [Setup Images and Machines](Step1.md)
2. Configuring Pfsense
3. Setting up Security Onion
4. Configuring and connecting other machines
5. Attacking Metasploitable 

<br>

### Inspirations 
---
[Cyberwox Cybersecurity Lab](youtube.com)

