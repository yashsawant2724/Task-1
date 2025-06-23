**# Task-1
Scanning my Local Network for Open Ports.**

Objective: Learn to discover open ports on devices in your local network to
understand network exposure.
Tools: Nmap (free), Wireshark (optional)

**Nmap:
**
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
Port 1900 commonly associated with UPnP (Universal Plug and Play) and SSDP (Simple Service Discovery Protocol): ttackers can exploit vulnerabilities in UPnP implementations to gain unauthorized access to networks, potentially launching DDoS attacks or redirecting traffic for malicious purposes. 
Port 1688, used by Key Management Service (KMS) for Windows activation, presents a security risk if not properly managed. Attackers can exploit vulnerabilities in KMS or the activation process itself to compromise systems, potentially leading to unauthorized access, malware distribution, or denial-of-service attacks. 
Port 50300, if exposed, can pose significant security risks. It's often used by services like Oracle WebLogic, and if not properly secured, can be exploited by attackers for unauthorized access, data breaches, or denial-of-service attacks. 

**Nmap Logs:
**

![image](https://github.com/user-attachments/assets/bcb8bb90-850b-4390-9ddd-ff0b14036f8a)
![image](https://github.com/user-attachments/assets/552ff628-9493-4562-9200-ff6d807e9d5b)
![image](https://github.com/user-attachments/assets/8e49b54f-6e37-4710-a90b-0d44c5402307)
![image](https://github.com/user-attachments/assets/2f1269f3-bd9d-47dd-9812-e62657ef0d6b)
![image](https://github.com/user-attachments/assets/5aad8a26-8880-416f-9ea1-67e6889a4f4b)



**Wireshark:
**
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
