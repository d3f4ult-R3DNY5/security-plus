### Types of access controls

### 1. MAC
---
>[!note]
>- Mandatory access control (MAC) systems **rely on the operating system to enforce control as set by a security policy administrator**.
>- users **do not** have the **ability to grant access to files or otherwise change the security policies** that are set centrally.
>- SELinux in linux and Mandatory Integrity control in windows 


### 2. DAC
---
>[!note]
>- Discretionary access control (DAC) is an access control scheme **that many people are used to from their own home PCs.**
>- it **assigns owners for objects like files and directories**, and then allows the owner to delegate rights and permissions to those objects as they desire.
>- Linux file system is the best example for this 

### 3. RBAC
---
>[!note]
>- Role based access control 
>- **rely on roles that are then matched with privileges** that are assigned to those roles.
>- Based on 3 primary rules 
>	- **Role assignment**, which states that subjects can use **only permissions that match a role they have been assigned.**
>	- **Role authorization, which states that the subject's active role** must be **authorized for the subject.**
>	- **Permission authorization,** which states tha**t subjects can use only permissions that their active role is allowed to use**


### 4. RuBAC
---
>[!note]
>- Rule based access control 
>- it is applied using **a set of rules, or access control lists (ACLs) that apply to various objects or resources.**
>- When an attempt is made to access the object it checks to see if the access is allowed 

### 5. ABAC
---
>[!note]
>- attribute based access control 
>- it relies on **policies that are driven by attributes of the users.**
>- complex ruleset definition but easy to manage 
>- useful  in system that has complex user rights 

