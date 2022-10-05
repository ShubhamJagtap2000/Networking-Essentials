# IPv4 - IPv6 coexistence

- There is no specific date to move to IPv6. 
- Both IPv4 and IPv6 will coexist in the near future and the transition is taking several years. 
- The IETF has created various protocols and tools to help network administrators migrate their networks to IPv6. 
- The migration techniques can be divided into three categories:

1. Dual Stack

- Dual stack allows IPv4 and IPv6 to coexist on the same network segment. 
- Dual stack devices run both IPv4 and IPv6 protocol stacks simultaneously. 
- Known as native IPv6, this means the customer network has an IPv6 connection to its ISP and is able to access content found on the internet over IPv6.

![Screenshot (639)](https://user-images.githubusercontent.com/63872951/173182193-395013aa-f8e2-4198-9d9a-8e79b1080e4d.png)

2. Tunneling

- Tunneling is a method of transporting an IPv6 packet over an IPv4 network. 
- The IPv6 packet is encapsulated inside an IPv4 packet, similar to other types of data.

![Screenshot (640)](https://user-images.githubusercontent.com/63872951/173182211-36491b8e-474c-4b78-b7a3-e4a5de409a3a.png)

3. Translation

- Network Address Translation 64 (NAT64) allows IPv6-enabled devices to communicate with IPv4-enabled devices using a translation technique similar to NAT for IPv4. 
- An IPv6 packet is translated to an IPv4 packet and an IPv4 packet is translated to an IPv6 packet. 
- The NAT64 router translates the different IP addresses between networks (the solid line) so that the PCs with different IP addresses can communicate (the dotted line).

![Screenshot (642)](https://user-images.githubusercontent.com/63872951/173182350-46bdcbce-059f-4ed9-be71-3f35bab7d895.png)
