# Rob Myers Week 20 Project 2: BLUE TEAM SOC Analysist 

1. **Identify the offensive traffic.**

   - <u>Identify the traffic between your machine and the web machine:</u>

        * Looking at the dashboard there was heavy traffic between source.ip: 192.168.1.90 and destination.ip: 192.1.105, port 4444

        * The dashboard indicates there were 499,498 hits

    - **When did the interaction occur?**

        * Looking at the Dashboard there was heavy traffic on November 12, 2021 and November 13th between 2pm and 2am

    - **What responses did the victim send back?**

        * Looking at the Dashboard there was a large amount of 401 HTTP Response Status Code Errors 

    - **What data is concerning from the Blue Team perspective?**

        * The amount of 401 HTTP Response Status Code Errors is concerning to the BLUE TEAM

        * There was also a large amount of URL HTTP Requests for: http://192.168.1.105/company_folders/secret_folder 

        * Another concern to the BLUE TEAM was the high number of Errors vs Successful Transactions

        * The BLUE TEAM observed "WebDAV" in the logs (http://192.168.1.105/webdav) indicating a remote connection to the server. This is an extremely unusual information as only the system administrator is authorized to establish a remote access connection 

        * The Dashboard is also indicating a total count of **116** 192.168.1.105/webdev/passwd.dav indicating a potential BRUTEFORCE Attack

        * The Dashboard indicates that there was a total count of **66** (http://192.168.1.105/webdev/reverser_shell.php indicating a remote connection via a reverse shell to the server. 

        * The Dashboard indicates that there was a total count of **58** (http://192.168.1.105/webdev/shell.php indicating a PHP file was accessed on the server.

        ### [BLUE TEAM Examples #1](b1.md)

2. **Find the request for the hidden directory.**

   - **How many requests were made to this directory? At what time and from which IP address(es)?**

        * The dashboard indicates that there were 64,001 HTTP Requests between November 12th, 2021 and November 14th 2021. 

        * Between November 12, 2021 at 6pm through November 13, 2021 between the hours of 6pm and midnight there was 46,899 HTTP Requests between source.ip: 192.168.1.90 and destination.ip: 192.168.1.105

        * At approximately 3am on November  14th, 2021 there was also 62737 HTTP Requests between source.ip: 192.168.1.90 and destination.ip: 192.168.1.105  

    - **Which files were requested? What information did they contain?**

        * According to the Log, there was 84,907 HTTP Get Requests from November 12, 2021 through November 14th, 2021

        * According to the Dashboard there was 62,735 HTTP Get Requests for (http://192.168.1.105/company_folders/secret_folder) 

        * The specific folder being requested: "secret folder" contained the HASH for Ryans password and instructions on how to establish a remote access connection 

        * Per the Dashboard http://192.168.1.105/company_folders/secret_folder/  was accessed 13 times 

    - **What kind of alarm would you set to detect this behavior in the future?**

        * I would recommend setting up an ALARM anytime a remote access connection is attempted and or established

        * I would recommend setting up an ALARM anytime a PHP, or executable file is detected

        * I would recommend setting up an ALARM anytime there are more then 10 401 (Logon failed) Error requests in ONE minute  

        * I would recommend setting up an ALARM anytime there are more then 10 Port Scans in ONE Minute  

        * I would ensure that access to the secret folder is restricted to authorized users only and establish an ALARM anytime that folder is accessed

    - **Identify at least one way to harden the vulnerable machine that would mitigate this attack.**

        * I would recommend keeping the "secret file" on a separate server that is not accessible via any publicly accessible server 

        * I would restrict user access to very specific users 

        ### [BLUE TEAM Examples #2](b2.md) 

3. **Identify the brute force attack.**

    - **Can you identify packets specifically from Hydra?**

        * YES: searching using - http.request.method : get and url.full : "http://192.168.1.105/company_folders/secret_folder" shows 62,735 hits

        * Clicking on the drop down arrow shows more specific information. Specifically: user_agent.original Mozilla/4.0 (Hydra)

    - **How many requests were made in the brute-force attack?** 

        * The Dashboard shows a count of 62,735 for URL: http://192.168.1.105/company_folders/secret_folder

    - **How many requests had the attacker made before discovering the correct password in this one?**

        * Dashboard indicates that out of the 62,737 requests the attacker was successful 6 times 

    - **What kind of alarm would you set to detect this behavior in the future and at what threshold(s)?**

        * I would recommend setting up an ALARM anytime there are more then 10 401 Error requests in ONE minute 

        * I would recommend setting up an ALARM anytime there are more then 10 Port Scans in ONE Minute  

        * I would recommend setting up an alarm if the user-agent.original indicates: Mozilla/4.0 (Hydra). Set Threshold to Zero       
    
    - **Identify at least one way to harden the vulnerable machine that would mitigate this attack.**

        * I would recommend implementing a strong password policy that locks out a user for 15 minutes after 3 unsuccessful login's as well as completely locking the user out after 6 unsuccessful login's 

        * I would recommend implementing a multi-authentication procedure when resetting passwords 

        * I would recommend restricting common injection attacks or brute force attacks by improving firewall rules. For example restricting all PHP files, executable files, and webdav or remote control access 

        * I would recommend dropping traffic from any IP Address after 15 400 error codes for ONE hour  

        ### [BLUE TEAM Examples #3](b3.md) 

4. **Find the WebDav connection.**
   - Use your dashboard to answer the following questions:
     - How many requests were made to this directory? 
     - Which file(s) were requested?
     - What kind of alarm would you set to detect such access in the future?
     - Identify at least one way to harden the vulnerable machine that would mitigate this attack.

5. **Identify the reverse shell and meterpreter traffic.**
   - To finish off the attack, you uploaded a PHP reverse shell and started a meterpreter shell session. Answer the following questions:
     - Can you identify traffic from the meterpreter session?
     - What kinds of alarms would you set to detect this behavior in the future?
     - Identify at least one way to harden the vulnerable machine that would mitigate this attack.





     











