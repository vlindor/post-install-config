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
8. Once you see the green banner at the time, this is an indication that Supreme Admin has succesfully been added as a role.
</p>
<br />

<p>
9. Next, we will begin configuring Departments. This is done so that specific tickets are only visible to relevant Departments.
</p>
<br />

<p>
<img width="962" alt="11" src="https://github.com/user-attachments/assets/c406d9f3-5afb-4173-9c6e-cfdef33e6b97">
</p>
<p>
10. While still in the Agents tab, click on the Departments tab.
</p>
<br />

<p>
<img width="962" alt="13" src="https://github.com/user-attachments/assets/8f6a8f6b-c406-422c-9150-008d1d2a68c8">
</p>
<p>
11. Click on "Add new Department".
</p>
<br />

<p>
<img width="949" alt="12" src="https://github.com/user-attachments/assets/7f167368-b5c9-4671-8361-e1eba3b771f6">
</p>
<br />

<p>
12. When configuring a new Department, it will display the option to select SLAs, a department manager, a set schedule, and the ticket assignment. For demonstration purposes we will only configure SLAs but there are various other options that can be selected to make each Department easier to manage. 
</p>

<br  />

<p>













