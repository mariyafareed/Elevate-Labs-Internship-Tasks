# Task 01 - Nmap Port Scanning

## 🎯 Objective
Discover open ports on local devices using Nmap and inspect traffic with Wireshark on Kali Linux.

## 🛠 Tools
- Nmap 
- Wireshark
- IP found using `ifconfig`: 10.0.2.15

## 🖥️ Results
Found 4 hosts; notable ports: 135 (msrpc), 445 (SMB), 8090 (web service).
Wireshark confirmed SYN, SYN-ACK, and RST packets.

⚠️ Risks: Ports 135/445/8090 expose system to RPC, SMB, or app-level exploits.
