
# Rob Myers Week 9 Homework
 
## Networks Fundamentals II: In a Network Far, Far Away!

Topics Covered in Your Assignments

DNS  
NSLOOKUP  
DNS record types:

    - A, PTR, MX, NS, SOA, SRV, TXT

Wireless

    - WEP, WPA

Aircrack-ng  
Wireshark Wireless analysis and decryption

# Mission 1: 

## Determine and document the mail servers for starwars.com using NSLOOKUP.

    * used DNS report: MX
    * nslookup -type=MX starwars.com
    * mail servers listed in picture below

![picture](IMAGE/mission1_nslookup_MX.PNG) 

## Explain why the Resistance isn't receiving any emails.
    * The resistance needs to update the MX Record so the primary and secondary servers  are documented corectly

    * currently the primary and secondary servers are not listed in the MX Report for starwars.com

## Document what a corrected DNS record should be.

### The following should be listed in the MX report:

    * starwars.com mail exchanger = 1 asltx.l.google.com
    * starwars.com mail exchanger = 5 asltx.2.google.com
