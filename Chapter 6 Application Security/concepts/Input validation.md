## Input validation
---
Applications that allow user input should perform validation of that input to reduce the likelihood that it contains an attack.

>[!caution]
>This is important because the input can expose apps to 
>- injection attacks 
>- cross site scripting attacks 
>- exploits 

### Best Stratergy 
---
>[!tip] Mitigation 
>- Allow listing :
>	- what is **type of the input that is expected by the users** 
>	- If the input is a text it should be a text 
>	- The application would then **reject any values outside the expected input** 
>- Deny listing 
>	- since it is impossible to write rules for all possible input we **can implement a deny list to specify what the users cant do** 
>	- blocking tags, queries and redirects 
>	- blocking certain metacharacters 


####  Parameter pollution 
---
>[!note]
>One way that the attackers bypass the input validation checks is by using parameter pollution . A web application might have a account label like the one below which is passed in the URL
>
>![Pasted image 20251002110553.png](../../images/Pasted%20image%2020251002110553.png)
>
>This might be modifiied to pass the URL like this 
>
>![Pasted image 20251002110642.png](../../images/Pasted%20image%2020251002110642.png)
>
>This might perform **input validation on the first argument properly but fail in providing validation  the second argument .**


