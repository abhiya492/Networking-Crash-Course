# Networking-Crash-Course


# 🌐 Complete Computer Networking Crash Course for Interviews (Expanded)


---

## 📘 Table of Contents

1. What is Computer Networking?
2. Types of Networks (LAN, WAN, MAN)
3. IP Address, MAC Address & DNS
4. TCP/IP vs OSI Model
5. HTTP, HTTPS & Web Communication
6. TCP vs UDP
7. Three-Way Handshake (TCP)
8. DNS & URL Resolution
9. REST APIs & Client-Server Model
10. Ports, Firewalls, NAT & DHCP
11. Networking Devices
12. Interview Questions

---

## 1️⃣ What is Computer Networking?

### 📌 Definition:
Computer networking is the process of **interconnecting multiple computing devices** for communication and resource sharing using hardware and software.

### 🧐 Why Networking?
- Share data and files
- Access the internet
- Use printers/storage remotely
- Enable communication across distances

### 💡 Example:
When you play an online game, your device talks to the game server using networking protocols like TCP/UDP.

---

## 2️⃣ Types of Networks

### 🔹 LAN (Local Area Network):
- Small, private network (home, office)
- Fast (Ethernet, Wi-Fi)
- Example: Connecting 4 PCs to one Wi-Fi router

### 🔹 MAN (Metropolitan Area Network):
- Covers a city or campus
- Example: College or city-wide Wi-Fi infrastructure

### 🔹 WAN (Wide Area Network):
- Largest network (covers countries/continents)
- The **Internet** is a global WAN
- Often uses leased telecom lines

---

## 3️⃣ IP Address, MAC Address & DNS

### 🔹 IP Address (Internet Protocol):
- Uniquely identifies each device on a network
- IPv4 (e.g., 192.168.1.1) or IPv6
- Can be static or dynamic

### 🔹 MAC Address (Media Access Control):
- Hardcoded into network card
- Unchangeable (e.g., 00:1B:44:11:3A:B7)
- Used for local device identification

### 🔹 DNS (Domain Name System):
- Translates domain names to IP addresses
- Example: google.com → 142.250.182.46

### 🧠 Analogy:
- IP Address = Your current address
- MAC Address = Your phone’s IMEI
- DNS = Phonebook that maps names to numbers

---

## 4️⃣ TCP/IP vs OSI Model

### 🔹 OSI Model (7 Layers):
1. **Physical** – cables, electrical signals
2. **Data Link** – switches, MAC addresses
3. **Network** – routers, IP
4. **Transport** – TCP/UDP, port numbers
5. **Session** – manage sessions (e.g., Zoom)
6. **Presentation** – encryption, compression
7. **Application** – protocols (HTTP, FTP, SMTP)

### 🔹 TCP/IP Model (4 Layers):
1. Link
2. Internet
3. Transport
4. Application

### 📅 Mnemonic:
"Please Do Not Throw Sausage Pizza Away" (OSI layers)

---

## 5️⃣ HTTP, HTTPS & Web Communication

### 🔹 HTTP:
- Text-based communication protocol
- Used by browsers to fetch web pages
- Stateless (server doesn’t remember previous requests)

### 🔹 HTTPS:
- Secure version of HTTP
- Uses TLS/SSL encryption
- Ensures data integrity and privacy

### 🌟 Example:
When you search on Google, your browser sends a **GET request** via HTTPS to Google servers.

---

## 6️⃣ TCP vs UDP

| Feature       | TCP                         | UDP                          |
|---------------|------------------------------|-------------------------------|
| Connection    | Connection-oriented         | Connectionless                |
| Speed         | Slower                      | Faster                        |
| Reliability   | Guaranteed (ACK, retry)     | No guarantee                  |
| Use cases     | Web, email, file transfer   | Streaming, gaming, VoIP       |

### 💡 Analogy:
- TCP = WhatsApp delivery (blue ticks)
- UDP = Radio broadcast (no feedback)

---

## 7️⃣ TCP Three-Way Handshake

### 🔹 Steps:
1. **SYN**: Client → Server (request connection)
2. **SYN-ACK**: Server → Client (acknowledge)
3. **ACK**: Client → Server (final confirm)

### 🔊 Analogy:
- Like knocking on a door:
  - You: Knock (SYN)
  - Roommate: Who is it? (SYN-ACK)
  - You: It's me (ACK)

---

## 8️⃣ DNS & URL Resolution

### What Happens When You Type `www.google.com`:
1. Browser checks DNS cache
2. If not found → sends DNS query to ISP
3. Gets IP address from DNS server
4. Sends HTTP/HTTPS request to that IP

### 📅 Bonus:
- DNS servers used: Google (8.8.8.8), Cloudflare (1.1.1.1)

---

## 9️⃣ REST APIs & Client-Server Model

### 🔹 REST API Methods:
- **GET**: Read data
- **POST**: Create data
- **PUT**: Update data
- **DELETE**: Remove data

### 🔹 Client-Server:
- Client: sends request (e.g., browser)
- Server: responds with data

### 📅 Real Example:
```http
GET /products/21
```
- Server returns JSON data of product #21

---

## 🔺 Ports, Firewalls, NAT & DHCP

### 🔹 Port:
- Logical endpoint of communication (e.g., 80 for HTTP, 443 for HTTPS)

### 🔹 Firewall:
- Monitors & controls network traffic
- Blocks malicious or unauthorized traffic

### 🔹 NAT:
- Maps multiple private IPs to one public IP
- Used by routers

### 🔹 DHCP:
- Dynamically assigns IP addresses to devices

---

## 🔻 Networking Devices

| Device       | Purpose                                  |
|--------------|-------------------------------------------|
| Router       | Routes data between networks (LAN → WAN) |
| Switch       | Connects devices in a LAN using MAC       |
| Hub          | Broadcasts to all devices (old tech)      |
| Modem        | Converts ISP signal into digital internet |

---

## 📅 Interview Questions (Networking)

### ✅ Theory-Based:
1. TCP vs UDP?
2. HTTP vs HTTPS?
3. Explain 3-way handshake.
4. What is DNS?
5. What is a port?

### ✅ Scenario-Based:
1. Why is UDP used in video streaming?
2. What happens when you type a URL?
3. Explain NAT and firewall roles in home Wi-Fi.

---

## 🏁 Conclusion
You now have a solid understanding of computer networks with real-world analogies. This is perfect for technical interviews and system design discussions.

Let me know if you want:
- Visual diagrams for TCP/IP model
- A summarized cheat sheet PDF
- Mock Q&A for practice

