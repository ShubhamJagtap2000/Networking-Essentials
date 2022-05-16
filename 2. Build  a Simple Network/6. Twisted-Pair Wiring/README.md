# Twisted-Pair Operation

- The color coding of the wire pairs in an UTP cable is determined by the type of standard that is used to make the cable.
- Different standards have different purposes and are closely governed by the standards organizations.
- For typical Ethernet installations, there are two standards that are widely implemented.
- The `TIA/EIA` organization defines two different patterns, or wiring schemes, called `T568A` and `T568B`, as shown in the figure.
- Each wiring scheme defines the pinout, or order of wire connections, on the end of the cable.

![Screenshot (585)](https://user-images.githubusercontent.com/63872951/168571893-1b919af2-624d-4d94-9ab6-294e3bfce2c6.png)

- On a network installation, one of the two wiring schemes (T568A or T568B) should be chosen and followed.
- It is important that the same wiring scheme is used for every termination in that project.

# Twisted-Pair Transmit & Receive Pairs

- When two devices are directly connected using an UTP Ethernet cable, it is important that the transmit function and the receive function on each end of the cable are reversed.
- One device sends data on a specific set of wires and the device on the other end of the cable listens for the data on the same wires.
- Two devices that use different wires for transmit and receive are known as unlike devices. 
- They require a straight-through cable to exchange data. Straight-through cables have the same color patterns on both ends of the cable.
- Devices that are directly connected and use the same pins for transmit and receive, are known as like devices.
- They require the use of a crossover cable in order to reverse the transmit function and receive function so that the devices can exchange data.
