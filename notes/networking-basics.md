# Networking Fundamentals

## Overview

Networking is the foundation of cybersecurity because all systems communicate through networks. Understanding how devices send and receive data helps analysts detect suspicious activity such as unauthorized connections, malicious traffic, or data exfiltration.

---

## Key Networking Concepts

### IP Address

An IP address uniquely identifies a device on a network.

Example:

```
192.168.1.10
```

Types of IP addresses:

- **Public IP** – reachable on the internet
- **Private IP** – used inside internal networks

Common private ranges:

```
10.0.0.0 – 10.255.255.255
172.16.0.0 – 172.31.255.255
192.168.0.0 – 192.168.255.255
```

---

### MAC Address

A MAC address is a unique hardware identifier assigned to a network interface card (NIC).

Example:

```
00:1A:2B:3C:4D:5E
```

MAC addresses are used for communication within a local network.

---

### Ports

Ports allow multiple services to run on the same device by identifying specific processes.

Common ports:

| Port | Protocol | Service |
| --- | --- | --- |
| 80 | HTTP | Web traffic |
| 443 | HTTPS | Secure web traffic |
| 22 | SSH | Secure remote login |
| 53 | DNS | Domain name resolution |
| 25 | SMTP | Email transmission |

Monitoring unusual port activity can indicate malicious behavior.

---

### TCP vs UDP

### TCP (Transmission Control Protocol)

TCP is a **connection-oriented protocol** that ensures reliable data delivery.

Characteristics:

- Reliable
- Ordered data transmission
- Error checking

Example services:

- HTTP
- HTTPS
- SSH

---

### UDP (User Datagram Protocol)

UDP is a **connectionless protocol** that sends data without verifying delivery.

Characteristics:

- Faster than TCP
- No delivery confirmation
- Used for real-time communication

Example services:

- DNS
- Video streaming
- VoIP

---

## DNS (Domain Name System)

DNS translates domain names into IP addresses.

Example:

```
google.com → 142.250.190.14
```

This process allows users to access websites using names instead of numeric addresses.

DNS traffic is often analyzed by security analysts to detect:

- Malicious domains
- Command-and-control servers
- Data exfiltration

---

## Why Networking Matters in Cybersecurity

Security analysts rely on networking knowledge to:

- Analyze packet traffic
- Identify suspicious connections
- Investigate malicious IP addresses
- Detect abnormal network behavior

Tools commonly used for network analysis include:

- Wireshark
- tcpdump

---

## Key Takeaways

- Every device on a network has an **IP address**
- **MAC addresses** identify physical hardware
- **Ports** allow services to communicate
- **TCP and UDP** control how data is transmitted
- **DNS** translates domain names to IP addresses

Understanding these fundamentals is essential for analyzing network traffic and identifying potential security threats.



