## Cloud Access Security Brokers
---
>[!note]
>- Managing security policies consistently across these services **poses a major challenge for cybersecurity analysts.**
>- Cloud access security brokers (CASBs) are software tools that serve as **intermediaries between cloud service users and cloud service providers.** This positioning allows them to **monitor user activity and enforce policy requirements.**


CASB uses two approaches 

##### Inline CASB
---
>[!important] Inline CASB
>- solutions physically or logically **reside in the connection path between the user and the service.**
>- They may do this through a hardware appliance or an endpoint agent that routes requests through the CASB
>- Requires additional network configurations 
>- It provides the **advantage of seeing requests before they are sent to the cloud service, allowing the CASB to block requests that violate policy.**

##### API Based 
---
>[!important] API based CASB
>- solutions do not interact directly with the user **but rather interact directly with the cloud provider through the provider's API.**
>- No additional configs 
>- Doesn't block request that violate policy 


