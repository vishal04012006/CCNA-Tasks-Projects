# CCNA-Tasks-Projects
Hands-on CCNA labs and projects with real-world networking scenarios using Cisco Packet Tracer.
# CCNA Tasks & Projects 🌐

## 📘 About
This repository contains **hands-on CCNA lab tasks and mini projects** created using **Cisco Packet Tracer**.  
The objective is to practice and demonstrate core **networking concepts** required for the **CCNA (200-301)** certification.

---

## 🧪 Project: VLAN & Inter-VLAN Routing with Remote Management

### 🔧 Concepts Covered
- VLAN creation and management  
- Inter-VLAN routing (Router-on-a-Stick)  
- Trunking using IEEE 802.1Q  
- Port Security  
- **SSH and Telnet configuration**  
- Network verification and troubleshooting  

---

## 🗂️ VLAN Details

| VLAN ID | Name | Network |
|------|------|---------|
| 10 | HR | 10.1.1.0/24 |
| 20 | IT | 10.1.2.0/24 |
| 30 | Interns | 10.1.3.0/24 |

---

## 🌐 Inter-VLAN Routing
- Implemented using **Router-on-a-Stick**
- Router configured with **sub-interfaces**
- Switch-to-router link configured as **trunk**
- Each VLAN uses a **separate IP subnet**

---

## 🔐 Security & Remote Access

### 🔒 Port Security
- Enabled on access ports
- Maximum MAC address limit configured
- Sticky MAC address learning
- Violation mode set to **shutdown**

### 🔑 SSH & Telnet
- Remote access enabled on **router and switches**
- Local user authentication configured
- RSA keys generated for SSH
- SSH version 2 enabled
- Telnet enabled for learning and testing purposes

---

## 🧪 Verification Commands
```bash
show vlan brief
show interfaces trunk
show ip interface brief
show ip route
show port-security
show ip ssh
