# Rootkit

A type of malicious software designed to give a hacker the ability to break into a device and take control of it. They typically only affect the software or operating system of the device they infect, but some can target the hardware or firmware. They act without giving any indication that they are active. Once in place, they allow the hacker to steal personal or financial data, install other malicious applications, or join a botnet.

## Types
- **For hardware or firmware**: They can infect hard drives, routers, or even the device's BIOS. Rootkits don't alter the operating system; they are interested in the device's firmware.
- **For memory**: They hide in the device's RAM and use system resources to perform malicious actions in the background.
- **For applications**: They replace system files with their own. Some change the way common applications work. They infect applications such as Paint, Notepad, or Microsoft Office programs.
- **Kernel mode**: These are especially dangerous because they affect the most central part of the operating system: its core. Hackers use them not only to access files stored on the device, but also to incorporate code that modifies the operating system's operation.
- **Virtual**: These are installed beneath the operating system. Once there, they run the original operating system in a virtual machine and intercept its interactions with the hardware.

## Examples

### Flame
This was a complex and sophisticated malware, considered a rootkit due to its stealth capabilities and deep system access. It was primarily used for cyberespionage in the Middle East. Its espionage capabilities include network traffic monitoring, screen capture, audio recording, keystroke logging, and document theft.