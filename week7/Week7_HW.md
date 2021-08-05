# Rob Myers WEEK 7 Home work

## Task 1: Create a GPO: Disable Local Link Multicast Name Resolution (LLMNR)
Instructions

Name the Group Policy Object No LLMNR.


Right-click the new No LLMNR GPO listing and select Edit to open the Group Policy Management Editor and find policies.


In the Group Policy Management Editor, the policy you are looking for is at the following path: Computer Configuration\Policies\Administrative Templates\Network\DNS Client.


Find the policy called Turn Off Multicast Name Resolution.


Enable this policy.

<br>


![picture](IMAGE/No_LLMNR.PNG)

 <br>

Exit the Group Policy Management Editor and link the GPO to the GC Computers organizational unit you previously created.

<br>

![picture](IMAGE/linkLLMNR.PNG)


![picture](IMAGE/LLMNR_Enabled.PNG)

## Task 2: Create a GPO: Account Lockout