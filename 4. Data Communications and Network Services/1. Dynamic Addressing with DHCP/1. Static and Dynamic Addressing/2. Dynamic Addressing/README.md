# Dynamic IPv4 Address Assignment

- On local networks it is often the case that the user population changes frequently.
- New users arrive with laptops and need a connection.
- Others have new workstations that need to be connected.
- Rather than have the network administrator assign IPv4 addresses for each workstation, it is easier to have IPv4 addresses assigned automatically.
- This is done using a protocol known as Dynamic Host Configuration Protocol (DHCP).
- DHCP automatically assigns addressing information such as IPv4 address, subnet mask, default gateway, and other configuration information, as shown in the figure.
- DHCP is generally the preferred method of assigning IPv4 addresses to hosts on large networks because it reduces the burden on network support staff and virtually eliminates entry errors.
- Another benefit of DHCP is that an address is not permanently assigned to a host but is only leased for a period of time.
- If the host is powered down or taken off the network, the address is returned to the pool for reuse.
- This is especially helpful with mobile users that come and go on a network.

![Screenshot (625)](https://user-images.githubusercontent.com/63872951/172642688-9da4cff5-a72e-4f03-a3cb-b4987d60174b.png)
