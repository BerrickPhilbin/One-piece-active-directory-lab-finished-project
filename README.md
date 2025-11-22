<p align="center">
  <img src="https://i.imgur.com/CS2qwib.png" alt="Active Directory Logo" />
</p>

<h1>Active Directory — Post-Deployment Configuration (One Piece Theme)</h1>

This repository documents the configuration performed after deploying an **Active Directory Domain Services (AD DS)** environment — focusing on **organizational structure**, **user creation**, **permissions**, and **server–client relationships**, all themed around characters from **One Piece**.

---

<h2>🧰 Environments and Technologies Used</h2>

- Windows Server (2019 / 2022)  
- Active Directory Domain Services  
- DNS  
- Group Policy Management  
- Windows 10 / 11 Client Machine  
- Remote Desktop  

---

<h2>🏗️ Overview of Post-Deployment Steps</h2>

- Step 1 — Designing the Organizational Unit (OU) Structure  
- Step 2 — Creating User Groups & Security Roles  
- Step 3 — Adding One Piece-Themed Users  
- Step 4 — Creating Administrative Accounts  
 

---

<h2>📝 Step 1: Designing the Organizational Unit (OU) Structure</h2>

An organized AD structure helps manage permissions, users, and policies.  
For this project, OUs were named after **One Piece factions** to make the environment more engaging.

**Example OUs Created:**  
- *Straw Hat Pirates*  
- *Red Head Pirates*  
- *BlackBeard Pirates*
- *Beast Pirates*

<p align="center">
  <img src="https://i.imgur.com/maTWHhF.png" width="80%" alt="OU Structure" />
</p>

---

<h2>📝 Step 2: Creating User Groups & Security Roles</h2>

Security groups were created to manage shared permissions efficiently.

**Examples:**  
- `CrewMates` Users
- `Captains`  Admins

These groups help apply permissions and GPOs consistently.

<p align="center">
  <img src="https://i.imgur.com/QaGlGOE.png" width="80%" alt="Security Groups" />
</p>

---

<h2>📝 Step 3: Adding One Piece-Themed Users</h2>

Using **Active Directory Users and Computers (ADUC)**, users were created to represent characters in the series.

**Example User Accounts:**  
- Ussop
- Zoro  
- Nami
- Sanji
- Robin   

Each user was placed in their appropriate Groups based on status, and faction.

<p align="center">
  <img src="https://i.imgur.com/BjNtZAL.png" width="80%" alt="User Creation" />
</p>

---

<h2>📝 Step 4: Creating Administrative Accounts</h2>

Separate admin accounts were created for elevated privileges (best practice).

**Examples:**  
- `Luffy.Captain` — Domain Admin  
- `Kaido.Captain` — Security Admin  
- `Shanks.Captain` — Organizational Admin  

Roles were assigned based on series hierarchy for fun and clarity.

<p align="center">
  <img src="https://i.imgur.com/AbvKzk4.png" width="80%" alt="Admin Accounts" />
</p>

---

<h2>📝 Step 5: Finishing up by assigning each "crew" (group) their own "ship"(work folders) based on their crew, and limiting access to said folders to their respective "crews" </h2>
 (except zoro, he gets a little lost)
<p align="center">
  <img src="https://i.imgur.com/TZNJcx1.png" width="80%" alt="Ship folders" />
</p>
<p align="center">
  <img src="https://i.imgur.com/bB6LH7C.png" width="80%" alt="Ship folders" />
</p>
<p align="center">
  <img src="https://i.imgur.com/ItP20p9.png" width="80%" alt="Ship folders" />
</p>

<h2>🎉 Conclusion</h2>

With users, groups, OUs, and policies in place — this AD environment now reflects a fully functional client–server domain, personalized with a **One Piece theme**.  
This setup mirrors real enterprise structure while keeping the learning process fun and relatable.

---
