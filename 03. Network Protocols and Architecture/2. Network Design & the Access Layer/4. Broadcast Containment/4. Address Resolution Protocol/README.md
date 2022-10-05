# The ARP

- ARP uses a three step process to discover and store the MAC address of a host on the local network when only the IPv4 address of the host is known: 

1. The sending host creates and sends a frame addressed to a broadcast MAC address. Contained in the frame is a message with the IPv4 address of the intended destination host.
2. Each host on the network receives the broadcast frame and compares the IPv4 address inside the message with its configured IPv4 address. The host with the matching IPv4 address sends its MAC address back to the original sending host.
3. The sending host receives the message and stores the MAC address and IPv4 address information in a table called an ARP table.

- When the sending host has the MAC address of the destination host in its ARP table, it can send frames directly to the destination without doing an ARP request.
- Because ARP messages rely on broadcast frames to deliver the requests, all hosts in the local IPv4 network must be in the same broadcast domain.


