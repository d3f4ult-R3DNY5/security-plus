## insecure direct object reference
---
web developers design an application to directly retrieve **information from a database** based on an argument provided by the user in either a query string or **a POST request**

This looks something like this 
![Pasted image 20251002073840.png](../../images/Pasted%20image%2020251002073840.png)

Thereis nothing wrong with this unless the user has access to the document that he only has access to which can be implemented through **ACL**

The problem occurs when these params are changed an **the user can access the documents that he doesnt have access to** 