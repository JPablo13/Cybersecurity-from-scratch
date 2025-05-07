# A05-2021 Security Misconfiguration
These are errors or inappropriate configurations in the environment, application, or services used, which expose the system to unnecessary risks. This failure may include:
- Insecure default configurations.
- Unnecessary exposure of information.
- Excessive permissions on files or services.

**Example**: Cloud storage with public permissions, or database instances exposed to the internet.

## Severity
- **Impacts multiple levels**: From the application to the underlying infrastructure.
- **Ease of exploitation**: Attackers often only need to explore public configurations or take advantage of default configurations.
- **Breadth of impact**: Can facilitate other attacks such as privilege escalation, code injection, or unauthorized access.

## Mitigation
- **Server hardening**: Apply recommended security configurations for the operating system, web server, and database.
- **Cloud Security**: Review and harden the security configurations of the cloud services used.
- **Secret Management**: Store credentials and other secrets securely, avoiding including them in the source code.
- **Configuration Security Analysis**: Use tools to scan and detect insecure configurations.
- **Information Security Policy**: It is important for companies to have information security policies that help employees configure systems correctly.