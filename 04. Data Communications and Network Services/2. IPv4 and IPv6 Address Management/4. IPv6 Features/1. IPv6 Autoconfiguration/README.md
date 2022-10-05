# IPv6 Autoconfiguration

- Stateless Address Autoconfiguration (SLAAC) allows a host to create its own internet-routable address (global unicast address or GUA), without the need for a DHCP server.
- As shown in the figure, with the default method the host receives the prefix (network address), prefix length (subnet mask), and default gateway from the Router Advertisement message of the router.
- The host can then create its own unique interface ID (host portion of the address) to give itself a routable global unicast address.

![Screenshot (643)](https://user-images.githubusercontent.com/63872951/173182503-513c6496-2cb8-4922-b3c9-407df31ba966.png)

