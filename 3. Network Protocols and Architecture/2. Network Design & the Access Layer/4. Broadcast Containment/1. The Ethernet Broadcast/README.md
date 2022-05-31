# Ethernet Broadcast

- Within the local network it is often necessary for one host to be able to send messages to all the other hosts at the same time.
- This can be done using a message called `broadcast`.
- Broadcasts are useful when a host needs to find information without knowing exactly what other host can supply it, or when a host wants to provide information to all other hosts in the same network in a timely manner.
- A message can only contain one destination MAC address.
- So, how is it possible for a host to contact every other host on the local network without sending out a separate message to each individual MAC?
- To solve this problem, broadcast messages are sent to a unique MAC address that is recognized by all hosts.
- The broadcast MAC address is actually a 48-bit address made up of all ones.
- Because of their length, MAC addresses are usually represented in hexadecimal notation.
- The broadcast MAC address in hexadecimal notation is FFFF.FFFF.FFFF.
- Each F in the hexadecimal notation represents four ones in the binary address.
