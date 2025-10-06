## Session attacks
---
The way that this attack is performed is by stealing the user's currently authenticated session .

### How does this work 
---
>[!example]
>- A user authenticates with the website via **http headers** . In this approach
>- The user accesses the **website's login form** and uses the credential to authenticate 
>- the website provides the user's browser with a **cookie** that may be used to authenticate future requests
>- Whenever a user makes further request they may use this cookie

![Pasted image 20251002070708.png](Pasted%20image%2020251002070708.png)


###  What is a cookie ?
---
The cookie is simply a **storage object** maintained in the user's browser that **holds variables that may later be accessed** by the website that created them.

A cookie can be stolen via [cookie stealing and manipulation](cookie%20stealing%20and%20manipulation.md)


### Methods of stealing sessions 
---
- [cookie stealing and manipulation](cookie%20stealing%20and%20manipulation.md)
- [unvalidated redirects](unvalidated%20redirects.md)