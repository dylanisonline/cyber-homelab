## Step 2: Configuring Pfsense Interfaces

<br>

![alt](https://securityaffairs.com/wp-content/uploads/2023/12/1200px-PfSense_logo.png)

<br>

Pfsense is an opensource firewall application solution that will filter traffic between our networks. 

<br>


| Network | Adapter Name | VM Network | IP Address Range |
| --- | --- | --- | --- |
| WAN | em0 | NAT | Automatic |
| LAN | em1 | vmnet2 | 192.168.1.11 - 192.168.1.200 |
| OPT1 | em2 | vmnet3 | 192.168.2.11 - 192.168.2.200 |
| OPT2 | em3 | vmnet4 | 192.168.3.11 - 192.168.3.200 |
| OPT3 | em4 | vmnet5 | 192.168.4.11 - 192.168.4.200 |



<br>

### Installing on VMware
---
1. Make sure that the ISO from the [previous step](Step1.md) is downloaded
2. Open VMware Workstation and create a new virtual machine
3. Configure hardware for network interfaces for Pfsense Machine

<p align="center">
  <img src="https://i.imgur.com/iGv60Hp.png" alt="Sublime's custom image" width=500/>
</p>

4. Start Virtual Machine
5. Use default settings on the installer and reboot after completion

<br>

### Assigning Interfaces
---

<br>


1. Enter `1` to Assign Interfaces


<br>

![alt](https://i.imgur.com/HUlLtAF.png)

<br>

2. `No` to VLANs
3. Assign interfaces according to the chart above.
4. Final configuration should look like this:

<br>

![alt](https://i.imgur.com/ZQFnzFF.png)

<br>


5. `Y` to proceed

<br>

### Configuring LAN
---

<br>

1. Enter `2` to configure IP addresses for network interfaces
2. Enter `2` to configure the LAN
3. Do not
4. Enable DHCP


#### Next Step: 

