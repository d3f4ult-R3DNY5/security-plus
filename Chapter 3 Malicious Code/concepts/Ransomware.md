## **Ransomware** 

### Overview 
---
>[!info]
>- malware that **takes over a computer** and then **demands a ransom**


### Types of ransomware
---
>[!warning]
>- **cryptomalware** - **encrypts files and then holds them hostage** until a ransom is paid
>- **threats** - report the user to law enforcement due to **pirated software** or **exposure of sensitive information**

### Method of delivery 
---
- Significant portion of ransomware attacks are delivered through **phishing emails** or **embedded links**
- They can also be delivered through **RDP** and other **vulnerable front facing applications**


### Related IOC's
---
>[!example] Indicator of Compromise
>-  **C2 traffic** and/or contact to known malicious IP addresses
>- Use of legitimat**e tools already present in the environment** in abnormal ways
>- **lateral movement** : gain information about the systems that are within the same level 
>- **encryption** of files 
>- **ransom note**
>- **data exfiltartion**

### Defense Stratergies 
---
>[!tip]
>- having consistent backups 

