
---
## **whoami**

#### **Kaniel Pinto**
B.Sc.(IT) - Batch of 2024.
Part of the VAPT Team at 63SATS.

---
## **Main Areas / Job Profiles**

----
### Vulnerability Analysis and Penetration Testing (VAPT)

A vulnerability assessment focuses on scanning hosts for vulnerabilities as individual entities so that security deficiencies can be **identified** and effective security measures can be deployed to **protect** the network in a prioritized manner. Most of the work can be done with automated tools and performed by operators without requiring much technical knowledge.

Penetration tests might start by scanning for vulnerabilities just as a regular vulnerability assessment but provide further information on how an attacker can chain vulnerabilities to achieve specific goals. While its focus remains on **identifying** vulnerabilities and establishing measures to **protect** the network, it also considers the network as a whole ecosystem and how an attacker could profit from interactions between its components.
#### **Key Responsibilities**:
- Perform vulnerability assessments and identify potential weaknesses.
- Conduct ethical hacking and penetration tests to simulate real-world cyberattacks.
- Report vulnerabilities with actionable steps to mitigate risks.
- Collaborate with development teams to ensure secure coding practices.

---
### Red Teaming

To keep up with the emerging threats, red team engagements were designed to shift the focus from regular penetration tests into a process that allows us to clearly see our defensive team's capabilities at **detecting** and **responding** to a real threat actor. They don't replace traditional penetration tests, but complement them by focusing on detection and response rather than prevention.

Red teams are tasked with mimicking the behaviour of cybercriminals or nation-state actors to evaluate how well an organization's security defences can withstand a full-blown cyberattack. Unlike penetration testing, which focuses on finding vulnerabilities, red teaming assesses an organization’s response to an actual attack scenario, including human error, physical security weaknesses, and more.

#### **Key Responsibilities**:
- Simulate advanced, multi-stage cyberattacks to test the resilience of security systems and protocols.
- Use techniques like social engineering, phishing, and network manipulation to gain unauthorized access.
- Work closely with blue teams (defenders) to improve response protocols.
- Provide insights into how adversaries could breach systems and exploit vulnerabilities.

---
### Blue Teaming

**Blue Teaming** focuses on defending an organization from cyberattacks and maintaining strong security measures. The blue team is responsible for identifying potential vulnerabilities, responding to security incidents, and continuously improving an organization's defence mechanisms. While red teams actively attempt to breach the system, blue teams work to detect, prevent, and mitigate these attacks.

Blue teams are typically tasked with real-time monitoring, incident response, and ensuring that security protocols are effectively implemented across an organization's infrastructure. They work to strengthen firewalls, intrusion detection systems, and other preventive measures to thwart attacks.

#### 1. *Security Analyst*

A **Security Analyst** monitors and analyses an organization's networks and systems to detect and respond to security threats and vulnerabilities.

#### 2. *Security Engineer*

A **Security Engineer** designs, implements, and manages secure systems, networks, and protocols to protect an organization’s IT infrastructure from cyber threats.

#### 3. *Incident Responder*

An **Incident Responder** handles and investigates security breaches or cyberattacks, working to contain, mitigate, and learn from the incident to prevent future attacks.

#### 4. *Digital Forensics Examiner*

A **Digital Forensics Examiner** recovers, analyzes, and preserves digital evidence from devices to investigate cybercrimes or security incidents.

#### 5. *Malware Analyst*

A **Malware Analyst** studies and dissects malicious software to understand its behavior, develop detection methods, and assist in mitigating future threats.

---
### Governance, Risk and Compliance (GRC)

**Governance, Risk, and Compliance (GRC)** is a critical aspect of cybersecurity that focuses on aligning security practices with regulatory requirements, managing risk, and ensuring an organization is in compliance with relevant laws and industry standards. GRC professionals help organizations define their security policies, assess risks, and ensure adherence to various laws and frameworks like GDPR, HIPAA, and ISO 27001.

The goal of GRC is to establish effective processes for managing risk, maintain proper governance over cybersecurity practices, and ensure that the organization’s activities comply with applicable laws, regulations, and standards.

#### **Key Responsibilities**:
- Develop and enforce security governance frameworks and policies.
- Assess and manage risks related to information security, privacy, and compliance.
- Monitor compliance with industry standards, regulations, and internal policies.
- Report on risk levels and propose mitigation strategies to senior management.

