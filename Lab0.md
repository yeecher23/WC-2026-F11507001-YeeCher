# Lab 0
## Installation
I went to the official Wireshark website (https://www.wireshark.org/#download) and downloaded the Windows 64bit installation. I followed the instructions of the setup wizard and successfully installed Wireshark. 
<img width="986" height="764" alt="image" src="https://github.com/user-attachments/assets/333c699e-c67e-4efb-b011-593efca3e6d1" />

## 1. Website Packet Capture
Which website did you access?
- Minecraft (https://www.minecraft.net/en-us)

<img width="2552" height="1382" alt="image" src="https://github.com/user-attachments/assets/93eaee8a-5f6e-4bdf-8019-43f583507321" />
What are the IP address and port number of the website server?
- IP address: 60.199.191.70 port number: 443

What are the IP address and source port number of your PC when initially accessing the website?
- IP address: 192.168.0.154 , port number: 64115

What is the process of the TCP three-way handshake?
1) The computer requests for a connection and sends a starting sequence number SYN. 
2) The server acknowledges the sequence number with an ACK and sends its own sequence number SYN. 
3) The computer then acknowledges the server's sequence number with an ACK.
<img width="2546" height="1410" alt="image" src="https://github.com/user-attachments/assets/35785d10-d236-494f-a21a-630c6138af1a" />
<img width="2558" height="1444" alt="image" src="https://github.com/user-attachments/assets/6dbe7062-907c-4997-bf4e-1c2c570a4d1d" />
<img width="2530" height="1350" alt="image" src="https://github.com/user-attachments/assets/ee785bb1-fa02-4ba6-97f9-bbf11227c194" />

## 2. DNS Packet Analysis
What are the IP address and port number of the DNS server?
IP address: 2001:4546:2::1 , port number: 53
<img width="2550" height="1360" alt="image" src="https://github.com/user-attachments/assets/5c529dff-8f3e-4ebe-87a1-6e0698df688b" />

What is the domain name in the DNS query?
www.minecraft.net

Which protocols does this DNS packet use? List the protocols from Layer 2 to Layer 5 in the TCP/IP five-layer model:
Layer 2: Ethernet II
Layer 3: Internet Protocol Version 6 (IPv6)
Layer 4: Transmission Datagram Protocol
Layer 5: Domain Name System (DNS)
<img width="2550" height="1358" alt="image" src="https://github.com/user-attachments/assets/ed33542d-ade3-4367-8612-6ba5b78edf3d" />
