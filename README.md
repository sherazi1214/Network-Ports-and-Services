# Network-Ports-and-Services

## What Are Network Ports?
A network port is a virtual point where network connections start and end. Ports allow a computer to distinguish between different types of traffic — like web browsing, email, or file transfer — even if it’s all happening over the same network.

### How Ports Work:
When data arrives at a device (like a PC or server), it uses the IP address to reach the device and a port number to reach the correct application or service.

Port numbers range from 0 to 65535.

0–1023: Well-known ports (used by core protocols)

1024–49151: Registered ports (assigned to user processes/applications)

49152–65535: Dynamic/private ports (used temporarily)

### Port Number Format Example:
When you connect to a website, your system may use:

IP address: 192.168.1.10

Port: 443 (for HTTPS)

Resulting in a destination like: 192.168.1.10:443

![Port](https://tse4.mm.bing.net/th?id=OIP.7Z81ZRVmjiJdxm4QR42quwHaEH&pid=Api&P=0&h=220)

# TCP vs UDP Ports:

TCP------------------	Connection-based, reliable, error-checked -----------------	Email, Web Browsing, File Transfer

UDP------------------	Connectionless, fast, no guarantee of delivery---------------	Video streaming, DNS, VoIP

## Why Ports Are Important:
Enable Multiple Services: A server can run a website (HTTP on port 80) and a mail server (SMTP on port 25) simultaneously.

Network Security: Firewalls and intrusion prevention systems use ports to allow or block specific traffic.

Troubleshooting: Knowing ports helps identify issues (e.g., blocked port 443 means HTTPS isn’t working).




