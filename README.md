# Small Office Network Design & Implementation (Cisco Packet Tracer)

##  Overview
This project demonstrates the design and implementation of a **small office network** using **Cisco Packet Tracer**.  
The network was built to simulate a real-world small business environment with **segmented VLANs, inter-VLAN routing, DHCP, and static IP assignments** for critical services.  

The goal of the project is to showcase practical skills in **network design, configuration, and troubleshooting**, suitable for enterprise-level networking scenarios.  

---

## Network Features
- **Multi-VLAN Architecture**  
  - VLAN 10: Admin  
  - VLAN 20: Sales  
  - VLAN 30: IT  
  - VLAN 40: Servers/Printers  

- **Router-on-a-Stick Inter-VLAN Routing**  
  Configured subinterfaces on the router with `802.1Q encapsulation` to enable communication between VLANs.  

- **Dynamic Host Configuration Protocol (DHCP)**  
  - DHCP pools configured per VLAN.  
  - Gateway and server/printer addresses excluded.  

- **Switching**  
  - VLAN assignments for access ports.  
  - Trunk links between core switch and router/access switches.  
  - VTP used for VLAN propagation across switches.  

- **Static IP Services**  
  - File/Print Server (192.168.10.194)  
  - Network Printer (192.168.10.195)  

- **Scalability & Security Considerations**  
  - Network segmented by function for efficiency and security.  
  - Design can be extended with firewalls, VPNs, and wireless access points.  

---

##  IP Addressing Plan

| VLAN  | Subnet              | Gateway         | Devices              |
|-------|----------------------|-----------------|----------------------|
| 10    | 192.168.10.0/26     | 192.168.10.1    | Admin PCs            |
| 20    | 192.168.10.64/26    | 192.168.10.65   | Sales PCs            |
| 30    | 192.168.10.128/26   | 192.168.10.129  | IT PCs               |
| 40    | 192.168.10.192/26   | 192.168.10.193  | Server & Printer     |

---


---

## Skills Demonstrated
- Network Design & Planning  
- VLAN Configuration & Trunking  
- Router-on-a-Stick Inter-VLAN Routing  
- DHCP Configuration on Routers  
- Switch VLAN Management & VTP  
- Static IP Assignment for Services  
- Network Troubleshooting & Verification  

---

## Topology Screenshot
![Topology](-labeled.png)  images/topology

---

## 🚀 How to Use
1. Clone the repository:  
   ```bash
https://github.com/esthermensah/small-office-network-design.git
```

