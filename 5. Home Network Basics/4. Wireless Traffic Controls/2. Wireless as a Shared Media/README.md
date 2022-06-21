# Wireless as a Shared Media

- In a shared media Ethernet wired network, collisions occur when two or more devices attempt to send messages on the network at the same time. 
- Ethernet protocols detect the collisions and all devices stop transmitting for a period of time in order to ensure that there is no additional contention for the media.

- Within a wireless LAN, the lack of well-defined boundaries makes it impossible to detect if collisions occur during transmission. 
- Therefore, it is necessary to use an access method on a wireless network that ensures collisions do not occur.
- Wireless technology uses an access method called Carrier Sense Multiple Access with Collision Avoidance (CSMA/CA). 
- CSMA/CA creates a reservation on the channel for a specific conversation between devices. 
- While a reservation is in place, no other device may transmit on the channel, thus possible collisions are avoided.
- How does this reservation process work? 
- If a device requires use of a specific communication channel in the wireless network, it must ask permission from the AP. 
- This is known as a Request to Send (RTS). 
- If the channel is available, the wireless access point (AP) will respond to the device with a Clear to Send (CTS) message indicating that the device may transmit on the channel. 
- A CTS is broadcast to all devices within the network. 
- Therefore, all devices in the network know that the requested channel is now in use.
- When the conversation is complete, the device that requested the channel sends another message to the AP known as an acknowledgment (ACK). 
- The ACK indicates to the AP or the router that the channel can be released. 
- This message is also broadcast to all devices on the WLAN. 
- All devices within the network receive the ACK and know that the channel is now available.

## 1.
![Screenshot (674)](https://user-images.githubusercontent.com/63872951/174812139-5c472844-72e2-4cdb-974a-9c31918508a2.png)

## 2.
![Screenshot (675)](https://user-images.githubusercontent.com/63872951/174812426-b354c619-3ab3-4997-8339-d1ababa8c7b0.png)

## 3.
![Screenshot (676)](https://user-images.githubusercontent.com/63872951/174812573-08532780-63c7-4865-b78f-abd8019c8c1c.png)

## 4.
![Screenshot (677)](https://user-images.githubusercontent.com/63872951/174812700-55218491-be7e-48df-97d0-93592628d2a6.png)
