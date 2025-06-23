Cybersecurity Internship - Task 1

Task: Scan Your Local Network for Open Ports

- [Nmap]

My Network Details

- **Device IP Address:** 192.168.0.102  
- **Subnet Mask:** 255.255.255.0  
- **Subnet Range Used:** `192.168.0.0/24`

 Nmap Command Used
nmap -sS 192.168.0.0/24 -oN scan_result.txt


Nmap successfully detected multiple devices in the network.

Open ports such as 22 (SSH), 80 (HTTP), and 443 (HTTPS) were observed.

This indicates the presence of various services like web servers, routers, or SSH-enabled machines.



What I Learned
How to identify my local IP and subnet range

How to use Nmap for SYN scans

How to analyze scan results to detect exposed services

Why it's important to secure unused or unnecessary open ports
