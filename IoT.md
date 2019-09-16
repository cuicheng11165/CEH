# IoT #

## IoT architecture ##

1. Application Layer        user gui
2. Middleware Layer         device  information management
3. Internet Layer           endpoint connectivity
4. Access Gateway Layer     Protocal translation and messaging
5. edge Technology Layer    IoT capable devices

## Iot Communication Models ##

1. device to device model   device之间互相通信
2. device to cloud model    device 直接和application进行通信
3. device to gateway model  gateway搜集信息并和application进行通信，同时提供安全，协议转换等功能
4. Back-End Data-Sharing Model  device被授权的第三方访问，控制

## IoT Attacks ##

1. ddos
2. rolling code or code hopping
3. blueborne attack exploit bluetooth vul
4. Jamming Attack
5. Backdoor

other attacks 

1. Eavesdropping
2. Sybil attack
3. Exploit kits
4. Man in the middle attack
5. Replay attack
6. Forged malicious devices
7. Side channel attack
8. Ransomware attack

## IoT Hacking Methodology ##

Information gathering
Vulnerability scanning
Launch attack
Gain access
Maintain attack

## countermeasures ##

Firmware update
Block unnecessary ports
Disable Telnet
Use encrypted communication such as SSL/TLS
Use strong password
Use encryption of drives
User account lockout
Periodic assessment of devices
Secure password recovery
Two-Factor Authentication
Disable UPnP

The following list is the top 4 of the OWASP Top 10 IoT Vulnerabilities and Obstacles:

1. Insecure web interface
Using default credentials
Absence of account lockout mechanisms
CSRF, SQLi, XSS vulnerabilities
2. Insufficient authentication/authorization
Insecure password recovery mechanisms
Weak passwords
Absence of two-factor authentication
3. Insecure network services
Vulnerable to Denial-of-Service attacks
Exposed ports via UPnP
Unwanted Ports are Open
4. Lack of transport encryption/integrity verification
Sensitive and confidential information is sent unencrypted
Absence of SSL/TLS or not properly configured
Use of proprietary encryption protocols

## IoT Security ##

Device Memory

- Clear-text credentials
- Third-party credentials
- Encryption keys

Ecosystem Access Control

- Implicit trust between components
- Enrollment security
- Decommissioning system
- Lost access procedures

Device Physical Interfaces

- Firmware extraction
- User CLI
- Admin CLI
- Privilege escalation
- Reset to insecure state
- Removal of storage media

Device Web Interfaces

- SQL injection
- Cross-site scripting
- Cross-site Request Forgery
- Username enumeration
- Weak passwords
- Account lockout
- Known default credentials

## Note ##

1. Mirai is a piece of malware that deliberately finds Internet of Things (IoT) devices to infect and add to a botnet
2. The first phase in IoT pen testing involves discovering the devices, which is accomplished with the Shodan, Censys, Thingful, and MultiPing tools to scan and document the devices connected to the network.
