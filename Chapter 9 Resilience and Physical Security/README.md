## Chapter 9 Resilience and Physical Security

### Exam Objectives
---
![Pasted image 20251006075626.png](../images/Pasted%20image%2020251006075626.png)


### Index
---
- [9.1 Resilience and Recovery in Security Architecture](index/9.1%20Resilience%20and%20Recovery%20in%20Security%20Architecture.md)
- [9.2 Architectural constraints and Security](index/9.2%20Architectural%20constraints%20and%20Security.md)
- [9.3 Storage Resiliency](index/9.3%20Storage%20Resiliency.md)
- [9.4 Response and Recovery controls](index/9.4%20Response%20and%20Recovery%20controls.md)
- [9.5 Physical Security Controls](index/9.5%20Physical%20Security%20Controls.md)

### Summary 
---
#### Core Concept
Resilient infrastructure ensures **availability** through redundancy, recovery, and robust design.  
Techniques like **geographic dispersal**, **power protection**, and **vendor diversity** maintain operations during disruptions.  

#### Technical and Design Elements
- **Geographic diversity** protects against regional disasters.  
- **High availability** uses clustering and load balancing to manage failures and scale systems.  
- **Multicloud and platform diversity** reduce dependency on any one provider.  
- **Backup power** (UPS, generators) sustains operations during power loss.  

#### Backup and Data Protection
- **Full backup**: copies all data.  
- **Differential backup**: copies changes since the last full backup.  
- **Incremental backup**: copies changes since the last backup (full or incremental).  
- **Snapshots**: capture system state at a specific moment.  
- **Images**: replicate full systems for recovery or deployment.  
- **Journaling**: logs changes for replication and restoration.  

#### Recovery and Continuity
- **Capacity planning** and **continuity testing** ensure readiness.  
- **Disaster recovery sites**:  
  - **Hot site**: fully operational immediately.  
  - **Warm site**: partially prepared, needs data/staff.  
  - **Cold site**: minimal setup, requires full deployment.  
- **Restoration order**: prioritize systems based on criticality and dependencies.  

#### Physical Security
- Protects infrastructure using **fences, bollards, lighting, access badges, and entry systems**.  
- **Sensors** detect breaches or anomalies.  
- Physical attacks require manual detection and response.  

#### TL;DR
Resilience = redundancy + recovery + readiness.  
Use geographic and vendor diversity, strong backups, and tested recovery plans.  
Combine **HA systems**, **DR sites**, and **physical security** for full operational continuity.


### Exam Essentials 
---
#### Redundancy Builds Resilience  
Redundant systems, networks, and even datacenters are a key element in ensuring availability.  
Redundant designs need to address the organizational risks and priorities that your organization faces to ensure the best trade-offs between cost and capabilities.  
Geographic dispersal; load balancers and clustering; power protection and redundancy; RAID; backups; and diversity of technologies, systems, cloud service providers, and platforms are all ways to build and ensure resiliency.  

Considerations include availability, resilience, cost, responsiveness, scalability, ease of deployment, risk transference, ease of recovery, patch availability, inability to patch, power, and compute.  
Capacity planning helps to ensure that there is enough capacity to handle issues and outages including ensuring you have enough people, technology, and infrastructure to recover.  
Multicloud environments as well as platform diversity can help ensure that a single technology or provider's outage or issue does not take your organization offline, but they create additional complexity and costs.  

---

#### Backups Ensure Recovery  
Backups help ensure organizations can recover from events and issues.  
Backups are designed to meet an organization's restoration needs, including how long it takes to recover from an issue and how much data may be lost between backups.  

Backup locations and frequency are determined based on the organization's risk profile and recovery needs, with offsite backups being a preferred solution to avoid losing backups in the same disaster as the source systems.  
Snapshots, journaling, and replication each have roles to play in ensuring data is available and accessible.  
Encryption is used to keep backups secure both in-transit and at rest.  

---

#### Response and Recovery Are Critical  
Failures will occur, so you need to know how to respond.  
Having a disaster recovery location, like a hot, warm, or cold site or a redundant cloud or hosted location, can help ensure that your organization can return to operations more quickly.  

Having a predetermined restoration order provides a guideline on what needs to be brought back online first due to either dependencies or importance to the organization.  
Testing, including tabletop exercises, failover testing, simulations, and parallel processing, are all common ways to ensure response and recovery will occur as planned.  

---

#### Physical Security Controls Are a First Line of Defense  
Keeping your site secure involves security controls like fences, lighting, alarms, bollards, access control vestibules, cameras, and other sensors.  
Ensuring that only permitted staff are allowed in using locks, badges, and guards helps prevent unauthorized visitors.  

Sensors must be selected to match the environment and needs of the organization.  
Infrared, ultrasonic, pressure, and microwave sensors have different capabilities and costs.  
Brute-force attacks, as well as attacks against RFID and environmental attacks, need to be considered in physical security design.
