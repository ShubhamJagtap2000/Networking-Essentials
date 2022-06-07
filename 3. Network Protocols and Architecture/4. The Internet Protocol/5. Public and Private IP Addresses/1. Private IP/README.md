# Private IP Address

- Public IPv4 addresses are addresses which are globally routed between ISP (internet service provider) routers.
- However, not all available IPv4 addresses can be used on the internet.
- There are blocks of addresses called private addresses that are used by most organizations to assign IPv4 addresses to internal hosts.
- In the mid-1990s private IPv4 addresses were introduced because of the depletion of IPv4 address space.
- Private IPv4 addresses are not unique and can be used by an internal network.
- Specifically, the private address blocks are:

    - 10.0.0.0 /8 or 10.0.0.0 to 10.255.255.255
    - 172.16.0.0 /12 or 172.16.0.0 to 172.31.255.255
    - 192.168.0.0 /16 or 192.168.0.0 to 192.168.255.255

- It is important to know that addresses within these address blocks are not allowed on the internet and must be filtered (discarded) by internet routers.
- For example, in the figure, users in networks 1, 2, or 3 are sending packets to remote destinations.
- The ISP routers would see that the source IPv4 addresses in the packets are from private addresses and would, therefore, discard the packets.
- **Note:** Private addresses are defined in RFC 1918.
- Most organizations use private IPv4 addresses for their internal hosts.
- However, these RFC 1918 addresses are not routable in the internet and must be translated to a public IPv4 address.
- Network Address Translation (NAT) is used to translate between private IPv4 and public IPv4 addresses.
- This is usually done on the router that connects the internal network to the ISP's network.
- Home routers provide the same capability.
- For instance, most home routers assign IPv4 addresses to their wired and wireless hosts from the private address of 192.168.1.0 /24.
-  The home router interface that connects to the internet service provider (ISP) network is assigned a public IPv4 address.

![Screenshot (622)](https://user-images.githubusercontent.com/63872951/172306575-295580fe-d270-42e7-b586-2b72c4455aad.png)
