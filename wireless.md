
1. WEP is an extremely weak encryption method that is defined in the 802.11b standard
2. WPA, which was designed to address weaknesses in Wired Equivalent Privacy (WEP), only adheres to a subset of the 802.11i standard.
3. Wi-Fi Protected Access 2 (WPA2) adheres to the entire Institute of Electrical and Electronics Engineers (IEEE) 802.11i standard


1. GSM 2G Protocol
2. AP Access Point
3. WAP Wireless Access Point
4. SSID Service Set Identifier
5. BSSID  Mac Address of an Access Point


Wireless Standard | Operating Speed | Frequency | Mdulation Type
-|-|-|-
802.11a | 54 | 5 | OFDM
802.11b | 11 | 2.4 | DSSS
802.11g | 54 | 2.4 | OFDM and DSSS
802.11n | 100+ | 2.4-5 | OFDM
802.11ac | 1000 | 5 | QAM
Bluetooth | 1-3 | 2.4 | N/A

## WIFI Chalking ##

WarWalking: Walking around to detect open Wi-Fi networks 
WarChalking: Using Symbol and Signs to advertise Open Wi-Fi networks 
WarFlying: Detection of open Wi-Fi networks using Drones 
WarDriving: Driving around to detect Open Wi-Fi networks 

## Types of Wireless Antenna ##

1. Directional Antenna 单一方向的锅盖，用于卫星电视和internet
2. omnidirectional antenna 全方向的天线 包含Dipole antenna 和Rubber Ducky antenna
3. parabolic antenna 抛物线电线
4. Yagi Antenna	电线杆
5. Dipole Antenna 两根直线

## Wireless Encryption ##

### WEP ###
It uses 24-bit initialization vector (IV) to create a stream cipher RC4 with Cyclic Redundant Check (CRC) to ensure 
confidentiality and integrity. 

Standard 64-bit WEP uses the 40-bit key,
 128-bit WEP uses 104-bit key and
 256-bit WEP uses a 232-bit key. 


### WPA ###
Wifi Protected Access 

### WPA2 ###
to replace WPA


Encryption | Encryption Algorithm | Encryption Key | Integraity check mechanism | integrity check
-|-|-|-|-
WEP | RC4 | 24 bits | 40/104-bits | CRC-32
WPA | RC4,TKIP| 48 bits | 128bits | MICHAEL ALGORITHM CRC32
WPA2 | AES,CCMP | 48 bits | 128bits | CBC-MAC
