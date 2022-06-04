# Local and Remote Network Segments

- Within a LAN, it is possible to place all hosts on a single local network or divide them up between multiple networks connected by a distribution layer device.
- How this placement is determined depends on desired results.

## Hosts on a Remote Segment

- Placing additional hosts on a remote network will decrease the impact of traffic demands.
- However, hosts on one network will not be able to communicate with hosts on the other without the use of routing.
- Routers increase the complexity of the network configuration and can introduce latency, or time delay, on packets sent from one local network to the other.

**Advantages:**

1. More appropriate for larger, more complex networks
2. Splits up broadcast domains and decreases traffic
3. Can improve performance on each segment
4. Makes the machines invisible to those on other local network segments
5. Can provide increased security
6. Can improve network organization

**Disadvantages:**

1. Requires the use of routing (distribution layer)
2. Router can slow traffic between segments
3. More complexity and expense (requires a router)

![Screenshot (614)](https://user-images.githubusercontent.com/63872951/172019516-449c41a2-b1bd-437f-b0a5-4b7903d917d8.png)

## All Hosts in One Local Segment

- Placing all hosts on a single local network allows them to be seen by all other hosts.
- This is because there is one broadcast domain and hosts use ARP to find each other.
- In a simple network design, it may be beneficial to keep all hosts within a single local network.
- However, as networks grow in size, increased traffic will decrease network performance and speed.
- In this case, it may be beneficial to move some hosts onto a remote network.

**Advantages:**

1. Appropriate for simpler networks
2. Less complexity and lower network cost
3. Allows devices to be "seen" by other devices
4. Faster data transfer - more direct communication
5. Ease of device access

**Disadvantages:**

1. All hosts are in one broadcast domain which causes more traffic on the segment and may slow network performance
2. Harder to implement QoS
3. Harder to implement security

![Screenshot (615)](https://user-images.githubusercontent.com/63872951/172019691-d404c998-2741-4958-a819-61e8f96663cf.png)
