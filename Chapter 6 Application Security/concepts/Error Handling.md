## Error Handling 
---
>[!note]
>**Attackers thrive on exploiting errors in code**. Developers must understand this and write their **code so that it is resilient to unexpected situations**

### Example 
---
>[!example]
>- if a web form requests an age as input , **it's insufficient to simply verify that the age is an integer.**
>- enter a 50,000-digit integer in that field in an attempt to perform an **integer overflow attack** or a negative number

>[!warning]
>An **overly verbose error may also be a problem** because they might reveal the inner workings of the code