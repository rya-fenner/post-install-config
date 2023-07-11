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

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents
- Configure Users
- Set up SLA
- Configure Help Topics

<h2>Configuration Steps</h2>
<p>
osTicket will open in the Agent panel.  Begin by selecting Admin panel in the top right corner.
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
From here, select "Agents" and then "Roles".
  Next, select "Add New Role".
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Name your role and then click on "Permissions" to configure it.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Give this new role all permissions and select "Add Role".
</p>
<br />
While remaining in the Agents tab, select "Departments".  By default you should see Support and Maintenance.

Click "Add New Department".

Title your new department "System Administrators".

From here you may select any SLA (we will explore how to customize this next) and assign a schedule for responding to tickets.  For now, you can leave all of this as default and click "Creat Dept" to finalize.

Next we will explore how to set up and configure teams of agents.

While remaining in the Agents tab, select "Teams".

Select "Add New Team" to create a new team.

Name this new team "Level II Support"

Select "Members" and make your only used a member by selectin their name from the drop-down menu and clicking "Create Team".

Next we want to allow anyone to create a ticket.
