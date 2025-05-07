# A04-2021 Insecure Design
Focuses on deficiencies at the architectural and design level, that is, before code implementation. This implies that security must be a primary consideration from the beginning of the software development lifecycle. Unlike other categories that focus on specific implementation errors, insecure design is a systemic problem that can lead to multiple vulnerabilities.

**Example**: Failure to separate internal and external networks, allowing an attack on one network to affect others.

## Severity
- **Causes structural problems**: Design flaws affect the entire system and are often difficult to correct without significant restructuring.
- **Enables other vulnerabilities**: An insecure design can facilitate the exploitation of issues such as injection, weak access control, etc.
- **Long-term risk**: Poorly designed systems are more likely to fail in the face of future threats.

## Mitigation
- **Threat Modeling**: Perform threat analysis to identify potential attack vectors and design security controls to mitigate them.
- **Secure Reference Architecture**: Use secure reference architectures and proven design patterns.
- **Security Design Reviews**: Conduct periodic security design reviews to identify and address potential vulnerabilities.
- **Risk-Based Development**: Prioritize security activities based on the risk posed by different system features and components.