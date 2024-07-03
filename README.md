<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>
<h1>osTicket - Post-Installation Configuration</h1>
This tutorial outlines the steps for configuring osTicket after installation to ensure the system is secure, efficient, and tailored to your organization's needs.<br />
<h2>Environments and Technologies Used</h2>
Microsoft Azure (Virtual Machines/Compute)
Remote Desktop
osTicket
<h2>Operating Systems Used</h2>
Windows 10 (21H2)
<h2>Configuration Steps</h2>
Initial Login and Basic Configuration

Access the osTicket admin panel via http://<your-vm-ip>/osTicket/scp/login.php
Login with admin credentials and update your profile, changing the default admin password.
 <p align="center">
 <img src="https://i.imgur.com/uHVdDsx.png" alt="osTicket login screen" height="40%" width="40%"/>
 </p>
System Settings

Navigate to "Admin Panel" -> "Settings" -> "System"
Set your help desk name, default email, time zone, and date format.
 <p align="center">
 <img src="https://i.imgur.com/fGXMpx4.png" alt="System settings" height="40%" width="40%"/>
 </p>
Email Configuration

Navigate to "Admin Panel" -> "Emails"
Configure email settings for sending and receiving support emails, using SMTP for outgoing and IMAP/POP for incoming emails.
 <p align="center">
 <img src="https://i.imgur.com/rgdZwmM.png" alt="Email configuration" height="40%" width="40%"/>
 </p>
Setting Up Departments

Navigate to "Admin Panel" -> "Agents" -> "Departments"
Create relevant departments (e.g., IT Support, Customer Service) and assign department heads and email addresses.
 <p align="center">
 <img src="https://i.imgur.com/LBGkAw6.png" alt="Departments" height="40%" width="40%"/>
 </p>
Creating Help Topics

Navigate to "Admin Panel" -> "Manage" -> "Help Topics"
Create help topics to categorize incoming tickets and assign default departments and SLA plans.
 <p align="center">
 <img src="https://i.imgur.com/Zf2jw07.png" alt="Help Topics" height="40%" width="40%"/>
 </p>
Configuring SLA Plans

Navigate to "Admin Panel" -> "Manage" -> "SLA Plans"
Create SLA plans to define response and resolution times and assign them to help topics and departments.
 <p align="center">
 <img src="https://i.imgur.com/LQjw9le.png" alt="SLA Plans" height="40%" width="40%"/>
 </p>
Agent Roles and Permissions

Navigate to "Admin Panel" -> "Agents" -> "Roles"
Create roles (e.g., Support Agent, Supervisor) with appropriate permissions and assign them to agents.
 <p align="center">
 <img src="https://i.imgur.com/CJ3RUbG.png" alt="Agent Roles" height="40%" width="40%"/>
 </p>
Ticket Settings and Automation

Navigate to "Admin Panel" -> "Settings" -> "Tickets"
Configure ticket settings such as auto-response, alerts, and notifications, and set up ticket filters and automation rules.
 <p align="center">
 <img src="https://i.imgur.com/uigyKjb.png" alt="Ticket Settings" height="40%" width="40%"/>
 </p>
Plugins and Add-ons

Explore available plugins to extend osTicket functionality and install/configure them as needed (e.g., LDAP authentication, reports).
 <p align="center">
 <img src="https://i.imgur.com/xZv1Yhw.png" alt="Plugins" height="40%" width="40%"/>
 </p>
Backup and Maintenance

Regularly back up your osTicket database and configuration, and schedule maintenance tasks and updates.
<p align="center">
<img src="https://i.imgur.com/jsJOPyn.png" alt="Backup" height="40%" width="40%"/>
</p>
<h2>Conclusion</h2>
Following these post-installation steps ensures your osTicket system is fully configured and ready to handle support tickets efficiently. For detailed guidance and troubleshooting, refer to the official osTicket documentation and community forums.
<h2>Additional Resources</h2>
- [osTicket Documentation](http://osticket.com/wiki/)
- [osTicket Community Forums](http://osticket.com/forums/)
- [Course Careers IT Course](https://coursecareers.com/courses/it-course/6e3f071f-86b0-4e8c-920f-2c91853a4e42)
