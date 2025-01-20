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

- Roles and Permissions:
- Departments
- Teams
- User Ticket Creation
- Agents and Users
- Service Level Agreements (SLAs)
- Help Topics

<h2>Configuration Steps</h2>

<p>
  
## step 1: Roles and Permissions
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

- Configured roles to group permissions for agents.
- Created a "Supreme Admin" role for top-level management.
</p>
<br />
  
## Step 2: Departments

</p>
<p>
  
- Added departments to manage ticket visibility and routing:
- Help Desk
- SysAdmins
- Networking
</p>
<br />

<p>
  
## Step 3: Teams 
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

- Set up cross-department teams for specialized tasks: Online Banking
</p>
<br />

<p>
  
## Step 4: User Ticket Creation
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

- Enabled registration-required ticket creation: Admin Panel -> Settings -> User Settings
- Unchecked "Allow unregistered users to create tickets."
</p>
<br />
  
## Step 5: Agents and Users
</p>
<p>

- Added agents for handling tickets: Jane: Assigned to SysAdmins, John: Assigned to Support.
- Added users (customers): Karen, Ken
</p>
<br />

<p>
  
## Step 6: Service Level Agreements (SLAs)
</p>
<p>
  
- Configured SLAs to manage ticket priority and deadlines:
- Sev-A: 1-hour grace period (24/7 schedule).
- Sev-B: 4-hour grace period (24/7 schedule).
- Sev-C: 8-hour grace period (business hours).
</p>
<br />

<p>
  
## Step 7: Help Topics
</p>
<p>
  
- Created help topics for users to categorize tickets effectively
- Business Critical Outage
- Personal Computer Issues
- Equipment Request
- Password Reset
- Other
</p>
<br />

<p>

## Conclusion
This osTicket configuration streamlines IT support by organizing roles, departments, and teams for efficient ticket routing. With SLAs, help topics, and secure access policies, it ensures timely issue resolution and system integrity. Explore the full implementation in my GitHub repository.
</p>
<br />

## Credits
This Project is based on the template by Josh Madakor. I've customized it to suit my needs while retaining the structure and inspiration from the original work. https://github.com/joshmadakorcc/post-install-config

![Azure](https://img.shields.io/badge/Azure-Cloud-blue)

