<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket. Agent Jane Doe will resolve tickets.<br />

***PLEASE NOTE: This tutorial builds on work done from last tutorial, <a href="https://github.com/uzodinma-okafor/post-install-config">osTicket: Post-Installation Configuration</a>.***

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Issue Categories Classified by Priority</h2>
<p>
In the last tutorial, we created new Help Topics, which are basically categories that different issues fall into. Help Desk Analysts have to resolve a lot tickets daily in a timely manner. This is done by prioritizing certain help topics over others. In this tutorial, for example, Business Critical Outage would be seen as High/Emergency Priority(Top Priority for purpose of this tutorial). Personal Computer Issues would be Medium Priority, Equipment Request would be Normal Priority, and Password Reset would fall under Least Priority.
</p>

<p>
<h2>Part 1: Intake</h2>
<img src="https://i.imgur.com/kGlWRJx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
- Regular end users (e.g. customers/clients) of osTicket use this site (http://localhost/osTicket/) to send their tickets for agents to resolve. To start things off, you're going to need tickets to resolve. A few tickets have been made with this site using info like email address, name, specific help topic, and issue summary (as seen in pic above).
</p>
<br /><hr>

<p>
<h2>Part 2: Assignment and Communication</h2>
<img src="https://i.imgur.com/QQPl89m.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
- In first pic, you're back on osTicket & see the list of 3 tickets that need to be addressed. However, they are shown to be unassigned and have "Normal" priority.

-We don't know the priority. They're all normal. Usually, there are tickets like this in the queue that haven't been assigned to someone yet. Usually, someone like a queue manager or a lead help desk analyst would come in and grade the tickets based on severity, the type of SLA they fall in, and assign them to someone to handle them. 
- We going to see how one of the tickets, ticket# 176150, gets assigned and prioritized by Agent Jane Doe. 
</p>
<br /><hr>

<p>
<img src="https://i.imgur.com/pYha2O2.png" height="50%" width="50%" alt="Disk Sanitization Steps"/><img src="https://i.imgur.com/AgExUHh.png" height="50%" width="50%" alt="Disk Sanitization Steps"/><img src="https://i.imgur.com/h7ST2U7.png" height="50%" width="50%" alt="Disk Sanitization Steps"/><img src="https://i.imgur.com/YM6ANh7.png" height="50%" width="50%" alt="Disk Sanitization Steps"/><img src="https://i.imgur.com/4VDwJAI.png" height="50%" width="50%" alt="Disk Sanitization Steps"/><img src="https://i.imgur.com/7jcc9BU.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
</p>
<p>
- From the last tutorial, Jane Doe was made a Supreme Admin for her primary Department, System Administrators. She was also given  extended access as a Supreme Admin for the Support Department.

- Log out of your account and log into Jane Doe's account( U: jane.doe, P: Password1). You should see the tickets that need to be resolved. Click on ticket #176150("entire mobile banking online is down"). (See 2nd pic down) 
- Click on "Normal" in Priority area (top left) and switch it to "High" leaving a note explaing why. (3rd pic down)
- Click on "Unassigned" in top left area (2nd pic) and assign it to Jane Doe (4th pic down). As a Supreme Admin, Jane has the ability to assign tickets to anyone, including herself.
- Click on "Default SLA" in SLA Plan area and change it to SLA-A (5th pic down) and leave a note explaining why.
- Click on "Support" in the Department and select to have the ticket transfered to "System Administrators" department, where Jane Doe works primarily.
</p>
<br /><hr>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br /><hr>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br /><hr>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br /><hr>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br /><hr>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br /><hr>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br /><hr>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br /><hr>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br /><hr>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br /><hr>
