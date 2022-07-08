# Why Protocols Matter?

- Protocols are required for computers to properly communicate across the network. 
- In both a wired and wireless environment, a local network is defined as an area where all hosts must "speak the same language", which, in computer terms means they must "share a common protocol".

- If everyone in the same room spoke a different language, they would not be able to communicate. 
- Likewise, if devices in a local network did not use the same protocols, they would not be able to communicate.

- Networking protocols define many aspects of communication over the local network. 
- These include message format, message size, timing, encoding, encapsulation, and message patterns.

#


| **Protocol Characteristic** | **Description** |
| --- | --- |
| **Message Format** | - What a message is sent, it must use a specific format or structure.<br> - Message formats depend on the type of message and the channel that is used to deliver the message. |
| **Message Size** | - The rules that govern the size of pieces across a network are very strict.<br> - They can also be different depending on the channel used.<br> - When a long message is sent from one host to another over a network, it may be necessary to break the message into smaller pieces in order to ensure that the message can be delivered reliably. |
| **Timing** | - Many network communication functions are dependent on timing.<br> - Timing determines the speed at which the bits are transmitted across the  network.<br> - It also affects when the individual host can send data and the total amount of data that can be sent in any one transmission. |
| **Encoding** | - Messages sent across the network are first converted into bits by sending host.<br> - The destination host receives and decodes the signals in order to interpret the message. |
| **Encapsulation** | - Each message on a network must include a header that contains addressing information that identifies the source and destination hosts, otherwise cannot be delivered.<br> - Encapsulation is the processs of adding this information to the pieces of data that make up the message. |
| **Message Pattern** | - Some messages require acknowledgement before sending the next message.<br> - This type ofrequest/response pattern is the common aspect of many networking protcols. |
