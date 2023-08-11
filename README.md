<h1>Hardening Kali Linux</h1>

<h2>Description</h2>
In this lab, a Kali Linux system was hardened to enhance its security by mitigating vulnerabilities. The process involved eliminating outdated software, default passwords, and improving the firewall configuration to reduce the potential attack surface. 

The first step was the installation of VirtualBox, a hypervisor facilitating the creation of a virtual OS within the host system. Subsequently, a Kali Linux virtual machine was set up using VirtualBox. With the Kali Linux VM up and running, both the command line and graphical user interface (GUI) were utilized to carry out the hardening procedures.

The activities included updating the operating system, modifying the default user password, creating new user accounts, managing user groups, and configuring the firewall settings. Through these measures, the security of the Kali Linux system was significantly bolstered.
<br />

<h2>Languages and Utilities Used</h2>

- <b>Oracle VirtualBox</b> 
- <b>Kali Linux</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> 

<h2>Program walk-through:</h2>

<p align="center">
Start Kali Linux: <br/>
<img src="https://imgur.com/5dyRxfS.png" height="80%" width="80%" alt="Hardening Kali Linux"/>
<br />
<br />
Password changed using command: <br/>
<img src="https://imgur.com/U2rONbb.png" height="80%" width="80%" alt="Hardening Kali Linux"/>
<br />
<br />
Password changed using GUI: <br/>
<img src="https://imgur.com/Lx1Ljez.png" height="80%" width="80%" alt="Hardening Kali Linux"/>
<br />
<br />
Add user using command: <br/>
<img src="https://imgur.com/hNefXJ6.png" height="80%" width="80%" alt="Hardening Kali Linux"/>
<br />
<br />
Add user using GUI: <br/>
<img src="https://imgur.com/5o03ADJ.png" height="80%" width="80%" alt="Hardening Kali Linux"/>
<br />
<br />
Manage user group: <br/>
<img src="https://imgur.com/V94zMJ5.png" height="80%" width="80%" alt="Hardening Kali Linux"/>
<br />
<br />
Configure the firewall using ufw: <br/>
<img src="https://imgur.com/204i5rd.png" height="80%" width="80%" alt="Hardening Kali Linux"/>
<br />
<br />
Allow & Deny rules - 
Port 22 is for the Secure Shell Protocol (SSH), so, created a rule that allows traffic on port 22. Port 80 is for HTTP web activity. So, create a rule that allows traffic on port 80. Port 23 is for the Telnet protocol,But unlike port 22, port 33 does not encrypt data, so blocking it is a security best practice: <br/>
<img src="https://imgur.com/Ns3Y0RE.png" height="80%" width="80%" alt="Hardening Kali Linux"/>
<br />
<br />

</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
