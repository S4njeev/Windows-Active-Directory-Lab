<h1>Windows Active Directory Lab</h1>

This project details my hands-on work with Microsoft Active Directory (AD) and Windows Server, completed through the TryHackMe Active Directory lab. It reflects my foundational abilities in managing users and groups, applying Group Policy Objects (GPOs), and gaining awareness of how core network services such as DNS and DHCP support Active Directory functionality. Through this experience, I gained practical knowledge of enterprise network architecture and account administration, building skills directly applicable to IT support and system administration.

---

## Project Explanation

Using the Active Directory Users and Computers (ADUC) console, I was able to perform the following tasks:

---

<img src="images/organizational_chart.png" alt="Screenshot of the organizational chart of company" width="600">

<div style="display: flex; gap: 10px; justify-content: flex-start;">
  <img src="images/extra_ou.png" alt="Screenshot displaying the extra OU that I am going to delete" width="295">
  <img src="images/permission_to_delete.png" alt="Screenshot showing enabling permission to delete the OU" width="295">
</div>

<img src="images/offboarding_users_from_ou.png" alt="Screenshot showing which users offboarded from the OU" width="600">

**User Lifecycle Management** – Given the organizational chart + contradictory AD displayed above, I was able to practice disabling and deleting Organizational Units (OU) and accounts to improve security during offboarding or inactivity.

---

<img src="images/delegation_control_wizard.png" alt="ADUC screenshot showing group creation and user assignments" width="600">

**Group Management** – Created security groups with descriptive names and assigned users to manage permissions and resource access.

---

<img src="images/delegation_of_permission.png" alt="ADUC screenshot showing delegated permissions for a user" width="600">

**User Delegation** — Assigned a user from the IT OU the permission to reset passwords for all users in the Sales department, demonstrating controlled administrative access.

---

<div style="display: flex; gap: 10px; justify-content: flex-start;">
  <img src="images/rdp_connection_screen.png" alt="RDP screenshot showing password reset step 1" width="400">
  <img src="images/reset_password_at_logon.png" alt="RDP screenshot showing password reset step 2" width="500">
</div>

**Helpdesk Simulation** — Logged in via RDP as the delegated account to perform a password reset, replicating a common IT support workflow.
