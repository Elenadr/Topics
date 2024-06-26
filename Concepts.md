1. [NIC teaming](#nic-teaming)
1. [ISO 31000](#iso-31000)
1. [Hoax](#hoax)
1. [NIST](#nist)
1. [Command and Control](#command-and-control)
1. [RDP 3389](#rdp-3389)
1. [Federation](#federation)




SIEM systems are related with log aggregation and correlation from various sources. SOAR provides automation tools which are going to reduce the amount of manual work for the analysts.

---

## cybersecurity framework(CSF)
is a list of activities and objectives undertaken to mitigate risks. The use of a framework allows an organization to make an objective statement of its current cybersecurity capabilities, identify a target level of capability, and prioritize investments to achieve that target. This is valuable for giving a structure to internal risk management procedures and provides an externally verifiable statement of regulatory compliance. Frameworks are also important because they save an organization from building its security program in a vacuum, or from building the program on a foundation that fails to account for important security concepts.

---

 minimize the number of backups that would need to be restored in case of data loss
Full backups followed by differential backups
**OWASP** (Open Web Application Security Project) es una comunidad global **de** voluntarios y expertos en seguridad informática. Su misión es mejorar la seguridad **de** las aplicaciones web mediante la concienciación, la educación y la promoción **de** las mejores prácticas **de** seguridad.
---
DHCP ports are 67,68, FTP:21, SFTP:22, and web pages are accessed through 443 and insecure http 80.
SMB use TCP Port 139 445、UDP Port 137 138
#### CIS Benchmarks

-> CIS Benchmarks from the Center of Internet Security (CIS) are a set of globally recognized and consensus-driven best practices to help security practitioners implement and manage their cybersecurity defenses.
### NIC teaming

which is a method used to group multiple network interface controllers (NICs) together to function as a single entity. This is often done for redundancy, load balancing, or both. It helps improve network reliability and performance by distributing network traffic across multiple NICs. ^3d74a6

**File integrity monitoring (FIM**), sometimes referred to as file integrity management, is a security process that monitors and analyzes the integrity of critical assets, including file systems, directories, databases, network devices, the operating system (OS), OS components and software applications for signs of tampering or corruption, which may be an indication of a [cyberattack](https://www.crowdstrike.com/cybersecurity-101/cyberattacks/).

### ISO 31000
is an international standard for risk management. It provides guidelines, principles, and a framework for organizations to manage risks effectively. The standard emphasizes the importance of identifying, assessing, treating, monitoring, and communicating risks in a systematic and structured manner. ISO 31000 is applicable to all types and sizes of organizations, regardless of their sector or industry.

### Hoax 
A hoax is a deceptive message or information that is spread with the intention to mislead or deceive recipients. By educating employees not to forward social media messages from unverified sources, the company can reduce the spread of false or misleading information, thereby minimizing the impact of hoaxes.

High data entropy will increase cryptographic security
NIST
following organizations sets frameworks and controls for optimal security configuration on systems?

### NIST

^cedf74

(National Institute of Standards and Technology) is the organization that sets frameworks and controls for optimal security configuration on systems. NIST is a non-regulatory agency of the United States Department of Commerce and plays a significant role in developing standards and guidelines for various aspects of information security, including cybersecurity best practices and security configuration.


### Command and Control 

^4f87d3

(C2 or C&C) - The weaponized code establishes an outbound channel to a remote server that can then be used to control the remote access tool and possibly download additional tools to progress the attack.


Don't>>Throw>>Sausage>>Pizza 
Development>>Test>>Staging>>Production

### RDP 3389

3389 is the default port for RDP connections. RDP is the protocol used to connect to windows desktops/servers remotely. In the scenario, the malware family is known to be distributed through manually logging on to servers and RDP would require a manual login to access the machine and be able to easily run scripts on the server especially through a GUI.

### Federation
Federation uses SAML (Security Assertion Markup Language) for authentication and single sign-on (SSO) between multiple systems or organizations. SAML is an XML-based open standard used to exchange authentication and authorization data between identity providers (IdP) and service providers (SP) to facilitate secure SSO. It enables users to access multiple applications or services with a single set of credentials, making it a key technology for enabling seamless authentication across federated systems.

### Comunity

n a community cloud deployment model, multiple organizations or entities with common interests share computing and storage resources. It is designed for specific communities of users who have shared concerns or requirements, such as research projects, government agencies, or educational institutions. In this scenario, where several universities are participating in a collaborative research project and need to share compute and storage resources, a community cloud deployment strategy would be the best fit.


# Digital signature
There are 2 general ways to use asymetric algorithm. 1 - For communication between 2 hosts: If bob sends a message to Alice, bob uses Alice's public key to encrypt the message, and Alice uses her private key to decrypt the message. 2 - For digital signature/Authentication: If ALice need to authenticate Bob, BOB uses his private key to sign the message, and Alice uses the public key of bob to decrypt the message. This process help to make sure the signature is owned by Bob. On this example, A is totally correct.

### SOC 2 
(Service Organization Control 2) Type 2 report  is a widely recognized report that provides assurance about the controls and security measures implemented by a service organization. It is designed to evaluate a service provider's controls relevant to security, availability, processing integrity, confidentiality, and privacy. The SOC 2 Type 2 report specifically assesses the effectiveness of these controls over a specified period of time. Given that the Chief Information Security Officer (CISO) is requesting supporting documents to show proper controls in place to protect customer data, a SOC 2 Type 2 report would be the best choice. This report demonstrates that the third-party vendor has undergone an independent audit of its controls, providing valuable information about its security practices and compliance with industry standards