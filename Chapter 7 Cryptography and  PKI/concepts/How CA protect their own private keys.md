### How CA protect their own private keys ?
---
To do this, they often use an offline CA to **protect their root certificate**.

>[!info]
>The root certificate is the top-level certificate for their **entire PKI that serves as the root of trust for all certificates issued by the CA.**

The Offline root certificate is powered down until its needed and is disconnected from all networks 