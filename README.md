<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to Deploy on-premises Active Directory within Azure Compute](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Ensure Connectivity between client and domain controller
- Install Active Directory
- Create a Normal User and Admin acct in Active Directory
- Run the script and observe the accounts being created

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/jCDSwAb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/wa1eNOk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Log into the DC and enable ICMPv4 in the local windows Firewall to connect the client and DC. I logged into the client and pinged DC's private IP to ensure the connectivity between the client and the domain controller.
</p>
<br />

<p>
<img src="https://i.imgur.com/SLE4ICP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Installed Active Directory.
</p>
<br />

<p>
<img src="https://i.imgur.com/s5zS92W.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
