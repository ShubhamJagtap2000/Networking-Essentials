# Cisco LAN Switches

- When a LAN network grows to the point where the four Ethernet ports provided by the wireless router are not enough for all of the devices that need to attach to the wired network, it is time to add a LAN switch to the network. 
- A switch can provide connectivity at the access layer of a network, connecting devices to a LAN. 
- A switch can allow the network to grow without replacing central devices. 
- When choosing a switch, there are a number of factors to consider, including the following:

## 1. Types of Ports

- When selecting a switch for your LAN, choosing the appropriate number and type of ports is critical. 
- Most lower-cost switches support only copper twisted-pair interface ports. 
- Higher priced switches may have fiber-optic connections. 
- These are used to link the switch to other switches that may be located over long distances. 

- The Cisco Catalyst 9300 series has a variety of options depending on your environment.

![Screenshot (713)](https://user-images.githubusercontent.com/63872951/177094370-5ced44c0-7cc8-4135-867c-80a0ad6d339f.png)


## 2. Speed Required

- Ethernet twisted-pair interfaces on a switch have defined speeds. 
- A 10/100 Ethernet port can only function at either 10 megabits per second (Mbps), or at 100 Mbps. 
- What this means is that even if the device that you are connecting to the 10/100 switch interface port is capable of connecting at gigabit speeds, the maximum speed at which it will be able to communicate will be 100 Mbps. 
- Switches may also include gigabit Ethernet ports. 
- If your Internet connection is more than 100 Mbps, then a gigabit port is necessary to take advantage of the higher Internet bandwidth. 
- Gigabit Ethernet ports will also operate at 10/100 Mbps. 
- Gigabit Ethernet is sometimes represented as 1000 Mbps. 

- The Cisco Catalyst 9300 48S switch in the figure has two 40 Gbps uplink ports to provide a fast path for the 48 ports to access the rest of the network and the internet.

- Similar to a switch port, Ethernet NICs operate at specific bandwidths such as 10/100 or 10/100/1000 Mbps. 
- The actual bandwidth of the attached device will be the highest common bandwidth between the NIC on the device and the switch port.

![Screenshot (714)](https://user-images.githubusercontent.com/63872951/177094519-791281bf-d116-465b-af8d-a0f206f7512d.png)


## 3. Expandability

- Networking devices come in both fixed and modular physical configurations. 
- Fixed configurations have a specific type and number of ports or interfaces. 
- Modular devices have expansion slots that provide the flexibility to add new modules as required. 

- The figure shows a Cisco Catalyst 9600 chassis in which you can install different configurations of hardware to address your particular environment.

![Screenshot (715)](https://user-images.githubusercontent.com/63872951/177094732-e26d59fd-cdcc-42be-a91c-a5dc01ba36e9.png)

## 4. Manageability

- Many basic, inexpensive switches are not configurable. 
- A managed switch that uses a Cisco operating system enables control over individual ports or over the switch as a whole. 
- Controls include the ability to change the settings for a device, add port security, and monitor performance. 
- The network administrator directly connects to a Cisco Catalyst switch using a console cable.
