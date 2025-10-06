### Stored / Persistent XSS
---
>[!note]
>Another common technique is to **store cross-site scripting code on a remote web server** in an approach known as **stored XSS.**

These attacks are **described as persistent because they remain on the server even when the attacker isn't actively waging an attack.**

### Example
---
>[!example]
>- Consider a message board that allows users to **post messages that contain HTML code**. This is very common because users may want to use HTML to add emphasis to their posts.
>- HTML tags would alter the appearance of the message
>
>![Pasted image 20251002085504.png](Pasted%20image%2020251002085504.png)
>
>This would be the modified attackers code
>
>![Pasted image 20251002085541.png](Pasted%20image%2020251002085541.png)

