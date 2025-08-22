# 🚀 Inter-VLAN Routing for a School Network

Welcome to my *Cisco Packet Tracer Networking Project! This lab demonstrates **Inter-VLAN Routing* for a school network using a *Router-on-a-Stick* configuration with multiple switches and VLANs.

---

## 🎯 Project Objective

- Create three VLANs for different user groups: Students, Faculty, and Guests.
- Configure *Router-on-a-Stick* for inter-VLAN communication.
- Test connectivity between PCs in different VLANs.

---

## 🖥 Network Topology

📌 The topology consists of:
- *1 Router (Cisco 1940)*
- *3 Switches (Cisco 2960)*
- *9 PCs across VLANs*

![Network Topology Screenshot](topology.png) 

---

## 📊 VLAN and IP Addressing Table

| VLAN ID | VLAN Name | Subnet | IP Address Range |
| :--- | :--- | :--- | :--- |
| *10* | Students | 192.168.10.0/24 | 192.168.10.1 - 192.168.10.254 |
| *20* | Faculty | 192.168.20.0/24 | 192.168.20.1 - 192.168.20.254 |
| *30* | Guests | 192.168.30.0/24 | 192.168.30.1 - 192.168.30.254 |

---



 



## 📂 Project Files

- [Download the Packet Tracer Topology](Inter-Vlan.pkt)
