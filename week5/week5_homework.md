## Week 5 Homework Submission File: Archiving and Logging Data

Please edit this file by adding the solution commands on the line below the prompt.

Save and submit the completed file for your homework submission.

---

### Step 1: Create, Extract, Compress, and Manage tar Backup Archives

1. Command to **extract** the `TarDocs.tar` archive to the current directory: 

sudo tar -xvvf TarDocs.tar 

2. Command to **create** the `Javaless_Doc.tar` archive from the `TarDocs/` directory, while excluding the `TarDocs/Documents/Java` directory:

sudo tar -cvvf Javaless_Doc.tar --exclude="Java" TarDocs

3. Command to ensure `Java/` is not in the new `Javaless_Docs.tar` archive:

Sudo tar -tf Javaless_Docs.tar | grep Java 

**Bonus** 
- Command to create an incremental archive called `logs_backup_tar.gz` with only changed files to `snapshot.file` for the `/var/log` directory:

#### Critical Analysis Question

- Why wouldn't you use the options `-x` and `-c` at the same time with `tar`? 

The reason you don't use the options -x and -c at the same time is becuase -x is to extract a file and -c is to create a file. You cant extract and create at the same time.  

---

### Step 2: Create, Manage, and Automate Cron Jobs

1. Cron job for backing up the `/var/log/auth.log` file:

0 6 * * 3 sudo tar -cvvzf /auth_backup.tgz /var/log/auth.log 

---

### Step 3: Write Basic Bash Scripts

1. Brace expansion command to create the four subdirectories:

mkdir -p ~/backups/{freemem,diskuse,openlist,freedisk}

2. Paste your `system.sh` script edits below:

    ```bash
    #!/bin/bash
    
    #prints the amount of free memory on the system and saves it to ~/backups/freemem/free_mem.txt

    free -h >> ~/backups/freemem/free_mem.txt 

    #prints disk usage and saves it to ~/backups/diskuse/disk_usage.txt

    du -h >> ~/backups/freemem/free_mem.txt

    #lists all open files and saves it to ~/backups/openlist/open_list.txt

    lsof >> ~/backups/freemem/free_mem.txt

    #prints file system disk space statistics and saves it to ~/backups/freedisk/free_disk.txt

    df -h >> ~/backups/freemem/free_mem.txt

    

3. Command to make the `system.sh` script executable:

sudo chmod +x system.sh 

**Optional**
- Commands to test the script and confirm its execution:

sh system.sh    or    ./system.sh 

**Bonus**
- Command to copy `system` to system-wide cron directory:

---

### Step 4. Manage Log File Sizes
 
1. Run `sudo nano /etc/logrotate.conf` to edit the `logrotate` configuration file. 

    Configure a log rotation scheme that backs up authentication messages to the `/var/log/auth.log`.

    - Add your config file edits below:

    ```bash
    /var/log/auth.log {
        weekly
        rotate 7
        notifempty
        delaycompression
        missingok
        endscript
    }
---



---
© 2020 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.