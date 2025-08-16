## Rootkits 

### Overview 
---
>[!info]
>- They are designed in such a way that they can access the systems through the **backdoor**
>- Modern rootkits involved the technologies to **evade the detection tactics**
>- Rootkit detection in a system can be very challenging because the system infected with malware **ca't be trusted**



### Defense Strategies
---
>[!tip]
>- The best mechanism to detect the rootkit is to **test the suspected system**
>- Look for **behaviours and signatures that resemble the rootkit**
>- **restore the affected system** from a previously known backup 
>- Having **up to date patches to address the critical flaws**

### Common IOC for rootkits 
---
>[!example] Indicators of Compromise
>- File hashes and signatures 
>- C2 domains, IP addresses, and systems
>- Behavior-based identification like the creation of services, config changes, file access and command invocation
>- Opening ports or Creation of a reverse proxy tunnel

