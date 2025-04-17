# Module 1: Introduction
## 📡 Chapter 1: Understanding Computer Networks – The Basics

### 💡 What is a Computer Network?

A **computer network** is a group of devices (like laptops, phones, or servers) that are **connected together** to **share resources or data**.

If you've ever streamed a video, sent an email, or downloaded a file—you were using a network!

---

### 🤔 Why Do We Use Networks?

Before modern networks, we used **CDs**, **floppy disks**, or **USB drives** to transfer files. That works if you're in the same room—but it's not ideal across long distances.

With networks, we can instantly share:

- 📁 Files (photos, documents, etc.)
- 📹 Videos and music
- 🌐 Internet access
- 📧 Email and messaging
- 🧠 Applications and services

---

### 🖥️ Devices on a Network: Nodes & Hosts

| Term  | Meaning                                                                 |
|-------|-------------------------------------------------------------------------|
| **Node** | Any device connected to the network (e.g., phone, computer, switch).    |
| **Host** | A node that can send or receive data (e.g., your phone or laptop).      |

---

### 🔄 The Client-Server Model

Most modern networks use the **Client-Server** architecture:

- **Server** – Shares or stores resources.
- **Client** – Requests and uses those resources.

> Example:  
> Your **phone** is the client.  
> **YouTube's servers** send videos to your device.

A device can be **both** a client and server (e.g., when hosting a shared folder over the network while browsing the web).

---

### 🔌 How Do Devices Connect?

Devices connect to networks in several ways:

- 🧵 **Wired (Ethernet)** – Copper (Cat5, Cat6) or fiber optic cables.
- 📶 **Wireless** – Wi-Fi or Bluetooth.
- 🛰️ **Satellite** – e.g., Starlink for remote access.

Even **two devices** (like two laptops or phones) can form a simple network.

---

### 🌍 Identifying Devices: IP Address & MAC Address

Every device has two key identifiers:

#### 🔹 MAC Address
- Hardware address burned into the **Network Interface Card (NIC)**.
- Unique per network interface on a device.
- Format: `00:1A:2B:3C:4D:5E`

#### 🔹 IP Address
- Logical address for communication.
- Format (IPv4): `192.168.0.101`
- Assigned by router using **DHCP (Dynamic Host Configuration Protocol)**

---

### 📡 What is a Protocol?

A **protocol** is like a language that devices use to talk to each other.

| Protocol | Purpose                              |
|----------|---------------------------------------|
| **IP**   | Delivers packets of data              |
| **HTTP** | Displays web pages                    |
| **HTTPS**| Secure version of HTTP                |
| **DNS**  | Translates website names to IPs       |
| **FTP**  | File transfer between devices         |

Just like people use English or Spanish, computers use **protocols**.

---

### 🔢 What Are Port Numbers?

Ports are like numbered **doors** on a device that services use to communicate.

| Port | Service            |
|------|--------------------|
| 80   | HTTP               |
| 443  | HTTPS (Secure Web) |
| 32400| Custom (e.g., Plex)|

To connect to a service, the client must use the correct **IP address + port number**.

---

### 💻 What is a Network Interface Card (NIC)?

A **NIC** is the hardware that lets a device connect to a network.

Types:
- 🌐 Ethernet NICs (Wired)
- 📶 Wireless NICs (Wi-Fi, USB Adapters)
- 🔌 Fiber NICs (SFP ports for high-speed)

Each NIC has a **MAC address** that identifies it on the network.

---

### 🕸️ Types of Networks

| Type | Description                              |
|------|------------------------------------------|
| **LAN**  | Local Area Network (Home, Office)         |
| **WAN**  | Wide Area Network (Cities, Countries)     |
| **Internet** | Global network of interconnected systems |

---

### ✅ Summary

✔ A **computer network** connects devices to share resources  
✔ Devices are identified using **MAC addresses** and **IP addresses**  
✔ Communication happens via **protocols** and **port numbers**  
✔ A **NIC** connects your device to the network  
✔ Networks can be **tiny (2 devices)** or **huge (the Internet)**

---

> 🔜 **Next Chapter**: Dive into **network topologies** and how data moves from point A to B!

---
