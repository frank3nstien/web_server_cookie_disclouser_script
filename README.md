web_server_cookie_disclouser_script
===================================

HTTP Only cookie is only accessed from the server side, no client script can access that cookie,
when a webserver get a big cookie like same 10000 of characters for example A is char, it cannot process so it get us back 
error 400 [bad request], in that error has a vulnerability, its disclose cookies on a webserver.

Most of all dont know about the how to check a HTTPOnly vulnerability and web server Cookie Disclouser Vulnerability,
some People runs a Tools like Acunetix and burp scan or netsparker there are most of time you will see a HTTPOnly flag is not
set or cookies not protected, they just saw it and patched it through .htaccess file or including scripts in php headers file
to protect a web server.
But Most of dnt know how to check it, So i made it a script for checking specially for cookie disclouser vulnerability on web server



[+] I Have Made a Python Script for Checking HTTPOnly and Web server Cookie Disclouser Vulnerability.
[+] Test it Manually for checking vulnerability of HttpOnly on Web Applications, this is very common vulnerabilty on nowadays
[+] Impact of this Vulnerability is Low as well as Medium depending upon the Attacker :D

Usage:-
[+] Using of this python file on windows is very Simple
[+] Download a python for windows from here:  https://www.python.org/ftp/python/2.7.8/python-2.7.8.msi
[+] Run a python File
[+] C:\python27>python.exe and file path
 
Here is some Screenshots:
[+] If Target is Vulnerable
http://i.imgur.com/ZxyvU3x.png

[+] If Target is Not Vulnerable
http://i.imgur.com/cxIvThx.png

[+] Proof of Exploiting Vulnerability using Browser, Need an Cookie Manager
http://i.imgur.com/SXCcYZq.png
