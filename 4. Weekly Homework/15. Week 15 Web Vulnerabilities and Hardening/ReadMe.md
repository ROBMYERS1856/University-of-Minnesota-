
# <u> Rob Myers Week 15: Web Vulnerabilities and Hardening</u> 

## Overview

In this homework scenario, you will continue as an application security engineer at Replicants. Replicants created several new web applications and would like you to continue testing them for vulnerabilities. Additionally, your manager would like you to research and test a security tool called BeEF in order to understand the impact it could have on the organization if Replicants was targeted with this tool.

## Topics Covered in Your Assignment

* Web application vulnerability assessments

* Injection

* Brute force attacks

* Broken authentication

* Burp Suite

* Web proxies

* Directory traversal

* Dot dot slash attacks

* Beef

* Cross-site scripting

* Malicious payloads

## <u>Web Application 1: Your Wish is My Command Injection</u>  

### 1. Lets get set up:

### [Set-Up Commands](IMAGE/1.md) 

### 2. Test the webpage by entering the IP address 8.8.8.8. 

* Behind the scenes, when you select Submit, the IP you type in the field is injected into a command that is run against the Replicants webserver. The specific command that ran on the webserver is ping <IP> and 8.8.8.8 is the field value that is injected into that command.

* This process is no different than if we went to the command line and typed that same command: ping 8.8.8.8

### [Ping 8.8.8.8](IMAGE/ping.md) 

### 3. Test if we can manipulate the input to cause an unintended result.

* This type of injection attack is called Command Injection, and it is dependent on the web application taking user input to run a command against an operating system.

* Were attempting to PING the DVWA website and determine if we can also access the Working Directory using the PWD command

### [Test PING and PWD](IMAGE/pwd.md)

### 4. Test the dot-dot-slash method to design two payloads that will display the contents of the following files:

**<u>Attempting to access etc/passwd:</u>**

* Using the dot-dot-slash method there are 5 sub-directories 

* Using command: **8.8.8.8 && cat ../../../../../ETC/PASSWD**

### [etc/passwd](IMAGE/etcpass.md)

**<u>Attempting to access etc/hosts:</u>**

* Using the dot-dot-slash method there are 5 sub-directories 

* Using command: **8.8.8.8 && cat ../../../../../ETC/HOSTS**

### [etc/hosts](IMAGE/etchosts.md) 

## **Mitigation Strategies:**

A) Establish Injection filtering firewall rules for HTTP Headers, Query parameters, URI paths, and Request Payloads.

B) Ensure that code writers are checking the code and fixing security flaws on a regular basis 

C) Ensure your website URI scheme is HTTPS and has an accredited and trusted certificate 

D) Make sure that your servers and applications/software is being updated on a consitant basis.

E) Assume that your application is not secure and act accordingly by encrypting or hashing passwords and other confidential data including connection strings.

F) Establish reasonable password policys and ensure that passwords are changed on a regular basis.

## <u>Web Application 2: A Brute Force to Be Reckoned With</u> 

### 1. Complete the following steps to set up the activity.

### [Brute Force Setup](IMAGE/brute.md) 

### 2. Use the web application tool Burp Suite, specifically the Burp Suite Intruder feature, to determine if any of the administrator accounts are vulnerable to a brute force attack on this web application.

### [List of Administrators](IMAGE/adminlist.md) 

### [Breached list of Passwords](IMAGE/breachedpwd.md) 

### 3. Using BURP to bruteforce attack the BWAPP Website:

### [Brute Force Attack](IMAGE/brute11.md)

### **Mitigation Strategies:**

A) Limit failed login attempts

B) Limit logins to a specified IP Address or range

C) Make special characters and a reasonable amount of characters standard

D) Regular schedualed/required pass word changes help mitigate bruteforce attacks

E) Dont just Hash your pass words. Make sure you also add SALT as well.

F) Apply the principle of least privilege. In other words, ensure that all users only have access to those resources that are absolutely necessary to their job function. Never use a domain administrator account as an SQL database connection account for example.

## Web Application 3: Where's the BeEF?

### 1. Set up BeEF (Browser Exploitation Framework Project)

### [Beef Set Up](IMAGE/beef.md)

### 2. Test the Replicants web application by using the BeEF Tool. You are tasked with using a stored XSS attack to inject a BeEF hook into Replicants' main website.

### [XSS Attack](IMAGE/beeff.md)























