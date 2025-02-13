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


<h2>Deployment and Configuration </h2>


![image](https://github.com/user-attachments/assets/4b92de5f-d89b-48b9-9554-0d9e717ac1b4)
</p>
<p>
Downloading Active directory domain services (AD DS) is required to set up an Active Directory domain, allowing centralized management of users, computers, and security policies.
</p>
<br />

![image](https://github.com/user-attachments/assets/6e0cd1a7-4c4e-4f2a-8be6-57289ed9a38d)
</p>
<p>
Creating and placing admin users in a dedicated OU named “Admins” allows IT teams to easily manage and apply policies specific to administrators. This keeps admin accounts separate from regular users, reducing security risks.
</p>
<br />

![image](https://github.com/user-attachments/assets/78a293af-9422-4559-84c3-d39750b1ff9d)
</p>
<p>
Through the virtual machine adding the client to domain.com to show up in Active Directory Users and Computers.
</p>
<br />


![image](https://github.com/user-attachments/assets/c7c595dd-6a16-4214-aa1e-68a58c23dc88)
</p>
<p>
Here is when I am setting up Account Policies in Group Policy Management Editor (GPME). This is essential for enforcing security, compliance, and account management rules within an Active Directory (AD) domain.
</p>
<br />



