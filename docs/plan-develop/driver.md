---
layout: default
title:  Driver
parent: Plan & Develop
---

# Driver
{: .no_toc }



DevSecOps is a methodology that seeks to integrate security into the software development lifecycle, rather than treating it as a separate process that is bolted on at the end. The goal is to build secure, reliable software that meets the needs of the business, while also protecting sensitive data and critical infrastructure. There are several drivers and challenges associated with implementing DevSecOps, which are outlined below.

**Drivers:**

1. Security concerns: With the increasing frequency and severity of cyberattacks, security has become a top priority for organizations. DevSecOps provides a way to build security into the software development process, rather than relying on ad hoc security measures.

2. Compliance requirements: Many organizations are subject to regulatory requirements such as PCI-DSS, HIPAA, and GDPR. DevSecOps can help ensure compliance with these regulations by integrating security into the development process and providing visibility into the security posture of the application.

3. Agility and speed: DevSecOps can help organizations develop and deploy software more quickly and with greater agility. By integrating security into the development process, organizations can reduce the time and cost of remediation and avoid delays caused by security issues.

4. Collaboration: DevSecOps encourages collaboration between developers, security teams, and operations teams. By working together, these teams can build more secure and reliable software.

**Challenges:**

1. Cultural barriers: DevSecOps requires a cultural shift in the organization, with developers, security teams, and operations teams working together in a collaborative manner. This can be challenging, particularly in organizations with a siloed culture.

2. Lack of skills: DevSecOps requires a range of skills, including development, security, and operations. Finding individuals with these skills can be difficult, particularly in a competitive job market.

3. Tooling and automation: DevSecOps relies heavily on tooling and automation to integrate security into the development process. Implementing and maintaining these tools can be challenging, particularly for smaller organizations with limited resources.

4. Complexity: DevSecOps can be complex, particularly for organizations with large, complex applications. It can be difficult to integrate security into the development process without causing delays or creating additional complexity.


## Application Security Verification Standard(ASVS):

Authentication, Session Management, Access Control, Malicious Input handling, Output encoding/escaping, Cryptography, Error handling and logging , Data Protection, Communication Security, Http Security configuration, Security configuration, Malicious, Internal Security, Business logic, Files and resources, Mobile, Web services

### Design review 

* Security compliance checklist 
* Security requirement checklist (OWASP ASVS) 
* Top 10 security design issues 
* Security issues in the previous release 
* Customer or marketing feedback on security issues 


### Implementation review 

* Secure coding 
* Selection of reliable and secure third-party components 
* Secure configuration 


### Third-party components 

* A third-party software evaluation checklist: 
* Recommended third-party software and usage by projects: 
* CVE status of third-party components: 

### Code Review

* Static Application Security Testing (SAST)->FindSecbugs, Fortify, Coverity, klocwork.
* Dynamic Application Security Testing (DAST)->OWASP ZAP, BurpSuite
* Interactive Application Security Testing (IAST)->CheckMarks Varacode
* Run-time Application Security Protection(RASP)->OpenRASP
* https://www.owasp.org/index.php/Category:OWASP _Code_Review_Project SEI CERT Coding https://wiki.sei.cmu.edu/confluence/display/seccode/SEI+CERT+Coding+Standards
* Software Assurance Marketplace (SWAMP): https://www.mir-swamp.org/

### Environment Hardening 

* Secure configuration baseline 
* Constant monitoring mechanism 

### Constant monitoring mechanism

1. Common vulnerabilities and exposures (CVEs) 
OpenVAS, NMAP 

2. Integrity monitoring
OSSEC

3. Secure configuration compliance
OpenSCAP

4. Sensitive information exposure 
No specific open source tool in this area. However, we may define specific regular expression patterns

