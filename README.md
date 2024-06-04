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

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 1. Configure Roles

- Admin Panel -> Agents -> Roles -> Add New role
- Add a name
- Click "Permissions" and Check all boxes on Tickets\Tasks\Knowledgebase
- Click Add Role
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 2. Configure Departments

- Admin Panel -> Agents -> Departments
- Click "Add New Department"
- Name it System Administrators
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 3. Configure Teams

- Admin Panel -> Agents -> Teams
- Click on "Add new Team"
- Name it "Level II Support"
  
Note: There should be a "Level I Support" team already there
</p>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 4. Allow anyone to create tickets

- Admin Panel -> Settings -> User Settings
- Make sure the "require registration and login to create tickets" box is unchecked
</p> 

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 5. Configure Agents (Workers)

- Admin Panel -> Agents -> Add New Agent
- Jane Doe - username: Jane.doe, "Access" System Administrators and Superb Admin, "Teams" put on Team II
- John Doe - username: John.doe, "Access" Support, View only

</p>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 6. Configure Users (Customers)

- Agent Panel -> Users -> Add New
- Sarah Doe
- Ken Doe
</p>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 7. Configure SLA

- Admin Panel -> Manage -> SLA
- Sev-A (1 hour, 24/7)
- Sev-B (4 Hours, 24/7)
- Sev-C (8 hours, Business Hours)
</p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 8. Configure Help Topics

- Admin Panel -> Manage -> Help Topics
- Business Critical Outage
- Personal Computer Issues
- Password Reset
</p>
<br />
