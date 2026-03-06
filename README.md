# ccna-small-office-network
Design and implementation of a small office network using CCNA concepts including VLANs, inter VLAN routing, OSPF, DHCP, ACLs, WAN connectivity, and wireless integration.

End to End Small Office Network Project
Project Overview

This project demonstrates the design and implementation of a small office network using core CCNA networking concepts.

The network simulates a real business environment with multiple departments, segmented VLANs, routing between networks, automatic IP assignment, WAN connectivity, and basic security controls.

The goal of this project is to strengthen practical networking skills and demonstrate the ability to design, configure, and troubleshoot enterprise style networks.

Network Objectives

Design a structured small office network

Segment departments using VLANs

Implement inter VLAN routing

Provide automatic IP addressing using DHCP

Implement DNS services

Connect a remote branch office

Configure OSPF dynamic routing

Apply Access Control Lists for security

Add wireless access for clients

Perform troubleshooting and validation

Network Topology

Devices used in the lab:

2 Cisco switches

2 Cisco routers

1 DNS server

1 wireless access point

Multiple wired PCs

Wireless clients

Logical layout:

Head Office Network

VLAN 10 Admin

VLAN 20 Staff

VLAN 30 Guest

Branch Office Network

Single LAN subnet

WAN Link

Serial connection between routers

IP Addressing Plan
Network	Purpose	Subnet
VLAN 10	Admin	192.168.10.0/24
VLAN 20	Staff	192.168.20.0/24
VLAN 30	Guest	192.168.30.0/24
Branch LAN	Branch Office	192.168.40.0/24
WAN Link	Router Interconnection	10.0.0.0/30
Technologies Used

This project demonstrates the following networking technologies.

VLAN segmentation

Trunking

Inter VLAN routing (Router on a Stick)

DHCP configuration

DNS services

Static routing

OSPF dynamic routing

Access Control Lists

Wireless network configuration

Network troubleshooting

VLAN Configuration

Three VLANs were created to segment departments.

VLAN	Department
VLAN 10	Admin
VLAN 20	Staff
VLAN 30	Guest****
