# WP_testing




Exploit 1
WP Version used: 4.2

Description: Using "XSS" Cross Site Scripting (JavaScript) to alert a message  

Steps:
1. Go to add 
2. new post 
3. in the body of new post text insert any javascript xss such as 
: <SCRIPT>alert('Hacked USING XSS')</SCRIPT>


