#Week 10 
<br>1 .[Tesco Bank Hack](http://www.bbc.co.uk/news/technology-37974776)
<br>2 .[The Dark Web Declassified](https://www.youtube.com/watch?v=pmjAyL2VYBA)
<br>3 . [DDoS Attack Articles](https://www.ddosattacks.net/)
<br>4 .[DDoS Attack Types](https://en.wikipedia.org/wiki/Denial-of-service_attack) 

##Group Exercise
<br>1 . Create a 10 minute presentation on a specific type of DDoS attack. How would a hacker engineer such an attack and what countermeasures can be used to stop the attack? 


#Week 9

<br>1 . [DDoS Attack Articles](https://www.ddosattacks.net/)
<br>2 . [DDoS Attack Map](http://www.digitalattackmap.com/)
<br>3 . [Norse Attack Map](http://www.digitalattackmap.com/)
<br>4 . [hping](http://www.hping.org/)
<br>5 . [hping3 Examples](http://0daysecurity.com/articles/hping3_examples.html)
<br>6 . [iptables](https://support.rackspace.com/how-to/introduction-to-iptables/)
<br>7 . [iptables v hping3](http://blog.sevagas.com/?Iptables-firewall-versus-nmap-and-hping3-32)

##Exercise

**Using hping3 with iptables**

<br>1 . Follow the hping3 and iptables tutorials above. 
<br>2 . Clone your Kali virtualbox machine. 
<br>3 . Change the network name, IP address and MAC address of the clone.
<br>4 . Use ifconfig and ping to make sure that the two machines can connect. 
<br>5 . Run DVWA on the clone.
<br>6 . Use the hping tutorials above to issue a DDos attack on DVWA on the clone.
<br>7 . Use iptables to defend against the DDos attacks (see [examples](http://blog.sevagas.com/?Iptables-firewall-versus-nmap-and-hping3-32) )
 



#Week 8
<br>1 . [Windows Code Injection](http://www.ibtimes.co.uk/all-windows-versions-potentially-exposed-cyberattacks-thanks-new-code-injection-atom-bombing-1588719)
<br>2 . Last week review:
```
python sqlmap.py -u "http://localhost:8765/read.php?id=1" --passwords
```
<br>3 . DVWA - Command Injection:
```
localhost; ls -l
```
<br>4 . [commix](https://github.com/commixproject/commix)
```
git clone https://github.com/commixproject/commix.git commix
python commix.py --url="http://localhost:8???/vulnerabilities/exec/#" --data="ip=localhost" --cookie="PHPSESSID=???????????????; security=low"
#XSS Reflected - obtain PHP Session ID:
<script>alert(document.cookie)</script>
```
##Exercise
Investigate [commix](https://github.com/commixproject/commix) and identify exploits in the URL above. Record you findings in a file named commix.txt.

#Week 7
 <br>1 . [DNS DDOS Attack](http://www.independent.co.uk/life-style/gadgets-and-tech/news/netflix-twitter-internet-down-not-working-broken-paypal-ebay-facebook-instagram-a7374506.html)
<br>2 . [sqlmap](http://sqlmap.org)
<br>3 . [sqlmap Tutorial](http://www.binarytides.com/sqlmap-hacking-tutorial/)
```
git clone https://github.com/sqlmapproject/sqlmap.git sqlmap-dev #download sqlmap
cp -r /home/share/phpcrud/sqli/ . #copy over example vulnerable web app
cd sqli 
gedit customers.sql #change ged to your username
gedit database.php #change ged to your username
mysql -u student < customers.sql #set up your own database
php -S localhost:8??? #run the web server in another terminal
cd ../sqlmap-dev # cd into the sqlmap directory to run commands
python sqlmap.py -u "http://localhost:8???/read.php?id=1" 
python sqlmap.py -u "http://localhost:8???/read.php?id=1" --dbs
python sqlmap.py -u "http://localhost:8???/read.php?id=1" --tables -D rab
```
##Exercise

Assume you are a hacker attempting to steal information from the database. Investigate the [sqlmap](http://sqlmap.org) documentation and identify other exploits on the URL provided. What is the best exploit you can find? Don't try to modify or delete the database - your goal is to steal the information without the owner of the database knowing. Document the exploit in a file called sqlmap.txt. There will be a really expensive prize for the best exploit identified. 
```
gedit sqlmap.txt
```
 
#Week 6
<br>1 . [XSS Example](https://en.wikipedia.org/wiki/Samy_(computer_worm))
<br>2 . [XSS Tutorial](http://excess-xss.com/)
<br>3 . Install DVWA on Kali - Start MySql:
```
sudo /etc/init.d/mysql start
```
<br>4 . Clone, cofigure and run DVWA:
```
git clone https://github.com/ethicalhack3r/DVWA.git
cd DVWA
gedit config/config.inc.php; #(change the p@ssword value to empty string)
php -S localhost:8???
```
##Exercises
<br> 1 .Research the links in DVWA for XSS and the complete the [XSS Exercises](https://docs.google.com/document/d/1C3DhOaoUeo-tUU4v3I7xR39xtYOKZmRIe2P00hc4Rew/edit?usp=docslist_api)

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
 
