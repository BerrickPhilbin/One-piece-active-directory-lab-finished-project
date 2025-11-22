<p align="center">
  <img src="https://i.imgur.com/CS2qwib.png" alt="Active Directory Logo" />
</p>

<h1>Active Directory — Post-Deployment Configuration (One Piece Theme)</h1>

This repository outlines the configuration steps performed after deploying an **Active Directory Domain Services (AD DS)** environment — focusing on **organizational structure**, **user and admin creation**, **permissions**, and **server–client relationships**, all inspired by the crews of **One Piece**.

---

<h2>🧰 Environments and Technologies Used</h2>

- Windows Server (2019 / 2022)  
- Active Directory Domain Services  
- DNS  
- Group Policy Management  
- Windows 10 / 11 Client Machine  
- Remote Desktop  

---

<h2>📝 Step 1: Designing the Organizational Unit (OU) Structure</h2>

To ensure the domain stays clean and easy to manage, a well-structured set of OUs was created. In this One Piece–themed setup, each OU represents a different pirate crew, blending functionality with creativity. These OUs replace standard business departments such as HR, IT, or Accounting.

**Example OUs Created:**  
- *Straw Hat Pirates*  
- *Red Hair Pirates*  
- *Blackbeard Pirates*  
- *Beast Pirates*


<p align="center">
  <img src="https://i.imgur.com/maTWHhF.png" width="80%" alt="OU Structure" />
</p>

---

<h2>📝 Step 2: Creating User Groups & Security Roles</h2>

Security groups were created to streamline permissions and simplify user management. By applying policies at the group level, permissions and GPOs remain consistent across the domain. These groups function similarly to Managers and Employees in a traditional corporate structure.
**Examples:**  
- `Captains` — Admin-level permissions  
- `CrewMates` — Standard user permissions  


<p align="center">
  <img src="https://i.imgur.com/QaGlGOE.png" width="80%" alt="Security Groups" />
</p>

---

<h2>📝 Step 3: Adding One Piece-Themed Users</h2>

With Active Directory Users and Computers (ADUC), user accounts were created for several well-known One Piece characters. Each account was assigned to the correct group to reflect the user’s role and crew within the domain.
**Example User Accounts:**  
- Ussop  
- Zoro  
- Nami  
- Sanji  
- Robin  



<p align="center">
  <img src="https://i.imgur.com/9QxI8cr.png" width="80%" alt="User Creation" />
</p>

---

<h2>📝 Step 4: Creating Administrative Accounts</h2>

Dedicated admin accounts were created to ensure proper security and adhere to best practices. The admin roles were intentionally assigned to mirror each character’s leadership role in the One Piece universe.
**Examples:**  
- `Luffy.Captain` — Domain Admin  
- `Kaido.Captain` — Domain Admin  
- `Shanks.Captain` — Domain Admin  



<p align="center">
  <img src="https://i.imgur.com/R0Q7MHl.png" width="80%" alt="Admin Accounts" />
</p>

---

<h2>📝 Step 5: Assigning Each Crew Their Own "Ship" (Work Folders)</h2>

To complete the setup, each crew (group) was assigned its own “ship” — a dedicated work folder.  
Permissions were configured so that only members of the same crew could access their ship’s folder.

(Except Zoro… he’s still trying to find his way there.)

<p align="center">
  <img src="https://i.imgur.com/TZNJcx1.png" width="80%" alt="Ship folders" />
</p>
<p align="center">
  <img src="https://i.imgur.com/bB6LH7C.png" width="80%" alt="Ship folders" />
</p>
<p align="center">
  <img src="https://i.imgur.com/ItP20p9.png" width="80%" alt="Ship folders" />
</p>

---

<h2>🎉 Conclusion</h2>

With users, groups, OUs, permissions, and work folders configured, this AD environment now operates as a fully functional client–server domain — uniquely themed around **One Piece**.  
This structure mirrors real enterprise environments while making the learning process more engaging and memorable.

---
