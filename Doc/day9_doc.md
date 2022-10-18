# Linux Command Practice

| command | for |
|---------|--------|
| ```df -h \| grep /dev \| awk -F " " '{print $5}' ```| output will be ur percentage of memory used of kali machine.Where grep used for search and awk used for get specific column data |
|``` find /var -type f -name access.log ```|    find access.log file from var directory |
|``` service apache2 start ```<br/>``` ps -eaf \| grep apache2 ```| grep apache2 process info |
|``` gunzip filename.ext ```<br/>``` cat filename.ext \| head \| outpur.txt ```| unzip a file then read first 10 line also redirect those in an another file |
|``` touch file_{1..10}.txt ```| make multiple blank file at a time with touch |
|``` echo "please try hard and hard" \| sed 's/hard/harder/g'  ```| replace all hard to harder with sed command |
|``` apt install terminal ``` | install terminal package |
|``` apt remove temrinal ```<br/>``` apt purge terminal ```|permanently remove any package | 


# Web site scan up Tool 

|Tool| command | desc |
|----|---------|------|
| Nikto | ``` nikto -h scanme.nmap.org >> scaned_output.txt ``` | scanme.nmap.org site scan with nikto tool then redirect those data at scaned_output.txt file|
| zaproxy | ```  zaproxy ``` |- open this tool<br/>- type example.com at url <br/>- click at attack<br/>- scanning will be shown in down part<br/>- after scanning generate html report from Report/generate report|


# Task 
1. Write a powershell script to generate a list of event id which is related to 4624 id of Windows security log event . Then redirect into a file.

2. nmap download on ur windows machine then scanme.nmap.org site scan and save scanned data in a file.

3. scan metasploitable/dvwa site with zaproxy also generate a report.

4. install zenmap on ur kali machine.

5. Exploit more 3/4 module from Metasploitable . (see previous class note)