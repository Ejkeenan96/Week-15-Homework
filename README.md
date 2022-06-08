# Week-15-Homework

## Web Application 1: Your Wish is My Command Injection

- Command Injection for ping 8.8.8.8 && cat ../../../../../etc/passwd

![ETC/PASSWD](Images/etc_passwd.jpg)

- Command Injection for ping 8.8.8.8 && cat ../../../../../etc/hosts

![ETC/HOSTS](Images/etc_hosts.jpg)

### Mitigation Stratergies

- Avoiding command line calls if at all possible. Whenever possible use only APIs
- Reducing the number of users to access the database and the secure the locations of all the confidential files and the directories by restricting the permissions
- Creating a white list of possible inputs for the system to accept only the pre-approved inputs. If you use this method avoid using characters such as: ; & | `

## Web Application 2: A Brute Force to Be Reckoned With

- Burp Attack
  - ![BURP](Images/Burp_Attack.jpg)

- Payload Usernames Input
  - ![BURP](Images/Usrname_Payloads.jpg)

- Payload Password Input
  -![BURP](Images/Passwd_Payloads.jpg)

- Succesful login
  -![Login](Images/Successful_Login.jpg)
