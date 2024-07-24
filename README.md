# ticket-lifecycle
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

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Ticket
- Resolution

<h2>Lifecycle Stages</h2>

 The first thing we will do is create a ticket from the user end of the osTicket platform.

Open osTicket: http://localhost/osTicket/


Select: Open a New Ticket
<p>

  ![image](https://github.com/user-attachments/assets/87604a43-f335-4f87-a2bd-da6cfe524612)
</p>
<p>
 

</p>
<br />
</p>
<p>
  
 Fill out the form to create the ticket :

Email Address: Karen@osticket.com

Name: Karen Karen

Help Topic: Business Critical Outage

Issue Summary: Entire mobile online banking is down

Ticket Details: Customers are reporting they are getting a 404 error when browsing to online banking.

Click: Create Ticket

</p>
<br />

<p>
  
![image](https://github.com/user-attachments/assets/a3199e61-f790-4288-97e8-5d40cccce698)

  
</p>
<p>
 2. Assign

 Login to osTicket as an Agent: (User: jane.doe / jane.doe@gmail.com)

  ![image](https://github.com/user-attachments/assets/b460b88c-8c8d-4b5b-bac5-17f5ad078bd6)

<br />

Click: The entire mobile online banking is down (this is the ticket we just created on the user end as Karen)

![image](https://github.com/user-attachments/assets/48468ad5-d9a4-47bf-9655-86bc642d750c)

Because the entire mobile banking is down and critical to business impact, we will change the priority of this ticket to EMERGENCY and the SLA to SEV-A.

![image](https://github.com/user-attachments/assets/08f9d721-8be7-4af1-9258-1c1facbc85c4)

Priority: Emergency

Type In: Business Impacting Event

Click: Update


We will also transfer the ticket to the system administrators department and then assign it to an agent, who in this case will be ourselves, Jane Doe.

Click: Department

Select: System Administrators

Details: Sys Admins responsible for mobile banking infrastructure

Click: Transfer

![image](https://github.com/user-attachments/assets/856c9708-fab4-4a2f-b4f8-332ea2e26dc8)

Assigned to: Jane Doe

Click: Assign

![image](https://github.com/user-attachments/assets/7b1b59fe-4317-4728-b346-ec7f9cf9c043)


SLA Plan: SEV-A

Details: Business Impacting, Critical Event

Click: Update

![image](https://github.com/user-attachments/assets/1b83afc8-ecca-44ad-941f-a313bb902623)

Note: Make sure your ticket information matches the image below and continue to the next step.

![image](https://github.com/user-attachments/assets/744c8c23-df5f-4c79-b32a-1e3d62a302f4)


This is where you will see the history and updates of the tickets. ↓


![image](https://github.com/user-attachments/assets/4e910b67-617b-4cd5-9786-fd3a1e9bd8e0)

3. ) Working the Issue

   
On the back end, Jane is working with the System Adminstrator team to resolve the issue.

Response Text Box: Coordinating with Sys Admin Team to bring mobile banking back online.

Select: Post Reply

![image](https://github.com/user-attachments/assets/8e4acb2a-d220-4682-81c7-a472a504c2f4)


4. ) Resolution

   
Return to the ticket and update the end user once the issue is resolved.

Response Text Box: Jerry from System Engineering found and connected a failed load balancer. Mobile banking should be back up.

Ticket Status: Resolved

Select: Post Reply

![image](https://github.com/user-attachments/assets/6e8f9d99-d9cd-4525-b3d0-ee788759b970)

The ticket should now be on the "closed" tab since it has been resolved.

![image](https://github.com/user-attachments/assets/8b8baad2-be66-40f7-85e7-4861f963d9d2)

🎉🎉🎉 Congratulations! You have successfully resolved your first ticket as a help desk support agent!








