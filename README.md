# Multi-Area OSPF Network with Centralized DHCP

## Project Overview

This project demonstrates the design and implementation of a scalable enterprise network using Cisco Packet Tracer. The network is divided into multiple OSPF areas to improve routing efficiency and reduce routing overhead.

A centralized DHCP server located in the Headquarters (HQ) network provides automatic IP address allocation to all remote areas through DHCP Relay Agents (IP Helper Address).

---

## Objectives

* Implement Multi-Area OSPF Routing.
* Establish dynamic route exchange between all routers.
* Deploy a centralized DHCP solution.
* Configure DHCP Relay Agents for remote networks.
* Verify end-to-end connectivity across all areas.
* Simulate a real-world enterprise network infrastructure.

---

## Network Architecture

| Area   | Purpose           |
| ------ | ----------------- |
| Area 1 | Headquarters (HQ) |
| Area 2 | Branch Office 1   |
| Area 3 | Branch Office 2   |
| Area 4 | Branch Office 3   |

The backbone network enables communication between all OSPF areas while maintaining efficient routing updates.

---

## Technologies Used

* Cisco Packet Tracer
* OSPF (Open Shortest Path First)
* DHCP Server
* DHCP Relay Agent (ip helper-address)
* IPv4 Addressing
* Dynamic Routing

---

## Key Configurations

### OSPF

* Multi-Area OSPF Deployment
* Dynamic Route Advertisement
* Inter-Area Routing

### DHCP

* Centralized DHCP Server
* Automatic Address Assignment
* Remote DHCP Requests Forwarding

### Connectivity

* End-to-End Communication
* Inter-Area Reachability
* ICMP Verification

---

## Verification Tests

### OSPF Verification

* OSPF Neighbor Adjacencies Established
* OSPF Routing Tables Populated Successfully

### DHCP Verification

* Successful IP Address Assignment
* Correct Default Gateway Distribution

### Connectivity Verification

* Successful Ping Between All Areas
* Full Network Reachability Confirmed

---

## Project Files

```text
Multi-Area-OSPF-Network/
│
├── Multi-Area-OSPF.pkt
├── README.md
│
└── screenshots/
    ├── topology.png
    ├── ospf-neighbors.png
    ├── show-ip-route.png
    ├── dhcp-success.png
    └── ping-test.png
```

---

## Screenshots

Refer to the screenshots directory for network topology, routing verification, DHCP operation, and connectivity testing.

---

## Learning Outcomes

Through this project, the following networking concepts were applied and validated:

* Enterprise Network Design
* Multi-Area OSPF Implementation
* Dynamic Routing Protocols
* DHCP Services
* DHCP Relay Configuration
* Network Troubleshooting
* End-to-End Connectivity Testing

---

## Author

**Mohamed Amr**

Network Engineering Student
