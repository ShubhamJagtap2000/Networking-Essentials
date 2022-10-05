# Denial of Service (DoS)

- DoS attacks are aggressive attacks on an individual computer or groups of computers with the intent to deny services to intended users. 
 
- DoS attacks can target end user systems, servers, routers, and network links. DoS attacks are relatively simple and can be initiated by an unskilled threat actor.

A threat actor uses a DoS attack to perform these functions:

    1. Flood a network, host, or application with traffic to prevent legitimate network traffic from flowing.
    2. Disrupt connections between a client and server to prevent access to a service.

- There are several types of DoS attacks. Security administrators need to be aware of the types of DoS attacks that can occur and ensure that their networks are protected. 

These are two common DoS attacks:

    1. SYN (synchronous) flooding - This is when a flood of packets are sent to a server requesting a client connection. The packets contain invalid source IP addresses. The server becomes occupied trying to respond to these fake requests and therefore cannot respond to legitimate ones.
    2. Ping of death - This is when a packet that is greater in size than the maximum allowed by IP (65,535 bytes) is sent to a device. This can cause the receiving system to crash.
