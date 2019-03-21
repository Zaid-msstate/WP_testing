# WP_testing
***************************************************************************************************
**************************************************************************************************
Using kali linux tool, Wpscan, after downgrading the wp version to 4.2 
: vulnerabilities identified
===========================
<img src="https://github.com/Zaid-msstate/WP_testing/blob/master/Wpscan.gif" width="800">


------------------------------------------------------------------------------------------------------
Exploit 1
-----------------------------------------------------------------------------------------------------
WP Version used: 4.2

Description: Using "XSS" Cross Site Scripting (JavaScript) to alert a message  

Steps:
1. Go to add 
2. new post 
3. in the body of new post text insert any javascript xss such as 
:// <SCRIPT>alert('Hacked USING XSS')</SCRIPT>



<img src="https://github.com/Zaid-msstate/WP_testing/blob/master/xss.gif" width="800">


---------------------------------------------------------------------------------------
Exploit 2 
--------------------------------------------------------------------------------------


Also, the this exploit follows the same idea which is using using XSS but in a different way: 

in this exploit, I used the xss in as a comment:

<img src="https://github.com/Zaid-msstate/WP_testing/blob/master/comment.gif"  width="800">






-------------------------------------------------------------------------------------------
Exploit 3
-----------------------------------------------------------
In this Exploit, I used a kali linux tool, wpscan
as a command line, I typed the commmand 

root@kali:~# wpscan --url http://wpdistillery.vm --enumerate u

this allows me to to expolit and display the list of all user on that machine 
including the admin



<img src="https://github.com/Zaid-msstate/WP_testing/blob/master/Enumerate_U.gif" width="800">
Enumerate_U
