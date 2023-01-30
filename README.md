<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Installed Active Directory Domain Services onto a virtual machine "Domain Controller, DC-1"
- Joined a different virtual machine "Client 1" to Domain Controller, DC-1's private IP address
- Created and added accounts in Powershell ISE

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/iw5ug5X.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Created a virtual machine in Azure and installed Active Directory Domain Services onto that virtual machine.
</p>
<br />

<p>
<img src="https://i.imgur.com/m46DKfg.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the Azure portal I joined the Client-1 virtual machine to the Domain Controls virtual machines server with DC-1's private IP address.
</p>
<br />

<p>
<img src="https://i.imgur.com/rRifK51.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
As an Administrator in Powershell ISE, I created and added 10,000 accounts with the ability to log into the network.
</p>
<br />
