Project Reflection: Secure Software Practices (CS 305)

Client Summary and Software Requirements
The client for this project was Artemis Financial, a financial services company that required secure communication for its web-based application. The primary issue the company needed addressed was ensuring the confidentiality and integrity of sensitive financial data transmitted between clients and the server. Artemis Financial required the implementation of secure communication protocols, data integrity verification, and vulnerability assessment to reduce security risks and align with industry standards.

Identifying Vulnerabilities and the Importance of Secure Coding
One area I performed well in was identifying and addressing software security vulnerabilities by applying industry-standard security practices rather than relying on outdated or insecure methods. Secure coding is critical because vulnerabilities can lead to data breaches, financial loss, and loss of customer trust. Strong software security adds value to a company by protecting sensitive data, maintaining regulatory compliance, and supporting long-term system reliability and business continuity.

Challenges and Helpful Aspects of the Vulnerability Assessment
A challenging aspect of the vulnerability assessment was interpreting third-party dependency reports and determining which risks were relevant versus informational. However, this process was also helpful because it reinforced the importance of understanding how external libraries can introduce security risks even when application code is well written.

Increasing Layers of Security and Future Assessment Methods
I increased layers of security by implementing Transport Layer Security (TLS) to encrypt data in transit, applying Secure Hash Algorithm 256 (SHA-256) for data integrity, and using digital certificates to support secure communication. In the future, I would continue using automated vulnerability scanning tools, secure configuration reviews, and threat modeling techniques to assess risks and determine appropriate mitigation strategies.

Ensuring Functionality and Security After Refactoring
To ensure the application remained functional and secure, I performed functional testing after refactoring the code and verified that the application started successfully without errors. I also reviewed the refactored code to ensure no insecure practices were introduced and ran dependency checks to identify potential vulnerabilities introduced by third-party components.

Tools, Resources, and Practices for Future Use
This project introduced several tools and practices that will be valuable in future work, including Java Keytool for certificate generation, OWASP Dependency-Check for vulnerability analysis, and secure coding practices such as externalized configuration and strong cryptographic standards. These tools support proactive security testing and safer application design.

Demonstrating Skills to Future Employers
For future employers, I would showcase this project as an example of implementing secure communication, performing vulnerability assessments, and applying industry-standard security practices within a real-world scenario. This assignment demonstrates my ability to analyze security requirements, refactor code responsibly, and validate both functionality and security in a software application.
