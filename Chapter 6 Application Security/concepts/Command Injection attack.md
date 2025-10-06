### Command Injection attack
---
>[!note]
>In some of the cases the the application directly talks with the underlying OS in such cases the attacker might exploit a flaw in the application to manipulate the OS 

### Example 
---
>[!example]
>Suppose if a user is asked to input the username 
>![Pasted image 20251002064511.png](Pasted%20image%2020251002064511.png)
>Now in such a scenario where the username is inputed as synder it would create a function call like 
>
>*system('mkdir /home/students/synder)*
>
>Now imagine if this was inputed 
>
>*mchapple & rm -rf /home*

