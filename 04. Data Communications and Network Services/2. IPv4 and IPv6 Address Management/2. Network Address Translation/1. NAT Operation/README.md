# NAT Opeartion

- The wireless router receives a public address from the ISP, which allows it to send and receive packets on the internet.
- It, in turn, provides private addresses to local network clients.
- Because private addresses are not allowed on the internet, a process is needed for translating private addresses into unique public addresses to allow local clients to communicate on the internet.
- The process used to convert private addresses to internet-routable addresses is called Network Address Translation (NAT).
- With NAT, a private (local) source IPv4 address is translated to a public (global) address.
- The process is reversed for incoming packets.
- The wireless router is able to translate many internal IPv4 addresses to the same public address, by using NAT.
- Only packets destined for other networks need to be translated.
- These packets must pass through the gateway, where the wireless router replaces the private IPv4 address of the source host with its own public IPv4 address.
- Although each host on the internal network has a unique private IPv4 address assigned to it, the hosts must share the single internet-routable address assigned to the wireless router.
