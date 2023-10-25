<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configuring Roles, Departments, Teams
- Configuring Agents and Users
- Configuring Service Level Agreements
- Configuring Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/XDTbOhl.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/aKGEQMC.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/Le81IAF.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
This step involved configuring roles, departments and teams for OS ticket. I established a supreme admin for roles, I created a system administrators for departments and I established two separate teams: level I support and level II support. These separate teams serve two different functions.
</p>
<br />

<p>
<img src="https://i.imgur.com/IDQcqkn.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/mxCm3WW.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
I configured two separate groups agents(workers) and users(customers). Since it is a project and I wanted to test the interface, I created the users group to see how the ticketing system work. The agent group was created by navigating to the admin panel then I created an agent subgroup and added two new agents, who are Help Desk Agents. The user group was by navigating to the agent panel I created an user subgroup and added two new customers.
</p>
<br />

<p>
<img src="https://i.imgur.com/JjAQRk3.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
A service level agreement is essentially the amount of time required to complete a ticket. Navigating from Admin panel to manage to SLA I added three different service level agreements: Sev-A(1 hour, 24/7), Sev-B(4 hours, 24/7) and Sev-C(8 hours, business hours).
</p>
<br />

<p>
<img src="https://i.imgur.com/O2oITYG.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
The help topics section is the reason for the ticket. In this case, I created four different options that a user can select as their reason for creating a ticket. The reasons in this case were business critical outage, personal computer issues, equipment request and password reset.
</p>
<br />
