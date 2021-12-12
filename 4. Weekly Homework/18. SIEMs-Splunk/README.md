# Rob Myers Unit 18 Homework: Lets go Splunking!
___

### Topics Covered in This Assignment

- Researching and adding new apps
- Installing new apps
- Uploading files
- Splunk searching
- Using fields
- Custom reports
- Custom alerts
---

## Vandalay Industries Monitoring Activity 


### Step 1: The Need for Speed 
___

**Task:** Create a report to determine the impact that the DDOS attack had on download and upload speed. Additionally, create an additional field to calculate the ratio of the upload speed to the download speed.

1. **Upload the following file of the system speeds around the time of the attack.**

    - ### [Server_speedtest Log](IMAGE/1.md) 

 
2. **Using the `eval` command, create a field called `ratio` that shows the ratio between the upload and download speeds.**

   - ### [Eval Command](IMAGE/2.md)

   <u> **Now we need to sort the data by Time and IP Address:**</u> 

    - ### [Sorting the data using the RATIO Command](IMAGE/3.md) 
      
3. **Based on the report created, what is the approximate date and time of the attack?**

    * Search Report shows that on 02-23-2020 at 14:30 (2:30pm) the DOWNLOAD Speed decreased and did not return to normal operating speeds unitll 23:30 (11:30pm).

    * According to the Search Report, the disruption in DOWNLOAD Speed lasted for approximately 8 hours.

    * The graph indicates that at 11:30pm on 02-22-2020 the DOWNLOAD SPEED began to decrease.

    * According to the Graph, the disruption in DOWNLOAD SPEED lasted for approximately 8 - 12 hours 

    **Conclusion:** The system took approximately 8 - 12 hours to fully recover

### Step 2: Are We Vulnerable? 

**Task:** Create a report determining how many critical vulnerabilities exist on the customer data server. Then, build an alert to notify your team if a critical vulnerability reappears on this server.

1. Upload the following file from the Nessus vulnerability scan.

    ### [Nessus Vulnerability Log](IMAGE/44.md)  

2. Create a report that shows the `count` of critical vulnerabilities from the customer database server.
   - The database server IP is `10.11.36.23`.
   - The field that identifies the level of vulnerabilities is `severity`.

    ### [Vulnerability Report](IMAGE/5.md) 
      
3. Build an alert that monitors every day to see if this server has any critical vulnerabilities. If a vulnerability exists, have an alert emailed to `soc@vandalay.com`.

    ### [Vulnerability Alert](IMAGE/6.md) 


### Step 3: Drawing the (base)line

**Task:** Analyze administrator logs that document a brute force attack. Then, create a baseline of the ordinary amount of administrator bad logins and determine a threshold to indicate if a brute force attack is occurring.

1. Upload the administrator login logs.

    ### [Admin Logins](IMAGE/7.md)

2. When did the brute force attack occur?

    * The Brute Force Attack occured on Feb 21, 2020 between the hours of 9:00am and 1:00pm

    * The Brute Force Attack lasted approximatelly FOUR Hours
    
3. Determine a baseline of normal activity and a threshold that would alert if a brute force attack is occurring.

    * Based on the Administrator Log the baseline for "failed Login's" is 16

    * The Threshold should be set at 35 or more "failed login" attempts

   ### [Failed Login/Brute Force Report](IMAGE/8.md) 

4. Design an alert to check the threshold every hour and email the SOC team at SOC@vandalay.com if triggered. 

    ### [Failed Login/Brute Force Alert](IMAGE/9.md) 






