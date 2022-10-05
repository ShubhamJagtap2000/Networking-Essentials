# DHCP Server

- If you enter an airport or coffee shop with a wireless hotspot, DHCP makes it possible for you to access the internet.
- As you enter the area, your laptop DHCP client contacts the local DHCP server via a wireless connection.
- The DHCP server assigns an IPv4 address to your laptop.
- Various types of devices can be DHCP servers as long as they are running DHCP service software.
- With most medium to large networks, the DHCP server is usually a local dedicated PC-based server.
- With home networks, the DHCP server may be located at the ISP and a host on the home network receives its IPv4 configuration directly from the ISP, as shown in the figure.

![Screenshot (626)](https://user-images.githubusercontent.com/63872951/172643758-909c8f97-1307-4abf-b173-d2eaf5c31189.png)

- Many home networks and small businesses use a wireless router and modem.
- In this case, the wireless router is both a DHCP client and a server. 
- The wireless router acts as a client to receive its IPv4 configuration from the ISP and then acts as a DHCP server for internal hosts on the local network.
- The router receives the public IPv4 address from the ISP, and in its role as a DHCP server, it distributes private addresses to internal hosts.
- In addition to PC-based servers and wireless routers, other types of networking devices such as dedicated routers can provide DHCP services to clients, although this is not as common.

- **Note:**
  1. DHCP for IPv6 (DHCPv6) provides similar services for IPv6 clients.
  2. One important difference is that DHCPv6 does not provide a default gateway address.
  3. It can only be obtained dynamically from the Router Advertisement message of the router.
