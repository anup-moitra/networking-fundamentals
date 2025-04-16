# **Module 1: Introduction to Computer Networking**  

*(Placeholder: Hero image of connected devices – laptops, servers, routers, cables)*  

## **Chapter 1: Fundamentals of Computer Networks**  

### **1.1 What is a Computer Network?**  
A system where devices (**nodes**) communicate to:  
- **Share resources**: Files, printers, internet.  
- **Enable services**: Video calls, cloud storage.  

**Key Idea**:  
> "Networks eliminate the need for physical transfers (like USB drives) by enabling instant digital communication."  

---

### **1.2 Core Components**  

#### **1. Devices**  
- **End Devices**: Smartphones, laptops, IoT devices *(Placeholder: Collage of devices)*.  
- **Infrastructure**: Routers, switches, access points.  

#### **2. Network Interface Cards (NICs)**  
- **Types**:  
  - Wired (Ethernet, fiber).  
  - Wireless (Wi-Fi, Bluetooth).  
*(Placeholder: Labeled NIC diagram)*  

#### **3. Communication Media**  
| Type       | Speed       | Use Case          |  
|------------|-------------|-------------------|  
| Ethernet   | 1 Gbps      | Home/Office       |  
| Wi-Fi 6    | 9.6 Gbps    | Wireless networks |  
| Fiber      | 100+ Gbps   | Data centers      |  

#### **4. Protocols**  
- **IP**: Device addressing (`192.168.1.1`).  
- **DNS**: Converts `google.com` → IP.  
- **HTTP/HTTPS**: Web traffic (ports `80/443`).  

---

### **1.3 How Networks Operate: Client-Server Model**  

*(Placeholder: Flowchart – Client → Internet → Server)*  

**Example**: Streaming a video:  
1. **Client** (your phone) requests data.  
2. **Server** (YouTube) sends video packets.  

**Critical Detail**:  
> "Ports act like service doors – `443` for HTTPS, `32400` for Plex."  

---

### **1.4 Addressing Simplified**  

#### **IP Addresses**  
- **IPv4**: `192.168.1.1` (local), `8.8.8.8` (Google DNS).  
- **IPv6**: Handles more devices (e.g., `2001:db8::1`).  

#### **MAC Addresses**  
- Hardware ID (e.g., `00:1A:2B:3C:4D:5E`).  
- **Pro Tip**: Phones randomize MACs for privacy.  

---

### **1.5 Network Types at a Glance**  

*(Placeholder: Venn diagram – LAN, WAN, Internet)*  

| Type | Scope          | Example               |  
|------|----------------|-----------------------|  
| LAN  | Single location | Home Wi-Fi           |  
| WAN  | Multiple sites  | Corporate VPN         |  

---

### **1.6 Practical Exercises**  

**1. Find Your Network Info**:  
```bash
# Windows: 
ipconfig /all  
# Mac/Linux: 
ifconfig
```  
*(Placeholder: Terminal output screenshot)*  

**2. Test a Port**:  
```bash
telnet google.com 443  # Checks HTTPS accessibility
```  

---