---
## **What is VAPT actually like ?**

---
### Initial Meeting and Walkthrough

Any VAPT project should ideally always begin with an initial meeting with both the relevant management team as well as the development team responsible for the project. This initial meeting usually includes a detailed discussion regarding the background of the application or servers as well as a complete walkthrough of the relevant systems and functions. It also includes a discussion about the scope of the assessment and any exceptions. 

---
### Vulnerability Analysis

This is the simplest form of security assessment, and its main objective is to identify as many vulnerabilities in as many systems in the network as possible. To this end, concessions may be made to meet this goal effectively. For example, the attacker's machine may be allow-listed on the available security solutions to avoid interfering with the vulnerability discovery process. This makes sense since the objective is to look at every host on the network and evaluate its security posture individually while providing the most information to the company about where to focus its remediation efforts.

---
### Penetration Testing

On top of scanning every single host for vulnerabilities, we often need to understand how they impact our network as a whole. Penetration tests add to vulnerability assessments by allowing the pentester to explore the impact of an attacker on the overall network by doing additional steps that include:

- Attempt to **exploit** the vulnerabilities found on each system. This is important as sometimes a vulnerability might exist in a system, but compensatory controls in place effectively prevent its exploitation. It also allows us to test if we can use the detected vulnerabilities to compromise a given host.
- Conduct **post-exploitation** tasks on any compromised host, allowing us to find if we can extract any helpful information from them or if we might use them to pivot to other hosts that were not previously accessible from where we stand.

---
### Reporting

**Documentation. Is. Important.**

A clean, well-formatted VAPT (Vulnerability Assessment and Penetration Testing) report is crucial because it provides clear, actionable insights for addressing security vulnerabilities. It helps stakeholders—technical teams, management, and decision-makers—understand the risks, their potential impact, and the steps needed for remediation. A well-organized report ensures that critical findings are not overlooked, facilitates efficient communication across teams, and aids in prioritizing tasks to strengthen the security posture of the system. Additionally, it serves as an important documentation for compliance and auditing purposes.

The actual testing is just half the job. In my opinion, its very much like the classic "**If a tree falls in a forest and no one is around to hear it, does it make a sound?**" philosophical saying. It doesn't matter how good you are at finding and exploiting vulnerabilities if you can't explain the process and consequence caused as well as provide advice regarding how to remediate poor security implementations in clear, simple (even non-technical) language.

