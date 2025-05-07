# DoS Attack

A Denial of Service (DoS) attack is a cyberattack in which the cybercriminal aims to make a computer or service unavailable to targeted users by disrupting the normal operation of the computer or service. These attacks usually work by overloading or flooding a targeted machine with requests until it is unable to process normal traffic. It is characterized by using a single computer to launch such an attack.

## How does it work?

### Buffer Overflow Attack
This type of attack takes advantage of vulnerabilities in software memory management.  By sending more data than a memory buffer can hold, an overflow occurs that can corrupt memory, cause system crashes and even allow malicious code to execute.

### Flooding attack
It consists of flooding the target server with an overwhelming volume of traffic, exceeding its processing capacity.  There are different types of flooding attacks, such as:
- **SYN Flood**: multiple SYN connection requests are sent to a server, but the TCP handshake is not completed (the acknowledgement ACK packet is not sent). This saturates the server's queue of pending connections, preventing it from processing new legitimate connections.
- **UDP Flood**: Bulk UDP packets are sent to the target server. Unlike TCP, UDP is a connectionless protocol, so the server attempts to process every UDP packet it receives. A massive volume of UDP packets can saturate the server and consume its bandwidth.