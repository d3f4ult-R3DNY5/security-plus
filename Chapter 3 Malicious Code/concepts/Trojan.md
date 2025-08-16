## **Trojan**

### Overview 
---
>[!info]
>- A type of malware that is **disguised as a legitimate software**
>- They are also called **trojan horses** 


### Types of Trojan 
---
RAT
- remote access Trojans 
- This used to gain a remote access to the system
- EDR is one of the best ways that can be used to detect the remote access Trojans


### Mitigation strategies
---
>[!tip]
>- **awareness programs** that help the employee to prevent them from installing the trojans 
>- **controlling the appplications and the softwares** that the users use 
>- **Antimalware and EDR ** tools 



### Related IOC's
---
>[!example] Indicators of Compromise 
>- **signatures** for the specific malware applications or downloadable files 
>- **C2 system hostnames and IP**
>- **Unknown** folders and files that are created on the target device 

### Example
---
>[!example]
>Trojan infection path starting with a user downloading an application from the Android app store that appears to be legitimate through automated download of malicious add-ons and remote control of the device.


![Pasted image 20250814160609.png](../../images/Pasted%20image%2020250814160609.png)

> [!example]
> Realife example is a **Triada Trojan** which acclaimed to be a modified, feature-enhanced WhatsApp version.
> - This would gain access of the host device information including the device ids subscriber and the devices hardware addresses .
> - This information is then used to register the device with a remote server 
> - Malicious payloads are then deployed and run on the target machine 

