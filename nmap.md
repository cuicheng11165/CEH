
# nmap #

## Full Connect ##

## Stealth (SYN Scan)##

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







