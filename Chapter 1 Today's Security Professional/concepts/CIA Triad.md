## **CIA Triad**
---

The CIA triad comprises of 
1. confidentiality 
2. integrity 
3. availability 


### **1. Confidentiality**
---
- unauthorised users should not have access to sensitive information
- cybersec professionals do so by implementing the security controls to prevent this issue from occurring 
	- use of firewalls 
	- use of ACL 
		- only people with certain access level can see the data 
	- use of encryption
		- where the messages is converted into an encoded format where only certain people who have access to the keys to decode the message can read it 
	- 2FA or Multi FA

### **2. Integrity** 
---
- there are no unauthorized modifications to information or systems whether done intentionally or unintentionally
- security controls are implemented by 
	- hashing 
		- mapping the data of any length to the data with fixed length of a unique value
	- integrity monitoring solutions 
	- Digital signatures 
	- certificates 
		- combines with digital signature to verify information


> [!tip]
> data received = data sent 
### **3. Availability** 
---
- Ensures that the system and information are readily available to the authorized individuals as and when needed 
- security controls that are used to implement this is as follows 
	- clustering 
	- fault tolerance 
	- backups 
	- redundacy 



>[!note]  
>Although non repudiation is not a part of the CIA triad it is an important security aspect

### **Non Repudiation**
---
- This mean that if someone or something has performed some action can't later deny that the action is not performed.
- This could be like a contract 

Works on two concepts 
#### 1. proof of integrity 
---
This verifies that the data has not changed .
>[!note]
>- The data remains accurate and consistent
>- This can be accomplished or a hash 
>- This doen't necessarily verify who has sent the data , It only tells us that the data has been changed 




tags : #GeneralSecurityConcepts 
