
# Corporate Network Lab – Network Overview

## Project Purpose

This project is a simulated corporate network built using Cisco Packet Tracer. It represents a small business environment with two departments: Office and IT.

The goal is to apply networking concepts through hands-on configuration, testing, and troubleshooting.

## Network Components

- Cisco 2911 Router
- Managed Cisco Switches
- Cisco ASA 5505 Firewall
- ISP Router
- Corporate Server
- Office and IT Desktop Computers
- Wireless Access Point and Laptop

## Network Addressing

| Department | Network | Default Gateway |

| Office | 192.168.1.0/24 | 192.168.1.1 |
| IT | 192.168.2.0/24 | 192.168.2.1 |

Corporate Server: 192.168.1.5

## Implemented Technologies

- VLAN configuration and network segmentation
- IPv4 addressing and subnetting
- Inter-network routing
- DHCP and DHCP relay
- DNS configuration
- Access Control Lists (ACLs)
- Switch port security
- SSH remote management
- Syslog configuration
- Spanning Tree Protocol (STP)
- WPA2 wireless security
- ASA firewall inside and outside interfaces

## Current Project Status

The internal network has been configured with Office and IT departments, centralized DHCP and DNS services, wired and wireless connectivity, and network security features.

The ASA 5505 firewall and ISP router have been added. Their directly connected interfaces have been tested.

## Remaining Work

- Configure and verify routing between the corporate router, firewall, and ISP.
- Configure NAT/PAT.
- Develop and test firewall access policies.
- Complete external network connectivity testing.

## Tools Used

- Cisco Packet Tracer
- Cisco IOS CLI
- Visual Studio Code
- Git and GitHub
- Markdown