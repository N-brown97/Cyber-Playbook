# 🌐 TCP/IP Protocol Suite Reference
**Course:** NET-1111 – Introduction to Networks  
**Focus:** Core protocols, ports, and functions within the TCP/IP 4-layer model

---

## 🧩 TCP/IP Model Overview

| **TCP/IP Layer** | **Corresponding OSI Layers** | **Primary Function** | **Common Protocols / Services** |
|------------------|-------------------------------|----------------------|----------------------------------|
| **Application Layer** | OSI Layers 5–7 (Session, Presentation, Application) | Provides user network services and application interfaces | HTTP, HTTPS, FTP, TFTP, SMTP, POP3, IMAP, DNS, DHCP, SNMP, Telnet, SSH, NTP |
| **Transport Layer** | OSI Layer 4 | Responsible for end-to-end delivery, segmentation, and error checking | TCP (reliable), UDP (fast, connectionless) |
| **Internet Layer** | OSI Layer 3 (Network) | Handles logical addressing and routing of packets | IP (IPv4/IPv6), ICMP, ARP, IGMP, NAT |
| **Network Access Layer (Link)** | OSI Layers 1–2 (Physical, Data Link) | Defines hardware addressing, framing, and media access | Ethernet, Wi-Fi (802.11), PPP, Frame Relay, MAC addressing |

---

## 📘 Common Application Layer Protocols

| **Protocol / Service** | **Port(s)** | **Transport Protocol** | **Purpose / Description** |
|--------------------------|--------------|--------------------------|----------------------------|
| **HTTP** | 80 | TCP | Transfers web pages (unencrypted) |
| **HTTPS** | 443 | TCP | Secure web browsing via SSL/TLS |
| **FTP** | 20 / 21 | TCP | File transfer (20 = data, 21 = control) |
| **TFTP** | 69 | UDP | Simple file transfer, no authentication |
| **SMTP** | 25 | TCP | Sends email messages |
| **POP3** | 110 | TCP | Retrieves email from mail server |
| **IMAP** | 143 | TCP | Accesses and manages email on server |
| **DNS** | 53 | TCP / UDP | Resolves domain names to IP addresses |
| **DHCP** | 67 / 68 | UDP | Dynamically assigns IP addresses to hosts |
| **SNMP** | 161 / 162 | UDP | Monitors and manages network devices |
| **Telnet** | 23 | TCP | Remote CLI access (unencrypted) |
| **SSH** | 22 | TCP | Secure remote CLI access |
| **NTP** | 123 | UDP | Synchronizes time between devices |

---

## ⚙️ Transport Layer Protocols

| **Protocol** | **Type** | **Description** | **Common Uses** |
|---------------|-----------|-----------------|----------------|
| **TCP (Transmission Control Protocol)** | Connection-oriented | Reliable delivery with acknowledgments, sequencing, and flow control | Web, Email, File Transfer (HTTP, HTTPS, SMTP, FTP) |
| **UDP (User Datagram Protocol)** | Connectionless | Fast but unreliable; no delivery confirmation | DNS, DHCP, Streaming, VoIP, TFTP |

---

## 🌍 Internet Layer Protocols

| **Protocol** | **Purpose** | **Notes** |
|---------------|-------------|-----------|
| **IP (Internet Protocol)** | Logical addressing and routing | IPv4 uses 32-bit addresses; IPv6 uses 128-bit |
| **ICMP (Internet Control Message Protocol)** | Diagnostics and error messages | Used by `ping` and `tracert` |
| **ARP (Address Resolution Protocol)** | Maps IP addresses to MAC addresses | Works within local networks (Layer 2 ↔ Layer 3) |
| **RARP (Reverse ARP)** | Maps MAC addresses to IP addresses | Legacy, replaced by DHCP |
| **IGMP (Internet Group Management Protocol)** | Manages multicast groups | Used in streaming and group communication |
| **NAT (Network Address Translation)** | Converts private IPs to a single public IP | Used by routers for Internet access |

---

## 🔌 Network Access (Link) Layer Protocols

| **Protocol / Technology** | **Purpose** | **Examples / Notes** |
|----------------------------|--------------|----------------------|
| **Ethernet (IEEE 802.3)** | Defines wired LAN communication | Uses MAC addressing; most common LAN tech |
| **Wi-Fi (IEEE 802.11)** | Wireless LAN communication | Operates at Layer 1–2; WPA2/WPA3 security |
| **PPP (Point-to-Point Protocol)** | Establishes direct connections | Used in serial or VPN links |
| **Frame Relay** | WAN data link technology | Legacy but still referenced in theory |
| **MAC Addressing** | Hardware-level identification | 48-bit address burned into NIC |
| **Physical Media** | Transmission medium | Copper, Fiber, Wireless signals |

---

## 🧠 Study Tips
- Remember: **TCP/IP has 4 layers**, OSI has 7.  
- **TCP = Reliable**, **UDP = Fast**.  
- Know your **ports by heart** — they’re always tested.  
- Understand how **IP, ICMP, and ARP** work together:  
  - IP = Logical routing  
  - ARP = Finds MAC for IP  
  - ICMP = Verifies connectivity (`ping`)

---

© 2025 Hocking College | NET-1111 – Introduction to Networks | TCP/IP Protocol Suite Reference
