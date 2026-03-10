# Inter-VLAN Routing Lab

## Objective

Configure VLANs, trunking, and router subinterfaces to enable communication between devices on different VLANs.

This lab demonstrates how inter-VLAN routing allows multiple segmented networks to communicate through a router using a router-on-a-stick configuration.

## Skills Demonstrated

- VLAN creation and configuration
- Switch access port assignment
- 802.1Q trunk configuration
- Router subinterface configuration
- Inter-VLAN routing
- Network troubleshooting and verification

## Tools Used

- Cisco Packet Tracer
- Cisco IOS CLI

## Scenario

This lab simulates a small network where multiple VLANs are configured on a switch and traffic between those VLANs is routed through a router using subinterfaces. Devices are assigned to separate VLANs representing different network groups, and routing is configured so that hosts on different VLANs can communicate. :contentReference[oaicite:0]{index=0}

## Network Configuration Overview

Key configurations in this lab include:

- Creating VLANs and assigning switch ports to the correct VLANs
- Configuring a trunk link between the switch and router
- Creating router subinterfaces for each VLAN
- Assigning IP addressing to each VLAN network
- Configuring a management VLAN and default gateway
- Disabling unused switch ports for security

## Validation

Connectivity between devices was verified using:

- `ping`
- `show vlan`
- `show interfaces trunk`
- `show ip interface brief`

Successful configuration allows devices in different VLANs to communicate through the router.

## Concepts Practiced

- Network segmentation using VLANs
- Router-on-a-Stick architecture
- Layer 2 switching and Layer 3 routing interaction
- Network verification and troubleshooting
