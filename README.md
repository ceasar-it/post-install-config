<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />
<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>


- Setup roles based access 
- Confrguare Departments 
- Select who can create tickets 
- Setup SLA levels (service level aggreements)
- Configure help topics (to categorize tickets that users create)

<h2>Configuration Steps</h2>
</p>

Once ticketing system is installed I setup roles in the Admin panel to allow role based access to users. 
<p>

![Main Desktop with Admin Panel-User Panel](https://github.com/user-attachments/assets/7defbd70-803e-4318-96d7-dc02c3636cf0)

</p>

![Under Admin Panel Accessed agents and roles to add permissions](https://github.com/user-attachments/assets/f5aed197-e9be-4589-a7cf-2769858ea4b7)
</p>

![All Access Role will give user all Permissions as shown](https://github.com/user-attachments/assets/c9f98998-42d6-4979-9a82-1e9e69ed8f43)

</p>
<br />

Next I confirgued a new department in the admin panel. I setup a new department for system administrators.  This will allow tickets from system administrator users to be sorted efficiently. 

![Creating different departments  I created a SysAdmin one here](https://github.com/user-attachments/assets/047528f5-7564-4616-9f52-5bbc7f01b01b)
</p>
<br />


I then setup to allow everyone the ability to submit tickets to the help desk, whether or not they are a user. 

![In Settings I am adjusting them to allow anyone to create a ticket](https://github.com/user-attachments/assets/9cb76be5-c63b-4004-bf8c-ef87348e0c4c)

</p>
<br />

I practiced setting up new employees and setup Jane Doe as a user. I gave her all permissions. 
</p>

![Setting up Ticketing system User](https://github.com/user-attachments/assets/b8961efc-0353-490c-9ebe-eb667e759c98)

</p>

I put her in the SystemsAdmin department that I created earlier in the lab.

![New User Access setting](https://github.com/user-attachments/assets/ae88aeb6-caa1-4a14-adb7-3123ffd70ebb)
</p>

I granted all permissions.

![New User Permission settings](https://github.com/user-attachments/assets/3acc275f-727b-43d5-a278-5b4bb5a8f5f0)

</p>
<br />

I ended this practice lab by setting an urgent service level agreement for tickets needing immediate assistance. 

![Setting up SLA plan](https://github.com/user-attachments/assets/70b6dfe2-f44e-4263-9cc9-cdf2e1afbf99)

</p>
