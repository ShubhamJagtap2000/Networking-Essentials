# Access, Distribution and Core Layer

## 1. Access Layer:

- The access layer provides a connection point for end user devices to the network and allows multiple hosts to connect to other hosts through a network device, usually a switch, such as the Cisco 2960-XR, or a wireless access point.
- Typically, all devices within a single access layer will have the same network portion of the IP address.
- If a message is destined for a local host, based on the network portion of the IP address, the message remains local.
- If it is destined for a different network, it is passed up to the distribution layer.
- Switches provide the connection to the distribution layer devices, usually a Layer 3 device such as a router or Layer 3 switch.

## 2. Distribution Layer:

- The distribution layer provides a connection point for separate networks and controls the flow of information between the networks.
- It typically contains more powerful switches, such as the Cisco C9300 series, than the access layer as well as routers for routing between networks.
- Distribution layer devices control the type and amount of traffic that flows from the access layer to the core layer.

## 3. Core Layer:

- The core layer is a high-speed backbone layer with redundant (backup) connections.
- It is responsible for transporting large amounts of data between multiple end networks.
- Core layer devices typically include very powerful, high-speed switches and routers, such as the Cisco Catalyst 9600.
- The main goal of the core layer is to transport data quickly.
