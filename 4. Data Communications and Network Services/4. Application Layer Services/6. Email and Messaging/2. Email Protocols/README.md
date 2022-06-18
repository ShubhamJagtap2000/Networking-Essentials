# Email Protocols

## SMTP

- Simple Mail Transfer Protocol
- SMTP is used by an email client to send messages to its local email server. 
- The local server then decides if the message is destined for a local mailbox or if the message is addressed to a mailbox on another server.

- If the server has to send the message to a different server, SMTP is used between those two servers as well. SMTP requests are sent to port 25.

## POP3

- Post Office Protocol 3

- A server that supports POP clients receives and stores messages addressed to its users. 
- When the client connects to the email server, the messages are downloaded to the client. 
- By default, messages are not kept on the server after they have been accessed by the client. 
- Clients contact POP3 servers on port 110.

## IMAP4

- Internet Message Access Protocol 4
- A server that supports IMAP clients also receives and stores messages addressed to its users. 
- However, unlike POP, IMAP keeps the messages in the mailboxes on the server, unless they are deleted by the user. 
- The most current version of IMAP is IMAP4 which listens for client requests on port 143.

- Many different email servers exist for the various network operating system platforms.
