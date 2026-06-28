# CS 305 Portfolio Artifact – Artemis Financial Secure Software Project
Repository Summary

This repository contains my completed Artemis Financial Practices for Secure Software Report from CS 305: Software Security. In this project, I improved the security of a Spring Boot application by implementing secure communication using HTTPS, generating a self-signed RSA certificate, creating SHA-256 checksum verification, and performing security testing with OWASP Dependency-Check.

Reflection
Briefly summarize your client, Artemis Financial, and its software requirements.

Artemis Financial is a company that develops personalized financial plans for its customers. Because the company handles sensitive financial and personal information, it needed stronger software security to protect customer data. My job was to identify security vulnerabilities, improve secure communications, and refactor the application to follow secure software development practices.

What did you do well when you found your client's software security vulnerabilities? Why is it important to code securely? What value does software security add to a company's overall well-being?

I think I did a good job identifying vulnerabilities through both manual code review and static testing. I found issues such as outdated dependencies, hard-coded credentials, missing input validation, and weak exception handling. Coding securely is important because it helps protect sensitive information, prevents attackers from exploiting vulnerabilities, and builds customer trust. Strong software security also helps organizations avoid financial losses, protect their reputation, and comply with industry regulations.

Which part of the vulnerability assessment was challenging or helpful to you?

The most challenging part was working with the OWASP Dependency-Check tool because I experienced NVD API errors, including HTTP 429 and HTTP 503 responses, while trying to retrieve vulnerability information. Even though those issues slowed me down, learning how dependency scanning works and understanding vulnerability reports helped me better understand how developers identify security risks in third-party libraries.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

I added several layers of security by implementing HTTPS with a self-signed RSA certificate, generating SHA-256 checksums to verify data integrity, and using OWASP Dependency-Check to identify vulnerable dependencies. In the future, I would continue using manual code reviews, static testing tools, dependency scanners, CVE databases, and the National Vulnerability Database (NVD) to evaluate vulnerabilities and determine the best mitigation strategies.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

After refactoring the application, I tested it by running the Spring Boot application and verifying that the HTTPS connection and checksum endpoint worked correctly. I also performed dependency scanning with OWASP Dependency-Check to review third-party libraries for known vulnerabilities. Functional testing helped confirm the application still worked correctly after the security improvements were added.

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

Throughout this project I used Java, Spring Boot, Eclipse, Maven, Java Keytool, SHA-256 hashing, RSA certificates, HTTPS configuration, OWASP Dependency-Check, and the National Vulnerability Database. I also practiced secure coding techniques such as validating input, improving exception handling, reducing dependency risks, and testing applications after making security changes. These are tools and practices I expect to continue using in future software development and cybersecurity projects.

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

I would show employers this project because it demonstrates several practical cybersecurity and software development skills. It shows that I can identify security vulnerabilities, implement HTTPS, generate certificates, create checksum verification using SHA-256, perform static security testing, and improve an application's overall security. I believe this project represents my ability to write more secure software while following industry best practices.
