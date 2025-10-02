### Reflected XSS
---
>[!note]
>XSS attacks commonly occur **when an application allows reflected input.**

### Example 
---
>[!example]
>- Consider a **simple web application that contains a single text box asking a user to enter their name**. 
>- When the user clicks Submit, **the web application loads a new page that says, “Hello, name.”**
>
>Attacker Manipulation 
>- Attacker knows that an **html script contains tags**
>- Suppose of entering the mike in the name field, it will enter the following 
> 		`Mike<SCRIPT>alert('hello')</SCRIPT>`
>- When this input is executed the script simply opens up a popup window saying that the word has **hello** in it 


### Mitigation strategies
---
>[!tip] Mitigation
>- Input Validation : The user should ever be allowed to use tags in the input 
