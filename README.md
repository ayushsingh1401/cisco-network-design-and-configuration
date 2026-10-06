# cisco-network-design-and-configuration
Designed and configured a multi-device network in Cisco Packet Tracer with router/switch configuration, IP addressing, connectivity testing, and basic network troubleshooting.
# Cisco Network Design & Configuration

## 📌 Project Overview

This project demonstrates the design, configuration, and testing of a small enterprise-style computer network using Cisco Packet Tracer.

The network was built to understand practical networking concepts such as IP addressing, router and switch configuration, device connectivity, routing, and network troubleshooting.

The project focuses on hands-on implementation rather than only theoretical networking concepts.

---

## 🎯 Objectives

- Design a functional computer network using Cisco Packet Tracer
- Configure routers and switches
- Assign IP addresses to network devices
- Configure end devices for network communication
- Establish connectivity between different network segments
- Verify network connectivity using diagnostic commands
- Understand basic routing concepts
- Practice network troubleshooting
- Document network configurations and testing results

---

## 🛠️ Technologies & Tools Used

- Cisco Packet Tracer
- Cisco Routers
- Cisco Switches
- IPv4 Addressing
- Ethernet
- Routing
- Switching
- ICMP / Ping
- Cisco IOS CLI

---

## 🌐 Network Architecture

The network consists of:

- Cisco routers
- Cisco switches
- Multiple end devices
- Different IP address ranges
- Interconnected network segments

The topology was designed to simulate a basic organizational network environment.

---

## 📐 Network Topology

![Network Topology](screenshots/network-topology.png)

The topology shows the overall network structure, including routers, switches, and connected end devices.

---

## 🔧 Configuration Performed

### 1. Router Configuration

The routers were configured using the Cisco IOS command-line interface.

Configuration tasks included:

- Assigning IP addresses to interfaces
- Activating interfaces
- Configuring routing
- Verifying interface status
- Testing connectivity

Example commands:

```text
enable
configure terminal
interface gigabitEthernet 0/0
ip address <IP_ADDRESS> <SUBNET_MASK>
no shutdown
exit
