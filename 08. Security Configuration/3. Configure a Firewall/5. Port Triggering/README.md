# Port Triggering

- Playing a game over the internet may require more than just a data connection between you and the other players. 
- You may want to talk with your friends, or chat, while playing. 
- In many multiplayer games, a number of TCP and UDP connections could exist between the players while the game is active. 
 
- Leaving a large number of ports open to the internet can represent a security risk.

- Port triggering allows the router to temporarily forward data through inbound TCP or UDP ports to a specific device. 
- You can use port triggering to forward data to a computer only when a designated port range is used to make an outbound request. 
- For example, a video game might use ports 27000 to 27100 for connecting with other players. 
- These are the trigger ports. 
- A chat client might use port 56 for connecting the same players so that they can communicate with each other while playing the game. 
- In this instance, if there is gaming traffic on an outbound port within the triggered port range, inbound chat traffic on port 56 is forwarded to the computer that is being used to play the video game and chat with friends. 
- When the game is over and the triggered ports are no longer in use, port 56 is no longer allowed to send traffic of any type to this computer.
