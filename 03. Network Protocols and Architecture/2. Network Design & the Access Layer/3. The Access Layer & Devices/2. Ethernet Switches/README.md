# Ethernet Switches

- An Ethernet switch is a device that is used at the access layer.
- When a host sends a message to another host connected to the same switched network, the switch accepts and decodes the frames to read the physical (MAC) address portion of the message.
- A table on the switch, called a MAC address table, contains a list of all of the active ports and the host MAC addresses that are attached to them.
- When a message is sent between hosts, the switch checks to see if the destination MAC address is in the table.
- If it is, the switch builds a temporary connection, called a circuit, between the source and destination ports.
- This new circuit provides a dedicated channel over which the two hosts can communicate.
- Other hosts attached to the switch do not share bandwidth on this channel and do not receive messages that are not addressed to them.
- A new circuit is built for every new conversation between hosts.
- These separate circuits allow many conversations to take place at the same time, without collisions occurring.
- Ethernet switches also allow for the sending and receiving of frames over the same Ethernet cable simultaneously.
- This improves the performance of the network by eliminating collisions. 
