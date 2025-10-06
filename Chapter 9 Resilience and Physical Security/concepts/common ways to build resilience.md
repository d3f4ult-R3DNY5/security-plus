## common ways to build resilience
---

### 1. Geographic dispersion of systems
---
>[!note]
>- ensures that a single disaster attack, or failure cannot disable or destroy them.
>- This is ensured in datacenters as well as other facilities 
>- Golden thumb rule is that : **place datacenters at least 90 miles apart, preventing most common natural disasters from disabling both**


### 2. Separation of servers 
---
>[!note]
>- This is commonly used **to avoid a single rack being a point of failure.**
>- Thus systems need to be placed **in two or more racks incase of a single point of failure of a Power distribution unit**


### 3. Use of multiple network paths 
---
>[!note]
>- This is used in case to ensure that the devices still have connectivity if there is a severed cable 


### 4. Redundant network devices 
---
Devices like IPS , witches , firewalls that are designed to **ensure high availability** 

[High availability designs](High%20availability%20designs.md)

### 5. Protection of power 
---
>[!note]
>- This can be made possible to have devices like UPS(uninterruptible power supply)
>- Devices like **battery , generators  etc** can be used 
>- **Managed power distribution units (PDUs)** are also used to provide Intelligent power management and remote control of power


### 6. system and storage redundancy 
---
>[!note]
>- backups , RAID, cloud services 


### 7. Platform diversity 
---
>[!note]
>- using frameworks and technologies from different vendors 
