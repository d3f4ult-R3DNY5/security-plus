### Certificate stapling
---
>[!note]
>- Extension to OCSP
>
>Normal Approach
>- When a user visits **a website and initiates a secure connection, the website sends its certificate to the end user**
>- Then the person **contacts the OCSP server to validate the cert** 
>
>Cert stapling 
>- In certificate staplin**g, the web server contacts the OCSP server itself and receives a signed and timestamped response from the OCSP server,** which it then attaches, or staples, to the digital certificate.
>- When a user initiates a secure connection **user's browser then** **verifies that the certificate is authentic**
>- Here time is saved usually the **timestamped validity is 24 hours** 