# The DMZ

- Many home network devices, such as wireless routers, frequently include multifunction firewall software. 
- This firewall typically provides NAT in addition to IP, application, and website filtering capabilities. 

- They also support demilitarized zone (DMZ) capabilities, as shown in the figure.

![Screenshot (708)](https://user-images.githubusercontent.com/63872951/176943128-4aa6b761-d3bc-47fb-8793-812a381478b7.png)


- In computer networking, a demilitarized zone (DMZ) refers to an area of the network that is accessible and controlled for both internal and external users. 
- It is more secure than the external network but not as secure as the internal network. 
 
- With the wireless router, a simple DMZ can be set up that allows an internal server to be accessible by outside hosts. 
- To accomplish this, the server requires a static IP address that must be specified in the DMZ configuration. 
- The wireless router isolates traffic destined to the IP address specified. 
- This traffic is then forwarded only to the switch port where the server is connected. 
- All other hosts are still protected by the firewall. 
- Game servers and other devices that need to be accessed directly by users located on the internet may need to be configured in the DMZ network.
