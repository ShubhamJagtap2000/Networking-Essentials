# Authentication Protocols

- Early wireless routers used a form of encryption known as Wired Equivalency Protocol (WEP) to secure wireless transmissions between clients and access points. 
- WEP is a security feature that encrypts network traffic as it travels through the air. 
- WEP uses pre-configured keys to encrypt and decrypt data. 
- A WEP key is entered as a string of numbers and letters and is generally 64 bits or 128 bits long. 
- In some cases, WEP supports 256 bit encryption keys.

- However, there are weaknesses within WEP, including the use of a static key on all WEP-enabled devices on the wireless LAN. 
- There are applications, which are readily available on the internet, that threat actors can use to discover the WEP key. 
- After the attacker has extracted the key, they have complete access to all transmitted information. 
- The latest authentication is WPA3 that includes both personal and enterprise versions.


- One way to overcome this vulnerability is to change the key frequently. 
- Another way is to use a more advanced and secure form of encryption known as Wi-Fi Protected Access (WPA).

- WPA2 also uses encryption keys from 64 bits up to 256 bits. 
- However, WPA2, unlike WEP, generates new, dynamic keys each time a client establishes a connection with the AP. 
- For this reason, WPA2 is considered more secure than WEP because it is significantly more difficult to crack. 
- The version of WPA2 designed for home networks is designated as WPA2-PSK. 
- The PSK indicates that this encryption method is based on a pre-shared key, in this case, your configured passphrase.

![Screenshot (706)](https://user-images.githubusercontent.com/63872951/176753490-ac0b4c39-d33a-469c-a067-0bf6545a05d1.png)
