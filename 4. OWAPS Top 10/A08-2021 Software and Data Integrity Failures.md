# A08-2021 Software and Data Integrity Failures

This is the inability to ensure that software and data have not been maliciously tampered with or altered during development, distribution, or execution. This may include:
- Use of software or library updates without verifying their integrity.
- Lack of validation of digital signatures on packages or data.
- Reliance on untrusted sources for acquiring software or components.

**Example**: Attackers compromising software repositories or development tools to inject malicious code.

## Severity
- **Severe Impact**: Allows attackers to inject malicious code into software or manipulate sensitive data.
- **Extended Risk**: Integrity failures can spread to multiple affected users or systems.
- **Hard-to-Detect Cases**: Software or data tampering can remain hidden for long periods.

## Mitigation
- **Code Signing**: Implement code signing to verify software authenticity and integrity.
- **Software Bills of Materials (SBOM)**: Generate and maintain SBOMs to track software dependencies.
- **Secure Execution Environments**: Use secure execution environments that restrict access to critical resources.
- **Supply Chain Management Policy**: Companies must have supply chain management policies so that system managers can properly handle these types of issues.