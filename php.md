#Week 8

<br>1 . [PHP Coding Standards](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-1-basic-coding-standard.md)

#Week 7
**UCAS Workshop 31.10.16 @12pm in BF47**
<br>1 . Assessmnet instructions:
```
cat /home/share/assessments/php/readme.txt
```
<br>2 . Examples:
```
/home/share/phpcrud/loginmysqli
/home/share/phpcrud/loginpdo
/home/share/phpcrud/addpassword (locked)
/home/share/phpcrud/betsiwithpassword (locked)
/home/share/phpcrud/betswithsession (locked)

```
<br>3 . [Sessions Tutorial](http://www.w3schools.com/php/php_sessions.asp) 
##Exercises
<br>1 . Copy and run the "loginpdo" example to your own environment and make sure that it runs correctly for your own database. 
<br>2 . Modify the "addbets" example PHP app to include a password for the customer. Create a default admin account in your sql script.  
<br>3 . Add a login screen. Admin should redirect to the index page. Other (non admin) users should redirect to the "read.php".
<br>4 . If the user clicks "register" then redirect them to the create.php page. 
<br>5 . Stop the user from accessing the "customers.php" unless they are logged in as admin (see [Sessions Tutorial](http://www.w3schools.com/php/php_sessions.asp)).
<br>6 . Stop the user from accessing the "read.php" page unless they have logged in as a normal user.

#Week 6 - Thursday

##Exercises
<br>1 . Complete the [PHP Login Exercises](https://docs.google.com/document/d/1DtnOoUNieZOVxIXimgvxUESsfXNqj9evYXAZfAbyRi0/pub)
<br>2 . Complete a first draft of your website design for your assessment.

#Week 6

<br>1 . [FileZilla](https://drive.google.com/file/d/0B-CFaefA1v4RbDVCQlp3bEFjams/view?usp=sharing)
<br>2 . Assessments - due 10.11.16 @11pm:
```
cd /home/share/assessments/php
evince lo2.pdf
``` 
<br>3 . ["Crows Foot" Quick Reference](https://docs.google.com/document/d/13g8ft7SfZx2bjcboiq_26PzOS3xFaWCfsHUqJkN5XA0/pub)


# Week 5 - Thursday
<br>1 . [PHP Session Tutorial](http://www.w3schools.com/php/php_sessions.asp)
<br>2 . [User Registration And Login Example](http://www.codingcage.com/2015/01/user-registration-and-login-script-using-php-mysql.html)
##Exercises
<br>1 . Complete Tuesday's exercises.
<br>2 . Complete the [PHP Session Tutorial](http://www.w3schools.com/php/php_sessions.asp).
<br>3 . Copy and run the [User Registration And Login Example](http://www.codingcage.com/2015/01/user-registration-and-login-script-using-php-mysql.html)



# Week 5
<br>1 . Backing up your code to a backups directory:
```
cd <into the directory you want to backup>
cp -r . <path to your backups directory>
``` 
<br>2 . Copying the tutorial code to a ```tutorials``` directory:
```
cp -r /home/share/phpcrud/. tutorials
```

##Exercises
<br>1 . Make sure you modify the ```datatbase.php``` and ```sql``` files in the tutorials to point to your own database. Make sure you can run the tutorials in your own environments.
<br>2 . Modify the "addbets" tutorial so that when a customer is viewed a CRUD grid appears for their bets. Add functionality to add, update and delete a bet.   
# Week 4
<br>1 . Turning off code completion for PHP in Eclipse:
```
Window->Preferences->PHP->Editor->Content Assist->Uncheck Enable Auto Activation
```
<br> 2 . [PHP Documentation](http://www.php.net/)
<br> 3 . [PHP CRUD Tutorial](https://www.startutorial.com/articles/view/php-crud-tutorial-part-1)
<br> 4 . [betged.sql](https://gist.github.com/GedMullen/84e27db349b477822fbb14b431a05f6f)
<br> 5 . Checking your bets table:
```
mysql -t -u student <yourdatabasename>
select * from bets;
```
##Exercises
<br> 1 . Modify the [PHP CRUD Tutorial](https://www.startutorial.com/articles/view/php-crud-tutorial-part-1) to turn it into a website that records customer bets. Record the bet description, odds and amount (demonstration will be provided). You will need to create a new SQL script to modify the customers database. Base it on [this conceptual diagram](https://drive.google.com/file/d/0B-CFaefA1v4RbkpXaG5GSWNrWjQ/view?usp=sharing).



# Week 3 - Thursday

<br> 1 . [PHP CRUD Tutorial](https://www.startutorial.com/articles/view/php-crud-tutorial-part-1)
<br> 2 . [HTML Forms](http://www.w3schools.com/html/html_forms.asp)
<br> 3 . [HTML Tables](http://www.w3schools.com/html/html_tables.asp)
<br> 4 . [Bootstrap](http://www.w3schools.com/bootstrap/)
<br> 5 . Copying bootstrap to your project directory:
```
cp -r /home/share/bootstrap/* .
```

# Week 3

<br> 1 . [Creating Tables](http://www.w3schools.com/sql/sql_create_table.asp)
<br> 2 . [Data Types](http://www.w3schools.com/sql/sql_datatypes.asp)
<br> 3 . [Primary Keys](http://www.w3schools.com/sql/sql_primarykey.asp)
<br> 4 . [Foreign Keys](http://www.w3schools.com/sql/sql_foreignkey.asp)
<br> 5 . [Inserting Data](http://www.w3schools.com/sql/sql_insert.asp)
<br> 6 . Creating a database:
```sql
DROP DATABASE IF EXISTS <yourusername>;
CREATE DATABASE <yourusername>;
USE <yourusername>;
```
<br> 7 . Useful "sanity check" commands to put at the end of your script:
```sql
SHOW TABLES;
DESCRIBE employees;
SELECT * FROM employees LIMIT 10;
```

## Exercises
<br> 1 . Create an SQL script in your sqlexercises folder called wk3.sql and create the employees tables within your own database. Use the correct data types e.g. INT, VARCHAR, DATE etc.
<br> 2 . Amend the script to set up Primary Keys on the tables.
<br> 3 . Insert data into the tables.
<br> 4 . Run previous weeks queries against your new database.


# Week 2 - Thursday

<br>1 . [MySQL Example Employee Database](https://dev.mysql.com/doc/employee/en/sakila-structure.html)
<br>2 . [Select](http://www.w3schools.com/sql/sql_select.asp)
<br>3 . [Where](http://www.w3schools.com/sql/sql_where.asp)
<br>4 . [Order By](http://www.w3schools.com/sql/sql_orderby.asp)
<br>5 . [Count](http://www.w3schools.com/sql/sql_func_count.asp)
<br>6 . [And & Or](http://www.w3schools.com/sql/sql_and_or.asp)
<br>7 . [Joins](http://www.w3schools.com/sql/sql_join.asp)

```
mysql -t -u student < wk2.sql
```

.screen_layout

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
.screenrc
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
Installing X2GO on Ubuntu

```
sudo add-apt-repository ppa:x2go/stable;sudo apt-get update;sudo apt-get install x2goclient

```

##Exercises

Create a directory on Ygritte called "sqlexercises" and create a file in that directory called "wk2.sql". Write SQL in wk3.sql to output the information from the employees database detailed in the tasks below. Once you have successfully completed each of the tasks use [comments](http://dev.mysql.com/doc/refman/5.7/en/comments.html) to comment out the SQL commands you have completed before moving on to the next task (don't delete the code you have completed).
 
1 . A list of the first 10 female employees (use LIMIT 10).
<br>2 . A list of female employees that have a last name of “Gils”
<br>3 . Use the SQL created in 2 to create a list showing only the first name, last name and DOB.
<br>4 . Sort the output in 3 by first name.
<br>5 . Sort the output in 3 by DOB.
<br>6 . List all employees whose DOB is 18/1/1962 (dates can be referenced as strings - birth_date = '1961-08-29')
<br>7 . Who is the oldest employee?
<br>8 . Who is the newest employee?
<br>9 . List all female employees that were born in the 60s.
<br>10 . List all male employees that were hired in the 80s.
<br>11 . Count the number of employees in the employees database.
<br>12 . Count the number of female employees that were born in the 50s.
<br>13 . What is the employee id of the person with the highest salary?
<br>14 . Use the employee id identified in Q1 to locate the employee details from the salaries table.
<br>15 . Find the employee details of the person with the lowest salary.
<br>16 . List all the salaries of Berni Sanella DOB 29/8/61 - order the query by to_date;
 

# Week 2

1 . [GitHub Is Your New CV](http://code.dblock.org/2011/07/14/github-is-your-new-resume.html)
<br>2 . [GitHub Home](https://github.com/)
<br>3 . [Example Profile](https://github.com/marijnh)
<br>4 . [GitHub CV Generator](http://resume.github.io/)

##Exercises

1 . Complete these [GitHub Exercises](https://docs.google.com/document/d/1CWRBnj2pL_RIDAdgzoiZjm_fWHf_yznotVnGvG21lyk/edit?usp=sharing)


# Week 1

<br> 1 . [Corners Game](https://docs.google.com/document/d/1f8YCnRpKR5dgO-aP77ZXJg5SU6BWLMkiLsc99n1WZe4/pub)
<br> 2 . [Netcraft Survey](https://news.netcraft.com/archives/2016/06/22/june-2016-web-server-survey.html)
<br> 3 . [Linux Command Line Tutorial](https://www.codecademy.com/learn/learn-the-command-line)
<br> 4 . [Dynamically Generated Content](https://docs.google.com/presentation/d/1bWMd9ypXXUJGt-jDpjpRSfh6_2zHMRKjjBcldO0OMeM/pub?start=false&loop=false&delayms=60000&slide=id.p3)
<br> 5 . [X2GO Client](https://drive.google.com/file/d/0B-CFaefA1v4RVWN5eFRlSV9YbVU/view?usp=sharing)
<br> 6 . [Connecting To Ygritte](https://docs.google.com/document/d/1wV6XGhOPlpwCMElZAqlH83YYXo_PpdNNdVMN6Toh3mw/pub)
<br> 7 . [mysqlexample.php](https://gist.github.com/GedMullen/f58ea879c98ada9ca055)
<br> 8 . You can start a PHP server on Ygritte by issuing the following command (replace ??? with your unique port number):
```
php -S localhost:8??? 
```
<br> 9 . Linux editors [vim](http://vim.rtorr.com/), [nano](http://www.howtogeek.com/howto/42980/the-beginners-guide-to-nano-the-linux-command-line-text-editor/) and [gedit](https://en.wikipedia.org/wiki/Gedit)
<br> 10 . [PHP Tutorial](http://www.w3schools.com/php/) 

## Exercises

<br>1 . Run eclipse from the command line. Familiarise yourself with the IDE using the help menus: Help->Help Contents->Workbench User Guide. Create the HelloWorld program using Eclipse. 
<br>2 . Start this [PHP Tutorial](http://www.w3schools.com/php/default.asp) and run some of the exercises on Ygritte using eclipse. 


