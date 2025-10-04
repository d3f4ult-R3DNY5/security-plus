### PKI
---
>[!note]
>The major strength of public key encryption is its ability to **facilitate communication between parties previously unknown to each other.**

### Certificates 
---
>[!note]
>- Digital certificates **provide communicating parties with the assurance that the people they are communicating with truly are who they claim to be**. So in a sense it provides some form of authentication
>- They are basically the **endorsed copy of a person's Public Key**
>- This endorsment is done by authorities known as **CA (Certificate Authority)**

>[!tip] About Digital Certificates 
>They contain the informatio**n that is governed by the international standard that is X509** and it contains the following attributes 
>- Version of the X509 certificate 
>- serial no 
>- Signature Algorithm identifier (techniques used by CA to sign the contents of the Cert)
>- Issuer name (name of the CA)
>- Validity period 
>- Subject's Common name (CN)
>- Subjects alternative names (SAN) which could be 
>	- domains 
>	- IP
>- Subjects Public Key 


### Support of the X509 version 3
---
- computer/ machines 
- users 
- email address
- devlopers

Some times the CA would include a wild card `*` in the Subjects Common name which means  it applies to all the sub domains 


### Certificate Authority 
---
Certificate authorities (CAs) are the glue that binds the public key infrastructure together. 
[Certificate Authority](Certificate%20Authority.md)