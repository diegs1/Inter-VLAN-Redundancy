OVERVIEW:
Implementation of a small enterprise-style campus network using VLAN segmentation, inter-VLAN routing, HSRP for gateway redundancy, and DHCP services for automated IP addressing.

Key Concepts
- Inter-VLAN Routing
- HSRP Configuration (MLS1 & MLS2) - Implemented Hot Standby Router Protocol to provide gateway redundancy. VLANs were load-balanced by assigning active roles across both multilayer switches.
- DHCP Configuration (MLS1)
- VLAN Segmentation & Trunking


Result
- All PCs successfully receive IP addresses via DHCP.
- Devices within and across VLANs can communicate.
- HSRP provides redundancy with seamless failover between multilayer switches.
- Load balancing is achieved by distributing active VLAN gateways across both MLS devices.
- End-to-end connectivity verified using ping and traceroute tests.

What I Learned
- How HSRP provides default gateway redundancy and ensures high availability.
- How to verify failover and network functionality using show commands and connectivity tests.
- The importance of proper network design for scalability, redundancy, and reliability.
