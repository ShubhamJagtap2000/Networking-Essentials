# Path Selection

**How does the router determine which interface to use to send the message on a path to get to the destination network?**

- Each port, or interface, on a router connects to a different local network.
- Every router contains a table of all locally connected networks and the interfaces that connect to them.
- These routing tables can also contain information about the routes, or paths, that the router uses to reach other remote networks that are not locally attached.
- When a router receives a frame, it decodes the frame to get to the packet containing the destination IP address.
- It matches the network portion of the destination IP address to the networks that are listed in the routing table.
- If the destination network address is in the table, the router encapsulates the packet in a new frame in order to send it out.

(Note that it will insert a new destination MAC address as well, and recalculate the FCS field, in the new frame).

- It forwards the new frame out of the interface associated with the path, to the destination network.
- The process of forwarding the packets toward their destination network is called routing.
- Router interfaces do not forward messages that are addressed to the local network broadcast IP address.
- As a result, local network broadcasts are not sent across routers to other local networks.
