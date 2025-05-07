# A02-2021 Cryptographic Failures

Refers to problems related to the incorrect implementation or absence of cryptographic measures necessary to protect sensitive data. Failures may include:
- Use of weak or obsolete cryptographic algorithms.
- Transmission of unencrypted sensitive data.
- Insecure storage of cryptographic keys.
**Example**: Storing passwords in plain text or transmitting confidential information without encryption.

## Severity
The risk is high, especially in systems that handle sensitive, financial, or authentication data.
- **Exposure of sensitive data**: Allows cybercriminals to access, modify, or steal confidential information.
- **Breach of confidentiality and integrity**: Can compromise user trust and security.
- **Impact on regulatory compliance**: Violations of GDPR, HIPAA, or other data protection regulations.

## Mitigation
1. **Data Encryption in Transit and at Rest**:
    - Use secure protocols such as TLS 1.2 or higher for transmission.
    - Ensure sensitive data is encrypted with modern algorithms such as AES-256.
2. **Avoid Insecure Algorithms**:
    - Do not use outdated algorithms such as MD5 or SHA-1.
    - Use updated standards such as SHA-256 or higher.
3. **Proper Cryptographic Key Management**:
    - Store keys in secure modules and not in source code or exposed locations.
4. **Validate Security Configurations**:
    - Correctly configure cryptographic protocols and tools, avoiding weak or default configurations.
5. **Comply with Security Standards**:
    - Follow regulations such as OWASP ASVS, NIST 800-53, or similar guides.
