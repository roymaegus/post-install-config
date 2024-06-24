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
<h4>Step 1 -  Admin Panel -> Agents -> Roles</h4>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<h4>Step 2 - Supreme Admin</h4>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<p>

<h4>Reload IIS (Open IIS, Stop and Start the server)</h4>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<br />

<h2>Configure Departments</h2>
<h4>Admin Panel -> Agents -> Departments</h4>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>

<h4>System Administrators</h4>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<br />


<h2>Configure Teams</h2>
<h4>Admin Panel -> Agents -> Teams</h4>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<h4>Level I Support</h4>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>

<h4>Level II Support</h4>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<br />

<h2>Allow anyone to create tickets</h2>
<h4>- Admin Panel -> Settings -> User Settings</h4>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<h4>- Registration Required: Require registration and login to create tickets </h4>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<br />


<h2>Configure Agents (workers)</h2>
<h4>- Admin Panel -> Agents -> Add New</h4>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<h4>-Jane and John</h4>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<br />


<h2>Configure Users (customers)</h2>
<h4>- Agent Panel -> Users -> Add New</h4>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<h4>- Karen and Ken</h4>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<br />


<h2>Configure Service-Level Agreement (SLA)</h2>
<h4>-Admin Panel -> Manage -> SLA</h4>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<h4>- Sev-A (1 hour, 24/7), Sev-B (4 hours, 24/7), Sev-C (8 hours, business hours)  </h4>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<br />


<h2>Configure Help Topics</h2>
<h4>- Admin Panel -> Manage -> Help Topics</h4>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<h4>- Business Critical Outage, Personal Computer Issues, Equipment Request, Password Reset</h4>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>

<br />


<h2>Congratulations, hopefully it is installed with no errors!</h2>
<h4>- Browse to your help desk login page: http://localhost/osTicket/scp/login.php</h4>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<br />
