## Chapter 11 Endpoint Security

### Exam Essentials 
---
![Pasted image 20251010081757.png](../images/Pasted%20image%2020251010081757.png)
![Pasted image 20251010081836.png](../images/Pasted%20image%2020251010081836.png)
![Pasted image 20251010081908.png](../images/Pasted%20image%2020251010081908.png)


### Index
---
- [11.1  Operating System Vulnerabilities](index/11.1%20%20Operating%20System%20Vulnerabilities.md)
- [11.2 Endpoint Security Tools](index/11.2%20Endpoint%20Security%20Tools.md)
- [11.3 Hardening Techniques](index/11.3%20Hardening%20Techniques.md)
- [11.4 OS hardening](index/11.4%20OS%20hardening.md)
- [11.5 Securing embedded systems and specialized systems](index/11.5%20Securing%20embedded%20systems%20and%20specialized%20systems.md)
- [11.6 Asset Management](index/11.6%20Asset%20Management.md)

### Summary 
---
#### Endpoint Security Overview
- Endpoints are the most common and varied devices in organizations.  
- Secure them from boot using firmware-based secure boot techniques.  
- Use TPMs, hardware security modules (HSMs), key management systems, and secure enclaves to protect secrets.  

#### Operating System and Hardware Considerations
- Understand OS vulnerabilities and their impact on endpoint security.  
- Keep firmware updated; account for hardware life cycle, end-of-life, and legacy systems.  

#### Endpoint Protection Techniques
- Use antivirus/antimalware tools to prevent infections.  
- Implement host-based firewalls and IPSs.  
- Disable unused ports, protocols, and default accounts.  
- Apply and enforce security baselines via Group Policy or SELinux.  
- Use EDR/XDR tools for detection, monitoring, and centralized response.  
- Deploy DLP tools to prevent unauthorized data exposure.  

#### Drive Encryption and Media Sanitization
- Use drive encryption to protect data on lost or stolen drives.  
- Sanitize media before disposal or reuse through wiping or physical destruction.  
- Match sanitization method to media type and data sensitivity.  

#### Securing Specialized and Embedded Systems
- Secure IoT, SCADA, ICS, and other embedded or real-time systems.  
- These devices are often in medical, industrial, and consumer environments.  
- Plan around limited capabilities, unique architectures, and security models.  

#### Asset Management
- Begin security tracking at procurement.  
- Maintain an inventory of all hardware, software, and data assets.  
- Assign ownership and classify assets by data sensitivity and criticality.  
- Track assets throughout their life cycle to prevent shadow IT or data loss.  


### Exam Essentials 
---
#### Understand Operating System and Hardware Vulnerabilities
- Operating systems can have vulnerabilities from weak configurations, unpatched services, or insecure applications.  
- Mitigate risks using patch management, configuration baselines, and hardening.  
- Hardware security includes firmware updates, secure boot, and proper life cycle management to address end-of-life and legacy risks.  

#### Hardening and Protecting Systems
- System protection requires securing the full endpoint — boot integrity, data storage, configuration, communication, and network exposure.  
- Use secure boot and trusted boot mechanisms to prevent driver and bootloader attacks.  
- Employ antivirus, antimalware, EDR, XDR, and DLP tools to monitor system activity and detect threats.  
- Network-based tools such as host intrusion prevention systems (HIPS) and host firewalls defend against network attacks.  

#### Endpoint Configuration, Policies, and Standards
- Apply system hardening by disabling unused services, changing default passwords, and using secure configuration options (Windows Registry, Linux configs, etc.).  
- Follow established policies and standards aligned with system risk profiles.  
- Maintain effective patch management for OS and applications to prevent exploitation of known vulnerabilities.  

#### Specialized Systems (SCADA, ICS, IoT)
- SCADA and ICS manage industrial environments like manufacturing plants and power systems.  
- IoT devices are network-connected and often controlled by third parties, introducing additional risks.  
- Secure these systems using isolation, network segmentation, and vendor-specific security updates.  

#### Asset Management for Software, Data, and Hardware
- Manage assets from acquisition to decommissioning.  
- Track ownership, classification, and inventory for visibility and accountability.  
- Ensure records support operations, security monitoring, and incident response activities.  

#### Drive Encryption and Data Sanitization
- Full-disk encryption secures all contents; volume or file encryption protects only specific areas.  
- Sanitization ensures data cannot be recovered using secure wiping or physical destruction.  
- Match sanitization techniques to the data’s sensitivity and the type of media being handled.  
