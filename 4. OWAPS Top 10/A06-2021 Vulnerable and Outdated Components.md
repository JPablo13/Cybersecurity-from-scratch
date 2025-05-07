# A06-2021 Vulnerable and Outdated Components

This refers to the use of libraries, frameworks, modules, operating systems, web servers, and any other software used in the system that has known vulnerabilities or is outdated. This occurs when:
- Old versions with previously reported security issues are used.
- Critical patches or updates are not applied.
- Dependencies are integrated without verifying their security.

**Example**: Servers running older versions of Linux or Windows without security patches.

## Severity
- **Widespread exploitation**: Attackers often look for specific versions with known vulnerabilities and automated tools to exploit them.
- **Systemic impact**: It can compromise not only an application, but the entire ecosystem if the component is widely used.
- **Difficult to mitigate in complex systems**: In projects with many dependencies, identifying and updating all components can be complicated.

## Mitigation
- **Update Automation**: Implement automation tools to keep components and dependencies up-to-date.
- **Software Composition Analysis (SCA)**: Use SCA tools to identify and manage software dependencies.
- **Lists of Known Vulnerabilities (CVE)**: Stay informed about known vulnerabilities through sources such as the CVE database.
- **Vulnerability Management Policy**: Companies must have vulnerability management policies so that system managers can properly handle these types of issues.