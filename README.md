# 🌐 Enterprise Network Infrastructure Design

## 🎯 Project Overview
This project involves the design and implementation of a scalable enterprise network using **Cisco Packet Tracer**. The architecture is designed to support multiple departments (VLANs) with a focus on high availability, dynamic routing, and network security.

## 🚀 Engineering Features
* **VLAN Segmentation:** Created isolated networks for HR, Engineering, and Guest traffic to reduce broadcast domains and improve security.
* **Inter-VLAN Routing:** Configured **Router-on-a-Stick** (or Layer 3 Switching) to allow controlled communication between departments.
* **Redundancy:** Implemented **Spanning Tree Protocol (STP)** to prevent switching loops while maintaining redundant links.
* **Dynamic Routing:** Configured **OSPF** (Open Shortest Path First) for efficient and scalable routing across the autonomous system.

## 🛡️ Security Implementation (Cybersecurity Focus)
* **Access Control Lists (ACLs):** Restrictive rules to prevent unauthorized access to the Server Farm.
* **Port Security:** Limited the number of MAC addresses per switch port to prevent CAM table overflow attacks.
* **SSH Management:** Disabled Telnet in favor of encrypted **SSH** for remote device configuration.

## 📂 Repository Contents
* `Network-Topology.pkt`: The full simulation file.
* `/Configs`: Raw Cisco IOS configurations for all major routers and switches.

## 🏁 How to View
1. Download and install **Cisco Packet Tracer**.
2. Open the `.pkt` file to see the live simulation.
3. Review the `/Configs` folder for detailed CLI implementations.
