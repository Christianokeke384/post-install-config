<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />





<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Connection
- Internet Information Services (IIS)
- osTicket

<h2>Operating Systems Used </h2>

- Windows 10</b> pro (22H2) x64 Gen 2

<h2>Post-Install Configuration Objectives</h2>

- Setup roles
- setup Departments
- Seteup Teams
- Setup Agents
- Setup Users
- Setup SLA
- setup HelpTopics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/GRm1yRa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Firstly, I created a new role called Chief Admin,Chief Admin has been granted complete permissions to every duties under Tickets,Tasks and Knowledgebase. There are other types of access like expanded,limited and view only access. 
</p>
<br />

<p>
<img src="https://i.imgur.com/KuLRQwF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Created a new dapartment under support called sysEngineer, SysEngineer will provide support if being assigned a ticket 
</p>
<br />

<p>
<img src="https://i.imgur.com/TuIg1Iv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Setup a new team which i named billing transaction,i would be able to send any issues relating to billing to this particular team.
</p>
<br />

<p>
<img src="https://i.imgur.com/RVgDmLn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I setup two new Agents Ann maxwells which i assigned to the Sys Engineer department and gave her Chief Admin Access and Micheal wells which i assigned to the support department and gave limited access, he won't be able to do everything like Ann maxwells. 
</p>
<br />

<p>
<img src="https://i.imgur.com/uki8hCm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Logged into the Agent panel and setup mark as a new user, i also went into settings to deselect the select box to enable users that are not registered to be able to create tickets. 
</p>
<br />

<p>
<img src="https://i.imgur.com/ORGoFhd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Logged into Admin panel, under Sevice Level Agreement and setup three(3) SLA plan which are Crit-1,Crit-2 and Crit-3. Depend on how critical each tickets are i assigned grace period and schedule for which a tickets should be answered unless it would be mark overdue. 
</p>
<br />

<p>
<img src="https://i.imgur.com/cJpExyx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Setup HelpTopics, added five(5) new helptopics to direct and help users easily navigate the platform,see solution to related issues and seek further assistance from support.
</p>
<br />
