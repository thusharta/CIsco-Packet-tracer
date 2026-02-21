# Cisco Packet Tracer – Networking Labs (CCNA Level)

## Overview
This repository contains my **Cisco Packet Tracer (.pkt) lab files** created as part of my hands-on learning in **computer networking and IT infrastructure**.  
The labs are aligned with **CCNA (200-301)** topics and focus on **practical configuration, troubleshooting, and validation of network concepts**.

These labs demonstrate my understanding of **routing, switching, VLANs, IP addressing, and basic network security**, along with a structured and methodical approach to network design and problem-solving.

---

## Lab Topics Covered
- Basic network device configuration (routers, switches, end hosts)
- IPv4 addressing and subnetting
- VLAN configuration and inter-VLAN routing
- Static routing and default routes
- Dynamic routing (introductory OSPF concepts)
- Access Control Lists (standard and extended)
- Network troubleshooting (ping, traceroute, interface status)
- Layer 2 concepts (ports, trunks, access mode)
- Basic network security and access control

---

## Tools & Technologies
- Cisco Packet Tracer
- Cisco Routers & Switches (IOS-based)
- TCP/IP, LAN/WAN concepts
- VLANs, subnetting, routing & switching
- CCNA-level networking fundamentals

---

## How to Use
1. Download and install **Cisco Packet Tracer**.
2. Clone or download this repository.
3. Open any `.pkt` file using Cisco Packet Tracer.
4. Review the topology, configurations, and test connectivity using CLI commands such as:
   - `show ip route`
   - `show running-config`
   - `ping`
   - `traceroute`

---

## Learning Objective
The goal of this repository is to:
- Strengthen practical networking skills
- Apply theoretical concepts in simulated environments
- Build confidence in configuring and troubleshooting real-world networks
- Support my preparation for **CCNA certification** and **entry-level network / managed services roles**

 
# Master’s Project – Software Managed Network Design (Cisco)

## Project Title
**Network Analysis and Recommendations – Software Managed Network Design**

## Academic Context
- **Degree:** Master of Networking  
- **Unit:** MN625 – Software Managed Network  
- **Institution:** Melbourne Institute of Technology  
- **Student:** Thushar Thymagondlu Anjanappa  

---

## Project Overview
This project presents the **design, implementation, and analysis of an enterprise-style network** using Cisco technologies and simulation tools.  
The objective was to design a **secure, scalable, and highly available network** that supports modern organizational requirements such as **segmentation, redundancy, dynamic addressing, and fault tolerance**.

The project was implemented and validated using **Cisco Packet Tracer**, with detailed configuration, testing, and documentation.

---

## Business Case Scenarios
The project is based on real-world inspired case studies, including:
- **Healthcare Network (Memorial Regional Healthcare)**  
- **Mobile Broadcasting Network (TV Skyline – OB Van)**  

Each scenario focuses on:
- High availability
- Security and traffic segmentation
- Scalability for future growth
- Performance and redundancy

---

## Network Architecture
- **Three-tier hierarchical design** (Core, Distribution, Access)
- Multiple routers configured for redundancy
- Layer 2 and Layer 3 switches
- VLAN-based network segmentation
- Trunking between switches
- Inter-VLAN routing using router-on-a-stick and multilayer switching concepts

---

## Key Technologies & Concepts Implemented
- Cisco Routing & Switching
- IPv4 addressing and subnetting
- VLAN creation and assignment
- Trunking (802.1Q)
- Inter-VLAN routing
- DHCP server configuration per VLAN
- Static routing and OSPF (dynamic routing)
- Redundant router design
- Network troubleshooting and validation (ping, routing tables)
- SDN concepts (theoretical – Omada SDN platform analysis)

---

## IP Addressing & VLAN Design
- Private addressing using **Class B network (172.16.0.0/16)**
- Department-based VLAN segmentation:
  - VLAN 10 – Administration
  - VLAN 20 – Clinical
  - VLAN 30 – Records
  - VLAN 40 – Guest
- Dynamic IP allocation using DHCP pools
- Reserved IP ranges for infrastructure devices

---

## Validation & Testing
The following validations were successfully completed:
- DHCP IP allocation on all VLANs
- Intra-VLAN connectivity testing
- Inter-VLAN routing verification
- Router-to-host connectivity checks
- End-to-end network reachability

Screenshots and configuration outputs are included in the project documentation.

---

## Files in This Repository
- `.pkt` files – Cisco Packet Tracer topology and configurations  
- Network analysis and recommendation report (DOCX/PDF)  
- Network topology plan and diagrams  
- Configuration screenshots and validation results  

---

## Learning Outcomes
Through this project, I gained hands-on experience in:
- Designing enterprise-grade network architectures
- Implementing VLAN-based security and segmentation
- Configuring Cisco routers and switches via CLI
- Applying redundancy and scalability principles
- Troubleshooting multi-VLAN and multi-router networks
- Translating business requirements into technical network solutions

---

## Relevance to Industry Roles
This project demonstrates practical skills relevant to:
- Network Engineer (Junior / Graduate)
- NOC / Managed Services Engineer (L1)
- Infrastructure Support Engineer
- IT Operations roles

---

## Notes
This project was completed for **academic learning purposes** and follows **CCNA-level and early enterprise networking best practices**.  
All configurations and designs reflect structured, standards-based networking approaches.

---
