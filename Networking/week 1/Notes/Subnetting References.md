# 🧮 IPv4 Subnetting Reference Guide
**Course:** NET-1111 – Introduction to Networks  
**Focus:** Understanding CIDR notation, subnet masks, usable hosts, and example ranges

---

## 📘 Subnet Table (Class C Example)

| **CIDR** | **Subnet Mask** | **# of Subnets (from /24)** | **Block Size (Increment)** | **Usable Hosts / Subnet** | **Example Network ID** | **Example Range (Usable)** | **Broadcast Address** |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| **/24** | 255.255.255.0 | 1 | 256 | 254 | 192.168.1.0 | 192.168.1.1 – 192.168.1.254 | 192.168.1.255 |
| **/25** | 255.255.255.128 | 2 | 128 | 126 | 192.168.1.0 | 192.168.1.1 – 192.168.1.126 | 192.168.1.127 |
|  |  |  |  |  | 192.168.1.128 | 192.168.1.129 – 192.168.1.254 | 192.168.1.255 |
| **/26** | 255.255.255.192 | 4 | 64 | 62 | 192.168.1.0 | 192.168.1.1 – 192.168.1.62 | 192.168.1.63 |
|  |  |  |  |  | 192.168.1.64 | 192.168.1.65 – 192.168.1.126 | 192.168.1.127 |
| **/27** | 255.255.255.224 | 8 | 32 | 30 | 192.168.1.0 | 192.168.1.1 – 192.168.1.30 | 192.168.1.31 |
|  |  |  |  |  | 192.168.1.32 | 192.168.1.33 – 192.168.1.62 | 192.168.1.63 |
| **/28** | 255.255.255.240 | 16 | 16 | 14 | 192.168.1.0 | 192.168.1.1 – 192.168.1.14 | 192.168.1.15 |
|  |  |  |  |  | 192.168.1.16 | 192.168.1.17 – 192.168.1.30 | 192.168.1.31 |
| **/29** | 255.255.255.248 | 32 | 8 | 6 | 192.168.1.0 | 192.168.1.1 – 192.168.1.6 | 192.168.1.7 |
|  |  |  |  |  | 192.168.1.8 | 192.168.1.9 – 192.168.1.14 | 192.168.1.15 |
| **/30** | 255.255.255.252 | 64 | 4 | 2 | 192.168.1.0 | 192.168.1.1 – 192.168.1.2 | 192.168.1.3 |
|  |  |  |  |  | 192.168.1.4 | 192.168.1.5 – 192.168.1.6 | 192.168.1.7 |

---

## 🧠 Key Subnetting Rules

| **Concept** | **Explanation** |
|--------------|----------------|
| **Network ID** | First address in subnet (all host bits = 0) |
| **Broadcast Address** | Last address (all host bits = 1) |
| **Usable Range** | Between network ID + 1 and broadcast − 1 |
| **Block Size** | 256 − last octet of subnet mask (e.g., /26 → 256 − 192 = 64) |
| **Usable Hosts** | 2^(host bits) − 2 (subtract network & broadcast) |
| **Private Ranges** | 10.0.0.0/8 172.16.0.0 – 172.31.255.255/12 192.168.0.0/16 |

---

## 🧮 Practice Tip

> Start with **/24 (255.255.255.0)** and remember each step halves hosts and doubles subnets.  
> Example:  
> /24 → 254 hosts  
> /25 → 126 hosts  
> /26 → 62 hosts  
> /27 → 30 hosts  
> /28 → 14 hosts  
> /29 → 6 hosts  
> /30 → 2 hosts  

---

© 2025 Hocking College | NET-1111 – Introduction to Networks | Subnetting Reference
