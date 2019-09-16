# Hacking Mobile Platforms #

## IOS JailBreaking ##

- Untethered jailbreaking 完美越狱
- Semi-tethered jailbreaking 重启后就不再越狱
- Tethered jailbreaking 重启后越狱补丁消失

Types of jailbreaking include

1. Userland exploit: Enables access to user-level functionality but does not allow iBoot-level access.
2. iBoot exploit: Provides user-level access and iBoot-level access.
3. Bootrom exploit: Provides user-level access and iBoot-level access.

Jailbreaking tools include, but are not limited to：

1. evasi0n7
2. GeekSn0w
3. Pangu
4. Redsn0w
5. Absinthe
6. Cydia

Tools for rooting an Android include

1. SuperOneClick
2. OneClickRoot
3. Kingo
4. unrevoked
5. RescueRoot
6. UnlockRootPro

## BYOD ##

BYOD is a ubiquitous business policy called Bring Your Own Device

Tools for cracking WEP include

1. Cain and Abel
2. Aircrack (both use Korek, but Aircrack is faster)
3. KisMAC
4. WEPCrack
5. chopchop
6. Elcomsoft’s Wireless Security Auditor tool

## Note ##

1. WPA2 is a strong encryption method, but almost everything can be hacked given time. Capturing the password pairwise master key (PMK) during the handshake is the only way to do it, and even then it’s virtually impossible if it’s a complicated password
2. Turning off the broadcast of an SSID is a good step, but SSIDs do nothing in regard to security. The SSID is included in every packet, regardless of whether it’s broadcast from the AP
3. Network SSID, MAC Address is required in order to attempt to crack a WEP AP
4. MIC protects against man-in-the-middle attacks in WPA
5. Blooover is designed for bluebugging
6. BBProxy and PhoneSnoop are both Blackberry tools
7. MDM (Mobile Device Management)  is an effort to add some control to enterprise mobile devices
8. SSIDs are important for identifying networks but do little to nothing for security
9. WPA uses temporal keys, making it a much stronger encryption choice than WEP
10. WEP uses RC4, which is part of the reason it’s so easily hacked and not considered a secure option
11. SuperOneClick is designed for rooting Android
12. The rogue access point is an easy attack , Sometimes referred to as an “evil twin”. The use of rogue APs (evil twins) may also be referenced as a mis-association attack
13. Droidsheep is a simple Android tool for web session hijacking
