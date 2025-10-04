### Storage and Destruction of Symmetric Keys
---
All the keys in a cryptographic system must be kept secure that is 
- **Never store an encryption key on the same system where encrypted data resides.**
- For sensitive keys, consider providing two different individuals with half of the key. They **then must collaborate to re-create the entire key.** This is known as the principle of split knowledge 


### Key Escrow and Recovery 
---
>If someone uses strong cryptography to **protect data and then loses the decryption key, they won't be able to access their data again**. This is where  **escrow services play a crucial factor** 


Organisations may use the protected copy of the key only for emergencies and **must follow the key recovery policies for which the key can be recovered from the escrow** .


