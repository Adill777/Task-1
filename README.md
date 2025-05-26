![image](https://github.com/user-attachments/assets/f9a781cb-9245-41e5-9d35-9270d0daba32)# Task 1 - Network Port Scanning

# Tools Used
- Nmap
- Wireshark (optional)

# Objective:
To perform a TCP SYN scan on the local network and identify open ports.

# Steps:
1. Found local subnet using `ipconfig`.
2. Ran: `nmap -sS 192.168.1.0/24`.
3. Saved scan output.
4. Identified open ports and services.
5. Noted potential risks of exposed ports.

## Sample Output
- 192.168.1.5 - Port 22 (SSH), 80 (HTTP)
- 192.168.1.10 - Port 445 (SMB)


