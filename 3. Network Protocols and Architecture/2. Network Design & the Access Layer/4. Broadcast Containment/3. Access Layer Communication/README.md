# Access Layer Communication

- On a local Ethernet network, a NIC only accepts a frame if the destination address is either the broadcast MAC address, or else corresponds to the MAC address of the NIC.
- Most network applications, however, rely on the logical destination IP address to identify the location of the servers and clients.
- The figure illustrates the problem that arises if a sending host only has the logical IP address of the destination host.
- How does the sending host determine what destination MAC address to place within the frame?
- The sending host can use an IPv4 protocol called address resolution protocol (ARP) to discover the MAC address of any host on the same local network. 
- IPv6 uses a similar method known as Neighbor Discovery.

![Screenshot (603)](https://user-images.githubusercontent.com/63872951/171256725-99afabfd-77c4-4746-a946-2e2ab7d1bb0b.png)

