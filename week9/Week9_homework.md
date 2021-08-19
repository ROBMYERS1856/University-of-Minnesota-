
# Rob Myers: Week 9 Homework
 
## Networks Fundamentals II: In a Network Far, Far Away!

Topics Covered in Your Assignments

1)  DNS  
2)  NSLOOKUP  
3)  DNS record types:   
        - A, PTR, MX, NS, SOA, SRV, TXT
4)  Wireless   
        - WEP, WPA
5)  Aircrack-ng  
6)  Wireshark Wireless analysis and decryption

# Mission 1: 

## Determine and document the mail servers for www.starwars.com using NSLOOKUP.

    * used DNS Record: MX
    * OSI Layer: 
    * nslookup -type=MX starwars.com
    * mail servers listed in picture below

![picture](IMAGE/mission1_nslookup_MX.PNG) 

## Explain why the Resistance isn't receiving any emails.

    * The resistance needs to update the DNS MX Record so the primary and secondary servers  are documented corectly

    * currently the primary and secondary servers are not listed in the MX Record for starwars.com

## Document what a corrected DNS record should be.

 The following should be listed in the MX record:

    * starwars.com mail exchanger = 1 asltx.l.google.com
    * starwars.com mail exchanger = 5 asltx.2.google.com

# Mission 2

## Your mission:

### Determine and document the SPF for theforce.net using NSLOOKUP.
    * used DNS record: TXT
    * nslookup -type=TXT starwars.com

![picture](IMAGE/mission2_txt.PNG) 

### Explain why the Force's emails are going to spam.

    * The resistance needs to update the TXT Record so that
    45.23.176.21 is included in the text = "v=spf1 a mx mx:smtp.secureserver.net include:
    aspmx.googlemail.com ip4:104.156.250.80 ip4:45.63.15.159 ip4:45.63.4.215" 

### Document what a corrected DNS record should be.

    * ADD the following to the below text: 
    ip4:45-23-176-21.lightspeed.rcsntx.sbcglobal.net

    * text = "v=spf1 a mx mx:smtp.secureserver.net include:
    aspmx.googlemail.com ip4:104.156.250.80 ip4:45.63.15.159 ip4:45.63.4.215 ip4:45-23-176-21.lightspeed.rcsntx.sbcglobal.net" 

![picture](IMAGE/mission2_yo.PNG)

# Mission 3

## Your mission:

### Document how a CNAME should look by viewing the CNAME of www.theforce.net using NSLOOKUP.

<brk>

Used DNS report: TXT

    * nslookup -type=CNAME www.theforce.net

![picture](IMAGE/mission3_number1.PNG)

### Explain why the sub page of resistance.theforce.net isn't redirecting to theforce.net.

    * the CNAME Report needs to be updated to include the alias: resistance.theforce.net

![picture](IMAGE/mission3_duce.PNG)

### Document what a corrected DNS record should be.

Here is what an updated DNS CNAME Reprot should look like:

    * sysadmin@UbuntuDesktop:~$ nslookup -text=CNAME www.theforce.net
    * Server:		8.8.8.8
    * Address:	8.8.8.8#53

    * Non-authoritative answer:
    * www.theforce.net	canonical name = theforce.net.
    * Name:	theforce.net
    * Address: 104.156.250.80

    * Non-authoritative answer:
    * Theforce.net	canonical name = resistance.theforce.net.
    * Name:	theforce.net
    * Address: 104.156.250.80


