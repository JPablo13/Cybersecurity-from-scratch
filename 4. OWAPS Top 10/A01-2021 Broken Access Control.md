# A01-2021 Broken Access Control

This flaw focuses on the inability to properly restrict the actions of authenticated users. This allows users to perform actions or access resources they are not authorized to perform. This includes:
- Privilege escalation.
- Unauthorized access to sensitive data.
- Modification or deletion of data without proper permissions.
**Example**: An attacker could modify cookies or session tokens to assume the identity of another user.

## Severity
The impact can range from exposed data to a complete system compromise, depending on the context in which it is exploited.
- Sensitive user and system data can be compromised.
- Severe impacts such as loss of information, privacy violations, and manipulation of system resources.
- It can be exploited with simple tools or manual changes to requests.

## Mitigation
Mitigating this vulnerability requires a continuous and updated approach, especially for systems that handle sensitive information or have multiple user levels. Measures that can be taken include:
- **Principle of Least Privilege (PoLP)**: This principle is fundamental. Each user or process should have only the permissions necessary to perform their tasks.
- **Role-Based Access Controls (RBAC)**: Implement RBAC to manage permissions centrally and efficiently.
- **Input Validation**: Validate all user input on the server side to prevent data manipulation.
- **Security by Default**: Deny all access by default and explicitly grant permissions.
- **Implementation of Access Control Policies**: Clear and properly documented access control policies must be implemented.