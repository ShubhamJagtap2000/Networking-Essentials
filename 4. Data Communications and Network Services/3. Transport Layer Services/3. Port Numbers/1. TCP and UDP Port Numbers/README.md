# TCP and UDP Numbers

- There are many services that we access through the internet in the course of a day. 
- DNS, web, email, FTP, IM and VoIP are just some of these services that are provided by client/server systems around the world. 
- These services may be provided by a single server or by several servers in large data centers.
- When a message is delivered using either TCP or UDP, the protocols and services requested are identified by a port number, as shown in the figure. 
- A port is a numeric identifier within each segment that is used to keep track of specific conversations between a client and server. 
- Every message that a host sends contains both a source and destination port.

![image](https://user-images.githubusercontent.com/63872951/173609905-7cc6aa9e-14e5-4ab9-8c70-0c4824e1ad5c.png)

- When a message is received by a server, it is necessary for the server to be able to determine which service is being requested by the client. 
- Clients are preconfigured to use a destination port that is registered on the internet for each service. 
- An example of this is web browser clients which are preconfigured to send requests to web servers using port 80, the well-known port for HTTP web services.
- Ports are assigned and managed by an organization known as the Internet Corporation for Assigned Names and Numbers (ICANN). 
- Ports are broken into three categories and range in number from 1 to 65,535:

    **1. Well-Known Ports -** Destination ports that are associated with common network applications are identified as well-known ports. These ports are in the range of 1 to 1023.
    
    **2. Registered Ports -** Ports 1024 through 49151 can be used as either source or destination ports. These can be used by organizations to register specific applications such as IM applications.
    
    **3. Private Ports -** Ports 49152 through 65535 are often used as source ports. These ports can be used by any application.

- The table displays some common well-known port numbers and their associated applications.

| **Port Number** | **Transport** | **Application Protocol** |
| --- | --- | --- |
| 20 | TCP | File Transfer Protocol(FTP) - Data |
| 21 | TCP | File Transfer Protocol(FTP) - Control |
| 22 | TCP | Secure Shell(SSH) |
| 23 | TCP | TelNet |
| 25 | TCP | Simple Mail Transfer Protocol(SMTP) |
| 53 | UDP, TCP | Domain Name Service(DNS) |
| 67 | UDP | Dynamic Host Configuration Protocol(DHCP) - Server |
| 68 | UDP | Dynamic Host Configuration Protocol(DHCP) - Client |
| 69 | UDP | Trivial File Transfer Protocol(TFTP) |
| 80 | TCP | Hypertext Transfer Protocol(HTTP) |
| 110 | TCP | Post Office Protocol version 3 (POP3) |
| 143 | TCP | Internet Message Access Protocol(IMAP) |
| 161 | UDP | Simple Network Management Protocol(SNMP) |
| 443 | TCP | Hypertext Transfer Protocol Secure(HTTPS) |
