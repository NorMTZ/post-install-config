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
- Configure User Settings
- Configure Agents (Workers)
- Configure Users (Customers)
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="![Postinstall supreme admin](https://github.com/NorMTZ/post-install-config/assets/174408540/ad0b924f-ddb8-43b0-9fa6-997ac919b185)
" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

# osTicket - Post Configuration Setup

This tutorial demonstrates the post configuration setup of the osTicket system.

## Post-Installation Setup Steps

Follow these steps for the post-installation configuration of your osTicket system:

### 1. Configure Roles

- **Navigate to:** Admin Panel -> Agents -> Roles
- **Create Role:** Click on "Add new role" and enter the name of the new role: **Supreme Admin**
  - **Permissions:** Assign all permissions to the Supreme Admin
  - **Note:** Roles determine an agent's permissions, so not all agents will have unlimited access
- **Result:** Your screen should look like this:
  <br />
  <img src="https://i.imgur.com/XHteqdt.png" height="80%" width="80%" alt="Roles Configuration"/>

### 2. Configure Departments

- **Navigate to:** Admin Panel -> Agents -> Departments
- **Create Department:** Click on "Add new department" and enter the name: **System Administrators**
  - **Settings:** Configure SLAs, managers, and email settings
- **Result:** Your screen should look like this:
  <br />
  <img src="https://i.imgur.com/dGK0RVM.png" height="80%" width="80%" alt="Departments Configuration"/>

### 3. Configure Teams

- **Navigate to:** Admin Panel -> Agents -> Teams
- **Create Teams:**
  - **Level I Support** (Default)
  - **Level II Support:** Click on "Add new team" and enter the name: **Level II Support**
  - **Note:** Teams allow you to pull agents from different departments and assign them to specific tasks
- **Result:** Your screen should look like this:
  <br />
  <img src="https://i.imgur.com/cYzWBD2.png" height="80%" width="80%" alt="Teams Configuration"/>

### 4. Allow Anyone to Create Tickets

- **Navigate to:** Admin Panel -> Settings -> User Settings
- **Configuration:** Set **Registration Required** to **Require registration and login to create tickets**
- **Result:** Your screen should look like this:
  <br />
  <img src="https://i.imgur.com/H1q2Fdh.png" height="80%" width="80%" alt="User Settings Configuration"/>

### 5. Configure Agents (Workers)

- **Navigate to:** Admin Panel -> Agents -> Add New
- **Add Agents:**
  - **Jane**
  - **John**
  - **Note:** Agents are the employees who work on solving tickets. They are assigned primary departments and roles
- **Result:** Your screen should look like this:
  <br />
  <img src="https://i.imgur.com/8WTOSre.png" height="80%" width="80%" alt="Agents Configuration"/>

### 6. Configure Users (Customers)

- **Navigate to:** Agent Panel -> Users -> User Directory -> Add New
- **Add Users:**
  - **Karen**
  - **Ken**
  - **Note:** Users are customers that create tickets when they are having issues. They are identified by their email address
- **Result:** Your screen should look like this:
  <br />
  <img src="https://i.imgur.com/xOprA9f.png" height="80%" width="80%" alt="Users Configuration"/>

### 7. Configure SLA Plans

- **Navigate to:** Admin Panel -> Manage -> SLA Plans
- **Create SLA Plans:**
  - **Sev-A:** 1 hour, 24/7
  - **Sev-B:** 4 hours, 24/7
  - **Sev-C:** 8 hours, business hours
  - **Note:** SLAs provide a length of time in which the help desk is expected to solve a specific ticket
- **Result:** Your screen should look like this:
  <br />
  <img src="https://i.imgur.com/LpjCaLd.png" height="80%" width="80%" alt="SLA Plans Configuration"/>

### 8. Configure Help Topics

- **Navigate to:** Admin Panel -> Manage -> Help Topics
- **Create Help Topics:**
  - **Business Critical Outage**
  - **Personal Computer Issues**
  - **Equipment Request**
  - **Password Reset**
  - **Note:** Help topics help users categorize their tickets
- **Result:** Your screen should look like this:
  <br />
  <img src="https://i.imgur.com/4yk1jb6.png" height="80%" width="80%" alt="Help Topics Configuration"/>
