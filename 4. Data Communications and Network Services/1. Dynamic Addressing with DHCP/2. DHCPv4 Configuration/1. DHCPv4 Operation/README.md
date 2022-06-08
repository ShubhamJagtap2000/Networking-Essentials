# DHCPv4 Operation

- When a host is first configured as a DHCP client, it does not have an IPv4 address, subnet mask, or default gateway.
- It obtains this information from a DHCP server, either on the local network or one located at the ISP.
- The DHCP server is configured with a range, or pool, of IPv4 addresses that can be assigned to DHCP clients.
- The DHCP server may be located on another network.
- DHCP clients are still able to obtain IPv4 addresses as long as the routers in-between are configured to forward DHCP requests.
- A client that needs an IPv4 address will send a DHCP Discover message which is a broadcast with a destination IPv4 address of 255.255.255.255 (32 ones) and a destination MAC address of FF-FF-FF-FF-FF-FF (48 ones).
- All hosts on the network will receive this broadcast DHCP frame, but only a DHCP server will reply. The server will respond with a DHCP Offer, suggesting an IPv4 address for the client.
- The host then sends a DHCP Request asking to use the suggested IPv4 address.
- The server responds with a DHCP Acknowledgment, as shown in the figure.

![Screenshot (627)](https://user-images.githubusercontent.com/63872951/172646257-c4f53253-9ba2-4ad2-a6a5-e725bea2d45d.png)
