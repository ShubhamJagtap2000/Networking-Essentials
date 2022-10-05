# Protocol Operations

- A web server and a web client use specific protocols and standards in the process of exchanging information to ensure that the messages are received and understood, as shown in the figure.
- The various protocols necessary to deliver a web page function at the four different levels of the TCP/IP model are as follows: 

## Application Layer Protocol

- Hypertext Transfer Protocol (HTTP) governs the way that a web server and a web client interact. 
- HTTP defines the format of the requests and responses exchanged between the client and server. 
- HTTP relies on other protocols to govern how the messages are transported between client and server.

## Transport Layer Protocol

- Transmission Control Protocol (TCP) ensures that IP packets are sent reliably, and any missing packets are resent. 
- TCP provides proper ordering of packets received out of order.

## Internetwork Layer Protocol

- The most common internetwork protocol is Internet Protocol (IP). 
- IP is responsible for taking the formatted segments from TCP, assigning the logical addressing, and encapsulating them into packets for routing to the destination host.

## Network Access Layer

- The specific protocol at the network access layer, such as Ethernet, depends on the type of media and transmission methods used in the physical network.

![Screenshot (646)](https://user-images.githubusercontent.com/63872951/173409557-354eb98f-0ab5-4477-a9e1-c7dfe2dcdda3.png)
