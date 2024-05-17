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
</p>
To configure roles, go to: Admin Panel > Agents > Roles. Add role. Name it and enable all ticket permissions.
<p>
<img src="https://imgur.com/5ZgRsnl.png" height="80%" width="40%"/>
<img src="https://imgur.com/6N3dB8N.png" height="80%" width="40%"/>
</p>
<p>
To create Departments, Go to Admin Panel > Agents > Departments, Name the department and select a manager. Click "Create Dept" at the bottom of the page.
</p>
<img src="https://imgur.com/L5dLBWM.png" height="80%" width="60%"/>
<img src="https://imgur.com/7cdMcsX.png" height="80%" width="60%"/>
<p>
<p>
Next, go to Admin Panel -> Agents -> Teams. Select "Add team". Name it "Level II Support" and add member by clicking on "Members" tab. Go to Admin Panel > Settings > User Settings to make sure the registration required box is not checked to allow anyone to create tickets.
</p>
<img src="https://imgur.com/904v9kg.png" height="80%" width="60%">
<img src="https://imgur.com/5ZUfS6t.png" height="80%" width="60%">
<p>
</p>
Go to Admin Panel -> Agents and click "Add new agent". Create name and email. Press the set password button. Deselect the "Send the agent a password reset" box and create a password. Deselect the "require password change" box and press "set".

<img src="https://imgur.com/Q2Z78Dn.png" height="80%" width="60%"/>
<img src="https://imgur.com/qt3iZYO.png" height="80%" width="60%"/>
<p>
<p>
Click on "Access" tab and select "System Administrators". Also select the department you created. In extended access below, select the department you created and add "support" department as well. Next, click on "teams" tab and select the team you created. Click "Create". Add another agent with limited permissions.
</p>
<img src="https://imgur.com/uLRAzBv.png" height="80%" width="60%">
<img src="https://imgur.com/oMRTTHn.png" height="80%" width="60%">
<img src="https://imgur.com/MkjlVV7.png" height="80%" width="60%">
<p>
<p>
To create users, switch to Agent Panel > Users > and click on "Add user". Create name and email, click "Add User".
<img src="https://imgur.com/buqOZQP.png" height="80%" width="60%">
<img src="https://imgur.com/06aTuBE.png" height="80%" width="60%">
</p>
<p>
Go to Admin Panel > Manage > SLA and click "add new SLA plan". Place these settings for Sev-A: (1 hour, 24/7). Sev-B will be (4 hours, 24/7) and Sev-C will be (8 hours, Monday - Friday).
<p>
<img src="https://imgur.com/NzbHMRr.png" height="80%" width="60%">
<img src="https://imgur.com/qzy4zoB.png" height="80%" width="60%">
<p>
<p>
Go to Admin Panel > Manage > Help Topics and click "Add help topic". Title the first one "Business Critical Outage", the second "Personal Computer Issues", the third "Equipment Request", and lastly "Password Reset". You can also set the departments, priority, SLA plan, and other features associated with each type of Help Topic.
<p>
<img src="https://imgur.com/xu9JJdF.png" height="80%" width="60%">
<img src="https://imgur.com/oAcWL10.png" height="80%" width="60%">
</p>
<br />
