<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Laptop/PC with a internet connection
- Virtual Machine (VmWare, Virtual box, Azure portal).
  - Check how to create a virtual machine and install osTicket [here](https://github.com/sdaramola08/osticket-prereqs) 

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h2>Post-Installation Configuration</h2>

- Configure [Roles](https://docs.osticket.com/en/latest/Admin/Agents/Roles.html)
   - Admin Panel -> Agents -> Roles
   - Supreme Admin
- Configure [Departments](https://docs.osticket.com/en/latest/Admin/Agents/Departments.html)
  - Admin Panel -> Agents -> Departments
  - System Administrators
- Configure [Teams](https://docs.osticket.com/en/latest/Admin/Agents/Teams.html)
  - Admin Panel -> Agents -> Teams
    - Level I Support
    - Level II Support
- Allow anyone to create tickets
  - Admin Panel -> Settings -> User Settings
  - Registration Required: Require registration and login to create tickets 
- Configure [Agents (workers)](https://docs.osticket.com/en/latest/Admin/Agents/Agents.html)
  - Admin Panel -> Agents -> Add New
    - Michael
    - John
- Configure [Users (customers)](https://docs.osticket.com/en/latest/Agent/Users/User%20Directory.html)
  - Agent Panel -> Users -> Add New
    - Jane
    - Ben
- Configure [SLA](https://docs.osticket.com/en/latest/Admin/Manage/SLA%20Plans.html)
  - Admin Panel -> Manage -> SLA
    - Sev-A (1 hour, 24/7)
    - Sev-B (4 hours, 24/7)
    - Sev-C (8 hours, business hours)
- Configure Help Topics
  - Admin Panel -> Manage -> Help Topics
    - Business Critical Outage
    - Personal Computer Issues
    - Equipment Request
    - Password Reset
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
