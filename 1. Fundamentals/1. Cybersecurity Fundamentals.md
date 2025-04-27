# Cybersecurity Fundamentals

Information security (InfoSec) is the protection of sensitive information from unauthorized access, disclosure, use, alteration, or disruption.

Computer security is the practice of protecting an organization's IT assets—computer systems, networks, digital devices, or data—from unauthorized access, data breaches, cyberattacks, and other malicious activity.

Cybersecurity is the practice of protecting systems, networks, and programs from digital attacks. It refers to all the processes, technologies, and security measures applied to protect information and systems in digital or connected environments, such as networks and the internet, from logical threats.

## Vulnerabilities and Types

A vulnerability is a security flaw, weakness, or defect in physical, logical, or human assets that can be exploited to compromise the confidentiality, integrity, or availability of systems, data, or services. Some examples of the most common vulnerabilities are:

- **Natural:** These are vulnerabilities caused by natural phenomena or environmental conditions, which can compromise a company's infrastructure.
- **Physical:** These refer to weaknesses in the protection of spaces where data is stored or processed, such as a lack of access controls, equipment exposed to the public, or poorly protected facilities.
- **Software:** These are programming errors, incorrect configurations, or lack of updates in operating systems, applications, and services, which can be exploited to compromise security.
- **Hardware:** These are defects in the physical components of a system, such as design, manufacturing, or maintenance flaws.
- **Connection:** These affect the security of data during transmission over networks or communication media.
- **Human:** These are errors or behaviors that attackers can exploit, such as weak passwords, lack of training, or susceptibility to social engineering techniques.

## Malware and Types

Malware is a set of malicious programs or codes designed to cause harm, obtain illicit benefits for its creator, or compromise devices, systems, or networks. It can manifest itself in various forms, depending on its purpose and behavior. Some examples are:
- **Virus:** All viruses are a type of malware, but not all malware is a virus. Viruses are programs designed to infect legitimate files, replicate, and spread to other devices.
- **Worm:** Malware that can replicate and spread autonomously, often exploiting vulnerabilities in networks.
- **Trojan:** A type of malware that presents itself as a legitimate or harmless program to trick the user into executing it. Once activated, it allows the attacker to perform malicious actions.
- **Spyware:** Spyware is designed to collect user information without their consent. This information may include browsing habits, credentials, or sensitive data; sometimes it is used for espionage or sold to third parties. - **Adware:** Generates and displays unwanted ads on infected devices, often with the goal of generating revenue for the attacker or redirecting the user to dangerous sites.
- **Ransomware:** Encrypts data on infected devices and demands a ransom, usually in cryptocurrency, in exchange for the decryption key.
- **Rogue:** Poses as legitimate security software, tricking users with nonexistent infection alerts into purchasing fake licenses or downloading other malware.

Malware operates in different ways, but most consist of two essential elements:

- **Exploit**: A set of instructions, code, or tools designed to exploit a specific vulnerability and compromise a system or asset by performing unauthorized actions.
- **Payload**: The malicious payload executed once the exploit has been successful. It can include actions such as installing malware, stealing data, or creating backdoors.
## Privacy/Anonymity

- **Privacy:** Refers to the control a person or entity has over their personal information. This involves the ability to decide what data to share, with whom to share it, and under what conditions.

*Example:* A social media user configures their profile so that only their friends can see their posts.

- **Anonymity:** Is the ability to act or communicate without revealing a person's identity. Its objective is to protect the individual from personal identity, whether through their name, IP address, fingerprint, or any other identifiable information.

*Example:* An activist uses the Tor network to publish a blog about corruption without revealing their identity, protecting themselves from retaliation.

## Zero Trust Architecture
It is based on the fundamental principle of **never trust, always verify**. Unlike traditional security models that focused on protecting the network perimeter, Zero Trust assumes that threats can originate from both outside and inside the network. Some key points of this architecture are:
- **Constant Verification:** Requires that all users, whether inside or outside the organization's network, be authenticated, authorized, and continuously validated before granting or maintaining access to applications and data.
- **Least Privilege:** Ensures that employees, teams, and third parties have access only to the IT resources they strictly need.

