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


  # Vic Modern Hotel Network

## Overview

This project is a complete enterprise network designed and implemented in Cisco Packet Tracer for a three-floor hotel environment. The network provides secure, scalable, and reliable communication between multiple departments while applying industry-standard networking concepts.

## Objectives

* Design a multi-floor enterprise network
* Segment departments using VLANs
* Enable communication between VLANs
* Implement dynamic routing using OSPF
* Provide automatic IP addressing with DHCP
* Configure secure remote management using SSH
* Implement switch port security
* Provide wireless connectivity for each floor

## Network Architecture

### Floor 1

* Reception (VLAN 80)
* Store (VLAN 70)
* Logistics (VLAN 60)

### Floor 2

* Finance (VLAN 50)
* HR (VLAN 40)
* Sales & Marketing (VLAN 30)

### Floor 3

* IT (VLAN 10)
* Admin (VLAN 20)

Three Cisco routers are interconnected using serial links and exchange routes through OSPF. Each floor contains a managed switch connected using Router-on-a-Stick to provide inter-VLAN routing.

## Technologies Used

* Cisco Packet Tracer
* VLANs
* IEEE 802.1Q Trunking
* Router-on-a-Stick
* OSPF
* DHCP
* SSH
* Port Security (Sticky MAC)
* Wireless Networking
* Serial WAN Links

## Key Features

* Enterprise network topology across three floors
* Eight department VLANs
* Dynamic routing using OSPF
* Automatic IP assignment with DHCP
* Secure SSH remote administration
* Wireless access on every floor
* Department printers
* Sticky MAC Port Security in the IT department
* Full end-to-end connectivity between all devices

## Verification

The completed network successfully demonstrates:

* Inter-VLAN communication
* Dynamic route advertisement using OSPF
* Successful DHCP address allocation
* SSH remote access to all routers
* Wireless client connectivity
* Port Security protecting the IT department
* End-to-end connectivity across the entire enterprise network

## Skills Demonstrated

* Enterprise Network Design
* IP Addressing & Subnetting
* VLAN Configuration
* Switching
* Dynamic Routing
* Network Security
* Router Configuration
* Troubleshooting
* Cisco IOS

## Author

**Yahya Melad**

Cisco Certified Support Technician (CCST) – Cybersecurity

Aspiring Network Engineer & Cybersecurity Student
<img width="1916" height="1080" alt="Screenshot 2026-07-12 082615" src="https://github.com/user-attachments/assets/4569e33b-7166-4cd4-9781-ca5b1011e5b4" />


