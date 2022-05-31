# Broadcast Domains

- When a host receives a message addressed to the broadcast address, it accepts and processes the message as though the message was addressed directly to it.
- When a host sends a broadcast message, switches forward the message to every connected host within the same local network.
- For this reason, a local area network, a network with one or more Ethernet switches, is also referred to as a broadcast domain.
- If too many hosts are connected to the same broadcast domain, broadcast traffic can become excessive.
- The number of hosts and the amount of network traffic that can be supported on the local network is limited by the capabilities of the switches used to connect them.
- As the network grows and more hosts are added, network traffic, including broadcast traffic, increases.
- To improve performance, it is often necessary to divide one local network into multiple networks, or broadcast domains, as shown in the figure.
- Routers are used to divide the network into multiple broadcast domains.

![Screenshot (602)](https://user-images.githubusercontent.com/63872951/171255959-c2c7bb1a-39cd-4b68-a383-41c18c5de2d3.png)

