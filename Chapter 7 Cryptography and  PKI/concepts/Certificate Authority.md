### Certificate Authority
---
Certificate authorities (CAs) are the **glue that binds the public key infrastructure together.** 

To obtain a **digital certificate from a reputable CA,** you must prove your **identity to the satisfaction of the CA.**

Here are some of the most reputed CA 
- IdenTrust 
- Amazon Web Services 
- DigiCert 
- Sectigo/Comodo
- Global Sign 
- GoDaddy 
- Let's Encrypt 

### Process of obtaining a certificate 
---
The certificates issued by a CA **are only as good as the trust placed in the CA** that issued them. This is extremely important if someone wants to verify the digital certificate.

>[!caution]
>It is generally **unsafe to trust a CA you dont recognise** 

- If you configure your browser to trust the CA it will trust all the certificates that is issued by the CA 

1. **Registration authorities (RAs) assist CAs** with the burden of verifying users' identities prior to issuing digital certificates. **They help in validating the user** 
2. Certificate authorities **must carefully protect their own private keys** , To understand more on how they do this head [here]([How CA protect their own private keys](How%20CA%20protect%20their%20own%20private%20keys.md))
3. The use a **root certificate to create subordinate intermediate CA** that issues the other Certificate this is known as **Certificate chaining** 

[Process of Obtaining a certificate](Process%20of%20Obtaining%20a%20certificate.md)

### Certificate formats 
---
Digital certificates are stored in files, and those files come in a variety of formats both binary and text 

- The most common binary format is the **Distinguished Encoding Rules (DER) format**
- **The Privacy Enhanced Mail (PEM) certificate format is an ASCII** is the text version of certificate 
- **The Personal Information Exchange (PFX) format is commonly used by Windows systems**
- Windows also use the **P7B**