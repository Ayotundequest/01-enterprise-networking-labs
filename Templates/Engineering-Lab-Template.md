# Lab 01 - Configure a Wireless Router and Clients

---

# Lab Information

| Item | Details |
|------|---------|
| Module | Networking Foundations |
| Week | Week 01 |
| Difficulty | Beginner |
| Lab Type | Cisco Packet Tracer |
| Estimated Duration | 60 Minutes |
| Author | Quadri Akinjole |
| Date Completed | 2026-07-20 |

---

# Learning Objectives

Upon completion of this lab, I was able to:

- Connect network devices using the correct cable types.
- Configure a home wireless router.
- Configure DHCP for automatic IP address assignment.
- Configure a secure wireless network using WPA2 Personal.
- Connect wired and wireless devices to the network.
- Verify successful Internet connectivity.

---

# Scenario

A homeowner has subscribed to a cable Internet service and requires a secure home network for wired and wireless devices.

The objectives are to:

- Connect all networking devices.
- Configure Internet connectivity.
- Secure the wireless network.
- Verify that all clients can successfully access the Internet.

---

# Prerequisites

## Software

- Cisco Packet Tracer

## Required Knowledge

- Basic networking concepts
- IPv4 addressing
- Ethernet cabling
- DHCP fundamentals

---

# Network Topology

Insert the network topology diagram here.

---

# Technologies Used

| Technology | Purpose |
|------------|---------|
| IPv4 | Network addressing |
| Ethernet | Wired communication |
| DHCP | Automatic IP assignment |
| TCP/IP | Network communication |
| Wireless LAN | Wireless connectivity |
| WPA2 Personal | Wireless security |

---

# Implementation

## Physical Connectivity

- Connected the cable modem to the cable splitter.
- Connected the cable modem to the wireless router using a copper straight-through cable.
- Connected both desktop computers to the router using Ethernet cables.

## Router Configuration

- Accessed the router's web management interface.
- Configured DHCP.
- Limited the DHCP pool to 10 clients.
- Changed the default administrator password.
- Configured the wireless SSID.
- Enabled WPA2 Personal security.
- Configured the wireless passphrase.

## Client Configuration

- Configured Office PC for DHCP.
- Configured Bedroom PC for DHCP.
- Connected the laptop to the wireless network.
- Verified all devices received valid IP addresses.

---

# Verification & Testing

The following tests were performed:

- Office PC successfully received an IPv4 address.
- Bedroom PC successfully received an IPv4 address.
- Laptop successfully connected to the wireless network.
- All devices successfully accessed the Internet.
- Verified successful connectivity using the Packet Tracer web browser.

---

# Troubleshooting

| Issue | Cause | Resolution |
|------|------|------------|
| Example: No IP Address Assigned | DHCP lease not completed | Used Fast Forward Time to complete DHCP negotiation |

> If no issues were encountered during the lab, state:
>
> **No configuration issues were encountered during implementation.**

---

# Key Takeaways

- A home router performs multiple networking functions including routing, switching, DHCP and wireless access.
- DHCP simplifies network administration by automatically assigning IP addresses.
- Default router credentials should always be changed.
- WPA2 provides stronger wireless security than an open wireless network.

---

# Skills Demonstrated

- Network cabling
- Router configuration
- DHCP configuration
- Wireless LAN configuration
- Wireless security implementation
- Connectivity verification
- Basic troubleshooting
- Technical documentation

---

# Evidence

## Packet Tracer File

- HomeNetwork.pkt

## Screenshots

- Physical topology
- Router GUI
- DHCP configuration
- Wireless configuration
- Successful client connectivity

## Diagrams

- Home Network Topology

---

# Next Steps

- Configure static IPv4 addressing.
- Compare DHCP and Static IP addressing.
- Learn subnetting.
- Configure multiple VLANs.
- Configure routing between networks.