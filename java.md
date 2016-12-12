# Week 14
<br>1 . [Class Diagrams Tutorial](http://agilemodeling.com/artifacts/classDiagram.htm)
<br>2 . [UML Class Diagrams](https://drive.google.com/file/d/0B-CFaefA1v4RTmhRa2NEUHpFcXc/view?usp=docslist_api)
<br>4 . [KitBuildIt CRC Answers](https://docs.google.com/document/d/11oA-s1ZZjbHmFfEW8533Nkb5umgPt2k9c8dmuT_35TE/edit?usp=sharing)
## Exercises
<br>5 . [KitBuildIt Class Diagram](https://drive.google.com/file/d/0B-CFaefA1v4RVU9OYnVUejk3c1U/view?usp=sharing)

In your groups create class diagrams from the CRC cards you created in week 13 for KitBuildIt and RitePrice.

# Week 13

<br>1 . [KitBuildIt scenario](https://docs.google.com/document/d/1LfL8Q6N1RXKshODRG5qTILTMhUhwRuHxJlr60PwaolI/edit?usp=sharing) 
<br>2 . [RitePrice scenario](https://docs.google.com/document/d/1UpPiSM-FM419uq4TGYwu3sv_oFBtG0l_cS3jlbBHayo/edit?usp=sharing)

## Exercises

In your groups complete the following for both of the scenarios above.

<br>1 . Create CRC cards.
<br>2 . Create a System Level Use Case Diagram
<br>3 . For each use case identified in Exercise 2 create a use case scenario for best case scenario with triggers, pre/post conditions. Alternative or exceptional behaviour must be included in at least one use case scenario. 


# Week 12

```
cat /home/share/assessments/java/readme.txt
firefox /home/share/assessments/java/umll023.pdf
```

# Week 11

1 . [CRC Model Tutorial](http://agilemodeling.com/artifacts/crcModel.htm)
<br>2 . [UML Distilled CRC Cards - Page 75](http://www.amazon.co.uk/UML-Distilled-Standard-Modeling-Technology/dp/0321193687) 
<br>3 . [UML Class Diagrams](https://drive.google.com/file/d/0B-CFaefA1v4RTmhRa2NEUHpFcXc/view?usp=docslist_api)
<br>4 . [Example CRC Answers](https://docs.google.com/document/d/1yvUCpbw0oomFoHb_7ILwoKIoluMLwvsUtA0PUxMbccc/edit?usp=sharing)

## Exercises

1 . For the each of the following [use case examples](https://docs.google.com/document/d/16bjjcqkVtlwYeDtSx9ekH_pQCFNNoFjQtit5UGgxO-w/edit?usp=docslist_api) create a CRC card file on Ygritte. Name the file crc.txt.
<br>2. (Group)Create CRC cards from the checkout use case scenario you created last week.

# Week 10

<br>1 . [Use Cases Tutorial](http://www.usability.gov/how-to-and-tools/methods/use-cases.html)
<br>2 . [Use Case Example - ATM](http://epf.eclipse.org/wikis/openup/core.tech.common.extend_supp/guidances/examples/use_case_spec_CD5DD9B1.html)
<br>3 . [Agile Use Case Tutorial](http://www.agilemodeling.com/artifacts/useCaseDiagram.htm)
<br>4 . [Ch3 UML Distilled Use Cases](http://www.amazon.co.uk/UML-Distilled-Standard-Modeling-Technology/dp/0321193687)
<br>5 . UML Stage 1 Due 11.12.16 @ 11pm
```
firefox /home/share/assessments/java/umll023.pdf
``` 
## Exercises

1. Think about the process of paying for shopping using a self service checkout at a supermarket. Write the main success scenario for this process. Create a file in Ygritte called checkout.txt in that directory to document your use case scenario. Make sure you include the precondition and trigger for the scenario.
2. Create an alternative path/scenario for a shopping basket that includes alcohol.
3. Create a separate Use Case that details the process of a checkout assistant checking the amount of money in the self service machine.
4. Create a System Level Use Case diagram for the two use cases above using draw.io.
5. Identify 4 other Use Cases associated with a computer system that serves a supermarket. Draw a system level use case diagram that shows these scenarios. 

# Week 9
1. [Java ArrayList](http://www.tutorialspoint.com/java/java_arraylist_class.htm)
2. [Java Arrays](http://www.tutorialspoint.com/java/java_arrays.htm)
3. [Java Dates And Times](http://www.tutorialspoint.com/java/java_date_time.htm)
```
/home/share/java/oopbasics/v1/Transaction.java
```
## Exercises
1. Create a project in Eclipse called "datesandarrays" and complete the tutorials above. Make sure you can run the code in the tutorials successfully in eclipse.
2. Make sure you create an OOPBasics project in Eclipse and continue with the [OOP Basics](https://www3.ntu.edu.sg/home/ehchua/programming/java/J3a_OOPBasics.html) tutorial. Create the classes in this tutorial as instructed.
3. You have been tasked with modifying the Account class in Example 3.1 in the tutorial above to include a record of transactions associated with the account. An extra method called printStatement() needs to be added to the class so that a statement of transactions can be issued as required. The method should list the date, description and amount of the transaction with an updated balance amount. Create a separate Transactions class to store the transaction information. Hint: you will need to modify the implementation of the credit() and debit() methods and store your transaction history in an Array or an ArrayList. The date of the transaction should be derived (i.e. set it to current time) and not passed as a parameter. Modify the TestAccount class to test the modified code. Create at least 10 transactions with a mixture of credit and debit.
4. Modify the Account class to allow customers to withdraw funds even if they do not have a positive balance. Create a method called hasBeenOverdrawn() that returns a value of true if the account has been overdrawn at any time. Create appropriate test code. 
5. Create another method in the account class called printOverdrawnTransactions() that prints all the transactions that are associate with the Account that have resulted in a negative balance. Create appropriate test code.
6. Create a shell script called checkoopbasics.sh in the bin folder of your OOPBasics project and add an entry into the script that runs your test code for exercises 3-5. Add entries into this shell script as you complete the exercies below. 
7. Create an overloaded move() method in the ball class in section 3.2 that takes a direction string of the value "north","south","east" or "west" and a distance attribute and moves the ball in the required direction the required distance. Create appropriate test code.
8. You have been asked to redesign the UML diagram in 3.3. Your modified design should change the Author class to have an array of Books as a field of the Author class. Use appropriate accessor methods. Remove the Author attribute from the Book class. Create appropriate test code.
9. Add a printBooks() method to the Author class that will print a description of the books published by the author. Create appropriate test code.
10. Add a printBooksOutOfStock() method to the Author class.
11. Add a getMostExpensiveBook() method to the Author class.
12. Redesign the Student class in section 3.4 so that the courses and grades array fields are encapsulated by a separate class called Unit. The Student class will then contain a Unit array field. Add two additional fields to the Unit class - attendance and effort. Like the grade field the attendance and effort fields should be in the range 0-100. Add the accessor methods for these new fields.
13. Add a constant class field called PASS_MARK to the Unit class and set it to 60.
14. Create a isPassed() method to the Unit class that averages the grade, attendance and effort fields and then compares the average to PASS_MARK and returns the value of true or false.  



# Week 8
<br>1 . [Java and OO Glossary](http://www.cs.kent.ac.uk/people/staff/djb/oop/glossary.html)
<br>2 . [Polymorphism Image](https://drive.google.com/file/d/0B-CFaefA1v4RaFFSeUpPbkpKVDQ/view?usp=docslist_api)
<br>3 . [Polymorphism Definition](http://whatis.techtarget.com/definition/polymorphism)
<br>4 . [Polymorphism Tutorial 1](https://www.tutorialspoint.com/java/java_polymorphism.htm)
<br>5 . [Polymorphism Tutorial 2](https://docs.oracle.com/javase/tutorial/java/IandI/polymorphism.html)
<br>6 . [Red Dwarf Polymorph Episode] (http://reddwarf.wikia.com/wiki/RD:_Polymorph)
##Exercises
1. Complete the group exercise on Polymorphism.
<br>2 . Complete the following group questions:
```
/home/share/java/oopmc3qs.txt
```
 
# Week 7

**UCAS Workshop 31.10.16 @12pm in BF47**

<br>1 . [Abstraction Tutorial](https://www.tutorialspoint.com/java/java_abstraction.htm)
<br>2 . [Encapsulation Tutorial](https://www.tutorialspoint.com/java/java_encapsulation.htm)
<br>3 . [OOP Basics](https://www3.ntu.edu.sg/home/ehchua/programming/java/J3a_OOPBasics.html)
##Exercises
```
/home/share/java/oopmc2.txt
```
1. Complete the group exercises on Abstraction and Encapsulation.
2. Create a new project in Eclipse on Ygritte called OOPBasics and complete the [OOP Basics](https://www3.ntu.edu.sg/home/ehchua/programming/java/J3a_OOPBasics.html) tutorial. Create the classes in this tutorial as instructed.
3. You have been tasked with modifying the Account class in Example 3.1 in the tutorial above to include a record of transactions associated with the account. An extra method called printStatement() needs to be added to the class so that a statement of transactions can be issued as required. The method should list the date, description and amount of the transaction with an updated balance amount. Hint: you will need to modify the implementation of the credit() and debit() methods and store your transaction history in an Array or an ArrayList. The date of the transaction should be derived (i.e. set it to current time) and not passed as a parameter. Modify the TestAccount class to test the modified code. Create at least 10 transactions with a mixture of credit and debit.
4. Modify the Account class to allow customers to withdraw funds even if they do not have a positive balance. Create a method called hasBeenOverdrawn() that returns a value of true if the account has been overdrawn at any time. Create appropriate test code. 
5. Create another method in the account class called printOverdrawnTransactions() that prints all the transactions that are associate with the Account that have resulted in a negative balance. Create appropriate test code.
6. Create a shell script called checkoopbasics.sh in the bin folder of your OOPBasics project and add an entry into the script that runs your test code for exercises 3-5. Add entries into this shell script as you complete the exercies below. 
7. Create an overloaded move() method in the ball class in section 3.2 that takes a direction string of the value "north","south","east" or "west" and a distance attribute and moves the ball in the required direction the required distance. Create appropriate test code.
8. You have been asked to redesign the UML diagram in 3.3. Your modified design should change the Author class to have an array of Books as a field of the Author class. Use appropriate accessor methods. Remove the Author attribute from the Book class. Create appropriate test code.
9. Add a printBooks() method to the Author class that will print a description of the books published by the author. Create appropriate test code.
10. Add a printBooksOutOfStock() method to the Author class.
11. Add a getMostExpensiveBook() method to the Author class.
12. Redesign the Student class in section 3.4 so that the courses and grades array fields are encapsulated by a separate class called Unit. The Student class will then contain a Unit array field. Add two additional fields to the Unit class - attendance and effort. Like the grade field the attendance and effort fields should be in the range 0-100. Add the accessor methods for these new fields.
13. Add a constant class field called PASS_MARK to the Unit class and set it to 60.
14. Create a isPassed() method to the Unit class that averages the grade, attendance and effort fields and then compares the average to PASS_MARK and returns the value of true or false.  

# Week 6
<br>1 . [Inheritance Tutorial](https://www.tutorialspoint.com/java/java_inheritance.htm)
<br>2 . [Overriding Tutorial](https://www.tutorialspoint.com/java/java_overriding.htm)
<br>3 . [Encapsulation Tutorial](https://www.tutorialspoint.com/java/java_encapsulation.htm)
<br>4 . [OOP Basics](https://www3.ntu.edu.sg/home/ehchua/programming/java/J3a_OOPBasics.html)
<br>5 . [Inheritance Group Presentation](https://docs.google.com/presentation/d/1RO0367u4KIo2GIjcRQKKBNhD9F9eFKOS2XFRVURtmf0/edit?usp=sharing)
<br>6 . [Overriding Group Presentation](https://docs.google.com/presentation/d/1uqAe0nmlPMXP7SI4eqT9z7R54RCMvW4nE335aq1DveY/edit?usp=sharing)

## Exercises
<br>1 . Complete the multiple choice questions created by the group:

```
vim /home/share/java/qs.txt
```

# Week 5
<br>1 . [Oracle OO Tutorial](https://docs.oracle.com/javase/tutorial/java/concepts/index.html)
<br>2 . [Tutorials Point - Objects and Classes](http://www.tutorialspoint.com/java/java_object_classes.htm)
<br>3 . [OOP Basics](https://www3.ntu.edu.sg/home/ehchua/programming/java/J3a_OOPBasics.html)
# Week 9
1. [Java ArrayList](http://www.tutorialspoint.com/java/java_arraylist_class.htm)
2. [Java Arrays](http://www.tutorialspoint.com/java/java_arrays.htm)
3. [Java Dates And Times](http://www.tutorialspoint.com/java/java_date_time.htm)
```
/home/share/java/oopbasics/v1/Transaction.java
```
## Exercises
1. Create a project in Eclipse called "datesandarrays" and complete the tutorials above. Make sure you can run the code in the tutorials successfully in eclipse.
2. Make sure you create an OOPBasics project in Eclipse and continue with the [OOP Basics](https://www3.ntu.edu.sg/home/ehchua/programming/java/J3a_OOPBasics.html) tutorial. Create the classes in this tutorial as instructed.
3. You have been tasked with modifying the Account class in Example 3.1 in the tutorial above to include a record of transactions associated with the account. An extra method called printStatement() needs to be added to the class so that a statement of transactions can be issued as required. The method should list the date, description and amount of the transaction with an updated balance amount. Create a separate Transactions class to store the transaction information. Hint: you will need to modify the implementation of the credit() and debit() methods and store your transaction history in an Array or an ArrayList. The date of the transaction should be derived (i.e. set it to current time) and not passed as a parameter. Modify the TestAccount class to test the modified code. Create at least 10 transactions with a mixture of credit and debit.
4. Modify the Account class to allow customers to withdraw funds even if they do not have a positive balance. Create a method called hasBeenOverdrawn() that returns a value of true if the account has been overdrawn at any time. Create appropriate test code. 
5. Create another method in the account class called printOverdrawnTransactions() that prints all the transactions that are associate with the Account that have resulted in a negative balance. Create appropriate test code.
6. Create a shell script called checkoopbasics.sh in the bin folder of your OOPBasics project and add an entry into the script that runs your test code for exercises 3-5. Add entries into this shell script as you complete the exercies below. 
7. Create an overloaded move() method in the ball class in section 3.2 that takes a direction string of the value "north","south","east" or "west" and a distance attribute and moves the ball in the required direction the required distance. Create appropriate test code.
8. You have been asked to redesign the UML diagram in 3.3. Your modified design should change the Author class to have an array of Books as a field of the Author class. Use appropriate accessor methods. Remove the Author attribute from the Book class. Create appropriate test code.
9. Add a printBooks() method to the Author class that will print a description of the books published by the author. Create appropriate test code.
10. Add a printBooksOutOfStock() method to the Author class.
11. Add a getMostExpensiveBook() method to the Author class.
12. Redesign the Student class in section 3.4 so that the courses and grades array fields are encapsulated by a separate class called Unit. The Student class will then contain a Unit array field. Add two additional fields to the Unit class - attendance and effort. Like the grade field the attendance and effort fields should be in the range 0-100. Add the accessor methods for these new fields.
13. Add a constant class field called PASS_MARK to the Unit class and set it to 60.
14. Create a isPassed() method to the Unit class that averages the grade, attendance and effort fields and then compares the average to PASS_MARK and returns the value of true or false.  


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


