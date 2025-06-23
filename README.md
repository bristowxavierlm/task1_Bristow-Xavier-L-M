# task1_Bristow-Xavier-L-M
First task of the cyber security internship

Nmap TCP SYN Scan Project

Overview
Performed a local network scan using Nmap with TCP SYN (-sS) to identify active hosts and open ports.

Tools Used
- Nmap
- Wireshark (for packet capture)
- Kali Linux VM

Files
- local_scan.txt: Nmap scan output
- wireshark_capture.pcapng: Wireshark packet capture
- screenshots/: Images from the scan process

Ports & their potential riskd
- HTTP : Web application vulnerabilities 
- DNS : DNS Cache Poisoning
- SSH : Bruteforce attacks
- FTP : Anonymous login allowed

Commands Used
- sudo nmap -sS 192.168.1.0/24 - Network Scan
- sudo nmap -sS 192.168.1.0/24 -oN network_scan.txt - Save as txt file


