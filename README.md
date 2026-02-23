Section 1: System Inventory

Section 2:The Access Control Model

Section 3: Top Process Analysis and Risk

Section 4: Git Submission



# Lab 02: System Audit 
 
**Student Name:** [Arielle Sidberry]   
**Date:** [2/3/2026] 
 
--- 
 
## Section 1: System Inventory 
 
| Component | Specification | 
|-----------|---------------| 
| Operating System | [Windows 11 Pro Version 25H2]  

Total Installed RAM | [ 16.0 GB (15.5 GB usable] 
| CPU Model & Clock Speed | [Intel(R)Core(TM) Ultra 5 135U @ 2.54 GHz] 
 
--- 
 
## Section 2: The Access Control Model 
 
### Model Definition 
My operating system ([Windows 11 Pro]) uses [RBAC] (Define the acronym) as its primary Access Control Model. 
 
**Definition:** [Role-Based Access Control is an access control model where permissions are assigned to roles, and users receive access based on their assigned job role within an organization.] 
 
### Relationship to Permissions 
[ IN RBAC, users are assigned read, write, and execute permissions based on their assigned role.] 
 
### Principle of Least Privilege (PoLP) Application 
[ Administrators enforce the Principle of Least Privilege by using Role Based Access Control to assign permissions to the roles based on job functions. The users are added to the role based on their job responsibilities.] 
 
**Concrete Example:** 
[Provide a specific example from your OS. Examples: 

- Windows: The Administrator creates security groups that define read, write, and execute permissions to users. Windows will enforce these permissions by blocking unauthorized access by requiring permission from certain users.  
 
--- 
 
## Section 3: Top Process Analysis & Risk 
 
### Process 1: [Bash] 
- **Process Name:** [bash.exe] 
- **Process ID (PID):** [1492] 
- **Resource Consumption:** [CPU: 0%] 
 
**Security Risk Hypothesis:** 
[ An attacker could execute unauthorized commands and gain access to sensitve files or network resources.] 
 
### Process 2: [Google Chrome] 
- **Process Name:** [chrome.exe] 
- **Process ID (PID):** [28036] 
- **Resource Consumption:** [RAM: 3.27 GB] 
 
**Security Risk Hypothesis:** 
[Example: The attacker could take advantage of a browsers vulnerability to compromise the system, users data and network access.] 
 
### Process 3: [Adobe Acrobat] 
- **Process Name:** [armsvc.exe] 
- **Process ID (PID):** [5680] 
- **Resource Consumption:** [RAM: 170 KB] 
 
**Security Risk Hypothesis:** 
[Example: The attacker can use a malicious PDF file to compromise the system and steal data.] 

## Screenshots of Operations System

 <img width="1851" height="850" alt="System Inventory 1" src="https://github.com/user-attachments/assets/ef619d33-0e5c-474b-a8bf-5963c658567b" />


<img width="1852" height="622" alt="System Inventory 2" src="https://github.com/user-attachments/assets/34a042a5-d564-4a79-ae1c-bccedab0e087" />

--- 
 
## Section 4: Submission Checklist 
 
- [ ] File named correctly: System-Audit.md 
- [ ] All sections completed with accurate information 
- [ ] Proper Markdown formatting used 
- [ ] Spell-checked and proofread 
- [ ] Committed to GitHub with meaningful message (e.g., "Lab 02: Initial System Audit") 
- [ ] Repository link verified 

https://github.com/asidberry/System-Audit.md.git 
