## Chapter 6 : Application Security
### Exam Objectives
---
![Pasted image 20251001135543.png](../images/Pasted%20image%2020251001135543.png)
![Pasted image 20251001135605.png](../images/Pasted%20image%2020251001135605.png)

### Index 
---
- [6.1 Software assurance best practices](index/6.1%20Software%20assurance%20best%20practices.md)
- [6.2 Software Security Testing](index/6.2%20Software%20Security%20Testing.md)
- [6.3 Injection Vulnerabilities](index/6.3%20Injection%20Vulnerabilities.md)
- [6.4 Exploiting Authentication Vulnerabilities](index/6.4%20Exploiting%20Authentication%20Vulnerabilities.md)
- [6.5 Exploiting the authorization vulnerabilities](index/6.5%20Exploiting%20the%20authorization%20vulnerabilities.md)
- [6.6 Exploiting Web App Vulnerabilities](index/6.6%20Exploiting%20Web%20App%20Vulnerabilities.md)
- [6.7 Application Security Controls](index/6.7%20Application%20Security%20Controls.md)
- [6.8 Secure Coding Practices](index/6.8%20Secure%20Coding%20Practices.md)
- [6.9 Automation and Orchestration](index/6.9%20Automation%20and%20Orchestration.md)

### Summary 
---
- Software is critical for business operations and infrastructure.
- Security professionals must **test software thoroughly** to ensure it meets business needs **without introducing risks**.
- Common risks arise from:
  - **Source code vulnerabilities** (bugs, insecure coding).
  - **Deployment vulnerabilities** (client-server misconfigurations, insecure web apps).
- Managing these risks requires:
  - Secure coding practices.
  - Testing methods (static/dynamic analysis, fuzzing, etc.).
  - Ongoing monitoring after deployment.

#### TL;DR
Software must be **securely developed, tested, and deployed**.


### Exam Essentials
---
##### Key Points

###### Secure Software Development
- Use a standardized SDLC (development → test → staging → production).  
- Avoid issues with **code reuse** and maintain **software diversity**.  
- Follow **OWASP principles** for web applications.  

###### Application Attack Indicators
- Common vulnerabilities: **memory injection, buffer overflow, race conditions**.  
- Web-specific attacks: **SQL injection (SQLi), cross-site scripting (XSS)**.  
- Recognizing attack methods = stronger defenses.  

###### Application Security Controls
- **Input validation** to prevent malicious input.  
- Secure session cookies with **transport encryption**.  
- Perform **code reviews + static/dynamic testing**.  
- **Code signing** ensures trust.  
- **Sandboxing** isolates code for testing.  

###### Automation & Scripting: Benefits and Drawbacks
- **Benefits**: saves time, enforces baselines, scales securely, reduces reaction times.  
- **Drawbacks**: complexity, cost, single points of failure, technical debt.  

###### Automation & Scripting: Use Cases
- **Provisioning users/resources**.  
- Managing **security groups and guard rails**.  
- Automating **tickets, services, and access**.  
- **Continuous integration and testing**.  
- Leveraging **APIs for automation**.  

#### TL;DR
Secure development = SDLC + OWASP + testing.  
Attacks include **buffer overflows, SQLi, XSS**.  
Controls = input validation, encryption, reviews, signing, sandboxing.  
Automation improves efficiency but adds complexity.