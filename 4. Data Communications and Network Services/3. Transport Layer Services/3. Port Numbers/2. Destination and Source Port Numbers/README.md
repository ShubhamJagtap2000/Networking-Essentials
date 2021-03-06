# Destination and Source Port Numbers

- The source port number is associated with the originating application on the local host. 
- The destination port number is associated with the destination application on the remote host.

## Source Port

- The source port number is dynamically generated by the sending device to identify a conversation between two devices. 
- This process allows multiple conversations to occur simultaneously. 
- It is common for a device to send multiple HTTP service requests to a web server at the same time. 
- Each separate HTTP conversation is tracked based on the source ports.

## Destination Port

- The client places a destination port number in the segment to tell the destination server what service is being requested, as shown in the figure. 
- For example, when a client specifies port 80 in the destination port, the server that receives the message knows that web services are being requested. 
- A server can offer more than one service simultaneously, such as web services on port 80 at the same time that it offers FTP connection establishment on port 21.

![Screenshot (650)](https://user-images.githubusercontent.com/63872951/173614429-a2a73bb1-3dd4-4e2d-b13b-cb7b276c9a1d.png)

- **Well-known ports** `(0 to 1023)` are reserved for common applications and services. 
- **Registered ports** `(1024 to 49151)` are assigned to user processes and applications. 
- **Dynamic, private, or ephemeral ports** `(49152 to 65535)` are assigned to client applications when initiating a connection.
