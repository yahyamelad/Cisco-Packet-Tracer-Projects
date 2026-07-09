# Cisco Packet Tracer Projects

Welcome to my networking portfolio.

This repository contains networking labs that I have built while learning Cisco networking and cybersecurity.

## Project 1: Simple Network

### Overview

This project simulates a small office network with two separate LANs connected through a router.

### Network Topology

* 1 Cisco Router
* 2 Cisco Switches
* 4 PCs (2 per LAN)
* 2 Network Printers (1 per LAN)

### Configuration

* Designed the network topology in Cisco Packet Tracer.
* Configured the router interfaces.
* Assigned IPv4 addresses using the **192.168.40.0** network with subnetting.
* Configured hosts with the correct IP addresses, subnet masks, and default gateways.
* Verified end-to-end connectivity using ping.

### Skills Demonstrated

* IPv4 Addressing
* Subnetting
* Router Configuration
* Switch Connectivity
* Basic Network Design
* Network Troubleshooting

---
## Network Topology

<img width="1917" height="1080" alt="Simple Network Project Screenshot" src="https://github.com/user-attachments/assets/f014bbb6-5c2b-4a55-8a3e-9ad1f7ebc3ae" />



## Project 2: Small Company VLAN Network

### Overview

This project simulates a small company network with three separate departments. VLANs were implemented to improve network organization, security, and traffic separation.

The departments are:

- Admin/IT
- Finance/HR
- CS/Reception

### Network Topology

- 1 Cisco Router
- 1 Cisco Switch
- 3 VLANs
- PCs for each department
- Network printers
- Wireless Access Points
- Network testing devices

### VLAN and IP Addressing Design

| VLAN | Department | Network Address | Subnet Mask |
|------|------------|----------------|-------------|
| VLAN 10 | Admin/IT | 192.168.1.0/26 | 255.255.255.192 |
| VLAN 20 | Finance/HR | 192.168.1.64/26 | 255.255.255.192 |
| VLAN 30 | CS/Reception | 192.168.1.128/26 | 255.255.255.192 |

### Configuration

- Created VLANs on the Cisco switch.
- Assigned devices to their correct VLANs.
- Configured router interfaces for inter-VLAN routing.
- Configured subnetting using the 192.168.1.0/24 network.
- Connected the router and switch using a trunk link.
- Configured default gateways for each VLAN.
- Tested connectivity between different VLANs successfully.

### Skills Demonstrated

- VLAN Configuration
- Inter-VLAN Routing
- Router-on-a-Stick
- IPv4 Subnetting
- Network Segmentation
- Cisco IOS Configuration
- Enterprise Network Design
- Troubleshooting

### Topology
<img width="1920" height="1080" alt="Simple Company Network Project " src="https://github.com/user-attachments/assets/a9304e7f-3d11-4e56-b158-7ef9fcd0d331" />

**Author:** Yahya Melad
Aspiring Cybersecurity & Networking Professional
