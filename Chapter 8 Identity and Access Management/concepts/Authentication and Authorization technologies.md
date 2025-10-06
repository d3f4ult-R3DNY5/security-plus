### Authentication and Authorization technologies

### EAP
---
>[!note]
>- The **Extensible Authentication Protocol (EAP) is an authentication framework** that is commonly used for wireless networks.
>	- This is implemented in the following 
>	- LEAP 
>	- EAP TLS
>	- EAP TTLS
>- **Challenge Handshake Authentication Protocol (CHAP)** is an authentication protocol designed to provide more security than **PAP**
>	- It uses a 3 way handshake and challenge to send credentials 
>![Pasted image 20251005132452.png](Pasted%20image%2020251005132452.png)

### 802.1 X systems  
---
This is responsible for **network access control (NAC)** and is primarly used for **authenticating the devices that need to connect to the network .** 

>[!note]
>- In 802.1X systems, supplicants send **authentication requests to authenticators** such as network switches, access points, or wireless controllers.
>- These controllers connect to an authentication server via **RADIUS**
>- The RADIUS server than relies on a backend directory like **LDAP or AD**
>![Pasted image 20251005132029.png](Pasted%20image%2020251005132029.png)



### RADIUS
---
>[!note]
>- This stands for **Remote Authentication Dial In user Service**
>- This is used for **authentication, authorization, and accounting (AAA)**
>- Operates via TCP and UDP on a client-server model 
>- Use**s IpSec to encrypt traffic** and **uses MD5 for the clients password** hash

### TACAS+
---
>[!note]
>- **Terminal Access Controller Access Control System Plus** designed by Cisco 
>- Use**s TCP traffic to provide** authentication, authorization, and accounting services.
>- It provides **full-packet encryption as well as granular command controls**, allowing individual commands to be secured as needed.


### Kerberos 
---
>[!note]
>- Kerberos is a protocol for **authenticating service requests between trusted hosts across an untrusted network like the Internet.**
>- This made for the user's who are authenticating via an untrusted network and uses Authetication to shield its traffic 
>- Kerberos account is made up of 3 things 
>	- primary which is the username which is also known as the realms which consist of a group of users 
>	- These are separated by trust boundaries and **Kerberos Key distribution Centers** 

Working 
>[!example] steps 
>1. When a client wants to use Kerberos to access a service, the client **requests an authentication ticket, or ticket-granting ticket (TGT).**
>2. An authentication server checks the client's credentials and **responds with the TGT, which is encrypted using the secret key of the ticket-granting service (TGS).**
>3. The client sends the **TGT to the TGS (which is usually also the KDC**) and **includes the name of the resource it wants to use.**
>4. The TGS sends back a v**alid session key for the service, and the client presents the key to the service to access it**
>![Pasted image 20251005133614.png](Pasted%20image%2020251005133614.png)


### SSO 
---
>[!note]
>- Allows a **user to login in with a single identity** and then use multiple **systems or services without reauthenticating**
>- Organisation implement SSO for many systems but may require additional authentication steps or use of an additional privileged account for high-security environments
>- Directory services like the **Lightweight Directory Access Protocol (LDAP) are commonly deployed as part of an identity management infrastructure** and offer **hierarchically organized information** about the org
>
>![Pasted image 20251005134404.png](Pasted%20image%2020251005134404.png)

[Core technologies involving SSO](Core%20technologies%20involving%20SSO.md)

### Federation 
---
>[!note]
>- In many organisation, identity information is handled by an **IdP**
>- The IdP are responsible for the **creation, maintenance and to eventual retirement of the identity** 
>- Federation is commonly used for many web services **, but is also used for other applications** 
>- Commonly used federated environment
>	- The principle is **typically a user**
>	- IdP : **parties reposnible for providing the identity**
>	- SP : **who provide services to users whose identities have been attested to by an identity provider**
>- The term **relying party** is the same the service party but will require **authentication and identity claims** from an IdP


In many scenarios the **SAML** and **OpenID is used for federal authentication** and **Oauth is used to handle the accessibility to authorized resources**