# A07-2021 Identification and Authentication Failures

This covers a wide range of errors in identity management and user authentication. It is crucial to understand that authentication not only verifies the user's identity but also establishes the basis for authorization. This can be caused by:
- Use of weak or default passwords.
- Lack of protection against brute-force attacks.
- Incorrect implementation of features such as password resets or session token handling.

**Example**: Failure to properly validate MFA codes or allowing MFA bypasses.

## Severity
- **Direct impact on system security**: Allows attackers to access sensitive accounts and data.
- **Risk of privilege escalation**: A compromised account can be used to gain additional access to the system.
- **Ease of exploitation**: Authentication failures are frequently exploited with automated brute-force or credential harvesting tools.

## Mitigation
- **Implement adaptive authentication**: Use contextual information, such as the user's location or device, to assess login risk.
- **Identity and Access Management (IAM)**: Implement IAM solutions to centrally manage user identities and access.
- **Authentication security testing**: Perform authentication-specific security testing, such as brute-force testing, credential stuffing testing, and MFA bypass testing.
- **Strong password policy**: Companies need to have strong password policies that help users generate strong passwords and manage them correctly.