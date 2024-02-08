## Step 2: Configuring Pfsense Interfaces

<br>

![alt](https://securityaffairs.com/wp-content/uploads/2023/12/1200px-PfSense_logo.png)

<br>

Pfsense is an opensource firewall application solution that will filter traffic between our networks. 

<br>

#### Installing on VMware
---
1. Make sure that the ISO from the [previous step](Step1.md) is downloaded
2. Open VMware Workstation and create a new virtual machine
3. Configure hardware for network interfaces for OPNsense Machine

<br>

#### Configure IP Addresses for interfaces
---
 
| Network | Adapter Name | VM Network | IP Address Range |
| --- | --- | --- | --- |
| WAN | em0 | NAT | |
| LAN | em1 | vmnet2 | 192.168.1.11 - 192.168.1.200 |
| OPT1 | em2 | vmnet3 | 192.168.2.11 - 192.168.2.200 |
| OPT2 | em3 | vmnet4 | 192.168.3.11 - 192.168.3.200 |
| OPT3 | em4 | vmnet5 | 192.168.4.11 - 192.168.4.200 |



#### Next Step: 

