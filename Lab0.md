# Lab 0
## Installation
I went to the official Wireshark website (https://www.wireshark.org/#download) and downloaded the Windows 64bit installation. I followed the instructions of the setup wizard and successfully installed Wireshark. 
<img width="986" height="764" alt="image" src="https://github.com/user-attachments/assets/333c699e-c67e-4efb-b011-593efca3e6d1" />

## 1. Website Packet Capture
Which website did you access?
- Minecraft (https://www.minecraft.net/en-us)

### What are the IP address and port number of the website server?
<img width="2552" height="1382" alt="image" src="https://github.com/user-attachments/assets/93eaee8a-5f6e-4bdf-8019-43f583507321" />
- IP address: 60.199.191.70 port number: 443

### What are the IP address and source port number of your PC when initially accessing the website?
- IP address: 192.168.0.154 , port number: 64115

### What is the process of the TCP three-way handshake?
<img width="2546" height="1410" alt="image" src="https://github.com/user-attachments/assets/35785d10-d236-494f-a21a-630c6138af1a" />
1) The computer requests for a connection and sends a starting sequence number SYN.

<img width="2558" height="1444" alt="image" src="https://github.com/user-attachments/assets/6dbe7062-907c-4997-bf4e-1c2c570a4d1d" />
2) The server acknowledges the sequence number with an ACK and sends its own sequence number SYN. 

<img width="2530" height="1350" alt="image" src="https://github.com/user-attachments/assets/ee785bb1-fa02-4ba6-97f9-bbf11227c194" />
3) The computer then acknowledges the server's sequence number with an ACK.

## 2. DNS Packet Analysis
What are the IP address and port number of the DNS server?
<img width="2550" height="1360" alt="image" src="https://github.com/user-attachments/assets/5c529dff-8f3e-4ebe-87a1-6e0698df688b" />
- IP address: 2001:4546:2::1 , port number: 53

### What is the domain name in the DNS query?
- www.minecraft.net

### Which protocols does this DNS packet use? List the protocols from Layer 2 to Layer 5 in the TCP/IP five-layer model:
Layer 2: Ethernet II
Layer 3: Internet Protocol Version 6 (IPv6)
Layer 4: Transmission Control Protocol
Layer 5: Domain Name System (DNS)
<img width="2550" height="1358" alt="image" src="https://github.com/user-attachments/assets/ed33542d-ade3-4367-8612-6ba5b78edf3d" />

## 3. Access an HTTP page
Which HTTP page did you access?
- http://httpforever.com

### What are the IP address and port number of the server hosting the page?
<img width="2560" height="1352" alt="image" src="https://github.com/user-attachments/assets/08055eec-096f-43e5-be91-cb55df39c828" />
- IP address: 2606:4700:3031::6815:4d2 , port number: 80

### What is the HTTP request method?
<img width="2552" height="1354" alt="image" src="https://github.com/user-attachments/assets/845261da-f12a-4f55-ac58-539e9a8977dc" />
- GET

### What is the HTTP response status code, and what does it mean?
<img width="2544" height="1350" alt="image" src="https://github.com/user-attachments/assets/200130ae-f232-4953-a34f-644f4e3df7db" />
- Request is successful and server returns to web page resource. 
