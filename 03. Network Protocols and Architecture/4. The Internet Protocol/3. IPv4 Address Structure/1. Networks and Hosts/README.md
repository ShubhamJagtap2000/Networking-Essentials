# Networks and Hosts

- The logical 32-bit IPv4 address is hierarchical and is made up of two parts, the network and the host.
- In the figure, the network portion is blue, and the host portion is red.
- Both parts are required in an IPv4 address. Both networks have the subnet mask 255.255.255.0.
- As an example, there is a host with an IPv4 address 192.168.5.11 with a subnet mask of 255.255.255.0.
- The first three octets, (192.168.5), identify the network portion of the address, and the last octet, (11) identifies the host.
- This is known as hierarchical addressing because the network portion indicates the network on which each unique host address is located.
- Routers only need to know how to reach each network, rather than needing to know the location of each individual host.
- With IPv4 addressing, multiple logical networks can exist on one physical network, if the network portion of the logical network host addresses is different. For example:
    - three hosts on a single, physical local network have the same network portion of their IPv4 address (192.168.18) and three other hosts have different network portions of their IPv4 addresses (192.168.5).

- The hosts with the same network number in their IPv4 addresses will be able to communicate with each other, but will not be able to communicate with the other hosts without the use of routing.
- In this example, there is one physical network and two logical IPv4 networks.
- Another example of a hierarchical network is the telephone system.
- With a telephone number, the country code, area code and exchange represent the network address and the remaining digits represent a local phone number.
 
 ![Screenshot (618)](https://user-images.githubusercontent.com/63872951/172181059-3709730e-c9ca-4e5a-802e-6281b94a9e28.png)



