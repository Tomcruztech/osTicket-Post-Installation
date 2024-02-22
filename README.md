<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)



<h2>Configuration Steps</h2>


---

## Part 3: Post Installation Setup

### Configure Roles
1. **Admin Panel -> Agents -> Roles**
   - Supreme Admin

### Configure Departments
2. **Admin Panel -> Agents -> Departments**
   - System Administrators

### Configure Teams
3. **Admin Panel -> Agents -> Teams**
   - Level I Support
   - Level II Support

### Allow anyone to create tickets
4. **Admin Panel -> Settings -> User Settings**
   - Registration Required: Require registration and login to create tickets 

### Configure Agents (workers)
5. **Admin Panel -> Agents -> Add New**
   - Jane
   - John

### Configure Users (customers)
6. **Agent Panel -> Users -> Add New**
   - Karen
   - Ken

### Configure SLA
7. **Admin Panel -> Manage -> SLA**
   - Sev-A (1 hour, 24/7)
   - Sev-B (4 hours, 24/7)
   - Sev-C (8 hours, business hours)

### Configure Help Topics
8. **Admin Panel -> Manage -> Help Topics**
   - Business Critical Outage
   - Personal Computer Issues
   - Equipment Request
   - Password Reset
![image](https://github.com/Tomcruztech/osTicket-Post-Installation/assets/160645953/ad2814dc-e7c8-407d-9995-ca33a7be1443)

![image](https://github.com/Tomcruztech/osTicket-Post-Installation/assets/160645953/65a95cd9-60c5-448c-b78a-4fd34a967339)


