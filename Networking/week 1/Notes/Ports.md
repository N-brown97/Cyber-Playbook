# 🧠 Common Networking Ports & Protocols

| **Port** | **Protocol / Service** | **Transport** | **Purpose / Description** |
|-----------|-----------------------|----------------|----------------------------|
| **🌐 Web & Internet Services** |  |  |  |
| 80 | HTTP (Hypertext Transfer Protocol) | TCP | Standard web traffic (unencrypted) |
| 443 | HTTPS (HTTP Secure) | TCP | Encrypted web traffic via SSL/TLS |
| **📂 File Transfer** |  |  |  |
| 20 / 21 | FTP (File Transfer Protocol) | TCP | Transfers files (20 = data, 21 = control) |
| 22 | SFTP / SSH | TCP | Secure file transfer & remote login |
| 69 | TFTP (Trivial File Transfer Protocol) | UDP | Simple file transfer, often for boot images |
| 445 | SMB (Server Message Block) | TCP | File & printer sharing over Windows networks |
| **✉️ Email Protocols** |  |  |  |
| 25 | SMTP (Simple Mail Transfer Protocol) | TCP | Sends outgoing email |
| 110 | POP3 (Post Office Protocol v3) | TCP | Downloads email from server |
| 143 | IMAP (Internet Message Access Protocol) | TCP | Accesses and manages email on server |
| **🧭 Network Services** |  |  |  |
| 53 | DNS (Domain Name System) | UDP / TCP | Resolves domain names to IP addresses |
| 67 / 68 | DHCP (Dynamic Host Configuration Protocol) | UDP | Automatically assigns IP addresses to clients |
| **🖥️ Remote Access** |  |  |  |
| 23 | Telnet | TCP | Unencrypted remote CLI access (legacy) |
| 22 | SSH (Secure Shell) | TCP | Secure remote command-line access |
| 3389 | RDP (Remote Desktop Protocol) | TCP | Remote access to Windows desktops (GUI) |
| **🛠️ Network Management** |  |  |  |
| 161 / 162 | SNMP (Simple Network Management Protocol) | UDP | Monitors and manages network devices |
| 514 | Syslog | UDP | Sends event messages to log servers |
| 389 | LDAP (Lightweight Directory Access Protocol) | TCP / UDP | Accesses directory services (e.g., Active Directory) |


