# Default Gateway

- The method that a host uses to send messages to a destination on a remote network differs from the way a host sends messages on the same local network.
- When a host needs to send a message to another host located on the same network, it will forward the message directly.
- A host will use ARP to discover the MAC address of the destination host.
- The IPv4 packet contains the destination IPv4 address and encapsulates the packet into a frame containing the MAC address of the destination and forwards it out.
- When a host needs to send a message to a remote network, it must use the router.
- The host includes the IP address of the destination host within the packet just like before.
- However, when it encapsulates the packet into a frame, it uses the MAC address of the router as the destination for the frame.
- In this way, the router will receive and accept the frame based on the MAC address.

## How does the source host determine the MAC address of the router?

- A host is given the IPv4 address of the router through the default gateway address configured in its TCP/IP settings.
- The default gateway address is the address of the router interface connected to the same local network as the source host.
- All hosts on the local network use the default gateway address to send messages to the router.
- When the host knows the default gateway IPv4 address, it can use ARP to determine the MAC address.
- The MAC address of the router is then placed in the frame, destined for another network.
- It is important that the correct default gateway be configured on each host on the local network.
- If no default gateway is configured in the host TCP/IP settings, or if the wrong default gateway is specified, messages addressed to hosts on remote networks cannot be delivered.
