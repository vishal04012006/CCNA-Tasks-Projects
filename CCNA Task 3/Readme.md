# Task 3 – Dynamic Routing Configuration (OSPF, EIGRP, RIP)

## 📌 Overview
This repository contains **Task 3** of my Cisco Packet Tracer practice labs.  
In this task, I designed and configured **dynamic routing protocols separately** using:

- **OSPF (Open Shortest Path First)**
- **EIGRP (Enhanced Interior Gateway Routing Protocol)**
- **RIP (Routing Information Protocol)**

Each routing protocol is implemented in an **independent topology** to clearly understand its working, configuration, and behavior.

The lab was created and tested using **Cisco Packet Tracer 8.2.2**.

---

## 🎯 Objective
The main objectives of this task are:

- To understand how different dynamic routing protocols work
- To configure **OSPF, EIGRP, and RIP separately**
- To verify routing using **end-to-end connectivity (ICMP ping)**
- To compare routing behavior across protocols

---

## 🧪 Lab Details

### 🔹 1. OSPF Configuration (Separate Topology)
- Used **OSPF single-area (Area 1)**
- Configured OSPF on multiple routers
- Advertised LAN and WAN networks using `network` commands
- Verified:
  - OSPF neighbor adjacency
  - Routing table entries
  - Successful ping between PCs in different networks

**Routing Protocol:** OSPF  
**Verification:** `show ip route`, `show ip ospf neighbor`, `ping`

---

### 🔹 2. EIGRP Configuration (Separate Topology)
- Implemented **EIGRP (Autonomous System based)**
- Configured EIGRP on all routers in the topology
- Advertised connected networks
- Ensured loop-free routing using EIGRP’s DUAL algorithm
- Verified routing and connectivity

**Routing Protocol:** EIGRP  
**Verification:** `show ip route`, `show ip eigrp neighbors`, `ping`

---

### 🔹 3. RIP Configuration (Separate Topology)
- Configured **RIP Version 2**
- Enabled classless routing using `version 2`
- Disabled auto-summary
- Advertised all connected networks
- Verified routing convergence and connectivity

**Routing Protocol:** RIP v2  
**Verification:** `show ip route`, `show ip protocols`, `ping`

---

## 🛠 Tools Used
- **Cisco Packet Tracer 8.2.2**
- Routers (ISR series)
- 2960 Switches
- End devices (PCs)

---

## ✅ Results
- All three routing protocols were configured successfully
- End-to-end communication was achieved in all topologies
- Routing tables updated dynamically without static routes
- ICMP tests confirmed successful network connectivity

---

## 📂 Files Included
- `.pkt` files for:
  - OSPF topology
  - EIGRP topology
  - RIP topology
- Screenshots of successful ping and routing verification

---

## 📚 Learning Outcomes
- Clear understanding of **dynamic routing concepts**
- Practical experience with **OSPF, EIGRP, and RIP**
- Improved troubleshooting and verification skills
- Hands-on exposure to real CCNA-level networking labs

---

## 🚀 Future Improvements
- Route redistribution between OSPF, EIGRP, and RIP
- Multi-area OSPF configuration
- Performance comparison between routing protocols

---

## 👨‍🎓 Student Details
- **Name:** Vishal A
- **Department:** BE – Cyber Security
- **Institution:** Mahendra Engineering College
