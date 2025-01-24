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

- **Step 1**:Roles and Permissions:
- **Step 2**:Departments
- **Step 3**:Teams
- **Step 4**:User Ticket Creation
- **Step 5**:Agents and Users
- **Step 6**:Service Level Agreements (SLAs)
- **Step 7**:Help Topics

<h2>Configuration Steps</h2>

<p>

<h2>Admin/Analyst Access</h2>

- Admin Panel: Login http://localhost/osTicket/scp/login.php

- End User Portal: User http://localhost/osTicket
  
## step 1: Roles and Permissions
![image](https://github.com/user-attachments/assets/ddc6d53f-6085-430c-9e18-38758195dda9)
</p>
<p>

- Configured roles to group permissions for agents: Agent / Roles / Add new role 
- Created a "Supreme Admin" role for top-level management.
</p>
<br />
  
## Step 2: Departments
## SysAdmins
![image](https://github.com/user-attachments/assets/27c00a89-d0f0-4325-b641-d3e1b864bdf1)
- Agent / Departments / add new Department / Sysadmin
  
## Help Desk
![image](https://github.com/user-attachments/assets/6f399d97-14f0-403e-8b7a-35b61b8032db)
- Agent / Departments / add new Department / Helpdesk
</p>
<p>
  
- Added departments to manage ticket visibility and routing
</p>
<br />

<p>
  
## Step 3: Teams 
## Online Banking
![image](https://github.com/user-attachments/assets/bcfb950d-307f-4bd2-a87d-40e1597b7860)
</p>
<p>

- Set up cross-department teams for specialized tasks: Agent / Teams / add new team / Online Banking
</p>
<br />

<p>
  
## Step 4: User Ticket Creation
![image](https://github.com/user-attachments/assets/6b2a7c1a-e87c-4443-8a82-96f91d3c6b8a)

</p>
<p>

- Enabled registration-required ticket creation: Admin Panel / Settings / User Settings
- Unchecked "Allow unregistered users to create tickets."
</p>
<br />
  
## Step 5: Agents and Users
## Agent John 
![image](https://github.com/user-attachments/assets/c82c036a-4fec-457e-92db-0859a13a7767)
- Agent / Agent / Add new agent:  John: Assigned to Support/Helpdesk
 
## Agent Jane
![image](https://github.com/user-attachments/assets/f7c975e9-1239-41b3-b6f4-d40246a2564b)
- Agent / Agent / Add new agent:  Jane: Assigned to SysAdmins
</p>
<p>

- Added agents for handling tickets.
</p>
<br />

## User Karen
![image](https://github.com/user-attachments/assets/e8e375f3-4896-4723-895c-cff38c6f81dd)
- Agent Panel / Users / Add user: Karen
- 
## User Ken
![image](https://github.com/user-attachments/assets/3740c420-f13d-49e6-85a6-772e1dd3d9a8)
- Agent Panel / Users / Add user: Ken
</p>
<p>
  
- Added users (customers)
</p>
<br />

<p>
  
## Step 6: Service Level Agreements (SLAs)
## Sev-A
![image](https://github.com/user-attachments/assets/16dfdc00-bd9c-455c-9e64-c85b7846745f)
 - Manage / SLA / Add new SLA plan
 - Sev-A: 1-hour grace period (24/7 schedule).
  
## Sev-B 
![image](https://github.com/user-attachments/assets/4dfa60c0-e36b-4c2a-891a-1ac4b6216ae1)
 - Manage / SLA / Add new SLA plan
 - Sev-B: 4-hour grace period (24/7 schedule).
   
## Sev-C
![image](https://github.com/user-attachments/assets/abbee200-a614-45df-8705-371b6bb1219b)
 - Manage / SLA / Add new SLA plan
 - Sev-C: 8-hour grace period (business hours).
</p>
<p>
  
- Configured SLAs to manage ticket priority and deadlines

</p>
<br />

<p>
  
## Step 7: Help Topics
</p>
<p>
  
- Created help topics for users to categorize tickets effectively

## Business Critical Outage
![image](https://github.com/user-attachments/assets/1179a027-c7c7-47b6-b9af-2d4dc2c4fa72)
- Manage / Help topics / Add new help topic / Business critical outage
- Parent Topic: Report a problem
  
## Personal Computer Issues
![image](https://github.com/user-attachments/assets/818ee26c-10ef-4942-a54a-6e1a0bb7c268)
- Manage / Help topics / Add new help topic / Personal computer issues
- Parent Topic: Report a problem
- 
## Equipment Request
![image](https://github.com/user-attachments/assets/683c7710-48f4-4013-8b12-095814be4298)
- Manage / Help topics / Add new help topic  / Equipment Request
- Parent Topic: General Inquiry

## Password Reset
![image](https://github.com/user-attachments/assets/4f09ab04-112a-4fb8-8c59-331480d99d81)
- Manage / Help topics / Add new help topic / Password Reset
- Parent Topic: Report a problem
  
## Other
![image](https://github.com/user-attachments/assets/f55411b9-6945-4787-b789-de0548b1da3b)
- Manage / Help topics / Add new help topic / Other
- Parent Topic: General Inquiry
</p>
<br />

<p>

## Conclusion
This osTicket configuration streamlines IT support by organizing roles, departments, and teams for efficient ticket routing. With SLAs, help topics, and secure access policies, it ensures timely issue resolution and system integrity. Explore the full implementation in my GitHub repository.
</p>
<br />


![Azure](https://img.shields.io/badge/Azure-Cloud-blue)

