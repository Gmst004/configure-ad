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

- Remotedesk into domain controller (DC-1) 
- Start Active Directory installation.
- Link both virtual machines (VM) on th same server.
- Create employes using powershell.

<h2>Deployment and Configuration Steps</h2>

<p>




This meticulous installation is a key element in establishing a resilient and efficient Active Directory environment, laying the groundwork for streamlined user authentication, resource management, and centralized administration.

![Activedir](https://github.com/Gmst004/configure-ad/assets/155221840/22b1ac6f-3c37-42c9-8908-4bfff3948a17)



<p>

![powersheel](https://github.com/Gmst004/configure-ad/assets/155221840/d6ce0a6d-2b66-42a9-bb1c-20a6707aabd8)

<p>
Executing a pre-written script has become the next pivotal phase in this deployment process. With the script designed to generate over 10,000 employee accounts, I initiate the automated procedure on the domain controller. Once a significant portion of these accounts is generated, the focus shifts to a testing phase.
</p>
<br />

<p>

![users](https://github.com/Gmst004/configure-ad/assets/155221840/85402303-e2f3-44ca-be0d-315a96196a76)

<p>
This is the location where employees will be displayed when utilizing PowerShell for employee creation from this point, we have the flexibility to choose any name and verify the correct creation of the account.
We can select any account to test its login functionality
</p>
<br />
