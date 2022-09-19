### Some example of google dork 

 
Google Dorking বলতে অনেকেই শুধু inurl,intitle, filetype আর intext ই বুঝেন। কিন্তু কিভাবে dork use করে কাঙ্খিত result পাওয়া যায় তা জানেন না
তাদের জন্যই আজকের ই পোস্ট। আশা করি আপনাদের কাজে লাগবে☺️🙂

1.Vulnerable web servers
inurl:/proc/self/cwd
এই dork ব্যবহারের মাধ্যমে আপনি বিভিন্ন vulnerable এবং hacked web server গুলো খুজে পাবেন।

2.Open FTP servers
intitle:"index of" inurl:ftp
এই dork টি ব্যবহারের মাধ্যমে আপনি বিভিন্ন public ftp servers গুলো খুজে পাবেন।

3.Live camera
এখানে আবার ৩টা dork use করতে হয়।
★Various IP based cameras:
inurl:top.htm inurl:currenttime
★WebcamXP-based transmissions:
intitle:"webcamXP 5"
★general live cameras:
inurl:"lvappl.htm"

4.Government documents
allintitle: restricted filetype:doc site:gov
এই dork এর মাধ্যমে আপনি সাম্প্রতিক
internet এ exposed হওয়া সরকারি document গুলো খুজে পেতে পারেন।

5.SSH private keys
intitle:index.of id_rsa -id_rsa.pub
এই dork এর মাধ্যমে আপনি google দ্বারা index কৃত SSH private key গুলো
খুজে পেতে পারেন।

6.Email lists
filetype:xls inurl:"email.xls"

7.MP3, Movie, and PDF files
intitle: index of mp3
intitle: index of pdf intext: .mp4

এই বিষয়ে তো বুঝার বলার কিছু নাই আপনি যদি কোনো কিছুর pdf অথবা movie খুজে না পান তাহলে এই dork টি use করবেন।

8.SQL dumps
"index of" "database.sql.zip"

9.WordPress Admin
intitle:"Index of" wp-admin
এই dork এর সাহায্য অতি সহজে word press login page খুজে পাবেন।

10.cPanel password reset
inurl:_cpanel/forgotpwd

11.JIRA/Kibana
This dorks can also be used to find web applications hosting important
enterprise data (via JIRA or Kibana).
inurl:Dashboard.jspa intext:"Atlassian Jira Project Management Software"

inurl:app/kibana intext:Loading Kibana

12.Apache2
intitle:"Apache2 Ubuntu Default Page: It works"
এই dork ও একই কাজ vulnerable web server খুজে বের করা বিশেষ করে
Apache2 server গুলো এর কারন হলো
Apache2 অনেক জনপ্রিয় hosting app/website.

13.Weather
intitle:"Weather Wing WS-2"

14.phphpmyadmin
"Index of" inurl:phpmyadmin

15.Zoom videos
Zoom meeting can still be found:
inurl:zoom.us/j and intext:scheduled for

16.web log file
allintext:username filetype:log

17.Bug hunting program
intext:Bug Bounty Program site:country [suggest by stive edison]
