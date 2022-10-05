# Calculating Number of Hosts

- The subnet masks we see most often with home and small business networking are: 255.0.0.0 (8-bits), 255.255.0.0 (16 bits) and 255.255.255.0 (24 bits).
- A subnet mask of 255.255.255.0 (decimal) or 11111111.11111111.1111111.00000000 (binary) uses 24 bits to identify the network number which leaves 8 bits to number the hosts on that network, as shown in the figure.
- To calculate the number of hosts that can be on that network, take the number 2 to the power of the number of host bits (2 ^ 8 = 256).
- From this number, we must subtract 2 (256-2).
- The reason we subtract 2 is that all 1s within the host portion of an IPv4 address is a broadcast address for that network and cannot be assigned to a specific host.
- All 0s within the host portion indicate the network ID and again, cannot be assigned to a specific host.
- Powers of 2 can be calculated easily with the calculator that comes with any Windows operating system.
- Another way to determine the number of hosts available is to add up the values of the available host bits (128+64+32+16+8+4+2+1 = 255).
- From this number, subtract 1 (255-1 = 254), because the host bits cannot be all 1s.
- It is not necessary to subtract 2 because the value of all 0s is 0 and is not included in the addition.
- With a 16-bit mask, there are 16 bits (two octets) for host addresses and a host address could have all 1s (255) in one of the octets.
- This might appear to be a broadcast but as long as the other octet is not all 1s, it is a valid host address.
- Remember that the host looks at all host bits together, not at octet values.

![Screenshot (620)](https://user-images.githubusercontent.com/63872951/172185376-4b8f21e6-1d37-4620-8cb2-14f1c8b62348.png)

