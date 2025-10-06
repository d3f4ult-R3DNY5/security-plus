## cookie stealing and manipulation
---
If an attacker is able to **steal someone's cookie**, they may then **impersonate that user to the website** that issued the cookie.

### Ways in which an attacker might obtain a cookie 
---
- Eavesdropping on unencrypted network 
- installing malware on target's system 
- Engaging in an on path attack 

>[!info]
>An on path attack is an attack in which the attacker tricks the user into thinking that the **attacker is actually the target website** and **presenting a fake authentication form**. They may then **authenticate to the website on the user's behalf and obtain the cookie.**

Once the attacker obtains a cookie he does something which is known as a **session replay attack**. 
![Pasted image 20251002071407.png](Pasted%20image%2020251002071407.png)

Another form of replay attack that is used on the **Windows system is pass the hash attack** targets windows OS and aims to exploit the AD 
### Mitigation 
---
>[!tip] mitigation
>The web developers resolve this issue by marking cookies with a **secure** attribute . Both servers and browsers understand that the cookie must be sent over the encrypted channels 

