## **Chapter 3 Malicious Code**


### **Exam Objectives**
---

![Pasted image 20250814152735.png](../images/Pasted%20image%2020250814152735.png)

### **Index**
---

[3.1 Malware](sub%20indexes/3.1%20Malware.md)

### Summary 
---
- **Ransomware**: Encrypts files, demands payment (often in cryptocurrency).
- **Trojans**: Disguised as legitimate software but execute malicious actions.
- **Worms**: Self-spreading through networks, email, or file shares.
- **Viruses**: Infect local systems, usually require user action.
- **Spyware**: Collects user/system data and sends it to attackers.
    - **Keyloggers**: Specialized spyware capturing keystrokes.
- **Rootkits**: Conceal attacker presence and resist security tools, often used with other malware.
- **Logic bombs**: Malicious code triggered by specific conditions; hidden in scripts or source code.
- **Bloatware**: Unwanted vendor software; not malicious but resource-heavy and vulnerable to exploitation.

**Defense Measures**

- Antivirus, antimalware, endpoint detection and response (EDR).
- Secure configuration and patching.
- User awareness to prevent, detect, and limit impact.


### Exam essentials 
---
### Malware Types & Traits

- **Ransomware**: Encrypts files, demands ransom.  
- **Trojans**: Fake legit software, runs malicious code.  
- **Worms**: Self-replicating across networks.  
- **Viruses**: Infect files/systems, need user action.  
- **Spyware**: Steals user/system info.  
- **Keyloggers**: Record keystrokes.  
- **Rootkits**: Hide attacker presence and tools.  
- **Logic bombs**: Triggered by specific conditions.  
- **Bloatware**: Unwanted vendor-installed software, resource-heavy and exploitable.  

---

### Indicators of Compromise (IoCs)

- Suspicious C&C traffic (IP, hostnames, domains).  
- Abnormal use of system utilities.  
- Lateral movement between systems.  
- New/modified files or directories.  
- File encryption or mass file changes.  
- Data exfiltration activity.  
- Malware signatures (though often obfuscated).  

---

### Mitigation Methods

- Manual removal or specialized tools.  
- System reinstallation or restore from clean backup.  
- Antivirus, EDR, and regular patching.  
- Awareness and monitoring for abnormal activity.  