## McCumber's Cube
![McCumber's Cube](https://github.com/JPablo13/Curso-Introductorio-a-la-Ciberseguridad/blob/main/Recursos%20Visuales/Cubo%20de%20McCumber.png)

### Security Principles
- **Confidentiality:** Refers to the protection against unauthorized access to information. It ensures that data is accessible by authorized people, processes, or systems, minimizing the risk of sensitive information leakage.

*Example:* Encrypt customer information during transmission (SSL/TLS on websites).

- **Integrity:** Ensures that information remains accurate, complete, and reliable over time, preventing unauthorized alteration or damage during storage, transmission, or processing.

*Example:* Use digital signatures to ensure that sent documents have not been altered.

- **Availability:** Ensures that authorized users can access data and systems when needed, minimizing downtime or interruptions due to technical failures, attacks, or disasters.

*Example:* Backup and failover systems allow services to remain accessible, even during outages.

### Data State
- **Data in transit:** Data being sent from one location to another, whether within the same network, between networks, or over the Internet. During this state, data is vulnerable to interception and manipulation. - **Data at rest:** Data stored on local devices or remote storage. During this state, the data is not being processed or transmitted, but it must be protected from unauthorized access through encryption and access controls.
- **Data in progress:** Data being actively manipulated, such as during entry, modification, calculation, or analysis. This state represents the time when data is most susceptible to errors, malicious alterations, or loss.

### Security Measures
Security measures are designed to protect an organization's data and infrastructure. To do so, they must be based on several fundamental pillars that address different aspects of protection: **Human Factor, Technology, Policies, and Procedures**. These pillars ensure that all security elements are integrated and managed effectively.

## Security Controls

![Security Controls](https://github.com/JPablo13/Curso-Introductorio-a-la-Ciberseguridad/raw/main/Recursos%20Visuales/Controles%20de%20seguridad.png)

### Physical Controls
These are designed to protect the organization's physical assets and prevent unauthorized access to sensitive areas. These include the use of hardware devices such as card readers, biometric access controls, surveillance cameras, perimeter fences, and specific architectural features of buildings, such as armored doors or restricted access systems. Furthermore, security actions must be carried out by authorized personnel, who must be trained to handle security measures appropriately.

### Technical Controls
These are security measures implemented directly on the organization's computer systems and networks. These include automated protection mechanisms such as firewalls, intrusion detection systems (IDS), data encryption, role-based access control (RBAC), multi-factor authentication (MFA), and patch management policies. They also facilitate the detection of security incidents, allow auditing of access and activities, and ensure the protection of sensitive applications and data, both at rest and in transit.

### Administrative Controls
These are policies, procedures, and directives that regulate the behavior of individuals within the organization, as well as interactions with external parties. These controls include the implementation of security policies, ongoing cybersecurity training for employees, regulations for the proper handling of sensitive data, incident response policies, and regular audits to ensure compliance.

## Defense in Depth

### Security Onion
This is a model based on the idea of ​​multiple layers of security. Each layer represents a protective measure (firewall, IDS, MFA, network segmentation) that an attacker must overcome to compromise the system. The advantage of this model is the redundancy of defenses, which increases the probability of detecting a potential attack.

*Example:* An attacker attempts to access a corporate server. But they must first confront a firewall, then an intrusion detection system (IDS), and finally, multi-factor authentication (MFA). These layers must be overcome to compromise the system.
### Security Artichoke
In this model, each layer of defense can contain sensitive information, meaning it is not necessary to reach the core of the system to extract valuable data. This highlights the importance of properly securing each layer, preventing information leaks at superficial points.

*Example:* An employee neglects to protect some data on a shared system. Although the attacker only compromises one layer, they can access relevant company data without needing to evade other security systems.
## Risk Management

It is an essential strategic process for organizations seeking to protect their digital assets and ensure the continuity of their operations. It consists of identifying, analyzing, evaluating, and mitigating threats to information systems. The main objective is to establish preventive controls and reduce exposure to potential security incidents.

### Key Stages in Cybersecurity Risk Management
1. **Risk Identification:** The first step is to recognize and document potential threats and vulnerabilities that could affect the organization. This involves a thorough understanding of information assets and potential weaknesses in the cybersecurity infrastructure.
2. **Analysis and Assessment:** Once the risks have been identified, they are analyzed to understand their potential impact on the organization. The likelihood of their occurrence and the potential damage they could cause to digital assets and business operations are assessed.
3. **Management and Mitigation:** In this stage, strategies to address the identified risks are defined and implemented. This may include implementing security controls, transferring risk (such as cyber insurance), or accepting risk when the cost of mitigation is too high compared to the potential impact.
4. **Monitoring and Review:** Risk management is an ongoing process. It is essential to constantly monitor the threat landscape, review the effectiveness of implemented controls, and adjust risk management strategies as needed to adapt to new challenges and vulnerabilities.

## Incident Response

This is the set of processes and actions that an organization must implement to detect, contain, eradicate, and recover from a cybersecurity incident. It is a critical function for minimizing damage and restoring normal operations as quickly as possible after a cyberattack.

### Key Phases in Incident Response
1. **Preparation:** Before an incident occurs, it is essential to establish an incident response plan. This includes defining roles and responsibilities, establishing communication procedures, identifying critical assets, and configuring the tools and technologies necessary for detection and response.
2. **Detection and Analysis:** This phase focuses on identifying the occurrence of a security incident. It involves continuous monitoring of systems and networks, analyzing security alerts, and assessing potentially suspicious events to confirm whether it is a real incident and determine its scope and nature.
3. **Containment:** Once an incident is confirmed, the primary objective is to prevent it from spreading and minimize its impact. Containment actions may include isolating affected systems, segmenting networks, disabling compromised services, or modifying firewall rules.
4. **Eradication:** This phase focuses on eliminating the root cause of the incident and restoring systems to a safe state. It may involve removing malware, correcting vulnerabilities, rebuilding compromised systems, or restoring data from backups.
5. **Recovery:** The objective of this phase is to restore the organization's normal operations as quickly as possible. This includes system and data recovery, security validation of restored systems, and the gradual resumption of affected services.
6. **Lessons Learned (Post-Incident):** After resolving the incident, it is crucial to conduct a post-incident review to analyze what happened, identify root causes, evaluate the effectiveness of the response, and document lessons learned. These lessons should be used to improve the incident response plan and strengthen the organization's security posture.

## Access Control Models

### Discretionary Access Control (DAC)
This is the least restrictive model and allows users to control access to their data as if they were the data owners. You can use ACLs or other methods to specify which users or groups of users have access to the information.

### Mandatory Access Control (MAC)
This enforces the strictest access control and is typically used in military or mission-critical applications. It assigns security-level labels to information and enables user access based on their authorization level.

### Role-Based Access Control (RBAC)
Access decisions are based on an individual's roles and responsibilities within the organization. Security privileges are assigned to different roles, and individuals are assigned the RBAC profile for the role. Roles can include different job titles, job classifications, or groups of job classifications.

### Attribute-Based Access Control (ABAC)
Allows access based on attributes of the object (resource) to be accessed, the subject (user) who will have access to the resource, and environmental factors that influence how the object will be accessed.

### Rule-Based Access Control (RuBAC)
Network security personnel specify sets of rules or conditions associated with access to data or systems. These rules may specify allowed or denied IP addresses, or certain protocols and other conditions.

### Time-Based Access Control (TAC)
Allows access to network resources based on the time and day.

## Authentication Protocols

### Extensible Authentication Protocol (EAP)
The client's password is sent as a hash to the authentication server. The authentication server has a certificate.

### Password Authentication Protocol (PAP)
A username and password are sent to a remote access server in plain text. Most network operating system servers support PAP. It is an insecure protocol because it transmits information in plain text.

### Chance Authentication Handshake Protocol (CHAP)
CHAP validates the identity of remote clients using a one-way hash function created by the client. The service also calculates the expected hash value. The server compares the two values; if they match, the transmission continues. The server also periodically verifies the client's identity during the transmission.

## Authentication Technologies

### 802.1x
An organization authenticates its identity and authorizes access to the network. Its identity is determined based on credentials or a certificate confirmed by a RADIUS server.

### RADIUS
When username/password authentication is required, RADIUS is used to accept or deny access. This service only encrypts the user's password from the RADIUS client to the RADIUS server. The username, usage record, and authorized services are transmitted in plain text. When implementing this technology, only security measures that protect against replay attacks are necessary.

### TACACS+
Uses TCP as the transport protocol. This encrypts all data between the client and server. Since network administrators can define ACLs, filters, and user privileges, it is the best choice for corporate networks that require more sophisticated authentication steps and control over authorization activities. 
### Kerberos
Kerberos uses strong encryption, requiring a client to prove its identity to a server, and the server in turn authenticates itself to the client.
The Kerberos server contains user IDs and hashed passwords for all users who will be authorized to use the domain's services. The Kerberos server also has secret keys shared with all servers to which it will grant access tickets. The first ticket is a ticket-granting ticket issued by the authentication service to a requesting client. The client can present this ticket to the Kerberos server with a ticket request to access a specific server.
By being able to encrypt the entire session, the inherently insecure transmission of items that can be intercepted on the network is eliminated. Tickets have an expiration date, so any attempt to reuse a ticket will be unsuccessful.

## AAA Operation

The Authentication, Authorization, and Audit (AAA) protocol provides the framework necessary to enable scalable access security.

### Authentication
Users and administrators must prove they are who they say they are. Authentication can be established using username and password combinations, challenge questions and answers, token cards, and other methods.
Authentication provides a centralized way to control network access.

### Authorization
Once a user is authenticated, authorization services determine which resources the user can access and what operations they are authorized to perform.

### Accounting
Accounting records also record what the user does, including what items they access, the amount of time they access the resource, and any changes made. Accounting keeps track of how network resources are used.
