
# nmap #

## Full Connect ##

## Stealth (SYN Scan) ##

-sS  

State | Response
-|-
OPEN | Ack,Syn | 
CLOSE | RST | 
FILTER | NO RESPONSE | 

## ACK Probe ##

## Inverse TCP Flag ##
FIN,URG,PSH

State | Response
-|-
OPEN | NO RESPONSE| 
CLOSE | RST | 

## XMAS ##
Turn on all flags. Does not work against windows due to (RFC793 compliant)

-sX

## ACK Probe ##

-sA  

State | Response
-|-
OPEN,CLOSE | RST | 
FILTER | NO RESPONSE | 

the attacker sends the ACK flag and looks at the return header (TTL or Window fields) to determine the port status. 

In the TTL version, if the TTL of the returned RST packet < 64, the port is open. 
In the Window version, if the WINDOW size on the RST packet has anything >  0, the port is open. 

## IDLE ##

-sI

-sL: DNS scan list scan

## HOST DISCOVERY ##

-sL: List Scan - simply list targets to scan
-sn: Ping Scan - disable port scan
-sP: Ping Scan 

-sW: windows scan
-sO Protocal scan

## Port Scan ##

-PS/PA/PU/PY[portlist]: TCP SYN/ACK, UDP or SCTP discovery to given ports

-PI  ICMP ping
-Po No Ping
-PS SYN Ping
-PT TCP ping
-Pn: Treat all hosts as online -- disable ping  Tells nMap to skip the discovery stage entirely and just test all IPs

## ICMP ##

-PE; -PP; -PM (ICMP Ping Types)

## SERVICE/VERSION DETECTION ## 

-sV: Probe open ports to determine service/version info

## Script Scan ##

-sC: equivalent to --script=default

## OS detection ##

-O: Enable OS detection

## Timing and performance ##

-T<0-5>

-A: Enable OS detection, version detection, script scanning, and traceroute  , -O, -sV, -sc, and -traceroute

The “s” commands determine the type of scan to perform, the “P” commands set up ping sweep options, and the “o” commands deal with output. The “T” commands deal with speed and stealth, with the serial methods taking the longest amount of time. Parallel methods are much faster because they run multiple scans simultaneously
