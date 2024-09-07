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

<h2>Operating Systems Used</h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Create a Domain Controller and a Client VM on the same VNet.
- Ensure connectivitey between the DC and Client VM's using PowerShell.
- Install Active Directory Domain Services on the DC and create a new domain.
- Join the Client VM to the domain and setup remote desktop for non-administrative users.
- Create a bunch of additional users using PowerShell_ise and attempt to login to the Client VM with one of the new users.

<h2>Deployment and Configuration Steps</h2>
