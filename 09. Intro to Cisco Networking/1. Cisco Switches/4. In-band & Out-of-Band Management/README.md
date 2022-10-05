**There are two methods to connect a PC to a network device to perform configuration and monitoring tasks:**

## 1. Out-of-band Management

- `Out-of-band management` requires a computer to be directly connected to the console port of the network device that is being configured. 
- This type of connection does not require the local network connections on the device to be active. 
- Technicians use out-of-band management to initially configure a network device, because until properly configured, the device cannot participate in the network. 
 
- Out-of-band management is also useful when the network connectivity is not functioning correctly, and the device cannot be reached over the network. 
- Performing out-of-band management tasks requires a terminal emulation client installed on the PC.

## 2. In-band Managemnt

- Use `in-band management` to monitor and make configuration changes to a network device over a network connection. 
- For a computer to connect to the device and perform in-band management tasks, at least one network interface on the device must be connected to the network and have an IP address configured on it. 
 
- Either Telnet, HTTP or SSH can be used to access a Cisco device for in-band management, monitor the network device, or make configuration changes.
