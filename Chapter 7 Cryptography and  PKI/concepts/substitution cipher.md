### substitution cipher
---
>[!note]
>A substitution cipher is a type of coding or ciphering system that **changes one character or symbol into another**.

### Examples
---
>[!example]
>- Caesar Cipher
>- ROT 13

**This type of cipher is more vulnerable to bruteforce and  has an easy complexity**

#### Polyalphabetic substitution 
---
Most simple example of a polyalphabetic substitution cipher is the **Vigenère cipher**

>[!example] working
>1. It used a **keyword to look up the cipher text** in a table
>2. The user would take the first letter in the text that they wanted to encrypt, **go to the Vigenère table**, and match that with the letter from the **keyword in order to find the ciphertext letter**
>3. This would be repeated until all the letters are finished 
>
>![Pasted image 20251003080211.png](../../images/Pasted%20image%2020251003080211.png)
>
>For the following pair 
>- plain text : SECRET MESSAGE
>- keyword : APPLE
>- Polyalphabetic substitution 
>![Pasted image 20251003080410.png](../../images/Pasted%20image%2020251003080410.png)
>- Corresponding cipher text  : S T R C I T B T D W A V T

