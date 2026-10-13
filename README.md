# 🌐 CCNA Networking Projects | Cisco Packet Tracer

Welcome to my **CCNA Networking Projects Repository!** 🚀

This repository contains my hands-on networking labs and practical implementations completed using **Cisco Packet Tracer** as part of my CCNA training.

Through these projects, I have practiced network configuration, router CLI commands, IP address management, routing, and network services to develop a strong understanding of computer networking.

---

## 📌 About This Repository

* **Domain:** Computer Networking
* **Certification Track:** CCNA (Cisco Certified Network Associate)
* **Tool:** Cisco Packet Tracer
* **Platform:** Cisco Routers and Switches
* **Focus:** Network Configuration, Routing, and Network Services
* **Level:** Beginner to Intermediate

---

## 🧪 Completed Networking Projects

### 1. DHCP Configuration

**Objective:** Configure a router as a DHCP server to automatically assign IP addresses to connected devices.

**Key Concepts:**

* Dynamic Host Configuration Protocol (DHCP)
* Automatic IP address allocation
* DHCP address pools
* Default gateway and DNS configuration
* IP address management

**Skills Practiced:**

* Configuring DHCP pools on a Cisco router
* Excluding reserved IP addresses
* Assigning IP addresses automatically to PCs
* Verifying IP configuration and connectivity

---

### 2. Telnet Configuration

**Objective:** Configure remote access to Cisco networking devices using Telnet.

**Key Concepts:**

* Remote device management
* Virtual terminal (VTY) lines
* Username and password authentication
* Router and switch CLI access

**Skills Practiced:**

* Configuring Telnet on Cisco devices
* Setting up login credentials
* Configuring VTY lines
* Accessing a router or switch remotely from a PC

**Note:** Telnet does not encrypt credentials or session traffic. SSH is recommended for secure remote administration.

---

### 3. NTP Configuration

**Objective:** Configure Network Time Protocol (NTP) to synchronize the clocks of network devices.

**Key Concepts:**

* Network Time Protocol
* Time synchronization
* NTP client and server concepts
* Accurate timestamps for network logs

**Skills Practiced:**

* Configuring NTP on Cisco devices
* Setting up an NTP server or reference device in the lab
* Verifying NTP status and synchronization

---

### 4. Routing — Ring Topology

**Objective:** Build a network using a ring topology and configure routers to enable communication between connected networks.

**Key Concepts:**

* Ring topology
* Router-to-router connectivity
* IP addressing
* Network interfaces
* Routing fundamentals

**Skills Practiced:**

* Connecting multiple routers in a ring
* Configuring router interfaces
* Assigning IP addresses
* Testing connectivity between network devices
* Troubleshooting connectivity issues

---

### 5. Static Routing — Ring Topology

**Objective:** Configure static routes in a ring topology to enable communication between different networks.

**Key Concepts:**

* Static routing
* Routing tables
* Destination networks
* Next-hop IP addresses
* End-to-end connectivity

**Skills Practiced:**

* Configuring static routes using Cisco IOS commands
* Selecting appropriate next-hop addresses
* Understanding route selection
* Verifying routing tables
* Testing connectivity using `ping` and `traceroute`

---

### 6. Cisco Router CLI

**Objective:** Practice Cisco IOS Command-Line Interface (CLI) commands for configuring and managing networking devices.

**Key Concepts:**

* User EXEC mode
* Privileged EXEC mode
* Global configuration mode
* Interface configuration
* Device monitoring and troubleshooting

**Commands Practiced:**

| Command                              | Purpose                                 |
| ------------------------------------ | --------------------------------------- |
| `enable`                             | Enter privileged EXEC mode              |
| `configure terminal`                 | Enter global configuration mode         |
| `hostname R1`                        | Set the device hostname                 |
| `interface gigabitEthernet 0/0`      | Enter interface configuration mode      |
| `ip address <IP> <MASK>`             | Assign an IP address to an interface    |
| `no shutdown`                        | Enable an interface                     |
| `show ip interface brief`            | Check interface status and IP addresses |
| `show running-config`                | Display the active configuration        |
| `show ip route`                      | Display the routing table               |
| `ping <IP>`                          | Test network connectivity               |
| `traceroute <IP>`                    | Trace the network path to a destination |
| `copy running-config startup-config` | Save the current configuration          |

*Note: Available interface names and command support depend on the Cisco device model and IOS version.*

---

## 🛠️ Tools and Technologies

| Tool / Technology   | Purpose                                   |
| ------------------- | ----------------------------------------- |
| Cisco Packet Tracer | Network simulation and lab implementation |
| Cisco IOS CLI       | Router and switch configuration           |
| DHCP                | Automatic IP address assignment           |
| Telnet              | Remote device access                      |
| NTP                 | Network time synchronization              |
| Static Routing      | Communication between different networks  |
| Ping                | Connectivity testing                      |
| Traceroute          | Network path troubleshooting              |

---

## 🎯 Skills Developed

By completing these networking labs, I have gained practical exposure to:

* Cisco router and switch configuration
* Cisco IOS CLI commands
* IPv4 addressing and subnet masks
* DHCP configuration and address allocation
* Telnet remote access
* NTP configuration and time synchronization
* Static routing
* Ring topology implementation
* Network connectivity testing
* Basic network troubleshooting

---

## 💻 How to Explore the Projects

1. Clone or download this repository.
2. Locate the required Cisco Packet Tracer project file (`.pkt`), if included.
3. Open the file using Cisco Packet Tracer.
4. Inspect the network topology and device configurations.
5. Open the router or switch CLI to review the commands.
6. Test connectivity using commands such as `ping` and `traceroute`.

**Note:** Packet Tracer files and screenshots should be included in the repository if you want others to reproduce and verify your labs.

---

## ⭐ Support

If you find these networking projects useful, consider giving this repository a star ⭐.

Thank you for visiting my CCNA Networking Projects Repository!
