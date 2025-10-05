### Authentication methods
---
>[!note]
>Once you've claimed an identity by providing a username, a certificate, or some other means, your next step is to **prove that the identity belongs to you.**

### Passwords 
---
>[!note]
>- common form of authentication 
>- Many orgs use NIST SP 800-63B as part of their Digital Identity Guidelines to have best password practices 
>	**- Reducing password complexity requirements and instead emphasizing length**
>	**- Not requiring special characters**
>	**- Allowing ASCII and Unicode**
>	**- Allowing pasting into password fields to allow password managers to work properly**
>	**- Monitoring passwords and checks if the password is not already compromised** 
>	**- Eliminate password hints** 
>
>- Common password configs used in modern systems 
>	- length 
>	- complexity with inclusion of charters symbols 
>	- reuse limitations 
>	- expiration dates 
>	- age
>
>- One of the best ways of storing passwords is through [Password Managers](Password%20Managers.md)


### Passwordless authentication 
---
>[!note]
>- Passwordless authentication is becoming increasingly common by relying on **something you have** like 
>	- security tokens
>	- one- time password applications
>	- certificates
>	- biometrics
>- For individuals, one option that provides a high level of security is **a [security key](security%20key.md)**

### Multi factor Authentication 
---
>[!note]
>- One way to ensure that a single compromised factor like a password does not create undue risk is to **use multifactor authentication** (MFA).
>- It could be 
>	- something you know 
>	- something you have 
>	- something you are 
>	- somewhere you are 
>- Only threat to this is **social engineering , cloning of cellphones, redirecting SMS messages over VOIP systems**


### OTP
---
>[!note]
>- one-time passwords (OTP) is a **mechanism of something you have** 
>- Can only use once and not again so its **not vulnerable** to bruteforce 
>- Two primary mechanism 
>	- [TOTP](TOTP.md)
>	- [HOTP](HOTP.md)
>- **SMS** can also be used as an OTP system 
>- **Phone call** be OTp is also used to verify the user of the system 
>- **They are vulnerable to social engineering attacks**

### Biometric
---
>[!note]
>- uses the **something you are factor** 
>- This could be done via 
>	- fingerprints 
>	- retina scanning 
>	- iris scanning 
>	- facial recognition 
>	- voice recognition 
>	- vein recognition 
>	- gait recognition : how a person walks 
>- Biometric systems are classified into 4 measures 
>	- **Type 1 errors : false rejection rate - legitimate biometric rejected**
>	- **Type 2 errors : false acceptance rate - illegitimate biometric accepted**
>- This is then used for **ROC** curve to compare FRR against FAR