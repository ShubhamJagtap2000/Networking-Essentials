# DHCP Service Configuration

- When a host is first configured as a DHCP client, it does not have an IPv4 address, subnet mask, or default gateway.
- It obtains this information from a DHCP server, either on the local network or one located at the ISP.
- The DHCP server is configured with a range, or pool, of IPv4 addresses that can be assigned to DHCP clients.
- The DHCP server may be located on another network.
- DHCP clients are still able to obtain IPv4 addresses as long as the routers in-between are configured to forward DHCP requests.
- A client that needs an IPv4 address will send a DHCP Discover message which is a broadcast with a destination IPv4 address of 255.255.255.255 (32 ones) and a destination MAC address of FF-FF-FF-FF-FF-FF (48 ones).
- All hosts on the network will receive this broadcast DHCP frame, but only a DHCP server will reply
- The server will respond with a DHCP Offer, suggesting an IPv4 address for the client.
- The host then sends a DHCP Request asking to use the suggested IPv4 address.
- The server responds with a DHCP Acknowledgment, as shown in the figure.

![Screenshot (628)](https://user-images.githubusercontent.com/63872951/172655995-93ba8644-6b08-4e7a-8de9-9edd53e97e68.png)

- The IPv4 address of 192.168.0.1 and subnet mask of 255.255.255.0 are the defaults for the internal router interface.
- This is the default gateway for all hosts on the local network and also the internal DHCP server IPv4 address.
- Most home wireless routers have DHCP Server enabled by default.
- On the DHCP configuration screen a default DHCP range is available.
- You can also specify a starting address for the DHCP range (do not use 192.168.0.1 because the router is assigned this address) and the number of addresses to be assigned.
- The lease time can also be modified (default in the graphic is 24 hours).
- The DHCP configuration feature on most routers gives information about connected hosts and IPv4 addresses, their associated MAC address, and lease times.

