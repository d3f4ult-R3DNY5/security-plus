## OCSP
---
>[!note]
>- Online Certificate Status Protocol
>- This eliminates latency by providing a means for real time verification from CA browser by sending requests to the CA OCSP server 
>- Server responds with good, revoked and unknown 

Primary issue with OCSP is that it places a significant **burden on the OCSP servers operated by certificate authorities.** These severs must processs the requests from every single visitor So we use [Certificate stapling](Certificate%20stapling.md)