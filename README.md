<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket Lifecycle / System Simulation </h1>

<h2>About this Project</h2>

This project builds on a previous osTicket configuration lab by simulating a full ticket lifecycle in a realistic IT support environment. Using the previously configured departments, roles, and permissions, the scenario follows a business-critical outage from the moment a user submits a ticket through triage, escalation, and final resolution. The project highlights key help desk practices such as SLA prioritization and proper escalation procedures.

<h2>Prerequisites, Environment & Technology Used</h2>

- Microsoft Windows Virtual Machine 
- Remote Desktop
- osTicket
- Admin/Analyst Login Page:
     http://localhost/osTicket/scp/login.php
- End Users osTicket URL:
     http://localhost/osTicket

<h2>Getting Started</h2>

<h3>Credentials and Scenarios</h3>

A ticket was created by a User(Karen) stating that their entire mobile/banking system is down. The ticket is viewed by John (Read-only Agent) for triaging. Jane(Admin) then sets the ticket's properties(SLA's/Dept. etc), and after resolving the ticket, Jane proceeds to closing it.

- Password: Password1
- User: Karen
- Agent: John
- Admin: Jane
- Issue: Entire mobile/online banking system is down.

<h3>Ticket Lifecycle stage 1: Creating a ticket.</h3>

- To create a ticket, open Support Center page / End User URL http://localhost/osTicket then click Open a New ticket.

   <img src="images/mock.png"  >

- Enter the User's information, Help Topic, Summary, the Details for openning the ticket, and hi Create Ticket.

   <img src="images/mock1.png"  >

- Ticket successfully created. Observe that a new ticket is showing under Agent/Admin Panel > Tickets.

   <img src="images/mock2.png"  >
   <img src="images/mock3.png"  >   


<h3>Ticket Lifecycle stage 2: Observing/Triaging/Escalating tickets.</h3>

- To view the created ticket as an Agent, login to the  portal  http://localhost/osTicket/scp/login.php as Agent John.

   <img src="images/mock.png"  >

- Enter the User's information, Help Topic, Summary, the Details for openning the ticket, and hi Create Ticket.

   <img src="images/mock1.png"  >

- Ticket successfully created.

   <img src="images/mock2.png"  >
             
              
