## site considerations
---
1. [Hot Sites](Hot%20Sites.md)
2. [warm sites](warm%20sites.md)
3. [cold sites](cold%20sites.md)

Restoration in these sites depends on the decisions balance the **criticality of systems and services to the operation of the organization against the need for other infrastructure to be in place and operational.**

A restoration order list would look like 
1. Restore network connectivity and a bastion or shell host.
2. Restore network security devices 
3. Restore storage and database services.
4. Restore critical operational servers.
5. Restore logging and monitoring service.
6. Restore other services as possible.

This is known as a **restoration order**
### Advantages of cloud over a warm site
---
**Cloud platforms** can **replace or complement traditional recovery sites** by using **multiple linked datacenters across regions**. Organizations can **replicate or design systems to run in multiple regions** for **resilience**. **Pay-as-you-go pricing** allows them to **scale or restore infrastructure in new locations when needed**, improving **capacity** and **disaster recovery efficiency**.