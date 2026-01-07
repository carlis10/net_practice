This project has been created as part of the 42 curriculum by cravegli.

# NetPractice – Project Description

NetPractice is a networking project from the 42 School curriculum designed to introduce students to the fundamentals of computer networking through practical exercises.

The main purpose of this project is to help students understand how network communication works by configuring and troubleshooting virtual network setups. Instead of writing code, students solve networking problems by applying theoretical concepts in realistic scenarios.

## Project Purposes

The NetPractice project aims to:

- Introduce core networking concepts, including:
- IP addressing
- Subnet masks
- Default gateways
- Routing basics
- Develop a clear understanding of how devices communicate within a network and across different networks.
- Teach students how to analyze and fix network configuration issues, such as incorrect IP addresses, subnet masks, or routing paths.
- Strengthen knowledge of the TCP/IP model and its relation to real-world network behavior.
- Encourage logical thinking and problem-solving skills without relying on programming.
- Prepare students for more advanced networking and system administration projects within the 42 curriculum.

## Learning Outcomes

By completing NetPractice, students are expected to:

- Correctly configure IP addresses and subnet masks.

- Understand how data flows from a local network to external networks using routers and gateways.

- Identify and resolve network connectivity problems.

- Gain practical experience with network topology and routing logic.

# Project Usage – NetPractice

To complete this project, we must use the interface provided on the project’s webpage.  
This tool allows us to put the project’s objectives into practice through interactive networking exercises.

---

## How to Use the Interface

Follow these steps to use the NetPractice interface:

- Open the `index.html` file in a web browser.
- Enter your **42 login** and select **Start**.
- Complete the exercise and click the `Check` button.
- If the configuration is correct, you can proceed to the next exercise.

---

## Exercises

- There are a total of **10 exercises**.
- The difficulty **increases progressively** as you advance through the levels.
- Each exercise focuses on applying networking concepts such as IP addressing, subnetting, and routing.

---

## Practice Mode (Without Login)

The interface can also be launched **without using a login**.  
This mode is useful to practice for the **evaluation**, which consists of:

- **3 random exercises**
- Selected from **levels 6 to 10**

This allows students to simulate real correction conditions and reinforce advanced concepts.

---

# Networking Fundamentals

This document explains the fundamental networking concepts:
**TCP/IP addressing, subnet masks, default gateways, routers, switches, and the OSI model**.

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

---

## 5. Switches

A switch connects devices within the same local area network (LAN).

### Main Functions
- Forwards traffic using MAC addresses
- Reduces collisions
- Improves network performance

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

