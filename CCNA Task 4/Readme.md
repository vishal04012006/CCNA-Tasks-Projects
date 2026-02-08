# Task 4 – Spanning Tree Protocol (STP) and VLAN Trunking Protocol (VTP)

## 📌 Overview
This repository contains **Task 4** of my Cisco Packet Tracer networking practice labs.  
In this task, I focused on **Layer 2 switching concepts** by implementing and verifying:

- **Spanning Tree Protocol (STP)**
- **VLAN Trunking Protocol (VTP)**

The main purpose of this task is to understand how enterprise networks prevent switching loops and manage VLANs efficiently across multiple switches.

The lab was designed, configured, and tested using **Cisco Packet Tracer 8.2.2**.

---

## 🎯 Objectives
The objectives of Task 4 are:

- To understand Layer 2 loop problems in switched networks
- To implement **STP** for loop prevention
- To analyze **Root Bridge election** and port states
- To configure **VTP Server, Client, and Transparent modes**
- To observe automatic VLAN propagation using VTP

---

## 🧪 Lab Description

### 🔹 Part 1: Spanning Tree Protocol (STP)

In this part of the task, multiple switches were connected with **redundant links**, which can cause Layer 2 loops and broadcast storms. To overcome this issue, **Spanning Tree Protocol (STP)** was implemented.

STP was used to:
- Elect a **Root Bridge**
- Calculate the best path to the root
- Block redundant links to maintain a loop-free topology

A specific switch was intentionally selected as the Root Bridge to control the network topology. After STP convergence, different **port roles and states** were observed, such as forwarding and blocking ports. This demonstrated how STP dynamically adapts to network topology changes.

---

### 🔹 Part 2: VLAN Trunking Protocol (VTP)

In the second part of the task, **VLAN Trunking Protocol (VTP)** was implemented to manage VLANs across multiple switches.

One switch was configured as a **VTP Server**, where VLANs were created and maintained. Other switches were configured as **VTP Clients**, which automatically received VLAN information from the server. Some switches were also configured in **VTP Transparent mode** to observe how they forward VTP advertisements without updating their VLAN database.

This setup helped in understanding how VTP simplifies VLAN administration in large-scale networks by reducing manual configuration on every switch.

---

## 🛠 Tools Used
- Cisco Packet Tracer 8.2.2
- Cisco 2960 Layer 2 Switches
- End devices (PCs)
- Trunk and access links

---

## ✅ Results
- STP successfully prevented Layer 2 loops
- One switch was elected as the Root Bridge
- Redundant links were placed in blocking state
- VLANs created on the VTP Server were propagated to VTP Clients
- Network stability and centralized VLAN management were achieved

---

## 📂 Files Included
- Packet Tracer file containing STP and VTP configurations
- Screenshots showing:
  - STP Root Bridge election
  - Port blocking and forwarding states
  - VTP domain configuration and VLAN propagation

---

## 📚 Learning Outcomes
Through Task 4, I gained:

- Practical understanding of **Layer 2 loop prevention**
- Knowledge of **STP topology control**
- Experience with **VTP-based VLAN management**
- Hands-on exposure to enterprise switching concepts
- Improved troubleshooting and verification skills

---

## 🚀 Future Enhancements
- Implementation of Rapid PVST+
- Multiple Spanning Tree (MST) configuration
- VTP pruning
- Integration of STP with EtherChannel

---

## 👤 Author
**[Vishal A]**  
