# Encapsulation

- When sending a letter, the letter writer uses an accepted format to ensure that the letter is delivered and understood by the recipient.
- In the same way, a message that is sent over a computer network follows specific format rules in order for it to be delivered and processed.
- The process of placing one message format (the letter) inside another message format (the envelope) is called `encapsulation`.
- De-encapsulation occurs when the process is reversed by the recipient and the letter is removed from the envelope. 
- Just as a letter is encapsulated in an envelope for delivery, so computer messages are encapsulated.
- Each computer message is encapsulated in a specific format, called a `frame`, before it is sent over the network. 
- A frame acts like an envelope; it provides the address of the intended destination and the address of the source host. 
- The format and contents of a frame are determined by the type of message being sent and the channel over which it is communicated.
- Messages that are not correctly formatted are not successfully delivered to or processed by the destination host.
- In the figure, the fields of the Internet Protocol version 6 (IPv6) packet identify the source of the packet and its destination. 
- IP is responsible for sending a message from the message source to destination over one or more networks.

![Screenshot (593)](https://user-images.githubusercontent.com/63872951/169664063-c3ab3165-e553-454f-a664-3bd9dee15ae6.png)
