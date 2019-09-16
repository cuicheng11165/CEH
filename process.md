# methodology #

1. reconnaissance
2. scanning
3. gaining access
4. maintaining access
5. clearing tracks

## threat modeling ##

- Identify Security Objectives
- Application Overview
- Decompose Application
- Identify Threats
- Identify Vulnerabilities

## EISA ##

Enterprise Information Security Architecture is a collection of requirements and processes that help determine how an organization’s information systems are built and how they work

Know 
1. preventive
2. detective
3. corrective

Business Impact Analysis (BIA) included measurements of the maximum tolerable downtime (MTD), which provided a means to prioritize the recovery of assets should the worst occur.

His business continuity plan (BCP) included a disaster recovery plan (DRP), addressing exactly what to do to recover any lost data or services

## ALE = SLE × ARO ##

the ALE (annualized loss expectancy) turned out to be the product of the ARO (annual rate of occurrence) and the SLE (single loss expectancy).

每年损失期望 = 每天发生次数 * 每次发生损失期望


## Bit flipping ##
Bit flipping is one form of an integrity attack. In bit flipping, the attacker isn’t interested in learning the entirety of the plain-text message. Instead, bits are manipulated in the cipher text itself to generate a predictable outcome in the plain text once it is decrypted

## TCSEC ##
TCSEC eventually gave way to the Common Criteria for Information Technology Security Evaluation (also known as Common Criteria, or CC)

## Evaluation Assurance Level (EAL) ##

They would then follow the controls and testing procedures to have their system tested at the EAL (Levels 1–7) they wished to have. Assuming the test was successful, the vendor could claim Successfully tested at EAL-4.

Target of evaluation (TOE)   What is being tested
Security target (ST)   The documentation describing the TOE and security requirements
Protection profile (PP)   A set of security requirements specifically for the type of product being tested

Security Policies

This identifies to employees what company systems may be used for

1. Information Security Policy This identifies to employees what company systems may be used for
2. Information Protection Policy This defines information sensitivity levels and who has access 
to those levels. It also addresses how data is stored, transmitted, and destroyed.

## Policy Mode ##

a permissive policy blocks only things that are known to be naughty or dangerous. 
The next step up is a prudent policy, which provides maximum security but allows some potentially and known dangerous services because of business needs.

## HIPAA ##

developed by the U.S. Department of Health and Human Services to address privacy standards with regard to medical information

## Sarbanes-Oxley (SOX) Act ##

SOX was created to make corporate disclosures more accurate and reliable in order to protect the public and investors from shady behavior


It defines three types of compliance for testing

legislative (government regulations), 
contractual (industry or group requirements)
standards based (practices that must be followed in order to remain a member of a group or organization).

## PCI-DSS ##

PCI-DSS and ISO/IEC 27001:2013. Payment Card Industry Data Security Standard (PCI-DSS) is a security standard for organizations handling credit cards, ATM cards, and other point-of-sales cards

## active footprinting versus passive footprinting ##

dumpster diving = passive

## know nslookup ##


## scanning methodology ##

Check for live systems
Check for open ports
Scan beyond IDS
Perform banner grabbing
Scan for vulnerabilities
Draw network diagrams
Prepare proxies

## ICMP ##

For example, 

consider an Echo Request (Type 8) sent to a host that returns a Type 3. The code could tell us whether the host is down (Code 1), the network route is missing or corrupt in our local route tables (Type 0), or a filtering device, such as a firewall, is preventing ICMP messages altogether (Type 13)

## Hping3 ##

1 ICMP Mode
2 UDP Model
8 San model
9 license mode
--flood


ECC defines some versions of MAC flooding as “switch port stealing.”

Discover, Offer, Request, and Acknowledge

