# Performing-Threat-Hunting CompTIA CySA Lab
Lab about performing threat hunting and tracking down symptoms related to IoC (Indicators of Compromise)
<h1>Assisted Lab: Performing Threat Hunting</h1>

<h2>Description</h2>
As a cybersecurity analyst, you are working to discover weaknesses and vulnerabilities that your organization, Structureality Inc., needs to mitigate throughout its internal network. In this lab, you will first use firewall logging to discover questionable network traffic. Next, you will use netstat to discover an IoC observable related to traffic abuse against a secure website. Next, you will perform focused threat hunting activities related to a few scenarios. Finally, you will investigate strange DNS activity to discover yet another IoC.

1.2 Given a scenario, analyze indicators of potentially malicious activity. <br />
1.3 Given a scenario, use appropriate tools or techniques to determine malicious activity. <br />
1.4 Compare and contrast threat-intelligence and threat-hunting concepts. <br />
3.2 Given a scenario, perform incident response activities <br />

<br />


<h2>Languages, Utilities Used and Environment used :</h2>

- LAMP hosting Ubuntu server <br />
- KALI hosting a pen-testing build of Debian Linux <br />
- DC10 hosting Windows Server 2019, serving as the domain controller, and hosting a secure website <br />
- MS10 hosting Windows Server 2016 <br />
- PC10 hosting Windows Server 2019, which is serving as a client in this lab environment <br />


<h2>Program walk-through:</h2>

<p align="center">
<br/>
<img src="https://i.imgur.com/kVfgblX.png" alt="Disk Sanitization Steps"/>
<br />
<br />
<br/>
<img src="https://i.imgur.com/9nLZaux.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br/>
<img src="https://i.imgur.com/wKZ2l3J.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br/>
<img src="https://i.imgur.com/jXvnurv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br/>
<img src="https://i.imgur.com/OLEnAne.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br/>
<img src="https://i.imgur.com/mgEoO2c.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br/>
<img src="https://i.imgur.com/b1zIFhI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br/>
<img src="https://i.imgur.com/8u7Tp9K.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br/>
<img src="https://i.imgur.com/QODCx1r.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br/>
<img src="https://i.imgur.com/ytzA0sf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br/>
<img src="https://i.imgur.com/sHndjL2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br/>
<img src="https://i.imgur.com/GsBwKOP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
br/>
<img src="https://i.imgur.com/wMcy0L4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br/>
<img src="https://i.imgur.com/0lslA4Q.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
