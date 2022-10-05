# UDP - Best Effort Delivery

- In some cases, the TCP acknowledgment protocol is not required and actually slows down information transfer, as shown in the figure. 
- In those cases, UDP may be a more appropriate transport protocol.
- UDP is a 'best effort' delivery system that does not require acknowledgment of receipt. 
- UDP is preferable with applications such as streaming audio and voice over IP (VoIP). 
- Acknowledgments would slow down delivery and retransmissions are undesirable.
- An example of an application that uses UDP is internet radio. 
- If some of the message is lost during its journey over the network, it is not retransmitted. 
- If a few packets are missed, the listener might hear a slight break in the sound. 
- If TCP were used and the lost packets were resent, the transmission would pause to receive them, and the disruption would be more noticeable.
- To illustrate how UDP is used, consider how a host resolves domain names to IP addresses using DNS. 
- DNS does not require the services of TCP because most DNS queries are resolved in one packet. 
- DNS will use UDP to resolve a name. The example in the figure illustrates this. 
- Notice how the client does not know the IP address of www.cisco.com. 
- It therefore sends a DNS request to the DNS server using UDP. 
- The server responds with the IP address of cisco.com in one packet.

![Screenshot (648)](https://user-images.githubusercontent.com/63872951/173415655-8177c0bf-c7d2-4e47-baf5-c767308425d1.png)

**The client uses UDP to send a DNS request to the**\
**The DNS server uses UDP to respond**
