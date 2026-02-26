# CS-305-SNHU-Swinson
Collection of work associated with assignments completed in CS 305 Software and Security 

**Client Summary**
Artemis Financial is a financial services company that specializes in secure client transactions and data protection. Their primary concern was that their existing software lacked modern security controls, in the areas of encrypted communication and data integrity. They requested an assessment and refactoring of their application to ensure that sensitive financial information could be transmitted securely. I identified vulnerabilities, implemented secure communication using HTTPS, added checksum verification for data integrity, and validated that the application complied with industry standard security practices.

**Why Secure Coding Matters**
One of the strengths of my approach was the thoroughness of my vulnerability identification process. I combined automated scanning with manual code review to uncover syntactical, logical, and security issues. Secure coding is important because it reduces the risk of data breaches, protects customer trust, and helps organizations maintain compliance with regulatory standards.

**Challenging Parts of the Assessment**
The most challenging part of the vulnerability assessment was configuring and running OWASP Dependency‑Check due to Java version conflicts and changes in how the tool is packaged. Troubleshooting these issues required patience and careful problem solving. The manual review portion was helpful because it forced me to examine the code closely and understand how each component contributed to the application’s security.
Increasing Layers of Security & Future Approaches
I increased the application’s security by implementing HTTPS with a PKCS12 keystore, adding SHA‑256 checksum verification, and reviewing the code for insecure patterns. In the future, I would continue using tools like OWASP Dependency‑Check, static analysis tools, and dynamic testing methods to assess vulnerabilities.

**Ensuring Functionality and Security After Refactoring**
To ensure the application remained functional and secure after refactoring, I performed a detailed manual review of all modified and newly created classes, including the TLS configuration, checksum logic, and Spring Boot entry point. I then executed the application to verify that it launched successfully under the new HTTPS configuration. Finally, I reran OWASP Dependency‑Check to confirm that no new vulnerabilities were introduced during the refactoring process.

**Resources, Tools, and Practices for Future Use**
Throughout this project, I relied on several valuable resources and tools, including the Java Security Standard Cipher Algorithm Names documentation, the Keytool reference guide, Spring Boot’s HTTPS configuration practices, and OWASP Dependency‑Check. These tools helped me implement secure communication, generate certificates, and identify vulnerabilities. The secure coding practices I applied like as avoiding hard‑coded credentials, validating configuration files, and using approved cryptographic algorithm, will be useful in future assignments.

**What I Can Show Future Employers**
From this assignment, I can demonstrate my ability to refactor legacy code, implement secure communication protocols, perform vulnerability assessments, and troubleshoot complex configuration issues. I can show employers my secure coding practices, my use of industry standard tools, and my ability to document and communicate technical findings clearly.

