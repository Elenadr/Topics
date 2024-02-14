Recap failed questions.
###### PKI

1. Business partners are working on a security mechanism to validate transactions securely. The requirement is for one company to be responsible for deploying a trusted solution that will register and issue artifacts used to sign, encrypt, and decrypt transaction files. Which of the following is the BEST solution to adopt?  

- <mark style="background: #BBFABBA6;"> A. PKI</mark> 
- B. Blockchain
- C. SAML
- D. OAuth
---
<mark style="background: #ADCCFFA6;">The main reason this is not blockchain is that blockchain is all about transparency. The transaction record is visible to all, and can be verified by the hash. Blockchain is not used to encrypt or decrypt anything.</mark>

---
###### Preventive&Detective

2. A Chief Security Officer (CSO) is concerned that cloud-based services are not adequately protected from advanced threats and malware. The CSO believes there is a high risk that a data breach could occur in the near future due to the lack of detective and preventive controls. Which of the following should be implemented to BEST address the CSO's concerns? (Choose two.)  

- A. A WAF
- <mark class="hltr-green"> B. A CASB</mark>
- <mark class="hltr-green">C. An NG-SWG</mark>
- D. Segmentation
- E. Encryption
- F. Containerization
---

<mark class="hltr-blue">An NG-SWG combines traditional secure web gateway capabilities with advanced security features such as advanced threat detection, sandboxing, data loss prevention, and SSL/TLS inspection. By deploying an NG-SWG, organizations can apply granular security policies to monitor and control web traffic to and from cloud-based services, ensuring that malicious activity is detected and blocked. The NG-SWG can provide advanced threat intelligence, content filtering, and behavioral analysis to protect against known and unknown threats. It also offers visibility into user activities, allowing organizations to detect anomalies and potential security breaches. A Cloud Access Security Broker (CASB) can also help address the concerns by providing additional security controls and visibility into cloud-based services. A CASB acts as an intermediary between users and cloud service providers, allowing organizations to enforce security policies, monitor user activity, and detect and prevent unauthorized access to cloud resources.-</mark>

---
##### Password History
Multiple business accounts were compromised a few days after a public website had its credentials database leaked on the Internet. No business emails were identified in the breach, but the security team thinks that the list of passwords exposed was later used to compromise business accounts. Which of the following would mitigate the issue?  

- A. Complexity requirements
* <mark class="hltr-green"> B. Password history</mark>
- C. Acceptable use policy
- D. Shared accounts

