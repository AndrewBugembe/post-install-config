<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to Configure OsTicket For HelpDesk & System Administration](https://youtu.be/83k7SXAlrCY)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Streamlined Support: It organizes and streamlines customer support by efficiently managing ticketing requests.
- Customizable Workflow: The system allows for customization of roles, departments, teams, and SLA plans to fit specific organizational needs.
- Accessibility: osTicket enables both registered and non-registered users to create tickets, making support accessible to a wider audience.
- Operational Efficiency: By assigning agents and defining help topics, it ensures that issues are routed and resolved promptly, improving overall operational efficiency.


<h2>Configuration Steps</h2>

1. **Configure Roles**
   - Roles grant permissions to agents based on the departments they have access to.
   - Each role has a set of permissions that can be checked or unchecked for agents associated with specific departments.
   - Example: *Admin Panel -> Agents -> Roles* (Supreme Admin)

2. **Configure Departments**
   - Set up departments for organizing agents.
   - Example: *Admin Panel -> Agents -> Departments* (System Administrators)

3. **Configure Teams**
   - Teams allow you to group agents from different departments to handle specific issues or users.
   - Use teams in conjunction with help topics or ticket filters.
   - Example: *Admin Panel -> Agents -> Teams*
     - Level I Support
     - Level II Support

4. **Allow Anyone to Create Tickets**
   - Enable ticket creation for all users (registered or not).
   - Example: *Admin Panel -> Settings -> User Settings*
     - Registration Required: Require registration and login to create tickets

5. **Configure Agents (Workers)**
   - Agents have access to the help desk to respond and resolve tickets.
   - Assign agents to primary departments and roles.
   - Agents can have extended access to additional departments and different roles.
   - Example: *Admin Panel -> Agents -> Add New*
     - Jane
     - John

6. **Configure Users (Customers)**
   - Users can create accounts and log in to create or check ticket status.
   - Users are associated with their email addresses as unique identifiers.
   - Example: *Agent Panel -> Users -> Add New*
     - Karen
     - Ken

7. **Configure SLA (Service Level Agreements)**
   - Define SLA plans with expected ticket closure times.
   - Plans can be unlimited.
   - Example: *Admin Panel -> Manage -> SLA*
     - SERVICE-A (1 hour, 24/7)
     - SERVICE-B (4 hours, 24/7)
     - SERVICE-C (8 hours, business hours)

8. **Configure Help Topics**
   - Define help topics for categorizing and routing tickets.
   - Example: *Admin Panel -> Help Topics -> Network issues, Login issues, Hardware etc*

<p>
<img src="https://i.imgur.com/gbgUjqv.png"/>
</p>
<p>
Configure roles in the Admin Panel to grant specific permissions to agents based on their department access, with each role offering customizable permissions for agents in various departments, such as the 'Supreme Admin' role.
</p>
<br />

<p>
<img src="https://i.imgur.com/wd7Hfg1.png"/>
</p>
<p>
<img src="https://i.imgur.com/rnpkkzh.png"/>
</p>
<p>
Organize agents into departments via the Admin Panel to improve management, such as creating a 'System Administrators' department
</p>
<br />

<p>
<img src="https://i.imgur.com/kMWf5me.png"/>
</p>
<p>
<img src="https://i.imgur.com/dv6y5yn.png"/>
</p>
<p>
Configure Teams: Group agents from various departments into teams to handle specific issues, utilizing these teams with help topics or ticket filters, like 'Level I' and 'Level II Support'.
</p>
<br />

<p>
<img src="https://i.imgur.com/sIDyxwy.png"/>
</p>
<p>
 Enable both registered and unregistered users to create tickets, with an optional registration requirement in the User Settings.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Teams: Group agents from various departments into teams to handle specific issues, utilizing these teams with help topics or ticket filters, like 'Level I' and 'Level II Support'.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Teams: Group agents from various departments into teams to handle specific issues, utilizing these teams with help topics or ticket filters, like 'Level I' and 'Level II Support'.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Teams: Group agents from various departments into teams to handle specific issues, utilizing these teams with help topics or ticket filters, like 'Level I' and 'Level II Support'.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Teams: Group agents from various departments into teams to handle specific issues, utilizing these teams with help topics or ticket filters, like 'Level I' and 'Level II Support'.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Teams: Group agents from various departments into teams to handle specific issues, utilizing these teams with help topics or ticket filters, like 'Level I' and 'Level II Support'.
</p>
<br />

