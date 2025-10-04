## Process of Obtaining a certificate
### Generation and Destruction 
---
###### Enrollment 

>[!info]
>To obtain a digital certificate 
>- You must **first prove your identity to the CA in** some manner, This is called **enrollment**
>	- This means physically appearing before an agent of the certification authority with the **appropriate identification documents**
>
>Once you've satisfied the certificate authority regarding your identity,
>- You provide them with your public key in the form of a **Certificate Signing Request (CSR).**
>	- The CA **creates an X.509 digital certificate** containing your identifying information and a copy of your public key.
>	- The CA then digitally signs the certificate using the **CA's private key** 
>
>Certificate authorities **issue different types of certificates** **depending on the level of identity verification** that they perform.
>- This could be certs such as 
>	- **Domain Validation (DV) certificates** : domain names
>	- **Extended Validation (EV) certificates** : verify if business is legitimate 

###### Verification 

>[!info]
>- You verify the certificate by checking the **CA's digital signature using the CA's public key**
>- Next, you must **check and ensure that the certificate was not revoked** using a 
>	- **Common Revocation List**
>	- **Online Certificate Status Protocol**

>[!caution]
>A certificate is legitimate if
>- The digital signature of the CA is authentic.
>- You trust the CA.
>- The certificate is not listed on a CRL.
>- The certificate actually contains the data you are trusting.

###### Revocation

>[!info]
>A certificate authority needs to revoke a certificate if 
>- The certificate was compromised
>- The certificate was erroneously issued
>- The details of the certificate changed
>- The security association changed 


### Verifying the authenticity of the certificates 
---
You can use three techniques to verify the authenticity of certificates
- [CRL](CRL.md)
- [OCSP](OCSP.md)