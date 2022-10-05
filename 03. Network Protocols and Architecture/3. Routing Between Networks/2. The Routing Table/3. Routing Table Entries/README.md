# Routing Table Entries

- Routers move information between local and remote networks.
- To do this, routers must use routing tables to store information.
- Routing tables are not concerned with the addresses of individual hosts.
- Routing tables contain the addresses of networks, and the best path to reach those networks.
- Entries can be made to the routing table in two ways:
  
  - dynamically updated by information received from other routers in the network,
  - or manually entered by a network administrator 

- Routers use the routing tables to determine which interface to use to forward a message to its intended destination.
- If the router cannot determine where to forward a message, it will drop it.
- Network administrators configure a static default route that is placed into the routing table so that a packet will not be dropped due to the destination network not being in the routing table.
- A default route is the interface through which the router forwards a packet containing an unknown destination IP network address.
- This default route usually connects to another router that can forward the packet towards its final destination network.
