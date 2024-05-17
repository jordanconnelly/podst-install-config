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
- Configure Teams and Departments
- Configure Agents
- Configure SLA
- Create Help Topics

<h2>Configuration Steps</h2>

<p>
Sign into osTicket using the Admin information created in the prerequisite stage. Confirm you are in the Admin panel at the top right of the page, if "Agent Panel" is displayed that means you are in the Admin panel. This is how you switch between Admin & Agent panels.
<p>
<img src="https://imgur.com/pN7NoHm.png" height="80%" width="40%"/>
<img src="https://imgur.com/imbBSvS.png" height="80%" width="40%"/>
<p>
To configure roles, go to: Admin Panel > Agents > Roles. Add role. Name it and enable all ticket permissions.
<p>
<img src="https://imgur.com/5ZgRsnl.png" height="80%" width="40%"/>
<img src="https://imgur.com/6N3dB8N.png" height="80%" width="40%"/>
</p>
</p>
<br />

<p>
<img src="https://i.imgur.com/2CTnRRu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go to Admin Panel > Agents > Departments, Name the department and select a manager. Click "Creat Dept". Next, go to Admin Panel -> Agents -> Teams. Select "Add team". Name it "Level II Support" and add member by clicking on "Members" tab. Go to Admin Panel > Settings > User Settings to make sure that the registration required box is not checked.
</p>
<br />

<p>
<img src="https://i.imgur.com/OIsYUDw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go to Admin Panel -> Agents and click "Add new agent". Create name and email. Press the set password button. Deselect the "Send the agent a password reset" box and create a password. Deselect the "require password change" box and press "set". Click on "Access" tab and select "System Administrators". Also select the department you created. In extended access below, select the department you created and add "support" department as well. Next, click on "teams" tab and select the team you created. Click "Create". Add another agent with limited permissions. To create users, go to Agent Panel > Users > and click on "Add user". Create name, email and password. Click "Add User".
</p>
<br />

<p>
<img src="https://i.imgur.com/rVfrerR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go to Admin Panel > Manage > SLA and click "add new SLA plan". Place these settings for Sev-A: (1 hour, 24/7). Sev-B will be (4 hours, 24/7) and Sev-C will be (8 hours, Monday - Friday).
</p>
<br />

<p>
<img src="https://i.imgur.com/sY9NZGT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  Go to Admin Panel > Manage > Help Topics and click "Add help topic". Title the first one "Business Critical Outage", the second "Personal Computer Issues", the third "Equipment Request", and lastly "Password Reset". Log into the user portal of osTicket at: http://localhost/osTicket/. Use a user you created to create tickets.
</p>
<br />
