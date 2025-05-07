# A03-2021 Injection

This occurs when a cyberattacker inserts malicious code into a query or command, tricking the system into executing that action. This happens by failing to properly validate user input. Injection types include:
- SQL Injection: Altering AQL queries to obtain or modify data.
- Command Injection: Executing arbitrary commands on the system.
- LDAP, NoSQL, and XSS Injections: Modifying queries in different contexts.
- XML ​​Injection (XXE): Exploiting vulnerabilities in XML data processing.
- HTTP Header Injection: Modifying HTTP headers to perform attacks such as header splitting.

**Example**: A form that allows an attacker to inject SQL code to obtain sensitive information directly from the database.

## Severity
A successful attack of this type can affect the confidentiality, integrity, and availability of the system.

- **High Impact**: Can compromise entire databases, execute arbitrary commands, or take control of the server.
- **Ease of Exploitation**: Tools like SQLmap make it easy to identify and exploit these flaws.
- **Financial and Reputational Damage**: Exploiting sensitive data can lead to illegal breaches and loss of trust.

## Mitigation
- **Input Whitelisting**: Instead of rejecting malicious characters, allow only known and safe characters.
- **Character Escaping**: Escape special characters in user input to prevent it from being interpreted as code.
- **Least Privilege Execution Environment**: Limit interpreter permissions to reduce the impact of a successful attack.
- **Static Code Analysis**: Use static analysis tools to identify potential injection vulnerabilities in source code.
- **Web Application Firewall (WAF)**: Implement a WAF to filter and block malicious requests.