# Rob Myers Week 20 Project 2: RED TEAM vs BLUE TEAM

## Overview:

We have covered a lot of Cyber Security Fundamentals up to this point. We have experience attacking machines as well as monitoring and protecting against breaches during our SIEMs units. Now, we are ready to apply our knowledge to many real-life scenarios. 

## RED TEAM vs BLUE TEAM Project:

For this project, you will work on a Red Team vs. Blue Team scenario in which you will play the role of both <u>**Pentester** and **SOC analyst**</u>.

As the <u>**RED TEAM**</u>, you will attack a vulnerable VM within your Azure Virtual Machine environment, and gain root access to the machine. 


As <u>**BLUE TEAM**</u>, you will use Kibana to review logs taken during the RED TEAM Attack. Last, you will interpret your log data to suggest mitigation measures for each exploit that you've successfully performed.

---

## RED TEAM Pen Test

A Red team is a group of offensive security professionals whose role is to use real world techniques to perform attacks on an organization with an aim to identify vulnerabilities, bugs and weakness in the infrastructure of an organization. A Red team could be a team from within an organization or can be hired exclusively to perform attacks. 

For this scenario we will be using our AZURE KALI LINUX Virtual Machine to attack the following CAPSTONE Virtual Machine.

* KALLI LINUX VM:
    
    - IP Address: 192.168.1.90

* CAPSTONE VM:

    - IP Address: 192.168.1.105 

### [RED TEAM](IMAGE/REDTEAM.md)  

## BLUE TEAM 

Now that we have performed our REDTEAM Pen Test we now will take on the role of the BLUE TEAM SOC Analysist.

A Blue team is a group of internal security professionals who defend the organization from cyber attacks through threat prevention, detection and response. They work to improve the security of the organization round the clock. They closely monitor the network traffic, data flow and suspicious activities and work to detect and prevent them. In case of any attacks, their role is to recover the organization from the damage and apply even stronger defense mechanism for future attacks.

Last, we will by using KIBANA to analyze logs taken during the Red Team attack.

### [BLUE TEAM](IMAGE/BLUETEAM.md)  

## RED vs BLUE Report

Communication skills are vital in the cybersecurity field. That is why cybersecurity professionals need to have a solid foundation knowing how to attack vulnerable networks as well as how to defend against attacks.

In the below link you will find a detailed report describing how the RED TEAM penetrated the network, evidence of the attack analyzing Kibana logs, as well as recommendations on how to secure the network.

[RED vs BLUE Report](IMAGE/Red_vs_Blue_Report.PDF)  





