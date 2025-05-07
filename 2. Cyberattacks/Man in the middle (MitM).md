# MitM

MitM is one of the main cyber threats that gets its name from the fact that an attacker inserts themselves between two communicating parties. If all communications pass through the attacker en route to their destination, this creates the possibility for the attacker to drop, read, or modify messages before they reach their final destination.

## How does it work?
First, they need to insert themselves into the communication in a way that allows them to intercept traffic en route to their destination. Some of the ways an attacker could achieve this are:
- **Malicious Wi-Fi:** All traffic flows through a wireless access point that the attacker controls, and they can trick users into connecting to it.
- **ARP Spoofing:** ARP is used to map IP addresses to MAC addresses. By using fake ARP messages, an attacker maps the target's IP address to their MAC address, causing the target's traffic to be sent to them instead.

- **DNS Spoofing:** DNS maps domain names to IP addresses. Poisoning a DNS cache with fake DNS records can cause traffic to the target domain to be routed to the attacker's IP address.
- **BGP Hijacking:** BGP is used to identify the autonomous system (AS) with the best route to a particular IP address. This hijacking involves advertising a fake route to force certain traffic to flow through the attacker's systems.

Once in the middle of a communication, the attacker needs to be able to read the messages; however, a large percentage of internet traffic is encrypted using SSL/TLS. If the traffic is encrypted, reading and modifying the messages requires the ability to spoof or disrupt the SSL/TLS connection.

## Examples

### Fake Digital Certificates
SSL/TLS are designed to protect against MitM attacks by providing confidentiality, integrity, and authentication to network traffic. However, it relies on the user only accepting digital certificates valid for the particular domain.

### Vulnerable Mobile Applications/IoT
Many mobile applications and IoT devices, especially older or low-cost ones, may lack strong encryption or use insecure protocols such as HTTP or Telnet. If applications or IoT devices transmit sensitive data unencrypted, an attacker on the same network can easily intercept and read that information.