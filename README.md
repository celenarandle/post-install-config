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

- Create Roles
- Create Departments  
- Create Teams
- Add Agents
- Establish SLAs

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/CEJDQdl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now that osTicket is up and running, it's time to do some configuring! Here, Roles are being added. From the Admin Panel>Agents>Roles>name this role "Supreme Admin". This process can be followed to add Departments and Teams as well.
</p>
<br />

<p>
<img src="https://i.imgur.com/2AC1AxB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
When the Roles, Departments, and Teams are created, Permissions must be added as well.
</p>
<br />

<p>
<img src="https://i.imgur.com/JL92fKh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this step. it is established that anyone will be allowed to create tickets (Admin Panel>Settings>User Settings) and it is important to choose to 'Require registration and login to create tickets'.
</p>
<br />

<p>
<img src="https://i.imgur.com/I47zSi3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After the Roles and Departments have been created with their desired Permissions, Agents may be added. Agents' profiles, once created, may have the necessary Access, Permissions, and Team(s) assigned. Admin Panel>Agents>Add New. Agent Panel>Users>Add New is the path to also use in order to add Users to osTicket.
</p>
<br />

<p>
<img src="https://i.imgur.com/cFNnAMQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this step, the SLAs {Service Level Agreements) are being established. These SLAs set the expectations for the timeframe in which the tickets are to be serviced. Admin Panel>Manage>SLA
</p>
<br />

<p>
<img src="https://i.imgur.com/04bBFTn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here, Help Topics are being added. These are used while working the tickets and can be helpful in determining the correct SLA for the issue at hand. Admin Panel>Manage>Help Topics
</p>
<br />
