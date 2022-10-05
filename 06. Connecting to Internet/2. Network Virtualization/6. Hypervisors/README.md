# Hypervisors 

- The hypervisor is a program, firmware, or hardware that adds an abstraction layer on top of the physical hardware. 

- The abstraction layer is used to create virtual machines which have access to all the hardware of the physical machine such as CPUs, memory, disk controllers, and NICs. 

- Each of these virtual machines runs a complete and separate operating system. 
- With virtualization, it is not uncommon for 100 physical servers to be consolidated as virtual machines on top of 10 physical servers that are using hypervisors. 

## Type 1 Hypervisor - "Bare Metal" Approach

- Type 1 hypervisors are also called the “bare metal” approach because the hypervisor is installed directly on the hardware. 
- Type 1 hypervisors are usually used on enterprise servers and data center networking devices.

- With Type 1 hypervisors, the hypervisor is installed directly on the server or networking hardware. 
- Then, instances of an OS are installed on the hypervisor, as shown in the figure. 

- Type 1 hypervisors have direct access to the hardware resources; therefore, they are more efficient than hosted architectures. 
- Type 1 hypervisors improve scalability, performance, and robustness.

![Screenshot (686)](https://user-images.githubusercontent.com/63872951/175617231-1b5bce2f-2a17-4dc5-81d4-15a5656218af.png)

## Type 2 Hypervisor - "Hosted" Approach

- A Type 2 hypervisor is software that creates and runs VM instances. 

- The computer, on which a hypervisor is supporting one or more VMs, is a host machine. 
- Type 2 hypervisors are also called hosted hypervisors. 
- This is because the hypervisor is installed on top of the existing OS, such as macOS, Windows, or Linux. 

- Then, one or more additional OS instances are installed on top of the hypervisor, as shown in the figure. 
- A big advantage of Type 2 hypervisors is that management console software is not required.

**Note:** It is important to make sure that the host machine is robust enough to install and run the VMs, so that it does not run out of resources.

![Screenshot (687)](https://user-images.githubusercontent.com/63872951/175617516-5aeddb79-38b5-4eca-8659-ce86967f19e1.png)
