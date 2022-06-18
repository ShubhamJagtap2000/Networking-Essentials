# Telnet

- Long before desktop computers with sophisticated graphical interfaces existed, people used text-based systems which were often just display terminals physically attached to a central computer. 
- After networks became available, people needed a way to remotely access the computer systems in the same manner that they did with the directly-attached terminals.
- Telnet was developed to meet that need. 
- Telnet dates back to the early 1970s and is among the oldest of the application layer protocols and services in the TCP/IP suite. 
- Telnet provides a standard method of emulating text-based terminal devices over the data network. 
- Both the protocol itself and the client software that implements the protocol are commonly referred to as Telnet. 
- Telnet servers listen for client requests on TCP port 23.
- Appropriately enough, a connection using Telnet is called a virtual terminal (vty) session, or connection. 
- Rather than using a physical device to connect to the server, Telnet uses software to create a virtual device that provides the same features of a terminal session with access to the server’s command line interface (CLI).
- In the figure, the client has remotely connected to the server via Telnet. The client is now able to execute commands as if it were locally connected to the server.

![Screenshot (658)](https://user-images.githubusercontent.com/63872951/174448548-dbac0f16-2370-4866-a52f-fa33057f11aa.png)

- **Note:** Telnet is not considered to be a secure protocol. SSH should be used in most environments instead of Telnet. Telnet is used in several examples in this course for simplicity of configuration.

