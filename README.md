# Router-On-A-Stick-mini-lab
## 📘 Description

In this lab, I implemented inter-VLAN routing using the **Router-on-a-Stick** method in Cisco Packet Tracer. The network includes three departments—Engineering, HR, and Sales—each assigned to a separate VLAN (10, 20, and 30 respectively) and configured with unique IP subnets.

All PCs were manually configured with static IP addresses, subnet masks, and default gateways corresponding to their VLAN subnets. These hosts are connected to a central access switch.

The switchport connected to each end device was configured as an **access port** assigned to the appropriate VLAN. The switchport connecting to the router was configured as a **trunk port**, allowing multiple VLANs to be carried over a single physical link.

On the router, I created **three sub-interfaces**, one for each VLAN, using 802.1Q encapsulation. Each sub-interface was assigned an IP address acting as the default gateway for its corresponding VLAN.

After configuration, I verified connectivity by performing successful **ping tests between hosts in different VLANs**, confirming that inter-VLAN routing was functioning correctly.
