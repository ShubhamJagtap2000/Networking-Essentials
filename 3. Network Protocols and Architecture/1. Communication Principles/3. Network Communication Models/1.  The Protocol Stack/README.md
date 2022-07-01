# The Protocol Stack

- Successful communication between hosts requires interaction between a number of protocols. 
- These protocols are implemented in software and hardware that are installed on each host and networking device.

- The interaction between the different protocols on a device can be illustrated as a protocol stack, as shown in the figure. 


![Screenshot (709)](https://user-images.githubusercontent.com/63872951/176952752-626db78b-88bc-4a01-8a52-79addd5df752.png)





- A stack illustrates the protocols as a layered hierarchy, with each higher-level protocol depending on the services of the protocols shown in the lower levels.

- The separation of functions enables each layer in the stack to operate independently of others. 
- For example, you can use your laptop computer connected to a cable modem at home to access your favorite website, or view the same website on your laptop using a wireless connection at the library. 
- The function of the web browser is not affected by the change in the physical location, nor the method of connectivity.

## The protocols in the figure are described as follows:

**1. Hypertext Transfer Protocol (HTTP) -** This protocol governs the way a web server and a web client interact. HTTP defines the content and formatting of the requests and responses that are exchanged between the client and server. Both the client and the web server software implement HTTP as part of the application. HTTP relies on other protocols to govern how the messages are transported between the client and server.

**2. Transmission Control Protocol (TCP) -** This protocol manages the individual conversations. TCP is responsible for guaranteeing the reliable delivery of the information and managing flow control between the end devices.

**3. Internet Protocol (IP) -** This protocol is responsible for delivering messages from the sender to the receiver. IP is used by routers to forward the messages across multiple networks.

**4. Ethernet -** This protocol is responsible for the delivery of messages from one NIC to another NIC on the same Ethernet local area network (LAN).
