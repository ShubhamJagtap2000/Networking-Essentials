# File Transfer Protocol

- In addition to web services, another common service used across the internet is one that allows users to transfer files.
- The File Transfer Protocol (FTP) provides an easy method to transfer files from one computer to another. 
- A host running FTP client software can access an FTP server to perform various file management functions including file uploads and downloads.
- The FTP server enables a client to exchange files between devices. 
- It also enables clients to manage files remotely by sending file management commands such as delete or rename. 
- To accomplish this, the FTP service uses two different ports to communicate between client and server.
- The example in the figure illustrates how FTP operates. 
- To begin an FTP session, control connection requests are sent to the server using destination TCP port 21. 
- When the session is opened, the server uses TCP port 20 to transfer the data files.

![Screenshot (655)](https://user-images.githubusercontent.com/63872951/174239574-a4e0de78-7a18-45fd-88e3-134c47971d94.png)

- FTP client software is built into computer operating systems and into most web browsers. 
- Stand-alone FTP clients offer many options in an easy-to-use GUI-based interface.
- Based on commands sent across the control connection, data can be downloaded from the server or uploaded from the client.
