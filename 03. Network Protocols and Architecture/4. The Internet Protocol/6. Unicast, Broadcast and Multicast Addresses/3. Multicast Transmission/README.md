# Multicast Transmission

- Multicast transmission reduces traffic by allowing a host to send a single packet to a selected set of hosts that subscribe to a multicast group.
- IPv4 has reserved the 224.0.0.0 to 239.255.255.255 addresses as a multicast range.
- The IPv4 multicast addresses 224.0.0.0 to 224.0.0.255 are reserved for multicasting on the local network only.
- These addresses are to be used for multicast groups on a local network.
- A router connected to the local network recognizes that these packets are addressed to a local network multicast group and never forwards them further.
- A typical use of reserved local network multicast address is in routing protocols using multicast transmission to exchange routing information.
- For instance, 224.0.0.9 is the multicast address used by Routing Information Protocol (RIP) version 2 to communicate with other RIPv2 routers.
- Hosts that receive particular multicast data are called multicast clients.
- The multicast clients use services requested by a client program to subscribe to the multicast group.
- Each multicast group is represented by a single IPv4 multicast destination address.
- When an IPv4 host subscribes to a multicast group, the host processes packets addressed to this multicast address, and packets addressed to its uniquely allocated unicast address.
