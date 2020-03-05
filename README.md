# Housing-Renting-Platform

This Readme file includes 5 questions and corresponding answers:

#### Question1: How to collect data?
#### Question2: How to execute the SQL implementation?
#### Question3: How to see results in Tableau?
#### Question4: How to test the website? 
#### Question5 : What techniques were used for website application?
#### Question6: How to play the video in our PPT?

(PS: We checked twice to make sure all the programs work on our laptops. If there does exist any problem , please feel free to contact us)

### Q1 : How to collect data?

Real Data: Neighborhood (nghHealth Center, nghEntertainment…)          
                    Apartment ( aptCampsDistance, rptGoogleReview…) 
                    Room (RomStatus, RomPrice..)

Makeup Data:  Renter (rntId, rntFirstName…)
                            Employee (empId, empFirstName…)
                            Company (cpyId, cpyName…)


###### Data Collection Technique

We put the python code in the file called "Project0503-07_Python_Data_Collection_Code.py".   

We wrote this program so that it could help us effectively get the real estate data from the rental website "www.apartment.com".


Step1: Put the file on the Desktop and Install Python3 and use Anaconda to open the Spider 3

Python3 Installation Address:
Windows: https://www.python.org/downloads/windows/
Mac: https://www.python.org/downloads/mac-osx/

Anaconda Installation Address:
Windows: https://docs.anaconda.com/anaconda/install/windows/
Mac: https://docs.anaconda.com/anaconda/install/mac-os/

Step2: Run the code


Suggestion: In order to run this program, you may first need to install the selenium package and chrome driver.

If you want to get more data from other regions, just change the key words above, then you could get millions or billions of data effectively if you want.


### Q2: How to execute the SQL implementation?

First, open SQL Server Management Studio and login to the respective server with your user details.

Then, use the Project0503-07_{purpose}-DDL CREATE TABLE.sql file to create the tables in the database, and if you need to drop any tables, you can find the DROP TABLE statements in the Project0503-07_{purpose}-DDL DROP TABLE.sql file.

To insert the data into the tables created earlier, execute the Project0503-07_{purpose}-DDL INSERT INTO.sql file. 

To create views use the Project0503-07_{purpose}-DDL CREATE VIEW.sql file and if certain views are to be dropped the Project0503-07_{purpose}-DDL DROP VIEW.sql file can be used.

Finally, for the user queries and the count statements, execute the Project0503-07_{purpose}-DML SELECT FROM.sql file.


### Q3: How to see results in Tableau?

Open the Tableau and login in with your user details.

If you cannot see some sheets, be sure to click the regenerate the extract button and save it on your computer.
If necessary, my Tableau username and password are provided here:
Username: BUDT758_Student_132
Password: yushengfu0421
Open the file ‘Project0503-07_Tableau.twb’ to see the tables and dashboards.


### Q4: How to test the website? 

To make it more convenient for you to get access to all the information on 
our website, we have rented a server which can help you view the website directly through this link: http://139.129.118.72

In the following part we will explain in detail about how we developed this website. And we've uploaded the zip file "Project0503-07_Website_Materials" that includes all the code required to run the website. Thank you very much for your patience!


Step1: Put the file on the Desktop and Installed Python2

Windows: https://www.python.org/downloads/windows/
Mac: https://www.python.org/downloads/mac-osx/


Step2: User terminal to run Python2, use command "ls" and "cd" to get the target dirrectory. Meanwhile, install the django

Here is a link about how to install django based on different laptop and could take as a reference: https://www.runoob.com/django/django-install.html

Typically, using the command "pip install django" in the terminal is good.

Step 3: Run the code " python manage.py runserver 0.0.0.0:8000 " in the terminal

Step 4: open a webpage, then enter " http://127.0.0.1:8000"

Step 5: Now we believe you could see our website home page 

Step 6: Remember you need to first sign up an account 

Step7: Go back to the home page, and sign in the account registered just now

Step8 : Congratulation! You're our client now, you could review all the information on our website by clicking into button "Neighborhood", "Apartment" and "Room" 

### Q5 : What techniques were used for this website application? 


For this website, we executed python code in the terminal, used django as web framework, used HTML to do the web page, used javascript to get the tableau code, and mapped the final results on the website. 

We've already shown how to test and run the website on a new laptop in this file 

For the tableau connection part, we'll also give the details in steps:

Step1: Logged in my Tableau account via VMWare, then connected Tableau to our SQL Server, 

Step2: Used the data from our database to do the case analysis

Step3: Extract the data and published it on the Tableau Public. (Following is the link of Tableau Public: 

https://public.tableau.com/profile/tableau20192803#!/vizhome/JustRentIt_Final/Apartment_DashBoard

Step4: Got the embedded code

Apartment:
 

Neighbourhood:
 

Room:
 

Step5: Put it in my code and realize the connection


### Q6 : How to play the video in our PPT ? 

The video of our website is in the file named Project0503-07_Website_Materials.zip. You can first unzip this file and put the video and the PPT in the same file, then you’ll be able to play the video in the PPT.

