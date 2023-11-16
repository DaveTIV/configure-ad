<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1> Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of Active Directory within Azure Virtual Machines.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Create Resource Group for AD 
- Create a Domain VM(Windows Server)
- Create the Client VM(Windows 10)
- Install Active Directory on Domain Server
- Create Organizational Units and Users in AD

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/4tHT0GI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
Here shows I have created a resource group "AD-Lab".
</p>
<img src="https://i.imgur.com/bO7mA8h.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
Here I have created the Domain Controller(DC-1) and the Client VM(Client-1) under the AD resource group.
</p>
<img src="https://i.imgur.com/ad3EqdV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
Here I am in the DC-server pre-installing Active Directory.
</p>
<img src="https://i.imgur.com/UaLpITA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
Here I have created two Organizational Units, "_ADMINS" and "_EMPLOYEES".
</p>
<img src="https://i.imgur.com/18jFeg2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
Here I opened Powershell ISE as an administrator, ran a script and created 100 users in AD.
