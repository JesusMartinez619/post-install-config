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

- Configure roles/Departments/Teams
- Configure Agents(workers)/Users(customers) 
- Configure SLA

<h2>Configuration Steps</h2>

- The first step in this section after installing osTicket I will start configuring roles/departments/teams, in the first image I configured a role for "Supreme Admin" giving this role all of the permissions available. In the second image we create the department "SysAdmins" setting it as a Top level department, meaning this department will be for Admins having "more access". In the Third picture I create a team named "Online banking".

![Screenshot 2024-12-25 210040](https://github.com/user-attachments/assets/ffdc80fd-b87e-4ed3-80c4-28080b5eb3fa) <img width="442" alt="image" src="https://github.com/user-attachments/assets/5c69c3b4-86b9-4d2a-9f16-c877277f7071" /> <img width="299" alt="image" src="https://github.com/user-attachments/assets/01b86321-f240-439f-862f-3c1e16167aab" />

- Second step is to configure the Agents/Users, in this first picture I configured 2 agents setting up password and level of access, one having the role of "SysAdmin/Top-level Department" and the other "Support". In the second picture I created an end-user who will be the customer that will create "Tickets".

<img width="431" alt="image" src="https://github.com/user-attachments/assets/3642c927-2f7f-46c3-9c02-c84b085be322" /> <img width="436" alt="image" src="https://github.com/user-attachments/assets/d11359c9-31e4-4da3-bf21-f7a20099b3f4" />

- Third step I will configure SLA/Help Topics, in this first picture I configured 3 different SLAs, (Sev-A) being a high-level severity (Sev-B) being mid-level severity (Sev-C) being low-level severity. In the second picture I configure a few "Help Topics" defining the type of issues.

<img width="437" alt="image" src="https://github.com/user-attachments/assets/213ca002-bdd0-4557-8940-4b7e7c34e004" /> <img width="433" alt="image" src="https://github.com/user-attachments/assets/ae283330-e718-4129-b7e0-061396386006" />

