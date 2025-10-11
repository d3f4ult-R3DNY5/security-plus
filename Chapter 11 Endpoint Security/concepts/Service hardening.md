## Service Hardening 
---

>[!note]
>One of the fastest ways to **decrease the attack surface of a system is to reduce the number of open ports and services that it provides by disabling ports and protocols**
>- Port scanners are commonly used to quickly assess which ports are open on systems on a network, **allowing security practitioners to identify and prioritize hardening targets.**


### Common services and ports used 
---
![Pasted image 20251010141038.png](../../images/Pasted%20image%2020251010141038.png)
![Pasted image 20251010141055.png](../../images/Pasted%20image%2020251010141055.png)


### Blocking 
---
Alothough blcoking the ports and the services using a firewall is a viable option, the best option for unneeded services is to disable them entirely

##### For windows
- Services.msc console
##### For linux 
- service --status-all



