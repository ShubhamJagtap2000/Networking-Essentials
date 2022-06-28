# Why Protocols Matter?

- Just like humans, computers use rules, or protocols, in order to communicate. Protocols are required for computers to properly communicate across the network.
- In both a wired and wireless environment, a local network is defined as an area where all hosts must "speak the same language", which, in computer terms means they must "share a common protocol".
- If everyone in the same room spoke a different language, they would not be able to communicate.
- Likewise, if devices in a local network did not use the same protocols, they would not be able to communicate.
- As shown in the table, these include message format, message size, timing, encoding, encapsulation, and message patterns.

| Protocol Characteristic | Description |
| --- | --- |
| Message format | When a message is sent, it must use a specific format/structure. Message formats depend on the type of message & the channel that is used to deliver the message |
| Message size | When a long message is sent from one host to another over a network, it may be necessary to break the message into smaller pieces in order to ensure that the message can be delivered properly |
| Timing | Timing determines the speed at which the bits are transmitted across the network |
| Encoding | Messages sent across the network are converted in bits by the sending host. Each bit is encoded into a pattern of sounds, light waves or electrical impulses depending on the network media over which messages are transmitted |
| Encapsulation | Each message transmitted on network must include a `header` which contains addressing information that identifies the source and destination hosts, otherwise it cannot be delivered. Encapsulation is the process of adding this information to the pieces of data that make up the message |
| Message pattern | Some messages require an acknowledgement before the next message can be sent. This type of request/response pattern is a common aspect of many networking protocols. However,there are other types of messages that maybe simply streamed across the network, without concern as to whether they reach their destination |
