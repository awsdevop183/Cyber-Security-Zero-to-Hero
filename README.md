# Cyber Security: Zero to Hero

My study notes from learning cyber security, starting with the basics. The notes cover Linux, networking, and web applications, which are the fundamentals you need before moving on to penetration testing.

The repo grows as I go. Notes are short and practical, with commands and examples I have tried myself.

## What's inside

| File | Topics |
|------|--------|
| [notes.txt](notes.txt) | Linux basics and networking fundamentals |
| [network protocols](network%20protocols) | Protocols, ports, URLs, IP addressing, firewalls, OSI and TCP/IP models, web app basics, HTTP methods and status codes |
| [client-server.png](client-server.png) | Diagram of the client–server model |
| [OSI vulnerabilties.png](OSI%20vulnerabilties.png) | Common attacks and vulnerabilities at each OSI layer |

## Topics covered

### 1. Linux basics
- Users and groups: `useradd`, `adduser`, deleting and modifying users
- Regular users, system users (UID < 1000) and root (UID 0)
- The principle of least privilege
- File permissions: `rwx`, octal notation (4/2/1), `chmod`
- The Linux file system layout (`/etc`, `/var`, `/home`, `/tmp`, `/proc`, ...)
- Text processing with `cut`, `awk` and `sed`
- Archiving with `zip` and `tar`
- Package managers: `apt`/`dpkg` (Debian, Kali, Ubuntu) and `yum`/`dnf`/`rpm` (CentOS, RHEL, Amazon Linux)

### 2. Networking fundamentals
- Network types: PAN, LAN, MAN, WAN
- Topologies: bus, star, ring, mesh, tree, hybrid
- Devices: NIC, hub (L1), switch (L2), router, modem
- MAC addresses

### 3. Network protocols
- TCP vs UDP and when to use each
- Common protocols and ports:

  | Protocol | Port |
  |----------|------|
  | FTP | 20, 21 |
  | SSH | 22 |
  | DNS | 53 |
  | HTTP | 80 |
  | HTTPS | 443 |
  | MySQL | 3306 |
  | RDP | 3389 |

- Also covered: ARP, IP, ICMP, SMB, DHCP
- How a URL is built: protocol, subdomain, second-level domain, TLD, path, query parameters
- IPv4 vs IPv6, and public vs private IPs
- Software and hardware firewalls

### 4. OSI and TCP/IP models
- The 7 OSI layers and what each one does
- Encapsulation and decapsulation
- How the OSI layers map to the 4 TCP/IP layers
- A walkthrough of what each layer does when you open a website

### 5. Web application basics
- A website vs a web application
- Frontend (HTML, CSS, JavaScript), backend (Node.js, Python, Java, Ruby) and databases (MySQL, PostgreSQL, MongoDB)
- HTTP methods: GET, POST, PUT, DELETE
- HTTP status code ranges (1xx to 5xx)
- Lab setup for web app pentesting: Metasploitable 3 and a Windows 7/10 VM

## Roadmap

- [x] Linux basics
- [x] Networking fundamentals
- [x] Network protocols
- [x] OSI and TCP/IP models
- [x] Web application and HTTP basics
- [ ] Web application penetration testing
- [ ] More topics as I learn them

## Disclaimer

These notes are for learning only. Only test systems you own or have written permission to test.
