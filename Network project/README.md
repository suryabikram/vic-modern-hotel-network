# 🏨 Vic Modern Hotel — Multi-Floor VLAN, OSPF, DHCP, and Secure SSH Network Design
> 🧩 A three-floor enterprise network design featuring VLAN segmentation, OSPF dynamic routing, DHCP automation, and secure SSH management.


![Network Topology Overview](Network%20project/topology_overview.png)
<p align="center"><em>Figure 1: Network Topology Overview</em></p>


## 📘 Project Overview
This project demonstrates the design and implementation of a three-floor enterprise network for **Vic Modern Hotel** using Cisco Packet Tracer.  
Each floor hosts multiple departments segmented by VLANs, with inter-VLAN routing performed through router-on-a-stick.  
Dynamic routing is achieved using **OSPF**, IP assignment through **DHCP**, and secure remote management via **SSH**.  
Switch port-security ensures endpoint control at the access layer.

---

## 🧱 Network Objectives
- Design a three-floor hierarchical topology (Core–Distribution–Access)
- Implement VLAN segmentation for eight departments
- Configure router-on-a-stick inter-VLAN routing
- Deploy OSPF (Area 0) for dynamic inter-router communication
- Configure DHCP pools for each VLAN
- Enable SSH for secure management access
- Apply port-security on IT switch using sticky MAC

---

## 🧩 Technologies Implemented
| Category | Technology |
|-----------|-------------|
| Layer 2 | VLANs 10–80, Trunk Links |
| Layer 3 | Router-on-a-Stick, OSPF Area 0 |
| Addressing | DHCP Server on Routers |
| Security | SSH Login, Port-Security (Sticky MAC) |
| Tools | Cisco Packet Tracer, Cisco IOS CLI, Markdown Docs |

---



## 🧠 Key Learnings
- Building a multi-router hierarchical design in Cisco Packet Tracer  
- Configuring VLANs and inter-VLAN routing via subinterfaces  
- Using OSPF for automatic route advertisement  
- Implementing DHCP to automate host IP allocation  
- Enabling SSH for secure management  
- Applying Layer-2 security through port-security

---

## ✅ Verification Summary
- All routers show OSPF neighbor adjacencies  
- VLAN hosts can ping across floors  
- DHCP leases confirmed on PCs  
- SSH remote login successful  
- Port-security enforces single device on Fa0/4  

---

## 👨‍💻 Author
**Surya Bikram Shahi**  
B.S. in Computer Information Technology — Cybersecurity Focus  
Minnesota State University, Mankato (2026)  

---
---
### 🏷️ Tags
`#Cisco` `#Networking` `#VLAN` `#OSPF` `#DHCP` `#SSH` `#PacketTracer` `#Cybersecurity` `#NetworkDesign`





