###
---
>[!note]
>Asymmetric key algorithms, also known as **public key algorithms**, provide a solution to the weaknesses of symmetric key encryption
>
>- Use 2 set of keys that is 
>	- private key : known to the user , kept secret 
>	- public key : known to the public 
>
>- Opposite keys must be used to **encrypt and decrypt** 

### Example 
---
>[!Example]
>1. . If Alice wants to send a message to Bob .
>2. She creates the message and then **encrypts it using Bob's public key.**
>3. The only way to **decrypt** this is by using bob's private key 

![Pasted image 20251004080921.png](../../images/Pasted%20image%2020251004080921.png)

Asymmetric key algorithms also provide support for **digital signature technology**

That is if bob wants to assure other users that the message is sent by him

>[!example] process
>1. he first creates a message digest by using **hashing algo**
>2. Bob **then encrypts that message digest using his private key**
>3. Any user who wants to verify the signature simply decrypts the message diggest using **Bob's Public Key**


### Pros of Asymmetric Key Cryprtograhy 
---
- The addition of **new users requires the generation of only one public-private key pair.**
- user's can be **removed** quite easily 
- Key **generation** is only required when **private key is compromised**
- Provides **, integrity, authentication and non repudiation**
- Key exchange is a simple **process**
- **No prexisting communication need's to exist**

### Cons 
---
- It slow for larger messages 

