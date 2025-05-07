# A10-2021 Server-Side Request Forgery (SSRF)

This occurs when a web application allows an attacker to manipulate and send requests to internal or external servers on behalf of the vulnerable server. This typically occurs due to insufficient validation of user-supplied input, allowing the attacker to:
- Access internal network resources.
- Execute additional attacks, such as data exfiltration or internal port scanning.
- Make malicious requests to external servers.

**Example**: An attacker could use SSRF to access internal databases, back-end servers, or internal APIs.

## Severity
- **Breadth of Impact**: It can be used to access internal networks, potentially exposing sensitive information or unprotected internal services.
- **Ease of Exploitation**: Many applications rely on user input to generate requests without proper validation.
- **Groundwork for secondary attacks**: Can enable attacks such as remote code execution, cloud metadata extraction, or compromise of internal systems.

## Mitigation
- **URL whitelisting**: Allow requests only to specific URLs or domains.
- **Disable redirects**: Avoid using features that allow redirects without validation.
- **Network isolation**: Isolate internal servers from the external network to limit the impact of an SSRF attack.
- **Request security policy**: It is very important for companies to have request security policies so that system administrators can properly handle these types of problems.