## Splunk Command Examples

A report with a table of signatures with associated SignatureID.
      
- source="windows_server_logs.csv"  | table signature signature_id | dedup signature

A report that provides the count and percent of the severity.

- source="windows_server_logs.csv" |  top severity

A report that provides a comparison between the success and failure of Windows activities.

- source="windows_server_logs.csv" | top  status
       
Determine an appropriate baseline and threshold for hourly level of failed Windows activity. 
       
- source="windows_server_logs.csv"  status=failure 
	         
Determine a baseline and threshold for hourly count of the signature **an account was successfully logged on**. 

- source="windows_server_logs.csv" signature="An account was successfully logged on"	         
                  
Determine a baseline and threshold for hourly count of the signature **a user account was deleted**. 
		
- source="windows_server_logs.csv" signature_id=4726
	                  
A line chart that displays the different `signature` field values over time.

- source="windows_server_logs.csv" | timechart span=1h count by signature

A line chart that displays the different `user` field values over time. 

- source="windows_server_logs.csv" | timechart span=1h count by user
    
A bar, column, or pie chart that illustrates the count of different signatures.

- source="windows_server_logs.csv" | top limit=10 signature
	
A bar, column, or pie chart that illustrates the count of different users.

- source="windows_server_logs.csv" | top limit=10 user

A statistical chart that illustrates the count of different users.

- source="windows_server_logs.csv" | top limit=10 user				

---

A report that shows a table of the different HTTP methods (GET, POST, HEAD, etc).

- source="apache_logs.txt" | top method

A report that shows the top 10 domains that referred to VSI's website.

- source="apache_logs.txt" | top limit=10 referer_domain	

A report that shows the count of the HTTP response codes.
	
- source="apache_logs.txt" | top status	

Determine a baseline and threshold for hourly count of activity from a country other than the United States. Create an alert to trigger when the threshold has been reached. The alert should trigger an email to SOC@VSI-company.com.

- source="apache_logs.txt"  | iplocation clientip | where Country!="United States"	

Determine a baseline and threshold for hourly count of the HTTP POST method. Create an alert to trigger when the threshold has been reached. The alert should trigger an email to SOC@VSI-company.com.

- source="apache_logs.txt" method=POST

A line chart that displays the different HTTP `methods` field over time.

- source="apache_logs.txt" | timechart span=1h count by method	

A geographical map showing the location based on the `clientip` field.

- source="apache_logs.txt" | iplocation clientip | geostats count	

A bar, column, or pie chart that displays the count of different URIs.

- source="apache_logs.txt" | top limit=10 uri    

A bar, column, or pie chart that displays the counts of the top 10 countries.

- source="apache_logs.txt"  | iplocation clientip | top limit=10 Country	

A statistical chart that illustrates the count of different user agents.

- source="apache_logs.txt"   |  top limit=10 useragent    

Design a search to view the POST events:

- source="radialgauge.csv" http_method=POST |stats  count as total

Design an SPL query using similar criteria that displays the top 10 URI paths:

- source="radialgauge.csv" http_method=POST| top limit=10 uri_path

Design a geographic map that displays a visualization of source IP address locations. 

- source="radialgauge.csv" http_method=POST| iplocation src_ip | geostats count

Modify the search to display in the same map the URIs being attacked: 

- source="radialgauge.csv" http_method=POST| iplocation src_ip | geostats count by uri_path

## Dashboards

In this activity you were tasked with combining all the visualizations you've created so far into a a single dashboard.

---

Select the saved radial gauge from the reports list.
   - Once opened, select **Add to Dashboard**.
   - Select **New** dashboard. 
   - Title the dashboard "Website Monitoring."
   - Leave all the defaults as they are.
   - Select **Save**.

Follow the same process for the pie chart and geographic map. For these, select **Existing** dashboard.
   - Select **Website Monitoring** from the dropdown when prompted. 

To create the fourth visualization:
    - Select the pie chart from the reports list.
    - Select **Add to Dashboard**.
    - For the **Panel Content** option, select **Statistics**.
    - Select **Save**.

Once in the dashboard is complete, select **Edit**.
    - Drag the statistical data view of the pie chart to be next to the pie chart.

## Advanced Dashboards

In this activity, you were tasked with modifying your dashboard to add a time range input as well as a drilldown capability to one of the panels.

---

Using the same dashboard, add the following features:

Time-based input on all panels.
    - Select **Edit** on the dashboard.
    - Select **Add Input** > **Time**.  
    - Under each panel, select the magnifying glass icon to edit the search. 
      - For the time range, select **Shared Time Picker**.

A drilldown in the geographic map that links to new searches.  
    - Click **Edit** on the dashboard.
    - Select the three vertical dots on the map for more actions.
    - Select **Edit Drilldown**.
    - Select **Link to search** in the dropdown.
    - Leave **Auto** selected.
    - Select **Apply**.
    - Save the dashboard.









