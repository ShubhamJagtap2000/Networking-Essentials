# Socket Pairs

- The source and destination ports are placed within the segment. 
- The segments are then encapsulated within an IP packet. 
- The IP packet contains the IP address of the source and destination. 
- The combination of the source IP address and source port number, or the destination IP address and destination port number is known as a socket.

![Screenshot (651)](https://user-images.githubusercontent.com/63872951/173615671-ec7546e6-d9df-47c6-ad36-a09f24999524.png)


- In the example in the figure, the PC is simultaneously requesting FTP and web services from the destination server.

- In the example, the FTP request generated by the PC includes the Layer 2 MAC addresses and the Layer 3 IP addresses. 
- The request also identifies the source port number 1305 (dynamically generated by the host) and destination port, identifying the FTP services on port 21. 
- The host also has requested a web page from the server using the same Layer 2 and Layer 3 addresses. 
- However, it is using the source port number 1099 (dynamically generated by the host) and destination port identifying the web service on port 80.

- The socket is used to identify the server and service being requested by the client. A client socket might look like this, with 1099 representing the source port number: 192.168.1.5:1099

- The socket on a web server might be 192.168.1.7:80

- Together, these two sockets combine to form a socket pair: 192.168.1.5:1099, 192.168.1.7:80

- Sockets enable multiple processes, running on a client, to distinguish themselves from each other, and multiple connections to a server process to be distinguished from each other.

- The source port number acts as a return address for the requesting application. 
- The transport layer keeps track of this port and the application that initiated the request so that when a response is returned, it can be forwarded to the correct application.
