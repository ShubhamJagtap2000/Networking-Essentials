# Packet Forwarding

- A router forwards a packet to one of two places: a directly connected network containing the actual destination host, or to another router on the path to reach the destination host.
- When a router encapsulates the frame to forward it out an Ethernet interface, it must include a destination MAC address.
- This is the MAC address of the actual destination host, if the destination host is part of a network that is locally connected to the router.
- If the router must forward the packet to another router through an Ethernet interface, it will use the MAC address of the connected router. Routers obtain these MAC addresses from ARP tables.
- Each router interface is part of the local network to which it is attached and maintains its own ARP table for that network.
- The ARP tables contain the MAC addresses and IPv4 addresses of all the individual hosts on that network.
