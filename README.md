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

<h2>Admin/Analyst Access</h2>

- Admin Panel: Login http://localhost/osTicket/scp/login.php

- End User Portal: User http://localhost/osTicket
  
## step 1: Roles and Permissions
![image](https://github.com/user-attachments/assets/ddc6d53f-6085-430c-9e18-38758195dda9)
</p>
<p>

- Configured roles to group permissions for agents.
- Created a "Supreme Admin" role for top-level management.
</p>
<br />
  
## Step 2: Departments
## SysAdmins
![image](https://github.com/user-attachments/assets/27c00a89-d0f0-4325-b641-d3e1b864bdf1)

## Help Desk
![image](https://github.com/user-attachments/assets/6f399d97-14f0-403e-8b7a-35b61b8032db)

</p>
<p>
  
- Added departments to manage ticket visibility and routing
</p>
<br />

<p>
  
## Step 3: Teams 
![image](https://github.com/user-attachments/assets/bcfb950d-307f-4bd2-a87d-40e1597b7860)
</p>
<p>

- Set up cross-department teams for specialized tasks: Online Banking
</p>
<br />

<p>
  
## Step 4: User Ticket Creation
![image](https://github.com/user-attachments/assets/6b2a7c1a-e87c-4443-8a82-96f91d3c6b8a)

</p>
<p>

- Enabled registration-required ticket creation: Admin Panel -> Settings -> User Settings
- Unchecked "Allow unregistered users to create tickets."
</p>
<br />
  
## Step 5: Agents and Users
## Agent John 
![image](https://github.com/user-attachments/assets/c82c036a-4fec-457e-92db-0859a13a7767)

## Agent Jane
![image](https://github.com/user-attachments/assets/f7c975e9-1239-41b3-b6f4-d40246a2564b)
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

