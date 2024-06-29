<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Virtual Machine of Windows 10
- Microsoft Remote Desktop
- IIS (Internet Information Service)

<h2>Configure Roles</h2>
<h4>Admin Panel -> Agents -> Roles</h4>
<h4>Supreme Admin</h4>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<p>

<h4>Reload IIS (Open IIS, Stop and Start the server)</h4>
<p>
<img src="images/1-configure-roles/1 - gotToAdmin.PNG" alt="gotToAdmin" width="50%" height="50%">
<img src="images/1-configure-roles/2 - adminPageAgents.PNG" alt="adminPageAgents" width="50%" height="50%">
<img src="images/1-configure-roles/3 - adminPageAgentsRoles.PNG" alt="adminPageAgentsRoles" width="50%" height="50%">
<img src="images/1-configure-roles/4 - addNewRole.PNG" alt="addNewRole" width="50%" height="50%">
<img src="images/1-configure-roles/5 - supremeAdmin.PNG" alt="supremeAdmin" width="50%" height="50%">
<img src="images/1-configure-roles/6 - permissions.PNG" alt="permissions" width="50%" height="50%">
<img src="images/1-configure-roles/7 - selectSupremeAdmin.PNG" alt="selectSupremeAdmin" width="50%" height="50%">
<img src="images/1-configure-roles/8 - addMorePermissions.PNG" alt="addMorePermissions" width="50%" height="50%">
</p>
<br />

<h2>Configure Departments</h2>
<h4>Admin Panel -> Agents -> Departments</h4>
<h4>System Administrators</h4>
<p>
<img src="images/2-configueDepartments/1 - departments.PNG" alt="departments" width="50%" height="50%">
<img src="images/2-configueDepartments/2 - addNewDepartment.PNG" alt="addNewDepartment" width="50%" height="50%">
<img src="images/2-configueDepartments/3 - form.PNG" alt="form" width="50%" height="50%">
<img src="images/2-configueDepartments/4 - departmentCreated.PNG" alt="departmentCreated" width="50%" height="50%">
</p>
<br />


<h2>Configure Teams</h2>
<h4>Admin Panel -> Agents -> Teams</h4>
<h4>Level I Support</h4>
<h4>Level II Support</h4>
<p>
<img src="images/3-configureTeams/1 - clickTeams.PNG" alt="clickTeams" width="50%" height="50%">
<img src="images/3-configureTeams/2 - addNewTeam.PNG" alt="addNewTeam" width="50%" height="50%">
<img src="images/3-configureTeams/3 - teamCreation.PNG" alt="teamCreation" width="50%" height="50%">
</p>
<br />

<h2>Allow anyone to create tickets</h2>
<h4>- Admin Panel -> Settings -> User Settings</h4>
<h4>- Registration Required: Require registration and login to create tickets </h4>
<p>
<img src="images/4-allowTicketCreation/1 - userForm.PNG" alt="userForm" width="50%" height="50%">
<img src="images/4-allowTicketCreation/2 - verifyUncheckedBox.PNG" alt="verifyUncheckedBox" width="50%" height="50%">
<br />


<h2>Configure Agents (workers)</h2>
<h4>- Admin Panel -> Agents -> Add New</h4>
<h4>-Jane and John</h4>
<p>
<img src="images/5-configureAgents/1 - goToAgents.PNG" alt="goToAgents" width="50%" height="50%">
<img src="images/5-configureAgents/2 - provideInfo.PNG" alt="provideInfo" width="50%" height="50%">
<img src="images/5-configureAgents/3 - setPassword.PNG" alt="setPassword" width="50%" height="50%">
<img src="images/5-configureAgents/4 - setAccess.PNG" alt="setAccess" width="50%" height="50%">
<img src="images/5-configureAgents/5 - assignTeam.PNG" alt="assignTeam" width="50%" height="50%">
</p>
<br />


<h2>Configure Users (customers)</h2>
<h4>- Agent Panel -> Users -> Add New</h4>
<h4>- Karen and Ken</h4>
<p>
<img src="images/6-configureUsers/1 - newUser.PNG" alt="newUser" width="50%" height="50%">
<img src="images/6-configureUsers/2 - userKaren.PNG" alt="userKaren" width="50%" height="50%">
<br />


<h2>Configure Service-Level Agreement (SLA)</h2>
<h4>-Admin Panel -> Manage -> SLA</h4>
<p>
<img src="images/7-configure-sla/1 - goToAdmin.PNG" alt="goToAdmin" width="50%" height="50%">
<img src="images/7-configure-sla/2 - manageSLA.PNG" alt="manageSLA" width="50%" height="50%">
<img src="images/7-configure-sla/3 - addSLA.PNG" alt="addSLA" width="50%" height="50%">
<img src="images/7-configure-sla/4 - newSLAForm.PNG" alt="newSLAForm" width="50%" height="50%">
<img src="images/7-configure-sla/5 - add SEV B.PNG" alt="add SEV B" width="50%" height="50%">
<img src="images/7-configure-sla/6 - sevBForm.PNG" alt="sevBForm" width="50%" height="50%">
<img src="images/7-configure-sla/7 - addSEVC.PNG" alt="addSEVC" width="50%" height="50%">
<img src="images/7-configure-sla/8 - sevCForm.PNG" alt="sevCForm" width="50%" height="50%">
</p>

<br />


<h2>Configure Help Topics</h2>
<h4>- Admin Panel -> Manage -> Help Topics</h4>
<h4>- Business Critical Outage, Personal Computer Issues, Equipment Request, Password Reset</h4>
<p>
<img src="images/8-configureHelpTopics/1 - goToHelp.PNG" alt="goToHelp" width="50%" height="50%">
<img src="images/8-configureHelpTopics/2 - BizOutage.PNG" alt="BizOutage" width="50%" height="50%">
<br />


<h2>Congratulations, hopefully it is installed with no errors!</h2>
<h4>- Browse to your help desk login page: http://localhost/osTicket/scp/login.php</h4>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<br />
