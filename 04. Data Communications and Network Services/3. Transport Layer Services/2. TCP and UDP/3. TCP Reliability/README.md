# TCP Reliability

- With all of the millions and millions of web pages being transmitted at any time over the internet, how can a server be certain that the page it sent is received by the client that requested it? 
- One of the mechanisms that helps ensure reliable delivery is the Transmission Control Protocol (TCP).
- When an application requires acknowledgment that a message is delivered, it uses TCP. 
- TCP breaks up a message into small pieces known as segments.
- The segments are numbered in sequence and passed to the IP process for assembly into packets.
- TCP keeps track of the number of segments that have been sent to a specific host from a specific application.
- If the sender does not receive an acknowledgment within a certain period of time, it assumes that the segments were lost and retransmits them.
- Only the portion of the message that is lost is resent, not the entire message.
- On the receiving host, TCP is responsible for reassembling the message segments and passing them to the application.
- FTP and HTTP are examples of applications that use TCP to ensure delivery of data.

