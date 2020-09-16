Little-Birds 1.0
Copyright (c) 2019 Rotem Shitrit, Elia Amar

Contents
========
 - General description
 - How to run "LittleBirds.exe"?
 - Manager info


General description
===================

Little-Birds is an emotion analysis system, that runs on short texts. 
The version we created is meant to run over tweets and scripts of Game of Thrones. 
The system runs a linear-regression-based prediction over the tweets.


How to run "LittleBirds.exe"?
===================

You must have MySQLserver (preferably 5.6 or 5.7) to run the system.
Load the databse that is saved at the file "LittleBirdsDataBase.sql", by following these steps:

1. Open the command prompt as an administrator.

2. Get to the MySQL-server's bin directory. For example, by entering the following command: "cd C:\Program Files\MySQL\MySQL Server 5.6\bin"

3. Then, create a "littlebirds" schema. For example, by entering the following command: "mysql - u root -p littlebirds < C:\LittleBirdsDataBase.sql
	Use your MySQL usrname instead of root.
	Use the path "C:\LittleBirdsDataBase.sql" if you copy the file to "C:\". Otherwise, provide the full path to the file instead.
	after running this command you'll be asked to insert your password as well.
	By the time the process is done in the terminal, "LittleBirds.exe" is ready to run.

4. Copy the file "LittleBirds.exe" to a directory outside the cd (important), with the directories "buttons" and "pictures", as well as the file "help.pdf".
	All of them must be located in the same directory. 
	Then, double-click on the icon of the file "LittleBirds.exe". Wait about 10 minuets until it'll get loaded.
	A black cmd screen will be opened as soon as you'll click, followed by the system's graphical interface when the loading is done. 


Manager info
===================

To login to the system as a manager, insert:
Username: "a"
Password: "a"