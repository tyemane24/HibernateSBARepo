# HibernateSBARepo

How to run:

1.DB Connection information is hibernate.cfg.xml, as well as in "sqlConnect" function in "HConnect.java" class. Please change accordingly:

Hconnect.java example:

	String url =  "jdbc:mysql://localhost:3306/SchoolDB"; 
		 String USER = "root";
		 String PASS = "Password123!";
     
   hibernate.xfg.xml example: 
   
   <property name="connection.driver_class">com.mysql.cj.jdbc.Driver</property>
   <property name="connection.url">jdbc:mysql://localhost:3306/SchoolDB?createDatabaseIfNotExist=true</property>
   <property name="connection.username">root</property>
   <property name="connection.password">Password123!</property>
   
   2. Run SQL script in zipped folder to initalize DB: 
   
   YemaneSMS/DBScript/SchoolDBScript.sql
   
   3. Run the application via "SMSRunner.java" class

   4. Example of full application below:

Are you a(n): 
 
1. Student 
 
2. Quit 
 Please enter 1 or 2.
1
Please enter your email
hluckham0@google.ru
Please enter your password
X1uZcoIh0dj

Would you like to: 
1.Register a class
2. Logout

Please Enter Selection: 
1

Course ID: 1 Course name: English Instructor: Anderea Scamaden

Course ID: 2 Course name: Mathematics Instructor: Eustace Niemetz

Course ID: 3 Course name: Anatomy Instructor: Reynolds Pastor

Course ID: 4 Course name: Organic Chemistry Instructor: Odessa Belcher

Course ID: 5 Course name: Physics Instructor: Dani Swallow

Course ID: 6 Course name: Digital Logic Instructor: Glenden Reilingen

Course ID: 7 Course name: Object Oriented Programming Instructor: Giselle Ardy

Course ID: 8 Course name: Data Structures Instructor: Carolan Stoller

Course ID: 9 Course name: Politics Instructor: Carmita De Maine

Course ID: 10 Course name: Art Instructor: Kingsly Doxsey

Course ID: 11 Course name: Psychology Instructor: Sigmund Freud

Course ID: 12 Course name: History Instructor: LaTonya Lewis
 
Which course would you like to be registered in? Enter the Course ID: 
5

Course ID:5 Course Name:Physics Instructor:Dani Swallow

You have been signed out!
