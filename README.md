# Performing-Threat-Hunting
Lab about performing threat hunting and tracking down symptoms related to IoC (Indicators of Compromise)
<h1>Assisted Lab: Performing Threat Hunting</h1>

<h2>Description</h2>
As a cybersecurity analyst, you are working to discover weaknesses and vulnerabilities that your organization, Structureality Inc., needs to mitigate throughout its internal network. In this lab, you will first use firewall logging to discover questionable network traffic. Next, you will use netstat to discover an IoC observable related to traffic abuse against a secure website. Next, you will perform focused threat hunting activities related to a few scenarios. Finally, you will investigate strange DNS activity to discover yet another IoC.

Understand your environment
You will be working from several virtual machines in this lab: <br />

LAMP hosting Ubuntu server <br />
KALI hosting a pen-testing build of Debian Linux <br />
DC10 hosting Windows Server 2019, serving as the domain controller, and hosting a secure website <br />
MS10 hosting Windows Server 2016 <br />
PC10 hosting Windows Server 2019, which is serving as a client in this lab environment <br />
Objectives
This activity is designed to test your understanding of and ability to apply content examples in the following CompTIA CySA+ objectives:

1.2 Given a scenario, analyze indicators of potentially malicious activity. <br />
1.3 Given a scenario, use appropriate tools or techniques to determine malicious activity. <br />
1.4 Compare and contrast threat-intelligence and threat-hunting concepts. <br />
3.2 Given a scenario, perform incident response activities <br />

<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Oracle Virtual Box</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> 
- <b>Server 2019</b> 
  
<h2>Program walk-through:</h2>

<p align="center">
Concept: <br/>
<img src="https://i.imgur.com/7qAqcnX.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Creating an Active Directory domain: <br/>
<img src="https://i.imgur.com/xDLq6X4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Adding names & creating user accounts and groups:  <br/>
<img src="https://i.imgur.com/njB8xKJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Scripts for adding and managing users:  <br/>
<img src="https://i.imgur.com/RXUQmto.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Configuring DHCP:  <br/>
<img src="https://i.imgur.com/YSor8Hz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Login with corporate credential:  <br/>
<img src="https://i.imgur.com/0EuZ36M.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
