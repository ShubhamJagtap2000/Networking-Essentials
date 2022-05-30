# Ethernet Hubs

- As Ethernet networks became more popular, connecting everyone on a single cable was no longer practical, nor even possible.
- Engineers developed a different type of network technology that made it easier to connect and reconnect multiple devices to the network.
- Hubs contain multiple ports that are used to connect hosts to the network.
- Hubs are simple devices that do not have the necessary electronics to decode the messages sent between hosts on the network.
- Hubs cannot determine which host should get any particular message.
- A hub simply accepts electronic signals from one port and regenerates (or repeats) the same message out all of the other ports.
- All hosts attached to the hub share the bandwidth, and will receive the message.
- Hosts ignore the messages that are not addressed to them.
- Only the host specified in the destination address of the message processes the message and responds to the sender.
- Only one message can be sent through an Ethernet hub at a time.
- It is possible for two or more hosts connected to a hub to attempt to send a message at the same time. If this happens, the electronic signals that make up the messages collide with each other at the hub. This is known as a `collision`.
- The message is unreadable by hosts and must be retransmitted.
- The area of the network where a host can receive a garbled message resulting from a collision is known as a collision domain.
- Because excessive retransmissions can clog up the network and slow down network traffic, hubs are now considered obsolete and have been replaced by Ethernet switches.
