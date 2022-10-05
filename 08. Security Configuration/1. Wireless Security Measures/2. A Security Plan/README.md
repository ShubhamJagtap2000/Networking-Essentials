# A Comprehensive Security Plan

- Security measures should be planned and configured before connecting the home wireless router to the network or ISP. 

### 1. Basic Wireless Settings

- Change the default Service Set Identifier (SSID).
- Disable SSID broadcast.

### 2. Wireless Security

- Set the security profile for each band:

  1. Configure the security mode to use WPA2 Personal.
  2. Set the encryption to Advanced Encryption Standard (AES).
  3. Configure a passphrase.
  
### 3. MAC Address Filtering
  
  - Configure the MAC addresses that you want to prevent or permit on the WLAN.
  
### 4. Port Forwarding
  
  - Configure the ports that should be forwarded to a specific device, such as a web server in your demilitarized zone (DMZ). 
  
### 5. Demilitarized Zone (DMZ) 
  
  - Configure the IPv4 address for the server in the DMZ. 
  
 #
 
 - **Note:** You will complete some of these configurations later in this module.

- Keep in mind that no single security measure will keep your wireless network completely secure. 
- Combining multiple techniques will strengthen the integrity of your security plan.

- When configuring the clients, it is essential that the SSID matches the SSID configured on the AP. 
- SSIDs are case sensitive, so the character string must match exactly. 

- Additionally, encryption keys and authentication keys must also match.
