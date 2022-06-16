# DNS Servers

- A DNS server contains a table that associates hostnames in a domain with corresponding IP addresses. 
- When a client has the name of server, such as a web server, but needs to find the IP address, it sends a request to the DNS server on port 53. 
- The client uses the IP address of the DNS server configured in the DNS settings of the host IP configuration.
- When the DNS server receives the request, it checks its table to determine the IP address associated with that web server. 
- If the local DNS server does not have an entry for the requested name, it queries another DNS server within the domain. 
- When the DNS server learns the IP address, that information is sent back to the client. 
- If the DNS server cannot determine the IP address, the request will time out and the client will not be able to communicate with the web server.
