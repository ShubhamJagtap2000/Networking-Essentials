# Upper and Lower Layers of OSI Model

- The OSI model breaks network communications down into multiple processes. 
- Each process is a small part of the larger task.

- For example, in a vehicle manufacturing plant, the entire vehicle is not assembled by one person. 
- Rather, the vehicle moves from station to station where specialized teams add specific components. 
- The complex task of assembling a vehicle is made easier by breaking it into manageable and logical tasks. 
- This process also makes troubleshooting easier. 
- When a problem occurs in the manufacturing process, it is possible to isolate the problem to the specific task where the defect was introduced, and then fix it.

- In a similar manner, the OSI model helps us troubleshoot by focusing on a specific layer to identify and resolve network problems. 
- Networking teams often refer to different functions occurring on a network by the number of the OSI model layer that specifies that functionality. 
- For example, the process of encoding the data bits for transmission across the media occurs at Layer 1, the physical layer. 
- The formatting of data so it can be interpreted by the network connection in your laptop or phone is described at Layer 2, the data link layer.


| Group | Layer Number | Layer Name | Common Network Components Associated       |
| --- | --- | --- | ------- |
| **Upper Layers** | **7**<br>**6**<br>**5** | **Application**<br>**Presentaion**<br>**Session** | **1.** Network aware applications<br><br>**2.** Email<br><br>**3.** Web browsers and servers<br><br>**4.** File transfer<br><br>**5.** Name resolution |
| **Lower Layers** | **4**<br><br>**3**<br><br>**2**<br><br>**1**<br> | **Transport**<br><br>**Network**<br><br>**Data Link**<br><br>**Physical** | **4. Transport**<br><br>- Video and voice streaming mechanisms<br>- Email<br>- Firewall filtering lists<br><br>**3. Network**<br><br>- IP addressing<br>- Routing<br><br>**2. Data Link**<br><br>- Network inteerface cards and drivers<br>- Network switching<br>- WAN connectivity<br><br>**1. Physical**<br><br>-Physical medium<br>-Hubs and repeaters<br> |
