## blind timing based SQLi
---
>[!info]
> penetration testers may use the **amount of time required to process a query** as a channel for retrieving information from a database.

### Example
---
>[!example]
>In some of the systems the attack mechanisms depends on the SQL server mechanisms for example the **Microsoft SQL Server's Transact SQL** allows for the following command
> 
>*WAITFOR DELAY '00:00:15'*
>
>In such a scenario if the **command is successful it would return the results in 15 seconds** 
>
>So for some complex query to extract the passwords from the database we would use the following command
> 
>![Pasted image 20251002063417.png](../../images/Pasted%20image%2020251002063417.png)


