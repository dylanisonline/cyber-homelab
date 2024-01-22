## Step 1: Preparing Images

First we must configure our virtual machine software. This project uses VMware Workstation Pro 17 which requires a paid license key. However, there is a trial version of this software that can used. This configuration should be achieveable on free desktop hypervisor solutions such as Virtual Box or VMware Workstation Player.

<br>

| Image      | Description |
| ----------- | ----------- |
| Kali      | Used for our threat actor machine       |
| Metasploitable   | Vulnerable Linux Server for testing      |
| OPNsense   | Opensource firewall solution for our networks        |
| Ubuntu Server   | Used for Splunk Server        |
| Ubuntu Desktop   | Used for our SOC analyst workstations        |
| Windows Desktop   | Used for any windows clients      |
| Windows Server   | Domain Controller        |

<br>

### Hypervisor Setup
---
#### VMware Workstation Pro 17
Downloads: [VMware](https://www.vmware.com/products/workstation-pro.html)

Workstation Pro will be the hypervisor solution for this lab environment. It is choosen due to it's prominence in industry, simple interface, and advanced features such as graphics acceleration.

<br>

**Step 1**: Create a VMware Account and purchase a license key for Workstation Pro.

**Step 2:** Download the executable from the customer connect portal

**Step 3:** Go through installation wizard

(OPTIONAL) Step 4: After installation is done, create a seperate folder to house the virtual machines and images.

_NOTE: I have a dedicated SSD to store my virtual machines._

<br>

### Downloading Images
---

#### Ubuntu

Downloads: [Desktop](https://ubuntu.com/download/desktop) , [Server](https://ubuntu.com/download/server)

Our Ubuntu clients will act as linux workstations in our network. 

<br>

**<p align="center">Desktop Client</p>**

![alt](https://i.imgur.com/9ajMNLD.png)

**<p align="center">Server</p>**

![alt](https://i.imgur.com/jwZRw01.png)

<br>

#### Kali

Downloads: [VM Image](https://www.kali.org/get-kali/#kali-virtual-machines), [Full ISO](https://www.kali.org/get-kali/#kali-installer-images)

Kali is a distribution of Linux that has many cybersecurity and penetration testing tools pre-installed. In this lab, Kali is going to be the operating system that the threat actor will use in the network. Although the virtual machine image is being used in this project, the full installer ISO can also be used instead. For this instance, download the **VMware Image** and save it to your computer.

<br>

**<p align="center">VM Download</p>**

![alt](https://i.imgur.com/bqNVdfu.png)

<br>

#### Windows

Downloads: [Windows 10 Evaluation](), [Windows Server Evaluation]()

This lab will be implementing Active Directory. Our instance of Windows server will be used as a domain controller for to manage our users and resources via active directory.

<br>

#### OPNsense

Download: [OPNsense](https://opnsense.org/download/)

OPNsense is an open source firewall solution that will be used to filter and monitor the traffic that is coming into our network. 

<br>

#### Metasploitable 2

Download: [Sourceforge](https://sourceforge.net/projects/metasploitable/)

Metasploitable is a deliberately vulnerable linux server that can be used to test various red-team functions.

<br>

#### **Next Step: [Setting up OPNsense Firewall](Step2.md)**





