# 📘 Task 2 – Static Routing and DHCP Configuration

## 🎯 Objective
The objective of this task is to configure **static routing** between multiple routers and implement **DHCP (Dynamic Host Configuration Protocol)** to automatically assign IP addresses to end devices using Cisco Packet Tracer.

---

## 📝 Task Description
In this task, a network topology consisting of three routers, three switches, and multiple PCs is created.  
Each router is connected to its own LAN and also connected to other routers through separate networks.  
Static routing is configured to enable communication between all LAN networks, and DHCP is configured on each router to dynamically assign IP addresses to the connected PCs.

---

## 🖧 Network Components
- **Routers:** 3 (ISR series)
- **Switches:** 3 (Cisco 2960)
- **PCs:** 6
- **Cables:** Copper straight-through
- **Simulation Tool:** Cisco Packet Tracer

---

## 🌐 IP Addressing Scheme

### Inter-Router Networks
| Network | Description |
|--------|------------|
| 10.0.0.0/24 | Router1 ↔ Router0 |
| 20.0.0.0/24 | Router0 ↔ Router4 |
| 30.0.0.0/24 | Router1 ↔ Router4 |

### LAN Networks
| Router | LAN Network | Gateway |
|-------|-------------|---------|
| Router1 | 40.0.0.0/24 | 40.0.0.10 |
| Router0 | 50.0.0.0/24 | 50.0.0.10 |
| Router4 | 60.0.0.0/24 | 60.0.0.10 |

---

## 🔁 Routing Technique
- **Static Routing**
- Routes are manually configured on each router to reach remote LAN networks.

---

## 📡 DHCP Configuration
- Each router is configured as a **DHCP server** for its respective LAN.
- DHCP pools are created with:
  - Network address
  - Default gateway
  - DNS server
- IP addresses are automatically assigned to PCs.

---

## 🧪 Verification
The following confirms successful configuration:
- Routing table verification using:
- Successful **ping** between PCs in different LANs.

---

## ✅ Result
All PCs successfully obtained IP addresses dynamically through DHCP, and communication between different networks was achieved using static routing.

---

## 🧾 Conclusion
This task demonstrates the configuration of static routing and DHCP in a multi-router network environment. It helps in understanding basic routing concepts and dynamic IP address allocation.

---

## 🛠 Software Used
- Cisco Packet Tracer

---

## 📌 Task Number
**Task 2**

---

## 👨‍🎓 Student Details
- **Name:** Vishal A
- **Department:** BE – Cyber Security
- **Institution:** Mahendra Engineering College
