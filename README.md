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
- Configure SLA
- Configure Help topics

<h2>Configuration Steps</h2>

<p>

![Screenshot_152](https://github.com/user-attachments/assets/5dd73cd5-bf59-45ba-9754-98439e9d7d7e)

</p>
<p>

- Configure Roles

    - Navigate to Admin Panel -> Agents -> Roles

    - Add a new role 'Supreme Admin' (All names in this section can be changed to meet your specific needs)

      - Give this new role all permissions

- Configure Departments

  - Navigate to Admin Panel -> Agents -> Departments

  - Add a new role 'System Administrators' 

- Configure Teams

  - navigate to Admin Panel -> Agents -> Teams

  - Add a new team 'Level II Support'

- Ensure anyone can create support tickets (Or not)

  - Navigate to Admin Panel -> Settings -> Users

  - Under 'Authentication Settings' look to 'Registration Required'

    - If checked, users will need to be logged in to create tickets

    - If unchecked, users will not need to be logged in to create tickets

</p>
<br />

<p>

![Screenshot_153](https://github.com/user-attachments/assets/c2f4de5a-0310-4093-8241-f59813b49f8b)

</p>
<p>

- Configure Agents

    - Navigate to Admin Panel -> Agents -> Add New

      - Set their password as needed or keep the box checked to have a password reset email sent to them


</p>
<br />

<p>

![Screenshot_154](https://github.com/user-attachments/assets/6299da4e-1eee-49f6-b29b-d4f516b04739)

</p>
<p>

- Configure Users

    - Switch to the Agent Panel in the upper right corner

    - Navigate to Agent Panel -> Users -> Add User

</p>
<br />

<p>

![Screenshot_155](https://github.com/user-attachments/assets/7ebbfb4d-08c1-4908-9a15-096e11f3cb81)

</p>
<p>

- Configure SLA

  - Switch back to the Admin Panel in the upper right corner

  - Navigate to Admin Panel -> Manage -> SLA -> Add New SLA Plan

- Configure Help Topics

  - Navigate to Admin Panel -> Manage -> Help Topics -> Add New Help Topic




</p>
