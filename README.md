# Enterprise Networking Project 07
### Multi-Floor Enterprise Network Design using Cisco Packet Tracer

## 📌 Project Overview

This project demonstrates the design and implementation of a multi-floor enterprise network infrastructure using Cisco Packet Tracer.

The network is designed for an organization with three floors, multiple departments, centralized server services, and redundant network connections to support reliable communication between departments.

The design uses VLAN segmentation, routers, multilayer switches, access switches, wireless access points, and centralized servers.

## 🏢 Network Architecture

The enterprise network consists of three floors and a dedicated server room.

### First Floor
- Sales & Marketing Department – VLAN 10
- HR & Logistics Department – VLAN 20

### Second Floor
- Finance & Accounts Department – VLAN 30
- Administration & Public Relations Department – VLAN 40

### Third Floor
- ICT Department – VLAN 50
- Server Room – VLAN 60

## 🌐 VLAN Configuration

| VLAN ID | Department | Network Purpose |
|---|---|---|
| VLAN 10 | Sales & Marketing | Department segmentation |
| VLAN 20 | HR & Logistics | Department segmentation |
| VLAN 30 | Finance & Accounts | Department segmentation |
| VLAN 40 | Admin & Public Relations | Department segmentation |
| VLAN 50 | ICT | Technical department |
| VLAN 60 | Server Room | Centralized server services |

## 🛠️ Technologies & Devices Used

- Cisco Packet Tracer
- Cisco Routers (2811 / 2911)
- Cisco Multilayer Switches (3560)
- Cisco Access Switches (2960)
- VLAN Configuration
- Trunking
- Inter-VLAN Routing
- Redundant Network Links
- Wireless Access Points
- DHCP Server
- DNS Server
- Mail Server

## ⚙️ Key Network Features

### 1. VLAN Segmentation
Separated departments into individual VLANs to organize network traffic and improve network management.

### 2. Inter-VLAN Communication
Designed the network to support communication between different departmental VLANs through Layer 3 routing.

### 3. Network Redundancy
Designed redundant connections between network devices to provide alternative communication paths in case of link failures.

### 4. Centralized Server Infrastructure
Implemented a dedicated server room containing:
- DHCP Server – Automatic IP address allocation.
- DNS Server – Domain name resolution.
- Mail Server – Email communication services.

### 5. Wireless Connectivity
Provided wireless access points for connecting laptops and other wireless devices across departments.

## 🖥️ End Devices

The network includes:
- Desktop computers
- Laptops
- Network printers
- Wireless access points
- Centralized servers

## 🧪 Testing & Verification

Network functionality can be verified using:

- `show vlan brief` – Verify VLAN configuration.
- `show interfaces trunk` – Verify trunk connections.
- `show ip interface brief` – Check interface status.
- `show ip route` – Verify routing information.
- `ping` – Test connectivity between network devices.
- DHCP testing – Verify automatic IP address allocation.
- DNS testing – Verify domain name resolution.
- Link failure testing – Verify network redundancy.

## 📁 Project Files

| File | Description |
|---|---|
| `Enterprise-Network-Project-07.pkt` | Cisco Packet Tracer project |
| `topology.png` | Enterprise network topology |
| `README.md` | Project documentation |

## 🎯 Learning Outcomes

- Enterprise network topology design.
- Multi-floor network architecture.
- VLAN-based network segmentation.
- Inter-VLAN routing concepts.
- Redundancy and network availability.
- Centralized network services.
- Cisco network configuration and troubleshooting.

## 💻 Software

Cisco Packet Tracer

## 👨‍💻 Project Type

Academic / Practical Networking Project
