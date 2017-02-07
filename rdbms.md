# Week 8

1 . [SQL Injection](http://www.w3schools.com/sql/sql_injection.asp)
<br> 2 . [SQLi Attack](https://www.youtube.com/watch?v=ciNHn38EyRc)
<br> 3 . [Damn Vulnerable Web App](http://www.dvwa.co.uk/)

## Exercises

<br>1 . Complete the [SQL Injection](http://www.w3schools.com/sql/sql_injection.asp) tutorial.
<br>2 . Send me an email with the following [message](https://docs.google.com/document/d/1B-ztaNF94ToirsNu_SIeT7LGtaPnOG0EWJOU5xzPkbU/edit?usp=docslist_api).
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
firefox http://localhost:8???/login.php
```
<br>6 . [SQL Injection Exercises](https://docs.google.com/document/d/19xmxzBD-6jzDeqOUDhtQ7Yt3bws0-YAZL3DfN2xZv9I/edit?usp=docslist_api)


# Week 7

1 . Week 5 Answers (Exercises 1-5)
```
vim /home/share/rdbms/wk5part1.sql
mysql -t -u student < /home/share/rdbms/wk5part1.sql 
```
<br>2 . [SQL GROUP BY](http://www.w3schools.com/sql/sql_groupby.asp)
<br>3 . [OWASP Top 10 Web Vulnerabilities](https://storage.googleapis.com/google-code-archive-downloads/v2/code.google.com/owasptop10/OWASP%20Top%2010%20-%202013.pdf)
<br>4 . [SQLi Examples](http://codecurmudgeon.com/wp/sql-injection-hall-of-shame/)

##Group Exercise

In your groups pick one of these [SQLi Examples](http://codecurmudgeon.com/wp/sql-injection-hall-of-shame/) and prepare a short 5 minute presentation on it.

##SQL Exercises

Complete previous weeks exercises first. Create a file in your sqlexercises folder on Ygritte called "wk7.sql" and complete the following exercises:

<br>1 . Display each last name in the employees table with a count of the number of occurrences of that last name.
<br>2 . Display each first name in the employees table with a count of the number of occurrences of that first name.
<br>3 . Use the ORDER BY and LIMIT clauses to identify the ten most common last names in the database.
<br>4 . Use the ORDER BY and LIMIT clauses to identify the ten most common first names in the database.
<br>5 . Write SQL to determine if there Is there anyone in the database that has the same first name/last name combination (group by first_name, last_name and count emp_no)?
<br>6 . Show the top 10 employees that have moved department the most.
<br>7 . Show the top 10 employees that have had the most changes in salary.
<br>8 . Show the top 10 employees that have had the most changes in title. 
<br>9 . Put the answers to your github SQL challenges on github. Check your challenge answers against other students.

# Week 6

<br>1 . Week 3 Answers:
```
vim /home/share/rdbms/wk3answers.sql
mysql -t -u student employees < /home/share/rdbms/wk3answers.sql 
```
<br>2 . [Elliot uses Vim](https://drive.google.com/open?id=0B-CFaefA1v4RSC1XQTF5TVIyZHc)
<br>3 . [Exiting Vim 1](https://drive.google.com/open?id=0B-CFaefA1v4RY1h5VjM2c3BZUGs)
<br>4 . [Exiting Vim 2](https://drive.google.com/open?id=0B-CFaefA1v4RaHZrdVdlZEpPNUk)
<br>5 . [Vim Cheat Sheet](https://vim.rtorr.com/)
<br>6 . [SQL Sub Queries](http://beginner-sql-tutorial.com/sql-subquery.htm)

##Exercises
1 . Read the tutorial on [SQL Sub Queries](http://beginner-sql-tutorial.com/sql-subquery.htm)
<br>2 . Continue with the exercises from Week 5.
<br>3 . Show the top 10 employees that have moved department the most. (use file wk6.sql) 
<br>4 . Are there any employees that have the same first/last name and DOB?
<br>5 . Familiarise yourself with [Vim](http://www.vim.org/)


# Week 5

1 . [Aliases](http://www.w3schools.com/sql/sql_alias.asp)
<br>2 . [Dates](http://www.w3schools.com/sql/sql_dates.asp)
<br>3 . [Functions](http://www.w3schools.com/sql/sql_functions.asp)
<br>4 . [Inner Join Alternative](https://gist.github.com/GedMullen/da443d8e6956046c02b2)

##Exercises
Make sure you have added your SQL challenge detailed in Week 4 Exercies to the blue repository. 
<br>Create a "wk5.sql" file in your sqlexercies directory on Ygritte and write implement each of the following exercises using one SQL statement.

1 . Berni Sanella DOB 29/8/61 contributed 10% of her  salary (salary * 0.1) to her pension. How much per annum did she pay into her pension for each of her salaries? Create a query to output the pension contributions for each of her salaries (use Exercise 16 from Week 3).
<br>2 . Create an alias for the pension column in Q1 called “Pension”.
<br>3 . How much was Berni paid in the month of October 1997 ( salary / 12 )?
<br>4 . List the first/last name and gender of all the department managers and include the department name in this list (requires 2 table joins).
<br>5 . List the first/last name of all employees that work in Sales (2 table joins required).
<br>6 . List the first/last name of all the employees that have worked for Margareta Markovitch. (TOO DIFFICULT!)
<br>7 . Display the birth date and hire date of Berni Sanella in the format “21 January 2015”. Use appropriate column aliases so that the data is displayed in a meaningful way. 
<br>8 . Use the DATEDIFF function to determine how long ago Berni Sanella was hired. 
<br>9 . Use the DATEDIFF function to determine how old in years Berni Sanell is (divide by 365).
<br>10 . How old was Berni when she was hired?
<br>11 . Assume that the maximum to_date in the salaries table determines when an employee left the company. How old was Berni when she left the company?
<br>12 . What is the name of the department that has the most employees on 1.1.1990?
<br>13 . What is the name of the manager that has the least employees on 1.1.1990?
<br>14 . What is the most common employee title in the company on 1.1.1990?
<br>15 . How many people have the least common title on 1.1.1990?
<br>16 . Which department has the least number of females on 1.1.1990?
<br>17 . Continue with solving the SQL challenges of your fellow students. 



# Week 4

1 . [GitHub Is Your New CV](http://code.dblock.org/2011/07/14/github-is-your-new-resume.html)
<br>2 . [GitHub Home](https://github.com/)
<br>3 . [Example Profile](https://github.com/marijnh)
<br>4 . [GitHub CV Generator](http://resume.github.io/)
<br>5 . [Mineplex Project Contributions](https://drive.google.com/file/d/0B7l9n3yk5ob0b0JCWXU5ZjY4dUk/view?ts=58170cea)
##Exercises

1 . Complete these [GitHub Exercises](https://docs.google.com/document/d/1CWRBnj2pL_RIDAdgzoiZjm_fWHf_yznotVnGvG21lyk/edit?usp=sharing)
<br>2 . Add a file called yourname_sqlchallenges.md to the [Fife College blue](https://github.com/Fife-College/blue) private repository with an SQL challenge for your fellow students. Make sure you have a solution to the challenge and if the challenge requires any other knowledge other than that presented in class, you must indicate what else is required in your challenge.
<br>3 . Create a directory on Ygritte called "sqlchallenges" and place the answer to your challenge in this directory in a file named answer.sql. Attempt some of the challenges posed by other students and put your answers in the sqlchallenges directory in the format nameofchallenger_answer.sql. 

# Week 3

<br>1 . Using MySql on Ygritte interactively:
```
you@ygritte:~$ mysql -u student employees
mysql> select * from employees limit 10;
```
<br>2 . Using MySql using a script

```
mkdir sqlexercises
cd sqlexercises
gedit test.sql
select * from employees limit 10;
you@ygritte:~$ mysql -t -u student employees < test.sql
```

<br>4 . [Select](http://www.w3schools.com/sql/sql_select.asp)
<br>5 . [Where](http://www.w3schools.com/sql/sql_where.asp)
<br>6 . [Order By](http://www.w3schools.com/sql/sql_orderby.asp)
<br>7 . [Count](http://www.w3schools.com/sql/sql_func_count.asp)
<br>8 . [And & Or](http://www.w3schools.com/sql/sql_and_or.asp)
<br>9 . [Joins](http://www.w3schools.com/sql/sql_join.asp)

##Exercises

Create a directory on Ygritte called "sqlexercises" and create a file in that directory called "wk3.sql". Write SQL in wk3.sql to output the information from the employees database detailed in the tasks below. Once you have successfully completed each of the tasks use [comments](http://dev.mysql.com/doc/refman/5.7/en/comments.html) to comment out the SQL commands you have completed before moving on to the next task (don't delete the code you have completed). 

1 . A list of the first 10 female employees (use LIMIT 10).
<br>2 . A list of female employees that have a last name of “Gils”
<br>3 . Use the SQL created in Exercise 2 to create a list showing only the first name, last name and DOB.
<br>4 . Sort the output in 3 by first name.
<br>5 . Sort the output in 3 by DOB.
<br>6 . List all employees whose DOB is 18/1/1962 (dates can be referenced as strings - birth_date = '1961-08-29')
<br>7 . Who is the oldest employee?
<br>8 . Who is the newest (most recently hired) employee?
<br>9 . List all female employees that were born in the 60s.
<br>10 . List all male employees that were hired in the 80s.
<br>11 . Count the number of employees in the employees database.
<br>12 . Count the number of female employees that were born in the 50s.
<br>13 . What is the employee id of the person with the highest salary?
<br>14 . Find the employee details (name DOB etc) of the person with the highest salary (you will need to join the salaries and employees tables).
<br>15 . Find the employee details of the person with the lowest salary.
<br>16 . List all the salaries of Berni Sanella DOB 29/8/61 - order the query by to_date;
<!--
<br>12 . Bernie contributed 10% of her  salary to her pension. How much per annum did she pay into her pension for each of her  salaries? Create a query to output the pension contributions for each of her salaries.
<br>12 . Create an alias for the pension column in Q5 called “Pension”.
<br>12 . How much was Bernie paid in the month of October 1997 ( salary / 12 )?
-->
#Week 1 & 2 
<br>1 . [Unit Descriptor](http://www.sqa.org.uk/files/hn/H16W35.pdf)
<br> 2 . [MySQL Example Employee Database](https://dev.mysql.com/doc/employee/en/sakila-structure.html)
<br> 3 . [Corners Game](https://docs.google.com/document/d/1f8YCnRpKR5dgO-aP77ZXJg5SU6BWLMkiLsc99n1WZe4/pub)
<br> 4 . [Netcraft Survey](http://news.netcraft.com/archives/2015/10/16/october-2015-web-server-survey.html)
<br> 5 . [X2GO Client](https://drive.google.com/file/d/0B-CFaefA1v4RVWN5eFRlSV9YbVU/view?usp=sharing)
<br> 6 . [Connecting To Ygritte](https://docs.google.com/document/d/1wV6XGhOPlpwCMElZAqlH83YYXo_PpdNNdVMN6Toh3mw/pub)
<br> 7 . [Learning the Command Line on Codecademy](https://www.codecademy.com/learn/learn-the-command-line)
<br> 8 . [The Art Of The Command Line](https://github.com/jlevy/the-art-of-command-line)
<br> 9 . [SQL Tutorial](http://www.w3schools.com/sql/)
<br> 10 . You can switch off messages from Alec and Jack by using the following command:
```
mesg n
```
You can switch messages back on using:
```
mesg y
```

##Exercises
<br>1 . Make sure you change your password using the following command:
```
passwd
```
<br>2 . In groups - study the [MySQL Example Employee Database](https://dev.mysql.com/doc/employee/en/sakila-structure.html) and identify what information you can derive from the database e.g. the oldest employee etc. Document you findings on Ygritte in a file called employees.txt. You can use gedit to edit the file:
```
gedit employees.txt
```


