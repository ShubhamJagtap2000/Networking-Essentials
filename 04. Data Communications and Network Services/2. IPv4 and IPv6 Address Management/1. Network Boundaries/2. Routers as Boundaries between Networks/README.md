# Routers as Boundary Between Networks

- The wireless router acts as a DHCP server for all local hosts attached to it, either by Ethernet cable or wirelessly.
- These local hosts are referred to as being located on an internal, or inside, network.
- Most DHCP servers are configured to assign private addresses to the hosts on the internal network, rather than internet routable public addresses.
- This ensures that, by default, the internal network is not directly accessible from the internet.
- The default IPv4 address configured on the local wireless router interface is usually the first host address on that network.
- Internal hosts must be assigned addresses within the same network as the wireless router, either statically configured, or through DHCP.
- When configured as a DHCP server, the wireless router provides addresses in this range.
- It also provides the subnet mask information and its own interface IPv4 address as the default gateway, as shown in the figure.
- Many ISPs also use DHCP servers to provide IPv4 addresses to the internet side of the wireless router installed at their customer sites
- The network assigned to the internet side of the wireless router is referred to as the external, or outside, network.
- When a wireless router is connected to the ISP, it acts like a DHCP client to receive the correct external network IPv4 address for the internet interface.
- ISPs usually provide an internet-routable address, which enables hosts connected to the wireless router to have access to the internet.
- The wireless router serves as the boundary between the local internal network and the external internet.

![Screenshot (630)](https://user-images.githubusercontent.com/63872951/172899375-1997b17b-a78d-42dc-b543-094db77efa07.png)
