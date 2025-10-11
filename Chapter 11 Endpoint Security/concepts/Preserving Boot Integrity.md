### Preserving Boot Integrity
---
>[!note]
>Keeping an **endpoint secure while it is running starts as it boots up**. If **untrusted or malicious components are inserted into the boot process, the system cannot be trusted.**

### Techniques that is used in modern UEFI 
---
> [!tip] Secure Boot 
> - **Secure Boot** uses software that belongs to the OEM 
>	- This uses the signatures of software and verifies it with the DB 
>![Pasted image 20251010091736.png](../../images/Pasted%20image%2020251010091736.png)
>- Prevents the **running of malicious code** 

>[!tip] Measured boot
>- **Measured Boot** measures the process of each component starting with the firmware and ending with the boot drives 
>	- It relies on UEFi to hash the firmware, bootloaders and other peripherals involved in the boot process and the data is them stored in a **Trusted Platform Module**
>	- It can also be used to monitor the **logs remotely** which can be used by admins later to verify the boot state of the system 
>	- This **boot attestation process allows comparison against known good states, and administrators can take action if the measured boot shows a difference from the accepted state.**

In both the cases the trust of the system begins with the **hardware root of trust**. 

### What is the hardware root of trust ?
---
It contains the cryptographic keys that is used to secure the boot process 


### Implementation of hardware root of trust 
---
Use of **TPM** chips for 
- Remote attestation, allowing hardware and software configurations to be verified
- Binding which encrypts data 
- Sealing hich encrypts data and sets requirements for the state of the TPM chip before decryption

They are one of the common  solution because the serial numbers cant be cloned because they have **unclonnable functions** impemented in them which is unique to a specific hardware.

Mostly TPM are used in **windows systems**


### For Apple systems 
---
- **Secure Enclave** is a **dedicated hardware module** built into Apple’s SoC (System on Chip).
- It handles **encryption key management** separately from the main CPU.
- Provides **isolation** so keys stay protected during storage and use.
- Enhances **device security** by limiting exposure of sensitive cryptographic operations.


### Protecting keys 
---
- [HSM](HSM.md)
