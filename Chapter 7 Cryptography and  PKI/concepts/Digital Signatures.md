### Digital Signatures
---
The hashing algorithm can be used to generate the digital signatures. The digital signatures can be used to 
- **Enforce non repudiation** - This is done by signing the message 
- **Ensure Integrity** - This is used to make Sure that the messages are not altered in transit 

They rely on 2 major components that is 
- **Public Key Cryprography**
- **Hashing**

### Working 
---
>[!example] Process 
>If Alice wants to digitally sign a message she's sending to Bob
>
>1. Alice generates a **message digest of the original plain-text message using one of the cryptographically sound hashing algorithms**, such as SHA3-512
>2. Alice then encrypts only the **message digest using her private key.**
>3. Alice appends the **signed message digest to the plain-text message.**
>4. Trasmit to Bob
>
>When Bob receives the digitally signed message, he reverses the procedure,
>
>1. Bob decrypts the **digital signature using Alice's public key.**
>2. Bob uses the **same hashing function to create a message digest of the full plain-text message received from Alice.**
>3. Compare with the digest that alice has sent **If its same then we can say that the message is real** 

This only ensures that the goals of **integrity, authentication, and non-repudiation are met.**

>[!caution] To ensure Confidentiality
>- The message could be taken one step further by e**ncrypting it with bobs Public key**


[HMAC](HMAC.md) is an algorithm that guarantees the integrity of a message during transmission 

