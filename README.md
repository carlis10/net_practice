This project has been created as part of the 42 curriculum by cravegli.


# Networking Fundamentals

This document explains the fundamental networking concepts:
**TCP/IP addressing, subnet masks, default gateways, routers, switches, and the OSI model**.

---

## Table of Contents
- [TCP/IP Addressing](#1-tcpip-addressing)
- [Subnet Mask](#2-subnet-mask)
- [Default Gateway](#3-default-gateway)
- [Routers](#4-routers)
- [Switches](#5-switches)
- [OSI Model](#6-osi-model-open-systems-interconnection)
- [Summary](#7-summary)

---

## 1. TCP/IP Addressing

TCP/IP addressing allows each device in a network to be uniquely identified.

### IP Address
An IP address is a logical identifier assigned to a device so it can communicate on a network.

**Example (IPv4):**
- IPv4 uses 32 bits (4 octets)
- IPv6 uses 128 bits and supports a much larger number of addresses

### Private IP Addresses
Used in internal networks:
- `10.0.0.0 – 10.255.255.255`
- `172.16.0.0 – 172.31.255.255`
- `192.168.0.0 – 192.168.255.255`

---

## 2. Subnet Mask

The subnet mask defines which part of an IP address belongs to the network and which part belongs to the host.

**Example:**
- Network: `192.168.1.0`
- Valid hosts: `192.168.1.1 – 192.168.1.254`

### Purpose
- Divide large networks into smaller subnets
- Improve security and performance
- Optimize the use of IP addresses

---

## 3. Default Gateway

The default gateway is the device that allows a host to communicate with other networks.

If the destination is not within the local network, traffic is sent to the gateway (usually a router).

---

## 4. Routers

A router connects different networks and decides the best path to forward data.

### Main Functions
- Routing between networks
- LAN ↔ WAN (Internet) connectivity
- DHCP (automatic IP address assignment)
- NAT (address translation)

### OSI Layer
- **Layer 3 (Network)**

---

## 5. Switches

A switch connects devices within the same local area network (LAN).

### Main Functions
- Forwards traffic using MAC addresses
- Reduces collisions
- Improves network performance

### OSI Layer
- **Layer 2 (Data Link)**
- Some advanced switches operate at **Layer 3**

---

## 6. OSI Model (Open Systems Interconnection)

The OSI model divides network communication into seven layers.

| Layer | Name | Function |
|------|------|----------|
| 7 | Application | User services (HTTP, FTP, SMTP) |
| 6 | Presentation | Formatting, encryption, compression |
| 5 | Session | Session control |
| 4 | Transport | Flow and error control (TCP/UDP) |
| 3 | Network | Addressing and routing (IP) |
| 2 | Data Link | MAC, switches, frames |
| 1 | Physical | Cables, signals, voltage |

