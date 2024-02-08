## Step 1: Preparing Images and Machines

First we must configure our virtual machine software. This project uses VMware Workstation Pro 17 which requires a paid license key. However, there is a trial version of this software that can used. This configuration should be achieveable on free desktop hypervisor solutions such as Virtual Box or VMware Workstation Player.

<br>

### Getting Images
---

#### Ubuntu

Downloads: [Desktop](https://ubuntu.com/download/desktop)

Our Ubuntu clients will act as linux workstations in our network. 

<br>

**<p align="center">Desktop Client</p>**
![alt](https://i.imgur.com/9ajMNLD.png)

<br>

#### Kali

Downloads: [VM Image](https://www.kali.org/get-kali/#kali-virtual-machines), [Full ISO](https://www.kali.org/get-kali/#kali-installer-images)

Kali is a distribution of Linux that has many cybersecurity and penetration testing tools pre-installed. In this lab, Kali is going to be the operating system that the threat actor will use in the network. Although the virtual machine image is being used in this project, the full installer ISO can also be used instead. For this instance, download the **VMware Image** and save it to your computer.

<br>

**<p align="center">VM Download</p>**

![alt](https://i.imgur.com/bqNVdfu.png)

<br>

#### Pfsense

Download: [Pfsense Community Edition](https://www.pfsense.org/download/))

Pfsense is an open source firewall solution that will be used to filter and monitor the traffic that is coming into our network. 

<br>

![https://i.imgur.com/Cj9aGY5.png](https://i.imgur.com/LB8E9Qo.png)

<br>

#### Metasploitable 2

Download: [Sourceforge](https://sourceforge.net/projects/metasploitable/)

Metasploitable is a deliberately vulnerable linux server that can be used to test various red-team functions.

<br>

![alt](https://i.imgur.com/9gSQztD.png)

<br>

#### **Next Step: [Setting up Pfsense Firewall](Step2.md)**





