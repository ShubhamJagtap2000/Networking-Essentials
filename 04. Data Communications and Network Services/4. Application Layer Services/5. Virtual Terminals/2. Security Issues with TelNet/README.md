# Security issues with the Telnet

- After a Telnet connection is established, users can perform any authorized function on the server, just as if they were using a command line session on the server itself. 
- If authorized, they can start and stop processes, configure the device, and even shut down the system.
- Although the Telnet protocol can require a user to login, it does not support transporting encrypted data. 
- All data exchanged during Telnet sessions is transported as plaintext across the network. 
- This means that the data can be easily intercepted and understood.
- The Secure Shell (SSH) protocol offers an alternate and secure method for server access. 
- SSH provides the structure for secure remote login and other secure network services. 
- It also provides stronger authentication than Telnet and supports transporting session data using encryption. 
- As a best practice, network professionals should always use SSH in place of Telnet, whenever possible.
- The figure illustrates how SSH is more secure than Telnet. 

- Notice how the data captured by the hacker when Telnet is used is clearly readable while the data captured when SSH is used is encrypted and therefore more secure.

![Screenshot (659)](https://user-images.githubusercontent.com/63872951/174448700-24445e63-ee5f-4182-94de-da45ef5217e0.png)
