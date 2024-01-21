## Step 1: Preparing Images

First we must configure our virtual machine software. This project uses VMware Workstation Pro 17 which requires a paid license key. However, there is a trial version of this software that can used. This configuration should be achieveable on free desktop hypervisor solutions such as Virtual Box or VMware Workstation Player.

<br>

| Image      | Description |
| ----------- | ----------- |
| Kali      | Used for our threat actor machine       |
| OPNsense   | Opensource firewall solution for our networks        |
| Ubuntu Server   | Used for Splunk Server        |
| Windows Desktop 1   | Windows machine with escalated priviledges      |
| Windows Desktop 2   | Windows machine with minimum permissions        |
| Windows Server   | Domain Controller        |
| Metasploitable   | Vulnerable Linux Server for testing      |

<br>

### Virtulization
---
Download Page: 

**Step 1**: Create a VMware Account and purchase a license key for Workstation Pro.

**Step 2:** Download the executable from the customer connect portal

**Step 3:** Go through installation wizard

<br>

### Prepare ISOs
---
**Step 1:** Create Seperate folder to house all homelab virtual machines and images

_NOTE: I have a dedicated SSD to store my virtual machines._

**Step 2:** Download all machine images

<br>

#### Ubuntu
Our Ubuntu clients will act as linux workstations in our network.

Downloads: [Desktop](https://ubuntu.com/download/desktop) , [Server](https://ubuntu.com/download/server)

<br>

#### Kali

Downloads: [VM Image](https://www.kali.org/get-kali/#kali-virtual-machines), [Full ISO](https://www.kali.org/get-kali/#kali-installer-images)

<br>

#### Windows

Downloads: [Windows 10 Evaluation](), [Windows Server Evaluation]()

<br>

#### OPNSense

Download: [OPNsense](https://opnsense.org/download/)

<br>

#### Metasploitable 2

Download: [Sourceforge](https://sourceforge.net/projects/metasploitable/)

<br>

#### **Next Step: [Setting up OPNsense Firewall](Step2.md)**





