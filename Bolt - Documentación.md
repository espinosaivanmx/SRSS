## 2. Bolt - Ariel Ivan Espinosa Herrera

## Task 1. Deploy the machine

1. Start the machine

![[Pasted image 20241017220351.png]]

## Task 2. Hack your way into the machine!

1. What port number has a web server with a CMS running?

![[Pasted image 20241017220557.png]]

2. What is the username we can find in the CMS?

![[Pasted image 20241017221020.png]]

3. What is the password we can find for the username?

![[Pasted image 20241017221502.png]]

4. What version of the CMS is installed on the server? (Ex: Name 1.1.1)

![[Pasted image 20241017222302.png]]

5. There's an exploit for a previous version of this CMS, which allows authenticated RCE. Find it on Exploit DB. What's its EDB-ID?

![[Pasted image 20241017222538.png]]

6. Metasploit recently added an exploit module for this vulnerability. What's the full path for this exploit? (Ex: exploit/....)

![[Pasted image 20241017224520.png]]

7. Set the **LHOST, LPORT, RHOST, USERNAME, PASSWORD** in msfconsole before running the exploit

![[Pasted image 20241017225025.png]]

8. Look for flag.txt inside the machine.

![[Pasted image 20241017225125.png]]

