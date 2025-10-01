### Blind Content Based SQLi
---
>[!info]
>In a content-based blind SQL injection attack, the perpetrator sends **input to the web application that tests** whether the application is interpreting injected code before attempting to carry out an attack 


### Example 
---
>[!example]
> Consider a web application that asks a user to enter an account number. 
> ![Pasted image 20251001202110.png](../../images/Pasted%20image%2020251001202110.png)
> 
> When a user sends an acc no to the page , it will obviously show the listing of the account with the account info 
> 
>  ![Pasted image 20251001202220.png](../../images/Pasted%20image%2020251001202220.png)
>  
>  From this we can make out that that there is query regarding the acc no send to the database which looks like
>   
>  ![Pasted image 20251001202434.png](../../images/Pasted%20image%2020251001202434.png)
>  
>  Imaging placing the following I/P into the account number field 
>  ![Pasted image 20251001202605.png](../../images/Pasted%20image%2020251001202605.png)
>  
> If successful this will be the query being sent to the databse 
> ![Pasted image 20251001202706.png](../../images/Pasted%20image%2020251001202706.png)
> 
> Now imagine the following query 
> ![Pasted image 20251001202815.png](../../images/Pasted%20image%2020251001202815.png)
> 
> This would result in an abnormal behaviour of the webpage like this ![Pasted image 20251001202855.png](../../images/Pasted%20image%2020251001202855.png)
> 

