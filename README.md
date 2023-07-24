<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This repository outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles, Departments, and Teams
- Allow any user to create tickets
- Configure Agents, Users, and SLAs
- Configure help topics

<h2>Configuration Steps</h2>

<p>
Configure Roles by navigating to the Admin Panel > Agents tab > Roles > Add New Role. This role will have full permissions so choose an appropriate name then navigate to the permissions tab and ensure all boxes are checked.
</p>
<br />

![config-roles](https://github.com/NicholasLudwig/post-install-config/assets/104456331/6112d9df-4c22-48a8-bf43-bba55b870342)

<br />
<p>
Configure Departments by navigating to Agents > Departments > Add New Department. This new department will be for System Administrators. Leave default settings for now as the SLAs and team members have not been created yet.
</p>
<br />

![config-depts](https://github.com/NicholasLudwig/post-install-config/assets/104456331/635e4c9c-d75d-4002-bac1-c351fbaf33b0)

<br />
<p>
Configure Teams by navigating to Agents > Teams > Add New Team. This team is for Level II Support. Enter the name and click Create Team.
</p>
<br />

![config-teams](https://github.com/NicholasLudwig/post-install-config/assets/104456331/6dfbfa28-e02f-43f7-94a7-0dad744aae68)

<br />
<p>
Allow anyone to create a ticket by navigating to Admin Panel > Settings > Users > Settings and ensure that the box for Registration required is <b>unchecked</b>.
</p>
<br />

![reg-reqs](https://github.com/NicholasLudwig/post-install-config/assets/104456331/7f432997-b920-49a6-a2aa-db1e09fb30b5)

<br />
<p>
Configure Agents by navigating to Admin Panel > Agents > Add New Agent. Create as many new agents as needed making sure to set a password. Ensure that the boxes requiring a password reset are unchecked. Assign new agents to appropriate Departments and Teams by navigating to the appropriate tab of the agent setup.
</p>
<br />

![agent-setup](https://github.com/NicholasLudwig/post-install-config/assets/104456331/dafa0142-ca3a-4bb5-8402-63d6d69c9fe1)

<br />
<p>
Configure Users by navigating to Agent Panel > Users > Add User. Enter the information for your new users (just a simple name and email address is all that is required).
</p>
<br />
<p>
Configure SLA by navigating to Admin Panel > Manage > SLA and create 3 new SLAs.
  <ul>
    <li>Sev-A (1 hour, 24/7)</li>
    <li>Sev-B (4 hours, 24/7)</li>
    <li>Sev-C (8 hours, normal business hours)</li>
  </ul>
</p>
<br />

![config-SLA](https://github.com/NicholasLudwig/post-install-config/assets/104456331/4ed65d47-9b48-43c7-8423-8df6d89abfc5)

<br />
<p>
Configure Help Topics by navigating to Admin Panel > Manage > Help Topics > Add New Help Topic and create 4 new Help Topics.
  <ul>
    <li>Business Critical Outage</li>
    <li>Personal Computer Issues</li>
    <li>Equipment Request</li>
    <li>Password Reset</li>
  </ul>
</p>
<br />

![config-topics](https://github.com/NicholasLudwig/post-install-config/assets/104456331/68b7d7e7-6699-469f-8fbc-57b8e81158f8)

