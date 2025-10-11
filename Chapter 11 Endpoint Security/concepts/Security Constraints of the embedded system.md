### Security Constraints of the embedded system
---
**Computational costs** 
- They typically use low-power processors.
- They have **less memory and limited storage space.**
- Cryptographic operations **may exceed available compute capacity.**
- CPU cycles must often be balanced **between security tasks and core functions.**
- **Limited memory and storage restrict** running extra security tools (e.g., firewall, antimalware).
- **Standard security solutions** may not fit within embedded system constraints.

**Network Connectivity Limitations in Embedded Systems**
- Some embedded systems lack network connectivity entirely.
- Others have n**etwork capability but disable it for environmental, operational, or security reasons**.
- Many are deployed in i**solated or low-connectivity areas.**
- Wireless features may exist but have **insufficient range for viable network access.**
- Limited or no connectivity **prevents remote patching, monitoring, or maintenance.**
- Such systems must often be secured and maintained as standalone units.

**Authentication Challenges in Embedded Systems**
- Limited CPU, memory, and connectivity make authentication difficult or impossible.
- Authentication may be avoided for safety or usability reasons.
- Embedded systems are often integrated into machinery, sensors, or household devices.
- Lack of authentication requires alternative security models to control authorized changes.

**Cost and Replacement Constraints in Embedded Systems**
- Some embedded systems are low cost, but many are part of expensive industrial or specialized equipment.
- Replacing a vulnerable embedded device is often impractical or impossible.
- Security must be maintained through compensating controls or specific design measures.
- Design choices must minimize risk to the larger system or organization.