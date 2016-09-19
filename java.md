
# Week 4

<br>1 . [Java Documentation Overview](http://www.oracle.com/technetwork/java/javase/documentation/api-jsp-136079.html)
<br>2 . [I/O From The Command Line](https://docs.oracle.com/javase/tutorial/essential/io/cl.html)
<br>3 . [Modified Password.java](https://gist.github.com/GedMullen/5f5b73758d0f2cfeac56a5a90e88d5e8)

## Exercises 

<br>1 . Implement the verify() and change() methods in the command line tutorial above to verify the password against an array of three possible existing passwords. The change() method should update the array with the new password. 
<br>2 . Create a new Menu class that displays a menu to the user. Provide a menu item for the user to change their password by using the code you wrote for Exercise 1. Also create menu items that allow the user to run the code you created in previous week's exercises. 
<br>3 . Modify the verify() and change() methods above to check the password for a given login id. 
<br>4 . Change your code so that only a user called "admin" can change their password. Do not show the change password menu item to users that are not admin. 

# Week 3

<br> 1 . [Oracle Academy](http://ilearning.oracle.com/ilearn/en/learner/jsp/login.jsp?site=OracleAcad)
<br> 2 . Linux editors [vim](http://vim.rtorr.com/), [nano](http://www.howtogeek.com/howto/42980/the-beginners-guide-to-nano-the-linux-command-line-text-editor/) and [gedit](https://en.wikipedia.org/wiki/Gedit)
<br>3 . [Oracle Certified Associate Java 7 Programmer 1](http://education.oracle.com/pls/web_prod-plq-dad/db_pages.getpage?page_id=5001&get_params=p_exam_id:1Z0-803&p_org_id=&lang=)
<br>4 . [OCA Java 7 Book](http://www.amazon.co.uk/OCA-Java-Programmer-Certification-Guide/dp/1617291048)
<br>5 .screen_layout
```
split -v
screen -t s1
focus
screen -t s2
split
focus
screen -t s3
focus
```
<br>6 .screenrc
```
defscrollback 10000
source .screen_layout
layout save def
startup_message off
# switch windows with F3 (prev) and F4 (next)
bindkey "^[OR" prev
bindkey "^[OS" next
# mouse tracking allows to switch region focus by clicking
mousetrack on
```
<br>7 . Installing X2GO on Ubuntu
```
sudo add-apt-repository ppa:x2go/stable;sudo apt-get update;sudo apt-get install x2goclient

```
## Exercises

<br>1 . Complete week 2 exercises. 
<br>2 . Start the Java Foundations course in [Oracle Academy](http://ilearning.oracle.com/ilearn/en/learner/jsp/login.jsp?site=OracleAcad)

 

# Week 2

<br>1 . [Java Introduction](https://docs.google.com/presentation/d/1dsZd2c00zmYxtRmyCM6NK-2RxiIFhm7JzrNebpi7v5A/pub?start=false&loop=false&delayms=3000&slide=id.p10)

## Exercises

<br>1 . Create a project called "warmup" in Eclipse on Ygritte and complete the following [exercises.] (https://docs.google.com/document/d/1zcppr0POAaVqlQIxyX2rl1E50z53ZFqc4E88hB9IQFQ/edit?usp=drive_web)


# Week 1

<br>1 . [X2GO Client](https://drive.google.com/file/d/0B-CFaefA1v4RVWN5eFRlSV9YbVU/view?usp=sharing)
<br>2 . [Connecting To Ygritte](https://docs.google.com/document/d/1wV6XGhOPlpwCMElZAqlH83YYXo_PpdNNdVMN6Toh3mw/pub)
<br>3 . Unit Descriptors: [H17135](http://www.sqa.org.uk/files/hn/H17135.pdf) and [H17235](http://www.sqa.org.uk/files/hn/H17235.pdf)
<br>4 . Ygritte reboot times: Monday-Friday during term time 08:00 and 20:00.
<br>5 . [Oracle Java Tutorial](https://docs.oracle.com/javase/tutorial/)
## Exercises

<br>1 . Use this [tutorial](https://docs.oracle.com/javase/tutorial/getStarted/cupojava/unix.html) to create a java program using the Linux command line. Don't put the file in the /temp directory, put it in a folder under your home directory. You can use gedit instead of pico as your editor if you prefer.
<br>2 . Run eclipse from the command line. Familiarise yourself with the IDE using the help menus: Help->Help Contents->Workbench User Guide. Create the HelloWorld program using Eclipse. 


