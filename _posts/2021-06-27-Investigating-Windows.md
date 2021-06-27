---
layout: post
title: Investigating Windows
---
![image](/assets/img/win/1.1.png)
	

# Task 1 Investigating Windows


### Q: What's the version and year of the Windows machine?
 
#### A: Windows Server 2016

to know about Windows details first open command prompt windows and enter systeminfo it will show you all information about windows

![image](/assets/img/win/1.2.png)

### Q: Which user logged in last?

#### A: Administrator

to know which is logged in last, we use net user Administrator because we log in with admin user

![image](/assets/img/win/1.3.png)

### Q: When did John log onto the system last?

#### A: 03/02/2019 5:48:32 PM

to know when did John log onto last, we use net user John command

![image](/assets/img/win/1.4.png)

### Q: What IP does the system connect to when it first starts?

#### A: 10.34.2.3

the IP shown when the machine start

![image](/assets/img/win/1.5.png)

### Q: What two accounts had administrative privileges (other than the Administrator user)?

#### A: Jenny, Guest

to see the accounts, we go to computer management and go to local users and groups and users

![image](/assets/img/win/1.6.png)

### Q: What's the name of the scheduled task that is malicious.

#### A: Clean file system


### Q: What file was the task trying to run daily?

#### A: nc.ps1


### Q: What port did this file listen locally for?

#### A: 1348

go to server manager to access to task scheduler

![image](/assets/img/win/1.7.png)


### Q: When did Jenny last logon?

#### Q: Never

we use net user Jenny to see all information about this user

![image](/assets/img/win/1.8.png)


### Q: At what date did the compromise take place?

#### A: 03/02/2019

in local disk C we find tmp file

![image](/assets/img/win/1.9.png)

### Q: At what time did Windows first assign special privileges to a new logon?

#### A: 03/02/2019 4:04:49 PM

open event viewer, go to windows logs and security and find even 4672

![image](/assets/img/win/1.10.png)


### Q: What tool was used to get Windows passwords?

#### A: Mimikatz

find it in TMP folder

![image](/assets/img/win/1.11.png)


### Q: What was the attackers external control and command servers IP?

#### A: 76.32.97.132

to see attacker external control and server IP go to windows and system32 and drivers etc and hosts file  

![image](/assets/img/win/1.12.png)


### Q: What was the extension name of the shell uploaded via the servers' website?

#### A: .jsp

the website server was in intetpub\wwwroot in local c

![image](/assets/img/win/1.13.png)


### Q: What was the last port the attacker opened?

### A: 1337

we go to Windows firewall and inbound Rules and allow outside connections

![image](/assets/img/win/1.14.png)


### Q: Check for DNS poisoning, what site was targeted?

#### A: Google.com

![image](/assets/img/win/1.15.png)


