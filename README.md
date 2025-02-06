# ticket-lifecycle-
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10 Pro</b> (22H2) at least 2vCPUs, 8GB RAM

<h2>Ticket Lifecycle Stages</h2>

- Ticket Creation and Submission
- Assignment and Initial Response 
- Issue Investigation and Troubleshooting 
- Resolution and Closure 

<h2>Working through Tickets</h2>

<p>
In this project, we'll simulate some helpdesk tickets and work through them to resolution. Before we start anything, make sure the Maintenance department is deleted as tickets somehow get routed here. Login as an admin,
hover over agents (big tab) and click on departments. Check the Maintenance department, click More then delete. Now we can begin.

Go to http://localhost/osTicket and open a new ticket. Let's create a ticket about a user named Karen and is reporting that their company's mobile/online banking system is down.
</p>

![image](https://github.com/user-attachments/assets/2f3af642-be0d-481c-a8a2-978a36b288f1)

<p>
   We will try and access this ticket with the Karen user we created in the Post-Installation project https://github.com/kavihakumaresan/post-install-config. Looks like we can assign this ticket to others can set the SLA.
Online banking being down for a company needs to be looked at urgently so we can set the SLA to Sev-A. Although Karen could probably resolve this ticket since he's part of the support team, it is more appropriate
to assign this to the Online Banking team.

![image](https://github.com/user-attachments/assets/8ec8c097-13b5-4926-973c-a1e813495c28)

  
![image](https://github.com/user-attachments/assets/0c61b7da-cbd0-42df-a835-7f5afdbca62b)

<p>
After getting more information, it turns out the charger was broken so this is a relatively easy fix, we can set the SLA to Sev-B and once we get someone to find a new charger and verify that the laptop can be
  powered on, we can close the ticket.
</p>
