Task 1: Scan Your Local Network for Open Ports

  Tools Used:
- Nmap
- Kali Linux

    What I Did:
1. Found local IP using ip a
2. Scanned my local network using: nmap -sS 192.168.1.0/24
3. Saved the results in task1_scan.txt

   What I Learned:
- How to scan a local network
- How to detect open ports


RESEARCH ON OPEN PORTS
Research on Open Ports

|Port-Service-   -      Description -            Risk Level  
 135 - MS RPC- Windows Remote Procedure Call-    Risky if exposed 
 445 - Microsoft-DS- Windows file sharing (SMB)- High risk if open 
 53  - DNS-Domain name resolution-                Medium risk    


These ports were found open on local devices. While some are needed for internal communication (e.g., DNS, file sharing), they can be *exploited* if exposed to the internet. Always secure or restrict access to such services using firewalls and best practices. 


here i used wiresharkto capture the network packets.and i saved it in the task1 file.
