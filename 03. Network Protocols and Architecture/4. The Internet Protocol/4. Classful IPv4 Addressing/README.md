# Classful and Classless Addressing

- In 1981, internet IPv4 addresses were assigned using classful addressing. 
- Customers were allocated a network address based on one of three classes, A, B, or C.
- The addresses were divided into the following ranges or classes:
    - **Class A (0.0.0.0/8 to 127.0.0.0/8)**: Designed to support extremely large networks with more than 16 million host addresses. It used a fixed /8 prefix (255.0.0.0) with the first octet to indicate the network address and the remaining three octets for host addresses.
    - **Class B (128.0.0.0 /16 - 191.255.0.0 /16)**: Designed to support the needs of moderate to large size networks with up to approximately 65,000 host addresses. It used a fixed /16 prefix (255.255.0.0) with the two high-order octets to indicate the network address and the remaining two octets for host addresses.
    - **Class C (192.0.0.0 /24 - 223.255.255.0 /24)**: Designed to support small networks with a maximum of 254 hosts. It used a fixed /24 prefix (255.255.255.0) with the first three octets to indicate the network and the remaining octet for the host addresses.
   
- **Note:** There is also a Class D multicast block consisting of 224.0.0.0 to 239.0.0.0 and a Class E experimental address block consisting of 240.0.0.0 - 255.0.0.0.

- As shown in the figure, the classful system allocated 50% of the available IPv4 addresses to 128 Class A networks, 25% of the addresses to Class B and then Class C shared the remaining 25% with Class D and E.
- Although appropriate at the time, as the internet grew it was obvious that this method was wasting addresses and depleting the number of available IPv4 network addresses.
- Classful addressing was abandoned in the late 1990s for the newer and current classless addressing system.
- The system in use today is referred to as classless addressing.
- The formal name is Classless Inter-Domain Routing (CIDR, pronounced “cider”).
- With classless addressing, customers receive an IPv4 network address and any size subnet mask, appropriate to the number of hosts required.
- The subnet mask can be any length and is not limited to the three subnet masks used in classful addressing.

![Screenshot (621)](https://user-images.githubusercontent.com/63872951/172224520-f162c84b-f4a4-42b0-a898-dea1de886523.png)