[You can find an example of a realistic VAPT report here.](https://invia.com.au/App/media/sample%20vapt%20report.pdf)

---
### Correspondence

This goes hand-in-hand with reporting. While theory may not be incredibly glamourous or exciting it is incredibly important that you are able to comfortably and clearly explain the information within the report. 

---
## **What are we looking for and why?**

---
### Impact of Vulnerabilities and Bad Security

**Vulnerabilities and bad security practices** are like open doors or weak points in a system that cybercriminals can exploit. These vulnerabilities can lead to a range of consequences for businesses, organizations, and individuals, affecting everything from daily operations to long-term financial health.

In general, **poor security** can allow attackers to bypass defences and gain unauthorized access to sensitive information or systems. The **impact** of these vulnerabilities can manifest in several ways, ranging from loss of data to significant financial losses, damage to reputation, or even legal trouble.

For example, poor password management—such as using default or weak passwords—can lead to unauthorized access to corporate systems. Imagine a scenario where an employee uses a weak password for accessing a company's internal database. If an attacker can guess or crack that password, they could potentially steal sensitive data, such as customer information or trade secrets, leading to a loss of trust and possibly regulatory fines.

Overall, the importance of addressing vulnerabilities and maintaining strong security practices cannot be overstated. The consequences of poor security are often far-reaching, and the impact can be felt in various ways. For example, a company might face direct financial costs due to an attack, such as the cost of remediation or ransom payments. On top of that, there's the longer-term impact on the company's **reputation**. Customers and clients may lose confidence in the company’s ability to protect their data, leading to a decrease in business. Additionally, organizations may also face legal consequences if they fail to comply with regulations regarding data protection, such as GDPR or HIPAA.

---
### Different Platforms

#### 1. Web

For **web applications**, the focus is primarily on identifying common vulnerabilities such as injection attacks (like SQL Injection and Cross-Site Scripting), broken authentication mechanisms, improper session management, and issues with input validation. A critical aspect of web testing is also evaluating the security of APIs and ensuring that sensitive data is protected from unauthorized access, both in storage and during transmission. VAPT for web applications aims to ensure that users and systems can’t be manipulated into gaining unauthorized access.
#### 2. Servers

For **servers**, the VAPT process focuses on identifying misconfigurations, outdated software, and potential weaknesses in running services. This includes checking for unpatched vulnerabilities, improper file system permissions, and configuration errors that could expose sensitive data or lead to privilege escalation. The security of network services and the overall integrity of server configurations are key areas of concern to ensure the server is protected from unauthorized access and exploitation.
#### 3. Desktop Applications

In the case of **desktop applications**, the testing primarily revolves around examining the application’s local storage of sensitive data, ensuring that it is encrypted and not exposed to unauthorized access. Another critical focus is reverse-engineering the client-side application to identify any potential flaws in its design, such as hardcoded credentials or vulnerabilities that could be exploited to bypass security measures. Additionally, testing evaluates the security of communication between the client and the server, looking for unencrypted channels or weak session management.

#### 4. Mobile

For **mobile applications**, VAPT emphasizes the need to protect sensitive data stored on the device, ensuring that it is encrypted and not accessible in plaintext. Secure communication between the mobile app and the backend server is another important focus, with a particular emphasis on ensuring that data is transmitted securely via protocols like HTTPS. Mobile testing also includes verifying that authentication and session management practices are robust and do not expose users to risks. Finally, it is critical to check that mobile applications only request necessary permissions and do not misuse sensitive device features, like location services or cameras, in ways that could compromise user privacy.


---
### The OWASP Top 10 

The **OWASP Top 10** is a list of the most critical web application security risks, maintained by the **Open Web Application Security Project (OWASP)**. It provides organizations and developers with a prioritized list of security vulnerabilities to address when developing or testing web applications. The OWASP Top 10 helps raise awareness and serves as a baseline for improving security posture.

https://owasp.org/www-project-top-ten/

---
## **Roadmap and Resources**

---
### Pre-Requisites

1. IT Basics
2. Hands-on familiarity with actually using Linux and Windows
3. Networking Concepts
4. How the Internet works
5. Scripting, Web and App Development
6. Cryptography Basics
7. Cybersecurity Landscape (CVEs, Standards, Communities) 
8. Familiarity with Word and Excel and Note-Taking (Completely Optional but recommended personally.)

---

For a Roadmap, you can follow this but its quite overwhelming IMO:
https://roadmap.sh/cyber-security

### My Suggested Roadmap

1. Learn the pre-requisites from TryHackMe or YouTube - either works but do it hands-on.
2. Start learning about vulnerabilities from the OWASP Top 10 and PortSwigger Web Security Academy.
3. Practice on vulnerable machines like DVWA and practice making a report.
4. Learn about pentesting on other platforms.
5. Do some CTFs
6. Figure it out 👍

---
### Resource Links

Kali Linux:
[VirtualBox Download](https://www.virtualbox.org/wiki/Downloads)
[Kali Linux Download](https://www.kali.org/get-kali/#kali-virtual-machines)

Burp Suite:
[Download](https://portswigger.net/burp/communitydownload)

Comprehensive Path for Beginners:
[TryHackMe](https://tryhackme.com/)

Learn about Vulnerabilities and how to exploit them:
[PortSwigger Web Security Academy](https://portswigger.net/web-security)
[The OWASP Top 10 (Web)](https://owasp.org/www-project-top-ten/)
[The OWASP Top 10 (Mobile)](https://owasp.org/www-project-mobile-top-10/)
[The OWASP Top 10 (Desktop App)](https://github.com/OWASP/www-project-desktop-app-security-top-10/blob/main/index.md)
[DVWA Setup](https://cybr.com/cybersecurity-fundamentals-archives/how-to-set-up-the-dvwa-on-kali-with-docker/)
[TryHackMe](https://tryhackme.com/)

Capture The Flag (CTF) and Vulnerable Machines:
[HackTheBox Labs](https://www.hackthebox.com/hacker/hacking-labs)
[VulnHub](https://www.vulnhub.com/)
[TryHackMe](https://tryhackme.com/)

Find exploits and tools:
[Exploit DB](https://www.exploit-db.com/)
[Github](https://github.com/)

---



