# Task-1
Scanning my Local Network for Open Ports.

Objective: Learn to discover open ports on devices in your local network to
understand network exposure.
Tools: Nmap (free), Wireshark (optional)

Nmap:
I have successfully installed Nmap in VMware and scanned my local Wi-Fi network through Nmap.
Performed nmap -sS 192.168.1.0/24 for TCP SYN scan.
Nmap SYN scan takes a lot of time.
Found various open ports using Nmap such as 
Open ports discovered by Nmap scans present significant security threats. 
They indicate potential entry points for attackers to exploit vulnerabilities, gain unauthorized access, and potentially compromise systems
Port 21 (FTP): Exposes files and credentials in plain text, making it vulnerable to man-in-the-middle attacks.
Port 22 (SSH): Can be vulnerable to brute-force attacks, and misconfigurations can lead to unauthorized access.
Port 25 (SMTP): Can be exploited for spamming or email spoofing if not properly secured.
Port 80 (HTTP): Exposes web applications to various attacks, including SQL injection, cross-site scripting, and others.
Port 443 (HTTPS): While encrypted, vulnerabilities in the underlying web server software can still be exploited. 

Nmap Logs:
![image](https://github.com/user-attachments/assets/bcb8bb90-850b-4390-9ddd-ff0b14036f8a)

Wireshark:
I have also successfully installed and alalysed traffic through Wireshark.
Used various filters on wireshark to filter traffic logs.
Used expert analysis to understand various packets in Wireshark.
Most common port found in Wireshark are DNS, HTTP, TCP, ARP.
Potential risks associated with DNS, TCP, and HTTP ports include various attacks like DDoS, DNS spoofing, cache poisoning, and various web application exploits like XSS and SQL injection. 
These attacks can lead to data breaches, malware infections, and service disruptions. 

Wireshark Logs:
![Screenshot 2025-06-23 175007](https://github.com/user-attachments/assets/8b87f310-3a5e-4ebb-b0c7-73e72cb51209)
![Screenshot 2025-06-23 175021](https://github.com/user-attachments/assets/a3d456b5-253b-4b4c-8b2c-b84818dbbe32)
![Screenshot 2025-06-23 174836](https://github.com/user-attachments/assets/11e69e04-961c-41b9-a5af-1b28bde80205)
![Screenshot 2025-06-23 174139](https://github.com/user-attachments/assets/f405ef06-9e54-48aa-912a-6b1fa5c25c16)
![Screenshot 2025-06-23 174124](https://github.com/user-attachments/assets/d4f35fc7-30da-4f9b-9620-107f8bf0511d)
![Screenshot 2025-06-13 145658](https://github.com/user-attachments/assets/9b53c2e7-4a4d-4ac0-8bf1-710214b3dd51)
