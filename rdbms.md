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
select * from employees limit 10
ged@ygritte:~$ mysql -t -u student employees < test.sql
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


