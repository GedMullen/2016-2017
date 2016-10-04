# Week 5

<br>1 . [Facebook Outage](http://www.bbc.co.uk/news/world-us-canada-34383655)
<br>1 . [SQL Tutorial](http://www.w3schools.com/sql/)
<br>2 . [SQL Injection Exercises](https://docs.google.com/document/d/19xmxzBD-6jzDeqOUDhtQ7Yt3bws0-YAZL3DfN2xZv9I/edit?usp=docslist_api)
<br>3 . [OWASP Zed Attack Proxy](https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project)
<br>4 . Installing ZAP: 
```
mkdir zap
cd zap
cp /home/share/zap/ZAP_2.5.0_Linux.tar.gz .
tar -zxvf ZAP_2.5.0_Linux.tar.gz
./zap.sh
```
##Exercises 
<br>1 . Introduce yourself to the concept of SQL programming by spending 20 minutes on the initial exercises in this [SQL Tutorial](http://www.w3schools.com/sql/)
<br>2 . Run DVWA and complete these [SQL Injection Exercises](https://docs.google.com/document/d/19xmxzBD-6jzDeqOUDhtQ7Yt3bws0-YAZL3DfN2xZv9I/edit?usp=docslist_api) 
<br>3 . Install ZAP using the instructions above. 

# Week 4

<br>1 . [OWASP Top 10 Web Vulnerabilities](https://storage.googleapis.com/google-code-archive-downloads/v2/code.google.com/owasptop10/OWASP%20Top%2010%20-%202013.pdf)
<br>2 . [SQLi Examples](http://codecurmudgeon.com/wp/sql-injection-hall-of-shame/)
<br>3 . [X2GO Client](https://drive.google.com/file/d/0B-CFaefA1v4RVWN5eFRlSV9YbVU/view?usp=sharing)
<br>4 . [Connecting To Ygritte](https://docs.google.com/document/d/1wV6XGhOPlpwCMElZAqlH83YYXo_PpdNNdVMN6Toh3mw/pub)


## Exercises 
<br>1 . Send me an email with the following [message](https://docs.google.com/document/d/1B-ztaNF94ToirsNu_SIeT7LGtaPnOG0EWJOU5xzPkbU/edit?usp=docslist_api).
<br>2 . Complete Exercise 1 from last week. 
<br>3 . Copy DVWA to your home drive using the following commands:

```
mkdir webapps
cp -r /home/share/dvwa/. webapps
```
You will need to change the database name in the following file (once you have copied it):
````
gedit webapps/DVWA-1.9/config/config.inc.php
````
<br> 4 . Run a PHP web server in the webapps directory:

```
cd 
cd webapps/DVWA-1.9
php -S localhost:8???
```
<br>5 . Point firefox to the following URL:
```
http://localhost:8???/login.php
```
<br>6 . [SQL Injection Exercises](https://docs.google.com/document/d/19xmxzBD-6jzDeqOUDhtQ7Yt3bws0-YAZL3DfN2xZv9I/edit?usp=docslist_api)



# Week 3

<br>1 . [Betfair DDos Attacks](http://www.information-age.com/how-to-survive-a-denial-of-service-attack-284366/)
<br>2 . [SQLi Examples](http://codecurmudgeon.com/wp/sql-injection-hall-of-shame/)
<br>3 . [OWASP](https://www.owasp.org/index.php/Main_Page)
<br>4 . [WebGoat](https://www.owasp.org/index.php/Category:OWASP_WebGoat_Project)
<br>5 . [SQL Tutorial](http://www.w3schools.com/sql/)
<br>6 . [Web Scarab](https://www.owasp.org/index.php/WebScarab_Getting_Started)
```
wget https://github.com/WebGoat/WebGoat/releases/download/7.0.1/webgoat-container-7.0.1-war-exec.jar
java -jar webgoat-container-7.0.1-war-exec.jar 
http://localhost:8080/WebGoat/
```

## Exercise

1 . Choose one of the [SQLi Examples](http://codecurmudgeon.com/wp/sql-injection-hall-of-shame/) and write a short report (500 words) describing the attack. Include information (if available) such as who carried out the attack, why they did it and what effect the attack had on the website or the server targeted. Was the exploit preventable? Search for other articles related to the attack and reference them in your report. 
 
