# The MAC Address Table

- If the destination MAC address is not in the table, the switch does not have the necessary information to create an individual circuit.
- When the switch cannot determine where the destination host is located, it uses a process called `flooding` to forward the message out to all attached hosts except for the sending host.
- Each host compares the destination MAC address in the message to its own MAC address, but only the host with the correct destination address processes the message and responds to the sender.

**How does the MAC address of a new host get into the MAC address table?**

- A switch builds the MAC address table by examining the source MAC address of each frame that is sent between hosts.
- When a new host sends a message or responds to a flooded message, the switch immediately learns its MAC address and the port to which it is connected.
- The table is dynamically updated each time a new source MAC address is read by the switch.
- In this way, a switch quickly learns the MAC addresses of all attached hosts.
