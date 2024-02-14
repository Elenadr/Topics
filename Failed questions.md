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
#### Fingerprint

A security analyst wants to fingerprint a web server. Which of the following tools will the security analyst MOST likely use to accomplish this task?  

- A. nmap -pl-65535 192.168.0.10
- B. dig 192.168.0.10
- C. curl --head http://192.168.0.10
- D. ping 192.168.0.10

![](Images/Captura%20de%20Pantalla%202024-02-14%20a%20las%2012.06.14.png)
