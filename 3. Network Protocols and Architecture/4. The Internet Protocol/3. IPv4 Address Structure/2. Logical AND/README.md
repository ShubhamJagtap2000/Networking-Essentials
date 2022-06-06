# Logical AND

- A logical AND is one of three basic binary operations used in digital logic.
- The other two are OR and NOT.
- Although all three are used in data networks, only AND is used in determining the network address.
- Therefore, our discussion here will be limited to the logical AND operation.
- To identify the network address of an IPv4 host, the IPv4 address is logically ANDed, bit by bit, with the subnet mask.
- ANDing between the address and the subnet mask yields the network address.
- To illustrate how AND is used to discover a network address, consider a host with IPv4 address 192.168.10.10 and subnet mask of 255.255.255.0.
- The following figure displays the host IPv4 address and converted binary address.
- The host subnet mask binary address is ANDed.

![Screenshot (619)](https://user-images.githubusercontent.com/63872951/172184032-52fa8dba-47a2-4749-9a2c-ac12b677f793.png)

