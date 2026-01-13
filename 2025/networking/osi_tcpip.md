# OSI & TCP/IP Models – Networking Basics

In this task, I learned about the OSI and TCP/IP models to understand how data travels from one computer to another over a network.

These models help us understand where and how communication happens when we use the internet.

---

## OSI Model (7 Layers)

| Layer | What it does | Example |
|------|-------------|--------|
| Application | Where user applications work | Web browser, email, file transfer |
| Presentation | Formats and encrypts data | HTTPS, data encoding |
| Session | Manages communication sessions | Keeping a login or connection active |
| Transport | Transfers data reliably | TCP for web pages, UDP for streaming |
| Network | Routes data between computers | IP addresses, routing |
| Data Link | Communication inside a local network | MAC address, switches |
| Physical | Actual hardware | Cables, WiFi, network cards |

---

## TCP/IP Model

| TCP/IP Layer | What it includes | Example |
|-------------|-----------------|---------|
| Application | User level protocols | HTTP, HTTPS, FTP, DNS |
| Transport | Data delivery | TCP, UDP |
| Internet | IP addressing and routing | IP, routers |
| Network Access | Hardware and local network | Ethernet, WiFi |

---

## How OSI and TCP/IP work in real life

When we open a website:

1. The browser sends a request (Application layer)  
2. Data is formatted and encrypted (Presentation layer)  
3. A session is created (Session layer)  
4. Data is sent using TCP or UDP (Transport layer)  
5. IP routes it to the destination (Network layer)  
6. Local network sends it to the right machine (Data Link layer)  
7. Physical cables or WiFi carry the data (Physical layer)

---

## Why this is important

OSI and TCP/IP models help us understand where a problem is when something is not working on the network.  
They make troubleshooting easier and networking more logical.
