<h1>Windows Active Directory Lab</h1>

This project details my hands-on work with Microsoft Active Directory (AD) and Windows Server, completed through the TryHackMe Active Directory lab. It reflects my foundational abilities in managing users and groups, applying Group Policy Objects (GPOs), and gaining awareness of how core network services such as DNS and DHCP support Active Directory functionality. Through this experience, I gained practical knowledge of enterprise network architecture and account administration, building skills directly applicable to IT support and system administration.

---

<h2>Tools Used</h2>

*Active Directory Users and Computers (ADUC)
*Remote Desktop Protocol (RDP)
*Command Prompt
*Group Policy Management Editor

---

## Project Explanation

**Using the Active Directory Users and Computers (ADUC) console, I was able to perform the following tasks:**

<p align="center">
  <img src="images/organizational_chart.png" alt="Organizational chart" width="500" /><br/>
  <img src="images/extra_ou.png" alt="Extra OU" width="260" />
  <img src="images/permission_to_delete.png" alt="Permission to delete OU" width="260" /><br/>
  <img src="images/offboarding_users_from_ou.png" alt="Offboarding users from OU" width="500" />
</p>

**User Lifecycle Management** – Given the organizational chart + contradictory AD displayed above, I was able to practice disabling and deleting Organizational Units (OU) and accounts to improve security during offboarding or inactivity.

<p align="center">
  <img src="images/delegation_control_wizard.png" alt="Group creation and user assignments" width="500" />
</p>

**Group Management** – Created security groups with descriptive names and assigned users to manage permissions and resource access.

<p align="center">
  <img src="images/delegation_of_permission.png" alt="Delegated permissions for a user" width="500" />
</p>

**User Delegation** — Assigned a user from the IT OU the permission to reset passwords for all users in the Sales department, demonstrating controlled administrative access.

<p align="center">
  <img src="images/rdp_connection_screen.png" alt="RDP password reset step 1" width="340" />
  <img src="images/reset_password_at_logon.png" alt="RDP password reset step 2" width="440" />
</p>

**Helpdesk Simulation** — Logged in via RDP as the delegated account to perform a password reset, replicating a common IT support workflow.
