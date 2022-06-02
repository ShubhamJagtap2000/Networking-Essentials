# Routing - Need

- Devices that are beyond the local network segment are known as remote hosts.
- When a source device sends a packet to a remote destination device, then the help of routers and routing is needed.
- `Routing` is the process of identifying the best path to a destination.
- A router is a networking device that connects multiple Layer 3, IP networks.
- At the distribution layer of the network, routers direct traffic and perform other functions critical to efficient network operation.
- Routers, like switches, are able to decode and read the messages that are sent to them.
- Unlike switches, which make their forwarding decision based on the Layer 2 MAC address, routers make their forwarding decision based on the Layer 3 IP address.
- The packet format contains the IP addresses of the destination and source hosts, as well as the message data being sent between them.
- The router reads the network portion of the destination IP address and uses it to find which one of the attached networks is the best way to forward the message to the destination.
- Anytime the network portion of the IP addresses of the source and destination hosts do not match, a router must be used to forward the message.
- If a host located on network 1.1.1.0 needs to send a message to a host on network 5.5.5.0, the host will forward the message to the router.
- The router receives the message, de-encapsulates the Ethernet frame, and then reads the destination IP address in the IP packet.
- It then determines where to forward the message. It re-encapsulates the packet back into a new frame, and forwards the frame on to its destination.

#

![Screenshot (608)](https://user-images.githubusercontent.com/63872951/171694876-3cd5f9e1-121a-4fe8-b9a4-b7623b78cbfd.png)

#

![Screenshot (610)](https://user-images.githubusercontent.com/63872951/171694939-672b31c9-6383-423a-8c1d-29971f599bda.png)

#

![Screenshot (612)](https://user-images.githubusercontent.com/63872951/171694977-4786f219-7632-4e00-8fb8-b059bb3c2376.png)
