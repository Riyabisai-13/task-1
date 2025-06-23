# task-1
1.Installed Nmap from the official website
Went to https://nmap.org and download the latest version for your operating system (Windows, Linux, or macOS).On Windows, it usually installs a GUI called Zenmap as well.
2.Found the local IP range (e.g., 192.168.1.0/24)
Found the local IP by running this command in Command Prompt (Windows): ipconfig
Then used the (nmap -sS 192.168.0.113) command which showed me the number open ports and ip addresses.
This command runs a stealth TCP SYN scan across all devices in your network range -sS tells Nmap to send SYN packets (a part of TCP handshake) to detect open ports without completing the full handshake. This scan is fast and less likely to be detected by firewalls.
Optionally analyzed packet capture with Wireshark. I ran the Wireshark while scanning to see live network packets being exchanged. This helped me visualize how Nmap communicates and how your devices respond. Useful for understanding TCP/IP in detail.
7. Identified potential security risks from open ports. Open ports expose the devices to attacks.
All these process has been done and uploaded as a file in this repository.






