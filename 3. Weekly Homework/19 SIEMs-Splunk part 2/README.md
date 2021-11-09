## Rob Myers Week 19 Homework: Protecting VSI from Future Attacks
---

### Part 1: Windows Server Attack

#### Question 1

Based on the attack signatures, what mitigations would you recommend to protect each user account? Provide global mitigations that the whole company can use and individual mitigations that are specific to each user.

### Global Solution:

* Ensure that all server software updates have been completed and are updated weekly
* Ensure that username and password policies are up-to-date and being enforced
* Ensure that user's are using 10 character pass words with two special characters
* Ensure that user passwords are changed every 90 days
* Ensure that appropriate multi-factor authentication's are being used to verify user identity before allowing password changes
* Ensure that user's with 3 failed log-in attempts are locked out for 15 minutes 
* Block all known VPN IP Address traffic 
* Ensure that all firewall rules are up to industry standards 

### Individual Solution:

**User K:** 

* On 3/25/2020 between 9am - 10am USER K had a high amount of failed password reset alerts
* No evidence that the attacker was successful gaining access however, the logs indicate a high volume of failed password resets

**Individual Mitigation Strategy:** 

* **Ensure that ALL Global Solutions are in effect and specifically for USER K, manually reset their password** 

## [User K: Graphs](IMAGE/1.md) 

**USER A:** 

* On 3/25/2020 between 1am - 2am USER A had a high amount of account lock out's
* There were approximately **<u>1694</u>** "lock outs" which would indicate the attacker was attempting to use a Brute Force Attack.  

**Individual Mitigation Strategy:**

* **Ensure that ALL Global Solutions are in effect and specifically for USER A, manually reset their password**

* **Follow up with the IT Dept, and perform a Pen Test to verify that the system is secure against Brute Force Attacks** 

## [User A: Graphs](IMAGE/2.md) 

  
#### Question 2
VSI has insider information that JobeCorp attempted to target users by sending "Bad Logins" to lock out every user.

What sort of mitigation could you use to protect against this?

* Ensure that you have industry standard policies and security measures in places
* Ensure that the Global Solutions are in place. This should prevent this specific type of attack as well as other common attacks as well
* Always share information with all employees and provide routine training to educate cyber security practices 
  
### Part 2: Apache Webserver Attack:

#### Question 1
Based on the geographic map, recommend a firewall rule that the networking team should implement.

* The majority of the attacks came from the Ukrain, and it would be a good practice to block traffic from the Ukraine.

* The Firewall rule should state the following: "Block ALL incoming HTTP and IP Address traffic from the Ukraine."

## [Geographical Map](IMAGE/3.md) 

#### Question 2  

- VSI has insider information that JobeCorp will launch the same webserver attack but use a different IP each time in order to avoid being stopped by the rule you just created.

- What other rules can you create to protect VSI from attacks against your webserver?

* Ensure that all GLOBAL SOLUTIONS are implemented
* Specifically ensure that all Known VPN IP address's are blocked
* Block all known 'user_agents" associated with the attack
  
