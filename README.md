# DiscussionForum
This project is discussion portal which is a web application , where Students can post questions/Queries, teachers and students Reply to Each Others questions and queries.


NOTICE :: ALL THE PROCESS NEED ACTIVE INTERNET CONNECTION

You’ll need XAMPP Server (Version 5.6)
(note : Dont use version above 5.6, otherwise database won't connect, we using some modules of 5.6 , which were taken off in higher Versions)
Lets first download XAMP from "https://xampp.site" and set it up.
It will install Apache, Maria DB(MySQL), PHP, Perl.
Next set up phpmyadmin , check whether phpMyAdmin is connected or not, by going to https://localhost/phpmyadmin ,Webpage should open for your localhost, if it show some error, connect it properly. 
(note : If error does not go , You can also try stopping "MySQL Database" and "APACHE Web Server" from XAMPP control panel of your System{in "Manage Servers" option} and start them again.)
Put the code_folder inside “c:/opt/xampp/htdocs/” or “c:/opt/lampp/htdocs/”. 
Go To “localhost/phpmyadmin” in any browser and create Database with name "tech-forum".
In that Database, Import the SQL file given in "Database" folder of Code.
Next  go to URL: “http://localhost/Discussion-Forum”
Website should run.

Some Credentials to login to website:

Administrator : Username : admin
                Password : admin

Faculty : Username : Rock
          Password : qwerty

Student : Username : Vikas
	  password : vikas

However you can register as a Student and login through that account also.
For Faculty, you can register as a Teacher, but first need to open admin account and verify that User as Faculty.
 
 
