# Lab 01 - VLAN Configuration

## Overview

This lab focuses on configuring VLANs in a small business
network using Cisco Packet Tracer. The main purpose is to
separate the Sales, IT, and HR departments into different
VLANs while allowing devices within the same department
to communicate across two switches.

## Network Topology

![Network Topology](Topology.png)

## Business Requirements

- Separate each department into its own VLAN.
- Allow communication between devices in the same VLAN.
- Configure a trunk link between the two switches.
- Maintain network isolation between departments.

## VLAN Assignment

| VLAN ID | Department | Network |
|---------|------------|---------|
| 10 | Sales | 192.168.10.0/24 |
| 20 | IT | 192.168.20.0/24 |
| 30 | HR | 192.168.30.0/24 |

## Technologies Used

- Cisco Packet Tracer
- Cisco Catalyst 2960
- VLANs
- IEEE 802.1Q Trunking
- IPv4 Addressing
- Layer 2 Switching

## Lab Documentation

- [Switch Configurations](./Configurations/)
- [Network Verification](./Verification/)
- [Packet Tracer File](./VLAN-Configuration.pkt)

## Scope and Limitations

This lab only covers Layer 2 network segmentation.
Inter-VLAN routing is not included and will be
implemented in a separate lab.
