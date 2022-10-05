# Dividing Local Network - Criteria

- As networks grow, it is often necessary to divide one access layer network into multiple access layer networks.
- There are many ways to divide networks based on different criteria: 

    - Broadcast containment
    - Security requirements
    - Physical locations
    - Logical grouping

- The distribution layer connects these independent local networks and controls the traffic flowing between them.
- It is responsible for ensuring that traffic between hosts on the local network stays local.
- Only traffic that is destined for other networks is passed on.
- The distribution layer can also filter incoming and outgoing traffic for security and traffic management.
- Networking devices that make up the distribution layer are designed to interconnect networks, not individual hosts.
- Individual hosts are connected to the network via access layer devices, such as switches.
- The access layer devices are connected to each other via the distribution layer device, such as a router.

## 1. Broadcast Containment

- Routers in the distribution layer can limit broadcasts to the local network where they need to be heard.
- Although broadcasts are necessary, too many hosts connected on the same local network can generate excessive broadcast traffic and slow down the network.

![Screenshot (604)](https://user-images.githubusercontent.com/63872951/171689109-5ea63647-be49-458d-b80d-4ca4e4f31c48.png)


## 2. Security

- Routers in the distribution layer can separate and protect certain groups of computers where confidential information resides.
- Routers can also hide the addresses of internal computers from the outside world to help prevent attacks, and control who can get into or out of the local network.

![Screenshot (605)](https://user-images.githubusercontent.com/63872951/171690060-4eebed35-d007-4c1e-8964-b38443f0a916.png)


## 3. Locations

- Routers in the distribution layer can be used to interconnect local networks at various locations of an organization that are geographically separated.

![Screenshot (606)](https://user-images.githubusercontent.com/63872951/171690646-e14233c7-2eca-48e1-8d45-d70447e67910.png)

## 4. Logical Grouping

- Routers in the distribution layer can be used to logically group users, such as departments within a company, who have common needs or for access to resources.

![Screenshot (607)](https://user-images.githubusercontent.com/63872951/171691231-906c0b87-d171-4005-a659-3b00b9305aaf.png)



