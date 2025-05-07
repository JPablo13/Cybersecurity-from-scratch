# DNS Spoofing

This is the process of altering entries in a DNS server to redirect a specific user to a malicious website controlled by an attacker. It typically occurs in a public Wi-Fi network environment, but it can also occur in any situation, allowing an attacker to alter ARP tables and force user devices to use the attacker-controlled device as a server for a specific website.

## What does it consist of?
Cybercriminals can use tools to perform DNS spoofing. Public Wi-Fi networks are typically the main points of attack, as they are poorly configured and often have weak security features. This provides cybercriminals with more opportunities to carry out their desired actions. Therefore, it is always recommended to consider the security of Wi-Fi networks, both private and public. However, it is important to understand that it is not limited exclusively to public networks and can occur in other network environments if the attacker manages to position themselves in the path of DNS communication.

## Basic Steps
- Use arpspoof to trick a user's computer into pointing to the attacker's computer when the user types a domain address into their browser.
- Issue another arpspoof command to trick the web domain server into thinking the client's IP is the attacker's computer's IP.
- Create a HOST file that points the attacker's computer's IP to the target web page.
- Set up a phishing web page that looks exactly like the "real" web page on a malicious local computer.
- Collect data from victims online, tricking them into authenticating or entering their information.

## Why is this a problem?
Since users are often phished in DNS spoofing attacks, they pose a threat to data privacy. The page to spoof depends on the attacker's objectives. For example, if an attacker wants to steal banking information, the first step would be to find a popular banking website, download the code and style files, and upload them to the malicious computer used to hijack connections. Most attackers test and verify that the spoofed page is properly crafted, but occasionally, small errors reveal that the page is being spoofed.