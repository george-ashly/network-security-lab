# Network Security Lab 

## Overview
A simulated enterprise network built in Cisco Packet Tracer, demonstrating 
network segmentation, inter-VLAN routing, and access control policies.

## Network Design
![Network Topology](topology.png)

## VLANs
| VLAN | Name | Subnet | Purpose |
|------|------|--------|---------|
| 10 | HR | 192.168.10.0/24 | HR department + server |
| 20 | IT | 192.168.20.0/24 | IT department |
| 30 | Guest | 192.168.30.0/24 | Guest access |

## Security Rules (ACL)
- Guest cannot access HR resources 
- Guest can access IT resources 
- HR and IT can communicate freely 

## What I learned
- How to segment a network using VLANs on a Cisco multilayer switch
- How inter-VLAN routing works via Switch Virtual Interfaces (SVI)
- How to write and apply Access Control Lists to restrict traffic
- Troubleshooting network connectivity issues in Cisco CLI

## Tools
- Cisco Packet Tracer
- Cisco 3650 Multilayer Switch
- Cisco CLI commands

## Note
Built in Cisco Packet Tracer for educational purposes only.
