
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

## Web Application 1: Your Wish is My Command Injection 

### 1. Lets get set up:

### [Set-Up Commands](IMAGE/1.md) 

### 2. Test the webpage by entering the IP address 8.8.8.8. Press Submit to see the results display on the web application.

* Behind the scenes, when you select Submit, the IP you type in the field is injected into a command that is run against the Replicants webserver. The specific command that ran on the webserver is ping <IP> and 8.8.8.8 is the field value that is injected into that command.

* This process is no different than if we went to the command line and typed that same command: ping 8.8.8.8

### [Ping 8.8.8.8](IMAGE/ping.md) 

### 3. Test if we can manipulate the input to cause an unintended result.













