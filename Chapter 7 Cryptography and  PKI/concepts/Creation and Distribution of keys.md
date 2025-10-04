### Creation and Distribution of keys
---

###### **Offline Distribution**
>[!note]
>- This involves the **physical exchange of key material.**
>- Can be done via 
>	- paper
>	- storage media
>- Most systems use electronic devices 
>- This system has a critical flaw cause if the thing is sent through mail **this might be easily intercepted**


###### Public key distribution 
>[!note]
>- Many communicators want to obtain the **speed benefits of secret key encryption without the hassles of key distribution**.
>- many people use **public key encryption to set up an initial communications link**
>- They exchange keys over this communication link

###### Diffie hellman 
>[!note]
>- This is used to establish a communication link when there is no **PKI** 

>[!example] Working 
>1. The communicating parties (we'll call them Richard and Sue) **agree on two large numbers:** **p (which is a prime number) and g (which is an integer) such that 1 < g < p.**
>2. Richard chooses a **random large integer r** and performs the following calculation:
>
>R = g^r mod p
>
>3. Sue chooses a random large integer s and performs the following calculation:
>
>R = g^r mod p
>
>4. **Richard sends R to Sue and Sue sends S to Richard.**
>5. Richard then performs the following calculation : K = S^r mod p
>6. Sue then performs the following calculation: K = R^s mod p



