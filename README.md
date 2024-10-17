<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This walkthrough outlines the post-installation configuration of the help desk ticketing system osTicket. This exercise is done to explore the osTicket portal before creating and solving mock tickets. <br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket Portal

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configuration of Roles in order to group those with similiar permissions together.
- Configuration of Departments
- Configuration of Teams
- Configuration of Agents
- Configuration of Users
- Configuration of SLAs
- Configuration of Help Topics

- <h2>Configuration Steps</h2>

<p>
<img width="426" alt="1" src="https://github.com/user-attachments/assets/85fd0548-f99d-4edd-8638-bb1b8f096b5f">
</p>
<p>
1. Firstly, we’re going to use this link (http://localhost/osTicket/scp/login.php ) to navigate to osTicket and login using the email and password created when osTicket was first installed. 
</p>
<br />

<p>
<img width="964" alt="2" src="https://github.com/user-attachments/assets/bcfa0d46-0a35-4831-903b-19b3e73150fc">
</p>
<p>
2. To begin configuration, we click on the Admin Panel button in the upper right corner of the screen.
</p>
<br />

<p>
<img width="957" alt="3" src="https://github.com/user-attachments/assets/8b52cf3e-54ff-4dc1-b8e0-165cd7358e81">
</p>
<p>
3. Click on the Agents Tab near the top of the screen.
</p>
<br />

<p>
<img width="960" alt="4" src="https://github.com/user-attachments/assets/f06eced7-ea74-4e28-8bdc-93322be91805">
</p>
<p>
4. Click on the Roles tab. We’re now going to begin configuring different Roles which are permissions granted to Agents per Department that they have access to. 
</p>
<br />

<p>
<img width="957" alt="5" src="https://github.com/user-attachments/assets/8cf225a5-961c-415a-8099-ad780a960b1f">
</p>
<p>
5. Click Add New Role.
</p>
<br />

<p>
<img width="955" alt="6" src="https://github.com/user-attachments/assets/8fb0e710-25b7-4dcb-929f-b3038e3c751c">
</p>
<p>
6. First, we’re going to create a role named “Supreme Admin” and this role will be given unlimited permissions. In order to do this, type in the name in the name box and then navigate to the permissions tab.
</p>
<br />

<p>
<img width="952" alt="7" src="https://github.com/user-attachments/assets/5326af72-810e-4290-a0ea-5825031495ec">
<img width="948" alt="8" src="https://github.com/user-attachments/assets/a837a535-f7a7-4839-95ed-b46eacfa0740">
<img width="952" alt="9" src="https://github.com/user-attachments/assets/831db6eb-9321-42c5-a94d-7a705f3f31d6">
</p>
<p>
7. Make sure to put a check next to every line under Tickets, Tasks, and Knowledgebase; this way there are no restrictions to this role.
</p>
<br />

<p>
<img width="958" alt="10" src="https://github.com/user-attachments/assets/bfa9bd53-161d-4d8c-ad6e-5bf433161170">
</p>
<p>
8. Once you see the green banner at the top, this is an indication that Supreme Admin has succesfully been added as a role.
</p>
<br />

<p>
<img width="962" alt="11" src="https://github.com/user-attachments/assets/c406d9f3-5afb-4173-9c6e-cfdef33e6b97">
</p>
<p>
9. Next, we will begin configuring Departments. This is done so that specific tickets are only visible to relevant Departments. To do this while still in the Agents tab, simply click on the Departments tab.
</p>
<br />

<p>
<img width="962" alt="13" src="https://github.com/user-attachments/assets/8f6a8f6b-c406-422c-9150-008d1d2a68c8">
</p>
<p>
10. Click on "Add new Department".
</p>
<br />

<p>
<img width="949" alt="12" src="https://github.com/user-attachments/assets/ffcbb363-8469-4bcc-b6bc-9607c5da83d5">
</p>
<p>
11. We are going to name this Department "SysAdmins" and assign users to it later. When configuring a new Department, it will also display the option to select SLAs, a department manager, a set schedule, and the ticket assignment. For demonstration purposes we will only configure SLAs but there are various other options that can be selected to make each Department easier to manage. 
</p>
<br />

<p>
<img width="968" alt="14" src="https://github.com/user-attachments/assets/7a925868-48c3-4256-9951-fa4f2dd8b7a3">
</p>
<br />

<p>
12. Next, we will configure Teams which (in this instance) will contain various users from different Departments. For example, if this configuration was being done for an Online Banking Team, we would be sure to include users from various roles such as a system administrator or a helpdesk user. To do this, click on the Teams tab.
</p>
<br />

<p>
<img width="956" alt="15" src="https://github.com/user-attachments/assets/b8321579-28fe-425e-960e-afa746e7f528">
</p>
<br />

<p>
13. Click on "Add New Team".
</p>
<br />

<p>
<img width="962" alt="16" src="https://github.com/user-attachments/assets/eea6e9c9-0a5d-4d23-9d6f-06e71ed2ffeb">
</p>
<br />

<p>
14. To remain consistent with the previous example, we can call this team "Online Banking" and will assign users later. Click on Create Team at the bottom when done.
</p>

<br />

<p>
<img width="964" alt="17" src="https://github.com/user-attachments/assets/22664c23-59ef-46a5-878b-ae6fc7f06e22">
</p>
<br />

<p>
15. Now, we're going to create a setting that will allow anyone (ex: endusers) to create tickets without being in the system. To do this, click on the Settings tab and then navigate to Users.
</p>

<br />

<p>
<img width="963" alt="18" src="https://github.com/user-attachments/assets/512b5ef1-905a-404f-b44f-0cf619e0a452">
</p>
<br />

<p>
16. It's important to make sure that "Registration Required" remains unchecked so that users do not have to login to an account just to create a ticket. Once the box has been unchecked, you can click on "Save Changes" at the bottom of the window.
</p>

<br />

<p>
<img width="959" alt="19" src="https://github.com/user-attachments/assets/fa36c20d-7722-407c-a2b3-20f03c4d33f2">
</p>
<br />

<p>
17. Now we will configure 2 mock Agents (employees): Jane who is a member of the SysAdmins Department and John who is part of the Support Department. To do this, click on the Agents tabe at the top and select "Add New Agent".
</p>

<br />

<p>
<img width="956" alt="20" src="https://github.com/user-attachments/assets/9b8a697f-0c03-426d-b8a7-50504f752e8d">
</p>
<br />

<p>
18. We will fill in the first name, last name, email address, and username for this Agent. Then click on the "access" tab to assign them to a department.
</p>

<br />

<p>
<img width="957" alt="21" src="https://github.com/user-attachments/assets/8caa5c5e-6420-4e80-b04c-8c169276564f">
</p>
<br />

<p>
19. For the sake of this example, Jane will be assigned to the SysAdmin department and be given the role of Supreme Admin. To place her on a specific team, we will click on the "Teams" tab.
</p>

<br />

<p>
<img width="958" alt="22" src="https://github.com/user-attachments/assets/6130e679-9b6e-40bc-994f-9f5350f06ddb">
</p>
<br />

<p>
20. The team we will be placing Agent Jane on is the Online Banking team. After this user has been configured, click on the Create button.
</p>

<br />

<p>
<img width="955" alt="23" src="https://github.com/user-attachments/assets/0c5fc0ba-f819-4503-8827-a56d82d68b10">
<img width="957" alt="24" src="https://github.com/user-attachments/assets/75e1a75e-2ac7-4aa8-b72d-b74ab184cea7">
</p>
<br />

<p>
21. Now, we will configre the next Agent John Doe the same way. Select "Add New Agent" and we will fill out the same information we did for Jane Doe. The difference is that John will be assigned to the Support Department and will be given the "View only" role for this example. We will not be selecting a Team for John. Click the Create button. 
</p>

<br />

<p>
<img width="962" alt="25" src="https://github.com/user-attachments/assets/79083f6d-b7c4-4a5e-a953-fa0031fbbd5b">
</p>
<br />

<p>
22. Now, we have the ability to set individual passwords for our Agent accounts. To do this, navigate back to the Agent tab and click on Jane Doe first. 
</p>

<br />

<p>
<img width="955" alt="26" src="https://github.com/user-attachments/assets/b400829e-797c-4799-ab81-7608b96e8871">
</p>
<br />

<p>
23. Click on the "Set Password" button next to the username given to the Agent.
</p>

<br />

<p>
<img width="646" alt="27" src="https://github.com/user-attachments/assets/14381f9d-4110-4abd-83c0-9cfe8871e5b3">
</p>
<br />

<p>
24. Make sure to uncheck the button next to "Send the agent a password reset email" and "Require password change at the next login". The passwords we will give to both agents for this example is "Password 1". Once, you're done click on the Update button on the lower right of the screen and do the same thing for Agent John Doe. 
</p>

<br />

<p>
<img width="957" alt="28" src="https://github.com/user-attachments/assets/2ae76ee2-8f52-4057-9e10-75d8b086e93a">
</p>
<br />

<p>
25. Now, we will configure 2 users (customers) for this example: Karen and Ken. To do this, we're first going to switch from the Admin Panel too the Agent Panel by clicking the Agent Panel button at the top right of the browser window. 
</p>

<br />

<p>
<img width="952" alt="29" src="https://github.com/user-attachments/assets/822ae5f1-32d8-4d58-9a96-b08264c50c7f">
</p>
<br />

<p>
26. Now we will click on the Users tab and select "Add New User".