[Reveal Solution](https://www.examtopics.com/exams/comptia/sy0-601/view/9/#)

--- 
#### Memory Leak
A systems administrator reports degraded performance on a virtual server. The administrator increases the virtual memory allocation, which improves conditions, but performance degrades again after a few days. The administrator runs an analysis tool and sees the following output:  
==3214== timeAttend.exe analyzed  
==3214== ERROR SUMMARY:  
==3214== malloc/free: in use at exit: 4608 bytes in 18 blocks.  
==3214== checked 82116 bytes  
==3214== definitely lost: 4608 bytes in 18 blocks.  
The administrator terminates the timeAttend.exe, observes system performance over the next few days, and notices that the system performance does not degrade. Which of the following issues is MOST likely occurring?  

- A. DLL injection
- B. API attack
- C. Buffer overflow
- <mark class="hltr-green">D. Memory leak</mark>
---

<mark class="hltr-blue">A memory leak occurs when a program or process does not release memory resources properly after it is no longer needed. As a result, memory consumption continues to increase over time, leading to degraded performance and potential system instability. In this case, the system administrator observed degraded performance on the virtual server, which improved temporarily after increasing the virtual memory allocation. However, the performance degraded again after a few days. The output of the analysis tool indicates that there are 4608 bytes in 18 blocks of memory that are "definitely lost" at the time of exit. By terminating the "timeAttend.exe" process and observing that the system performance does not degrade afterward, it suggests that the memory leak issue was related to the "timeAttend.exe" process. Terminating the process would release the allocated memory, resolving the memory leak and improving system performance.
</mark>

---


----
#### Transit Gateway
Which of the following components can be used to consolidate and forward inbound internet traffic to multiple cloud environments though a single firewall?  

<mark class="hltr-green">- A. Transit gateway</mark>
- B. Cloud hot site
- C. Edge computing
- D. DNS sinkhole
---
<mark class="hltr-blue"> A transit gateway is a simpler means of managing these interconnections. Essentially, a transit gateway is a virtual router that handles routing between the subnets in each attached VPC and any attached VPN gateways (aws.amazon.com/transit-gateway).
</mark>
---

#### Scalability
DDoS attacks are causing an overload on the cluster of cloud servers. A security architect is researching alternatives to make the cloud environment respond to load fluctuation in a cost-effective way. Which of the following options BEST fulfills the architect's requirements?  

- <mark class="hltr-green">A. An orchestration solution that can adjust scalability of cloud assets</mark>
- B. Use of multipath by adding more connections to cloud storage
- C. Cloud assets replicated on geographically distributed regions
- D. An on-site backup that is displayed and only used when the load increases

An orchestration solution that can adjust the scalability of cloud assets is the best option to fulfill the security architect's requirements. Orchestration in the context of cloud computing refers to the automated management and coordination of various cloud resources to handle changes in demand and optimize performance. By using an orchestration solution, the cloud environment can dynamically scale resources up or down based on load fluctuations caused by DDoS attacks or any other factors. This allows the organization to respond to changing demands in a cost-effective and efficient manner.

---
#### Context aware authentication

A security proposal was set up to track requests for remote access by creating a baseline of the users' common sign-in properties. When a baseline deviation is detected, an MFA challenge will be triggered. Which of the following should be configured in order to deploy the proposal?  

* <mark class="hltr-green"> A. Context-aware authentication</mark>
- B. Simultaneous authentication of equals
- C. Extensive authentication protocol
- D. Agentless network access control

<mark class="hltr-blue">Context-Aware authentication -> An access control scheme that verifies an object's identity based on various environmental factors, like time, location, and behavior.
</mark>


---
#### casb

The Chief Information Security Officer directed a risk reduction in shadow IT and created a policy requiring all unsanctioned high-risk SaaS applications to be blocked from user access. Which of the following is the BEST security solution to reduce this risk?  

- <mark class="hltr-green">A. CASB</mark>
- B. VPN concentrator
- C. MFA
- D. VPC endpoint

<mark class="hltr-blue">cloud access security broker (CASB) is on-premises or cloud-based software that sits between a cloud service consumer and a cloud service provider. It serves as a tool for enforcing an organization's security policies through risk identification and regulation compliance whenever its cloud-residing data is accessed.
</mark>

---
### AUP
Users are presented with a banner upon each login to a workstation. The banner mentions that users are not entitled to any reasonable expectation of privacy and access is for authorized personnel only. In order to proceed past that banner, users must click the OK button. Which of the following is this an example of?  

* <mark class="hltr-green"> A. AUP</mark>
- B. NDA
- C. SLA
- D. MOU

---
### Certs
An untrusted SSL certificate was discovered during the most recent vulnerability scan. A security analyst determines the certificate is signed properly and is a valid wildcard. This same certificate is installed on the other company servers without issue. Which of the following is the MOST likely reason for this finding?  

<mark class="hltr-green">- A. The required intermediate certificate is not loaded as part of the certificate chain.</mark>
- B. The certificate is on the CRL and is no longer valid.
- C. The corporate CA has expired on every server, causing the certificate to fail verification.
- D. The scanner is incorrectly configured to not trust this certificate when detected on the server.
---

<mark class="hltr-red">120. As part of a security compliance assessment, an auditor performs automated vulnerability scans. In addition, which of the following should the auditor do to complete the assessment?  </mark>

		- A. User behavior analysis
		- B. Packet captures
		- C. Configuration reviews
		- D. Log analysis

#### duda
<mark class="hltr-red">Which of the following is the BEST action to foster a consistent and auditable incident response process?  </mark>

- A. Incent new hires to constantly update the document with external knowledge.
- <mark class="hltr-yellow">B. Publish the document in a central repository that is easily accessible to the organization.</mark>
- C. Restrict eligibility to comment on the process to subject matter experts of each IT silo.
- D. Rotate CIRT members to foster a shared responsibility model in the organization.

<mark class="hltr-red">An organization implemented a process that compares the settings currently configured on systems against secure configuration guidelines in order to identify any gaps. Which of the following control types has the organization implemented?  </mark>

- A. Compensating
- B. Corrective
- C. Preventive
- D. Detective


An organization wants to implement a biometric system with the highest likelihood that an unauthorized user will be denied access. Which of the following should the organization use to compare biometric solutions?  

- A. FRR
- B. Difficulty of use
- C. Cost
- D. FAR
- E. CER
A company recently experienced a significant data loss when proprietary information was leaked to a competitor. The company took special precautions by using proper labels; however, email filter logs do not have any record of the incident. An investigation confirmed the corporate network was not breached, but documents were downloaded from an employee's COPE tablet and passed to the competitor via cloud storage. Which of the following is the BEST remediation for this data leak?  

- A. User training
- B. CASB
- C. MDM
- D. DLP

Which of the following control types would be BEST to use in an accounting department to reduce losses from fraudulent transactions?  

- A. Recovery
- B. Deterrent
- C. Corrective
- D. Detective

A company labeled some documents with the public sensitivity classification. This means the documents can be accessed by:  

- A. employees of other companies and the press.
- B. all members of the department that created the documents.
- C. only the company's employees and those listed in the document.
- D. only the individuals listed in the documents.

---

#### Fingerprint

A security analyst wants to fingerprint a web server. Which of the following tools will the security analyst MOST likely use to accomplish this task?  

- A. nmap -pl-65535 192.168.0.10
- B. dig 192.168.0.10
- C. curl --head http://192.168.0.10
- D. ping 192.168.0.10

![](Images/Captura%20de%20Pantalla%202024-02-14%20a%20las%2012.06.14.png)

-