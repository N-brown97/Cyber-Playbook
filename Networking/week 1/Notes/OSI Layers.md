# 🧠 OSI Model Reference Guide

**Course:** NET-1111 – Introduction to Networks  
**Focus:** Understanding the 7 Layers of the OSI Model and their real-world functions

---

## 🧩 OSI Model Overview

| **Layer #** | **Layer Name** | **Primary Function** | **Key Protocols / Technologies** | **Example Devices** | **Notes** |
|--------------|----------------|-----------------------|----------------------------------|---------------------|------------|
| **7** | **Application** | Provides user interfaces and network services directly to applications. | HTTP, HTTPS, FTP, DNS, SMTP, POP3, IMAP | Web browser, Email client, Web server | Closest to the end user. Determines how software communicates over the network. |
| **6** | **Presentation** | Formats and encrypts data for the Application layer; ensures compatibility between systems. | SSL/TLS, JPEG, MPEG, ASCII, EBCDIC | Application gateways | Handles encryption, compression, and data translation. |
| **5** | **Session** | Establishes, manages, and terminates sessions between applications. | NetBIOS, RPC, PPTP | Gateways, API handlers | Manages conversations between applications (start, stop, sync). |
| **4** | **Transport** | Provides reliable or unreliable delivery and error recovery using TCP or UDP. | TCP, UDP, TLS | Firewalls, Load balancers | Responsible for segmentation, sequencing, and port numbers. |
| **3** | **Network** | Handles logical addressing, routing, and path determination. | IP, ICMP, ARP, RIP, OSPF | Routers, Layer 3 switches | Determines best path for data; responsible for IP addressing. |
| **2** | **Data Link** | Handles framing, MAC addressing, and error detection on the local network. | Ethernet, PPP, Frame Relay, VLANs | Switches, Bridges, NICs | Defines how data is formatted for transmission over a physical medium. |
| **1** | **Physical** | Transmits raw bits over a physical medium (electrical or optical). | Cables, Hubs, Repeaters | Ethernet cables, Fiber optics, Hubs | Defines hardware specs like voltage, pinouts, and data rates. |

---

## 🧠 Mnemonics to Remember the Layers

**Bottom-Up (Layer 1 → 7):**  
> “**Please Do Not Throw Sausage Pizza Away**”

---

## ⚙️ Common Exam Associations

| **Exam Question Type** | **Hint / Layer Connection** |
|--------------------------|-----------------------------|
| Port numbers (80, 443, 53, 67/68) | Layer 4 – Transport |
| IP addressing / routing | Layer 3 – Network |
| MAC addressing / switching | Layer 2 – Data Link |
| Physical cables, connectors | Layer 1 – Physical |
| Encryption / compression | Layer 6 – Presentation |
| HTTP / DNS / SMTP activity | Layer 7 – Application |
| Session setup / teardown | Layer 5 – Session |

---

**TCP**:Transmission Control Protocol- A reliable connection oriented protocol that ensurse all data packets are recieved in the correct order.
**UDP**:User Datagram Protocol- A faster connectionless protocol that priorities speed over gauranteed delivery.


