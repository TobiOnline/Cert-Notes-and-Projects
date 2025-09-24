# Networking Concepts

## Key Topics
- OSI Model
- TCP/IP Protocols
- IP Addressing (IPv4/IPv6)

## Notes: OSI Model

### Overview
The OSI (Open Systems Interconnection) Model is a 7-layer framework to understand how networks operate. Each layer handles a specific function.

### Layers
Mnemonic: "Please Do Not Throw Sausage Pizza Away"

| Layer | Name          | Function                              | Examples                     |
|-------|---------------|---------------------------------------|------------------------------|
| 7     | Application   | User interface, services             | Browsers, SMTP, FTP          |
| 6     | Presentation  | Data formatting, encryption          | SSL/TLS, JPEG, ASCII         |
| 5     | Session       | Manages sessions/connections         | NetBIOS, RPC                 |
| 4     | Transport     | Reliable data transfer, error correction | TCP, UDP                  |
| 3     | Network       | Routing, IP addressing               | IP, ICMP, routers            |
| 2     | Data Link     | Physical addressing, error detection | Ethernet, MAC addresses, switches |
| 1     | Physical      | Hardware, cables, signals            | Cables, hubs, NICs           |

### Key Points
- Data flows down from Layer 7 to 1 (encapsulation) when sending, up from 1 to 7 (decapsulation) when receiving.
- Layers 1-2: Hardware-focused (e.g., cables, switches).
- Layers 3-4: Handle routing and reliable delivery (e.g., IP, TCP).
- Layers 5-7: Software-focused (e.g., apps, encryption).

### Study Tip
Visualize data flow with diagrams (e.g., draw a packet moving through layers). Check Professor Messer’s video: [OSI Model Explained](https://www.youtube.com).

## Practice Questions
**Question**: Which OSI layer is responsible for logical addressing and routing?  
**Answer**: Network Layer (Layer 3).  
**Explanation**: Uses IP addresses to route packets between networks (e.g., routers operate here).

## Resources
- [Professor Messer Network+ Videos](https://www.youtube.com/playlist)
- [CompTIA Network+ Objectives](https://www.comptia.org) (Official PDF)

## Last Updated
September 24, 2025
