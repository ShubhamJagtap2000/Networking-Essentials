# Control Plane and Data Plane

- A network device contains the following planes: 

  **1. Control plane -** This is typically regarded as the brains of a device. It is used to make forwarding decisions. The control plane contains Layer 2 and Layer 3 route forwarding mechanisms, such as the IPv4 and IPv6 routing tables, and the ARP table. Information sent to the control plane is processed by the CPU.
  
  **2. Data plane -** Also called the forwarding plane, this plane is typically the switch fabric connecting the various network ports on a device. The data plane of each device is used to forward traffic flows. Routers and switches use information from the control plane to forward incoming traffic out the appropriate egress (outgoing) interface. Information in the data plane is typically processed by a special data plane processor without the CPU getting involved.

- The figure illustrates how Cisco Express Forwarding (CEF) uses the control plane and data plane to process packets.

![Screenshot (689)](https://user-images.githubusercontent.com/63872951/175621101-a84dabe6-003e-4ae8-8776-c10fe145bf2e.png)
