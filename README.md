## Hi, I'm Akhil

Full stack Java developer. About three and a half years building trading and portfolio management platforms for buy-side firms, with Java and Spring Boot on the back end, Angular on the front, and AWS underneath.

I came to development through security (M.S. in Computer Science with a cyber security focus from NJIT), so it shows up in how I write code: Spring Security and JWT on the services, input validation on every write path, and a habit of asking how something could be abused before it ships.

📍 Princeton, NJ · 🌐 [akhil-1527.github.io](https://akhil-1527.github.io)

### What I work on

- **Backend:** Java 17, Spring Boot 3, REST and microservices, Spring Security, Hibernate/JPA, Oracle and PostgreSQL
- **Frontend:** Angular, TypeScript, RxJS, NgRx, ag-Grid
- **Cloud and delivery:** AWS (EC2, S3, RDS, IAM, CloudWatch), Docker, Jenkins, GitHub Actions
- **Domain:** Charles River (CRD) orders and positions, allocations, buy-side trading
- **Testing:** JUnit, Mockito, Jasmine, Karma

### Open source

- **[OWASP Java Encoder](https://github.com/OWASP/owasp-java-encoder/pull/155)** (merged): made the JavaScript encoders encode backtick and `$`, so their output is also safe inside template literals
- **[Kestra](https://github.com/kestra-io/kestra)**: adding unit tests for the UI design system

### Security side projects

Small tools I built to go deeper on AWS and application security. Most use only the standard library so they're easy to read and audit.

- **[aws-iam-privesc-finder](https://github.com/Akhil-1527/aws-iam-privesc-finder)**: finds known IAM privilege escalation paths in an AWS account, mapped to MITRE ATT&CK
- **[cloudtrail-hunter](https://github.com/Akhil-1527/cloudtrail-hunter)**: hunts CloudTrail logs for root usage, logins without MFA, IAM tampering and log evasion
- **[secretscan](https://github.com/Akhil-1527/secretscan)**: secrets scanner using regex rules plus entropy, with redaction and CI-friendly exit codes
- **[s3-auditor](https://github.com/Akhil-1527/s3-auditor)** and **[sg-auditor](https://github.com/Akhil-1527/sg-auditor)**: flag public S3 buckets and internet-open security groups
- **[agentaudit](https://github.com/Akhil-1527/agentaudit)**: a multi-agent system that red-teams AI agents and MCP servers for security flaws

### Certifications

AWS Certified Solutions Architect, Associate · AWS Certified Developer, Associate
