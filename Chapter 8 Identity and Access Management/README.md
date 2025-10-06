## Chapter 8 Identity and Access Management

### Exam Objectives
---
![Pasted image 20251005084930.png](../images/Pasted%20image%2020251005084930.png)


### Index
---
- [8.1 Identity](index/8.1%20Identity.md)
- [8.2 Accounts](index/8.2%20Accounts.md)

### Summary
---
- **IAM** secures who can access what and how.
- **Authentication**: verifies identity using factors — something you know (password), have (token), are (biometrics), or where you are (location).
- **Authorization**: defines what authenticated users can do.
- **Account types**: guest, user, service, and administrative. Managed through policies like lockouts, expirations, and disabling inactive accounts.

#### Authentication Systems
- Common protocols: **RADIUS, LDAP, EAP, CHAP, OAuth, OpenID, SAML**.
- **SSO (Single Sign-On)**: single login grants access across systems.
- **Federation**: identity is shared across organizations using trusted identity providers.
- **Attestation**: validates that an identity truly belongs to its user.

#### Multifactor Authentication (MFA)
- Reduces risks of password theft and brute-force attacks.
- Factors: biometrics, hardware tokens, software authenticators.
- **Biometric accuracy** depends on false acceptance/rejection rates.
- **Password vaults** securely store credentials for individuals or enterprises.

#### Password and Authentication Practices
- Focus on **password length** over complexity (per NIST guidance).
- **Passwordless authentication** uses tokens or secure apps instead of passwords.
- Enforce password policies: reuse prevention, aging, and reset controls.

#### Access Control Models
- **ABAC**: access based on attributes.  
- **RBAC**: access by role.  
- **DAC**: owner decides permissions.  
- **MAC**: system-enforced strict control.  
- **PAM (Privileged Access Management)**: governs admin privileges.
- **Just-in-time** and **ephemeral accounts** reduce standing privileges.

### Exam Essentials: Identity and Access Management (IAM)
---
#### Identities and Authentication
- Identities form the base of **authentication** and **authorization**.  
- Users authenticate using **usernames**, **certificates**, **tokens**, **SSH keys**, or **smartcards**.  
- Identities include **attributes** such as role, title, or personal data to define access.  

#### Single Sign-On (SSO) and Federation
- **SSO** allows one login to access multiple systems.  
- **Federation** extends authentication across organizations via trusted providers.  
- Common technologies: **LDAP**, **OAuth**, **SAML**.  

#### Passwords, Passwordless, and Multifactor Authentication (MFA)
- **Password policies** define length, complexity, reuse, expiration, and age.  
- **Password managers** reduce reuse and secure credential storage.  
- **MFA** adds layers beyond passwords:  
  - Something you know (password)  
  - Something you have (token)  
  - Something you are (biometrics)  
  - Somewhere you are (location)  
- **Passwordless authentication** uses secure tokens or apps instead of passwords.  

#### Account Management and Privileged Access
- Account types: **user**, **guest**, **admin**, **service**.  
- Manage **provisioning, deprovisioning**, and **account life cycle**.  
- **Privileged Access Management (PAM)** uses:  
  - **Just-in-time permissions**  
  - **Ephemeral accounts** for temporary elevated access.  

#### Access Control Models
- **ABAC (Attribute-Based)**: access by user attributes.  
- **RBAC (Role-Based)**: access by role.  
- **Rule-Based Access Control**: uses defined rules to allow or deny.  
- **MAC (Mandatory Access Control)**: admin-enforced access.  
- **DAC (Discretionary Access Control)**: user decides access to owned resources.  
- **PAM**: controls and audits administrative accounts.  
