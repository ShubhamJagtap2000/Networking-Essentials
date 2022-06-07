# Broadcast Transmission

- Broadcast packets are sent to all hosts in the network using a broadcast address. With a broadcast, the packet contains a destination IPv4 address with all ones (1s) in the host portion.
- This means that all hosts on that local network (broadcast domain) will receive and look at the packet.
- Many network protocols, such as DHCP, use broadcasts.
- When a host receives a packet sent to the network broadcast address, the host processes the packet as it would a packet addressed to its unicast address.
- Broadcast may be directed or limited.
- A directed broadcast is sent to all hosts on a specific network.
- For example, a host on the 172.16.4.0/24 network sends a packet to 172.16.4.255.
- A limited broadcast is sent to 255.255.255.255. By default, routers do not forward broadcasts.
- When a packet is broadcast, it uses resources on the network and causes every receiving host on the network to process the packet.
- Therefore, broadcast traffic should be limited so that it does not adversely affect the performance of the network or devices.
- Because routers separate broadcast domains, subdividing networks can improve network performance by eliminating excessive broadcast traffic.
