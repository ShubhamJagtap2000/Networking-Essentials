# OSI and TCP/IP Model Comparison

- Because TCP/IP is the protocol suite in use for internet communications, why do we need to learn the OSI model as well?

- The TCP/IP model is a method of visualizing the interactions of the various protocols that make up the TCP/IP protocol suite. 
- It does not describe general functions that are necessary for all networking communications. 
- It describes the networking functions specific to those protocols in use in the TCP/IP protocol suite. 
- For example, at the network access layer, the TCP/IP protocol suite does not specify which protocols to use when transmitting over a physical medium, nor the method of encoding the signals for transmission. 
- OSI Layers 1 and 2 discuss the necessary procedures to access the media and the physical means to send data over a network.

- The protocols that make up the TCP/IP protocol suite can be described in terms of the OSI reference model. 
- The functions that occur at the internet layer in the TCP/IP model are contained in the network layer of the OSI Model, as shown in the figure. 
- The transport layer functionality is the same between both models. 
- However, the network access layer and the application layer of the TCP/IP model are further divided in the OSI model to describe discrete functions that must occur at these layers.

![Screenshot (711)](https://user-images.githubusercontent.com/63872951/176998135-2331f2bd-9613-48e5-b762-0e8295305fa6.png)




- The key similarities are in the transport and network layers; however, the two models differ in how they relate to the layers above and below each layer:

  - OSI Layer 3, the network layer, maps directly to the TCP/IP internet layer. This layer is used to describe protocols that address and route messages through an internetwork.<br>
  
  - OSI Layer 4, the transport layer, maps directly to the TCP/IP transport layer. This layer describes general services and functions that provide ordered and reliable delivery of data between source and destination hosts.
  
  - The TCP/IP application layer includes several protocols that provide specific functionality to a variety of end user applications. The OSI model Layers 5, 6, and 7 are used as references for application software developers and vendors to produce applications that operate on networks.
  
  - Both the TCP/IP and OSI models are commonly used when referring to protocols at various layers. Because the OSI model separates the data link layer from the physical layer, it is commonly used when referring to these lower layers.
