# Ethernet Frame

- The Ethernet protocol standards define many aspects of network communication including frame format, frame size, timing, and encoding.
- When messages are sent between hosts on an Ethernet network, the hosts format the messages into the frame layout that is specified by the standards. 
- Frames are also referred to as Layer 2 protocol data units (PDUs).
- This is because the protocols that provide the rules for the creation and format of the frame perform the functions that are specified at the data link layer (Layer 2) of the OSI model.
- The format for Ethernet frames specifies the location of the destination and source MAC addresses, and additional information including:

    - Preamble for sequencing and timing
    - Start of frame delimiter
    - Length and type of frame
    - Frame check sequence to detect transmission errors

- The size of Ethernet frames is normally limited to a maximum of 1518 bytes and a minimum size of 64 bytes from the Destination MAC Address field through the Frame Check Sequence (FCS).
- The preamble and the Start of Frame Delimiter (SFD) are used to indicate the beginning of the frame.
- They are not used in the calculation of the frame size.
- Frames that do not match these limits are not processed by the receiving hosts.
- In addition to the frame formats, sizes and timing, Ethernet standards define how the bits making up the frames are encoded onto the channel.
- Bits are transmitted as either electrical impulses over copper cable or as light impulses over fiber-optic cable.

![Screenshot (595)](https://user-images.githubusercontent.com/63872951/169664357-0b831a18-a035-42b5-9d07-8a63a5a11329.png)
