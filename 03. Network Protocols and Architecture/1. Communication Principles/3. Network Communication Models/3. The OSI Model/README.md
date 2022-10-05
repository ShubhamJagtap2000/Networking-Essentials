# The OSI Model

- There are two basic types of models that we use to describe the functions that must occur in order for network communications to be successful: 

  ### 1. Protocol model 

  - This model closely matches the structure of a particular protocol suite. 
  - A protocol suite includes the set of related protocols that typically provide all the functionality required for people to communicate with the data network. 

  - The TCP/IP model is a protocol model because it describes the functions that occur at each layer of protocols within the TCP/IP suite.
    
  ### 2. Reference model 

  - This type of model describes the functions that must be completed at a particular layer, but does not specify exactly how a function should be accomplished. 
  - A reference model is not intended to provide a sufficient level of detail to define precisely how each protocol should work at each layer. 

  - The primary purpose of a reference model is to aid in clearer understanding of the functions and processes necessary for network communications.


- The most widely known internetwork reference model was created by the Open Systems Interconnection (OSI) project at the International Organization for Standardization (ISO). 

- It is used for data network design, operation specifications, and troubleshooting. 
- This model is commonly referred to as the OSI model.

#


| **OSI Model Layer** | **Description** |
| --- | --- |
| 7 - Application | contains protocols used for process-to-process communication |
| 6 - Presentation | provides services for common representation of the data transferred between application layer services |
| 5 - Session | provides services to presentation layer to organize its dialogue and to manage data exchange |
| 4 - Transport | defines servies to segment, transfer, and reassemble the data for individual communications between the end devices |
| 3 - Network | provides services to exchange the individual pieces of data over the network between identified end-devices | 
| 2 - Data Link | Data link layer protocols describe methods for exchanging data frames between devices over a common media |
| 1 - Physical | describe the mechanical, electrical, funtional, and procedural means to activate, maintain, and de-activate physical connections for a bit transmission to  and from a network device |
