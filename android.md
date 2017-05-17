# Week 7

<br>1. Android SDK command line:
```
android -h
```
<br>2. Create a directory for your example android project:
```
mkdir androidstuff
cd androidstuff/
```
<br>3 . Create an android project:
```
android create project --target 1 --name HelloApp --path ./helloapp --activity MainActivity --package com.example.helloapp
```
<br>4 . Create a build file and build the app:
```
cd helloapp/
android update project --path .
ant release
```
<br>5. The app will be created at bin/HelloApp-release-unsigned.apk.
```
ls bin
```
<br>6. Only a signed app can be installed in an Android device. You can sign an apk with your own keystore.
```
keytool -genkey -v -keystore mykey.keystore -alias mykeyname -keyalg RSA -keysize 2048 -validity 365
```
Update ant.properties with your keystore info:
```
vim ant.properties

key.store=<keystore file location>
key.alias=<alias name>
key.store.password=<keystore password>
key.alias.password=<alias password>
```
<br>7. Build a signed app:
```
ant release
ls bin
```
Your app should appear as ```HelloApp-release.apk```.

<br>8. Copy the apk file to your android device and install it. 

<br>9. [Basic Structure of an Android Project](https://www.codeproject.com/Articles/395614/Basic-structure-of-an-Android-project)

##Exercises

<br>1. Change the name of your app.
<br>2. Change the launcher icon for your app.
<br>3. Add another TextView object to your main.xml layout file. 
<br>4. Add other objects to your layout file. 






# Week 6

1 . [Google VR Example ](http://burgler-ferret-12012.netlify.com/vr2/googlevr.html)
```
mkdir vr
cd vr
cp -r /home/share/vr/* .
```

# Week 5

1 . [Introduction to Android](https://docs.google.com/presentation/d/1v3cFgXF55k_Pqv0fOaEDTcNAq9N5cAO2t5-bD7Ye3Bw/pub?start=false&loop=false&delayms=60000)
<br>2 . [Android History](https://en.wikipedia.org/wiki/Android_version_history)
<br>3 . [Android Market Share](https://qz.com/826672/android-goog-just-hit-a-record-88-market-share-of-all-smartphones/)

# Week 4
1 . Android report assessment:
```
firefox /home/share/assessments/android/mobile.pdf 
```
# Week 2

1 . [Week 1 answer](https://gist.github.com/GedMullen/59e62a564e4aaf6acbca)
<br> 2 . [Validating XML](http://www.w3schools.com/xml/xml_validator.asp)
<br> 3 . [DTDs](http://www.w3schools.com/xml/xml_dtd.asp)
<br> 4 . [DTD Tutorial](http://www.w3schools.com/xml/xml_dtd_intro.asp)
<br> 5 . [Creating/Editing XML files in Eclipse](http://help.eclipse.org/mars/index.jsp?topic=%2Forg.eclipse.wst.xmleditor.doc.user%2Ftopics%2Ftxedttag.html)
<br> 6 . XML Assessment 2
<br> 7 . [Using XSL With Eclipse ](http://help.eclipse.org/luna/index.jsp?topic=%2Forg.eclipse.wst.xsl.doc%2Fhtml%2Flaunching%2Flaunching.html)
<br> 8 . [XSLT Tutorial](https://www.w3schools.com/xml/xsl_intro.asp)
```
firefox /home/share/assessments/android/lo2xml.pdf 
cp /home/share/assessments/android/ass2.xml . 
firefox /home/share/assessments/android/lo3xml.pdf 
cp /home/share/assessments/android/ass3.xml . 
```

## Exercises

<br> 1 . Add another 2 Invoice items to the invoice.xml file in the XMLExamples project in Eclipse. Change the date to a UK format. Make sure that the XML file still validates against the invoice.dtd file. 
<br> 2 . Modify the invoice.xml and invoice.dtd files in the XMLExamples project in eclipse so that a zip OR postcode can be specified. Modify the zip element in invoice.xml to test your DTD changes. 
<br> 3 . Change the name and phone attributes to elements. Test your modifications.
<br> 4 . Add a delivery address element.
<br> 5 . Modify the xml and dtd to allow for multiple invoices in the one XML file. 

# Week 1

<br>1 . Assessment Schedule:
```
vim /home/share/assessments/android/readme.txt
```
<br>2 . [XML Unit Descriptor](http://www.sqa.org.uk/files/hn/FM9735.pdf)
<br>3 . [XML Tutorial](http://www.w3schools.com/xml/)
<br>4 . XML Assessment 1
```
firefox /home/share/assessments/android/lo1xml.pdf 
```
## Exercise

1 . In groups create an XML document called "teams.xml" on Ygritte that represents the following [data](http://www.football-league.co.uk/sky-bet-championship/league-table/) (just create data for the first three teams as an example.) The XML document is to be regularly updated and provided to partner sites (such as the BBC) to display the latest league table.

