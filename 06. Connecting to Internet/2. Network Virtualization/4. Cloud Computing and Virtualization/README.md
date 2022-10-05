# Cloud Computing and Virtualization

- The terms “cloud computing” and “virtualization” are often used interchangeably; however, they mean different things. 

- Virtualization is the foundation of cloud computing. Without it, cloud computing, as it is most-widely implemented, would not be possible.

- Over a decade ago, VMware developed a virtualizing technology that enabled a host OS to support one or more client OSs. 
 
- Most virtualization technologies are now based on this technology. 
- The transformation of dedicated servers to virtualized servers has been embraced and is rapidly being implemented in data center and enterprise networks.

- Virtualization means creating a virtual rather than physical version of something, such as a computer. 
- An example would be running a "Linux computer" on your Windows PC, which you will do later in the lab.

- To fully appreciate virtualization, it is first necessary to understand some of the history of server technology. 
- Historically, enterprise servers consisted of a server OS, such as Windows Server or Linux Server, installed on specific hardware, as shown in the figure. 

- All server RAM, processing power, and hard drive space were dedicated to the service provided (e.g., web, email services, etc.).


## Dedicated Servers
![Screenshot (685)](https://user-images.githubusercontent.com/63872951/175615187-df52926a-61c1-40e1-ac8e-c6353929362e.png)


- The major `problem` with this configuration is that when a component fails, the service that is provided by this server becomes unavailable. 
- This is known as a single point of failure. 
- Another problem was that dedicated servers were underused. 
- Dedicated servers often sat idle for long periods of time, waiting until there was a need to deliver the specific service they provide. 
- These servers wasted energy and took up more space than was warranted by the amount of service provided. 
- This is known as server sprawl.
