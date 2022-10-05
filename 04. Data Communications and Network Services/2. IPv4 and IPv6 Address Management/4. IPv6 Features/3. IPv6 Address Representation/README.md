# IPv6 Address Representation

- It is no problem for computers to read the new 128-bit IPv6 addressing.
- IPv6 just adds more 1s and zeros to the source and destination addresses in the packet.
- Techniques have been developed to compress the written IPv6 address into a more manageable format.

## Compressing IPv6 Addresses

- IPv6 addresses are written as a string of hexadecimal values. 
- Every 4 bits is represented by a single hexadecimal digit for a total of 32 hexadecimal values. 
- The figure shows a fully expanded IPv6 address and two methods of making it more easily readable. 
- There are two rules that help reduce the number of digits needed to represent an IPv6 address.

#### **Rule 1 - Omit Leading Zeros**

- The first rule to help reduce the notation of IPv6 addresses is to omit any leading 0s (zeros) in any 16-bit section. 
- For example:

  - 0DB8 can be represented as DB8
  - 0000 can be represented as 0
  - 0200 can be represented as 200
  
#### **Rule 2 - Omit One “all zero” Segment**

- The second rule to help reduce the notation of IPv6 addresses is that a double colon (::) can replace any group of consecutive segments that contain only zeros. 
- The double colon (::) can only be used once within an address, otherwise there would be more than one possible resulting address.

| **Fully Expanded** | **2001:0DB8:0000:1111:0000:0000:0000:0200** |
| --- | --- |
| No leading 0s | 2001:DB8:0:1111:0:0:200 |
| Compressed | 2001:DB8:0:1111::200 |
