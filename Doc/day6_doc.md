### Canary Token for trace people
if u want to trace anyone's ip or location then u can generate a canary token via word / excell or etc file. 
- select ur token 
- give ur email address
- write any path like c:\

- thn u can download ur token file
- now give this file those, whom   ip or location u want to check
- if that person click on that file then u will get his/her location, ip etc to see these info click on [manage this token / history ] or u will get an email . 

**Note: don't click any suspicious link or file may be u r a targeted person for phishing method by threat actor** 

***Disadvantage:***
 - social engineer can harm u
***Advantage:***
 - u can generate a doc token file then u can store that file in ur machine
 - so if any outsider open that file u can get email 
 - so u can use this token for secure ur file



 ### python practice
  we can run any [powershell command from our python file](https://www.phillipsj.net/posts/executing-powershell-from-python/) . For example we want to close out any software means any process ,so powershell command is :
   ```Stop-Process -Name notepad (write any process name )```
 now we wanna run this command via python file .let's do it.

 1. create any python file like stop_process.py
 2. write this code onto ur python file 
   ```
   import subprocess
   subprocess.run(["powershell","-Command","Stop-Process -Name  notepad "])

   ```
 3. save python file
 4. now run the python file 
 5. you will see that if notepad is opened then it will be  close after run the python file.


 ### Task 
1. Write a  python program for generate a file with software name list from ur installed software list in windows os , just took ur software name and version and write in another file.
2. write a program for shut down ur computer in a  specific time 