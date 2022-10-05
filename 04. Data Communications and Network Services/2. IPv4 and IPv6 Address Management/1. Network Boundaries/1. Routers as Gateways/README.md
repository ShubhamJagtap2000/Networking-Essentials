# Routers as Gateways

- The router provides a gateway through which hosts on one network can communicate with hosts on different networks.
- Each interface on a router is connected to a separate network.
- The IPv4 address assigned to the interface identifies which local network is connected directly to it.
- Every host on a network must use the router as a gateway to other networks. 
- Therefore, each host must know the IPv4 address of the router interface connected to the network where the host is attached.
- This address is known as the default gateway address.
- It can be either statically configured on the host, or received dynamically by DHCP.
- When a wireless router is configured to be a DHCP server for the local network, it automatically sends the correct interface IPv4 address to the hosts as the default gateway address.
- In this manner, all hosts on the network can use that IPv4 address to forward messages to hosts located at the ISP and get access to hosts on the internet.
- Wireless routers are usually set to be DHCP servers by default.
- The IPv4 address of that local router interface becomes the default gateway address for the host configuration.
- The default gateway is provided, either statically or by DHCP.
- When a wireless router is configured as a DHCP server, it provides its own internal IPv4 address as the default gateway to DHCP clients.
- It also provides them with their respective IPv4 address and subnet mask, as shown in the figure.

![Screenshot (629)](https://user-images.githubusercontent.com/63872951/172867913-8ecdafe6-e4a1-4446-b73d-3735425735f6.png)
