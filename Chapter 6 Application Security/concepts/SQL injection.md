## SQL injection
---
>[!note]
>Web applications often receive input from users and use it to compose a database query that provides results that are sent back to a user.

### Example 
---
>[!example]
>If a user enters orange tiger pillow into the search box, the web server needs to know what products in the catalog might match this search term 
>
>![Pasted image 20251001200853.png](Pasted%20image%2020251001200853.png)
>
>This command retrieves a list of items that can be included in the results returned to the end user. Now an **SQLi**  attack would look like 
>
>![Pasted image 20251001201024.png](Pasted%20image%2020251001201024.png)
>
>Corresponding data query would look like 
>![Pasted image 20251001201128.png](Pasted%20image%2020251001201128.png)
>
>The attacker is able to provide the input to the application and is able to then monitor the O/P of the application which might reveal sensitive data 
>
>Some times the **result of the attack is not visible but the attack has happened** this is known as a **blind SQLi**


### Two types Blind SQLi
---
1. [blind content based SQLi](blind%20content%20based%20SQLi.md)
2. [blind timing based SQLi](blind%20timing%20based%20SQLi.md)

