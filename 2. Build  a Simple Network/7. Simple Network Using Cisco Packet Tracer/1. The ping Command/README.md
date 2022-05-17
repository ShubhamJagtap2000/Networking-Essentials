# The ping

- The `ping` utility tests end-to-end connectivity between the IP address of the source of the message and the IP address of its destination.
- It measures the time that it takes test messages to make a round trip from the source to the destination, and whether the transmission is successful.
- However, if the test message does not reach the destination, or if delays are encountered along the way, there is no way to determine where the problem is located.
- The format of the ping command is universally implemented.
- Almost all network attached devices provide a way to perform a ping test.
- The format of the ping command is ping x.x.x.x, where x.x.x.x is an IP address or domain name:

For example, `ping 192.168.30.1`
