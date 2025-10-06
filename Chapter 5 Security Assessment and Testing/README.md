## Chapter 5 : Security Assessment and Testing
---

### Exam objectives 
---
![Pasted image 20250822203009.png](../images/Pasted%20image%2020250822203009.png)
![Pasted image 20250822203049.png](../images/Pasted%20image%2020250822203049.png)

### Indexes
---
- [5.1 Vulnerability Management](sub%20indexes/5.1%20Vulnerability%20Management.md)
- [5.2 Vulnerability scanning tools](sub%20indexes/5.2%20Vulnerability%20scanning%20tools.md)
- [5.3 Reviewing and Interpreting Scan Reports](sub%20indexes/5.3%20Reviewing%20and%20Interpreting%20Scan%20Reports.md)
- [5.4 Vulnerability Classification](sub%20indexes/5.4%20Vulnerability%20Classification.md)
- [5.5 Pentesting](sub%20indexes/5.5%20Pentesting.md)
- [5.6 Audits and Assessments](sub%20indexes/5.6%20Audits%20and%20Assessments.md)
- [5.7 Vulnerability Life Cycle](sub%20indexes/5.7%20Vulnerability%20Life%20Cycle.md)


### Summary 
---
- Purpose: Maintain effective controls and adapt to environmental changes.

**Vulnerability Scanning**

- Identifies potential issues before attackers exploit them.
- Common findings:
    - Missing patches.
    - Weak system configurations.
    - Default accounts.
    - Insecure protocols or ciphers.

**Penetration Testing**
- Simulates attacker behavior.
- Actively exploits weaknesses to reveal risks.
- Results guide improvements to security controls.

**TL;DR**  
Vulnerability scans find weaknesses (patches, configs, accounts, ciphers). Penetration tests exploit issues to show real risk and improve defenses.

### Exam Essentials
---
Many vulnerabilities exist in modern computing environments. Cybersecurity professionals should remain aware of the risks posed by vulnerabilities both on-premises and in the cloud.

- Improper or weak patch management can be the source of many vulnerabilities, providing attackers with a path to exploit operating systems, applications, and firmware.
- Weak configuration settings that create vulnerabilities include open permissions, unsecured root accounts, errors, weak encryption settings, insecure protocol use, default settings, and open ports and services.
- When a scan detects a vulnerability that does not exist, the report is known as a false positive. When a scan does not detect a vulnerability that actually exists, the report is known as a false negative.

#### Threat Hunting
Threat hunting discovers existing compromises. Activities presume that an organization is already compromised and search for indicators of those compromises. 
- Efforts include the use of advisories, bulletins, and threat intelligence feeds in an intelligence fusion program.
- They search for signs that attackers gained initial access to a network and then conducted maneuver activities on that network.

#### Vulnerability Scans
Vulnerability scans probe systems, applications, and devices for known security issues. 
- They leverage application, network, and web application testing to check for known issues. 
- Scans may be conducted in a credentialed or noncredentialed fashion and may be intrusive or nonintrusive.
- Analysts reviewing scans should also review logs and configurations for additional context.
- Vulnerabilities are described consistently using the Common Vulnerabilities and Exposures (CVE) standard and are rated using the Common Vulnerability Scoring System (CVSS). Both are components of the Security Content Automation Protocol (SCAP).

#### Penetration Testing
Penetration testing places security professionals in the role of attackers. 
- Tests may be conducted with full information (known environment), no information (unknown environment), or partial knowledge (partially known environment).
- Testers follow rules of engagement and begin with reconnaissance efforts such as war driving, war flying, footprinting, and open source intelligence (OSINT).
- They then gain initial access, escalate privileges, and move laterally or pivot to expand access.
- Persistence is achieved to allow continued access even after patches.
- Cleanup activities restore systems to normal and remove traces of activity.

#### Bug Bounty Programs
Bug bounty programs incentivize vulnerability reporting. 
- External testers probe the security of public-facing systems.
- Discoveries are rewarded financially, encouraging hackers to help improve security rather than exploit vulnerabilities.

#### Security Audits
Audits are formal examinations of an organization's security controls. 
- They may be conducted by internal teams or third-party auditors.
- At the conclusion, auditors make an attestation about the adequacy and effectiveness of security controls.

#### Vulnerability Life Cycle
The stages of the vulnerability life cycle include:

1. Vulnerability Identification – from scans, penetration tests, bug bounty programs, responsible disclosure, or audits.  
2. Analysis – confirming and prioritizing vulnerabilities using CVSS/CVE and organization-specific context.  
3. Response and Remediation – applying patches, isolating systems, compensating controls, transferring risk, or accepting risk.  
4. Validation – ensuring the vulnerability is removed.  
5. Reporting – informing stakeholders of findings, actions, trends, and recommendations for improvement.  