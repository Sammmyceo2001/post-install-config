# post-install-config
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation] [https://www.youtube.com/watch?v=mbckqBHjLxM)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Install / Enable IIS
- Register PHP from within IIS
- Open PHP and Enable or disable an Extensions
- Installing mySQL
- Configuring Agent Panel vs Admin Panel

<h2>Configuration Steps</h2>

<p>
<img src="https://github.com/user-attachments/assets/456369fb-9844-42dd-9fd5-1bfe34ff8667" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This is when i installed IIS, i opened up the Control Panel, 2)Programs then click “Turn on or off window features, 
click Internet information services   “World 
Wide Web” and  web management tools , then 
expand on World wide web and expand on 
application development features and click CGI (CGI creates IIS)
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/87104c34-095c-4c6f-9241-e3f0e3241aa1" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Note that some extensions are not enabled 
Going back to IIS, sites -> Default -> osTicket 
PHP Manager 
“Enable or disable an extension” 
Enable: php_imap.dll 
Enable: php_intl.dll 
Enable: php_opcache.dll 
Refresh the osTicket site in your browser, observe the changes
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/63d80462-c80c-4fbb-9097-7ee25475d759" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Acknowledge Agent Panel vs Admin Panel, Configuring Roles, Departments, Teams, Agents, Users and SLA (Service Level Agreement), and Help Topics.
</p>
<br />
