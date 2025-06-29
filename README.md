# CS305
Client Summary
Artemis Financial is a financial consulting firm specializing in personalized plans for savings, investments, retirement, and insurance. They approached this project with a goal of modernizing their digital infrastructure and securing their public web interface—particularly by implementing a checksum-based file verification step to ensure secure data transfers and protect client financial records.

Security Implementation Overview
To meet these needs, I implemented SHA-256 hash verification and HTTPS encryption. These additions addressed key security gaps and aligned the system with financial industry standards. Secure software practices are essential in financial applications, not just for preventing breaches, but also for maintaining trust, meeting compliance standards, and strengthening competitive advantage. This project highlighted how software security delivers real business value through risk reduction and data integrity.

Assessment Highlights
The OWASP Dependency Check tool was especially useful for identifying vulnerabilities in third-party libraries. One of the more challenging tasks was setting up SSL/TLS certificate configurations. However, this process helped me gain a better understanding of secure transport protocols. Manual code review also stood out as a helpful way to spot weak cryptographic usage and better understand real-world risk factors.

Security Layers Added
Application Layer: SHA-256 hash verification for file integrity

Transport Layer: HTTPS and SSL encryption to secure communications

Infrastructure Layer: Certificate-based authentication to validate identity

Security Testing & Validation
I verified the success of the implementation through multiple methods:

Unit Testing: Confirmed application startup and hash output without errors

Integration Testing: Verified HTTPS functionality in-browser and correct hash generation

OWASP Scanning: Confirmed that no new vulnerabilities were introduced

Manual Code Review: Evaluated logic for secure implementation and best practices

Tools and Resources
OWASP Dependency Check: Automated security scanning

Java Keytool: Certificate generation and management

MessageDigest API: SHA-256 cryptographic hashing

Spring Boot Security: SSL/HTTPS setup and management

Maven: Build automation and dependency control

Portfolio Showcases for Employers
To demonstrate security proficiency to potential employers, I would showcase:

A complete secure application that includes full-stack protection

Code samples for SHA-256 hash generation and validation

Proper SSL certificate configuration in a Spring Boot environment

Security documentation detailing threat modeling and mitigation

Clean, maintainable code that includes error handling and input validation

Final Reflection
This project gave me hands-on experience in designing and implementing security measures at all levels of a software system—from cryptographic algorithms to secure transport and infrastructure. It’s a strong portfolio piece for roles in software development or cybersecurity and shows my ability to deliver secure, functional solutions for sensitive data environments.
