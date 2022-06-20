<!----------------------------------------------------------------------------------------------------------------------------->
**Date : 1-Feb-2022** 
<h3 align='center'>Introduction to Linux & Installing Ubuntu</h3>

<p align="justify">Linux is an open-source operating system like other operating systems such as Microsoft Windows, Apple Mac OS, iOS, Google android, etc. An operating system is a software that enables the communication between computer hardware and software. It conveys input to get processed by the processor and brings output to the hardware to display it. This is the basic function of an operating system.</p>

- Download the linux distribution of your choice.
- Creating Boot pendrive using rufus.exe in windows.
- Restart the system and open boot menu using boot key. (Eg.- F8, F2 etc.)
- Select your boot device in boot menu.
- Select Install Ubuntu then Click Normal Installation.
- Select where to install alongside window or Erase disk or something else.
- Then Click next and start ubuntu installation.
- For More detail about Installation Guide [Click here](https://phoenixnap.com/kb/install-ubuntu-20-04)
<br>

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 2-Feb-2022** 
<h3 align='center'>Introduction to LAMP Stack</h3>

<p align="justify">The LAMP stack is a popular open-source solution stack used primarily in web development.LAMP consists of four components necessary to establish a fully functional web development environment. The first letters of the components' names make up the LAMP acronym:</p>

- Linux is an operating system used to run the rest of the components.
- Apache HTTP Server is a web server software used to serve static web pages.
- MySQL is a relational database management system used for creating and managing web databases, but also for data warehousing, application logging, e-commerce, etc.
- PHP, Perl, and Python are programming languages are used to create web applications.
- Installing lamp on Ubuntu System.
- Verifying by run LAMP on localhost.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 3-Feb-2022**
<h3 align='center'>Introduction to frappe</h3>

<p align="justify">Frappe, pronounced fra-pay, is a full stack, batteries-included, web framework written in Python and Javascript with MariaDB as the database. </p>
**Why Frappe?
<p align="justify">The key difference in Frappe compared to other frameworks is that meta-data is also treated as data. This enables you to build front-ends very easily. We believe in a monolithic architecture, so Frappe comes with almost everything you need to build a modern web application. It has a full featured Admin UI called the Desk that handles forms, navigation, lists, menus, permissions, file attachment and much more out of the box.</p>

- Install Frappe-bench and its required tool. For more info [Click here](https://frappeframework.com/docs/v13/user/en/installation).
<br>

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 4-Feb-2022**
<h3 align='center'>Creating App and Site & run on local server in Frappe</h3>

- Start Bench in one Terminal.
- In Second Terminal.
- Creating App by using **bench new-app library_management** inside Frappe-bench Directory.
- Creating site by using **bench new-site library.test** inside Frappe-bench Directory.
- Run Site on Localhost by using library.test custom port name.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 5-Feb-2022**
<h3 align='center'>Introduction to Github Pages</h3>

- Getting Information What is GitHub Pages.
- Create a New Repository on GitHub.
- Setting Repository as the main branch and setting a theme for GitHub pages.
"policy domain="path" rights="none" pattern="@*"- Learning about Personal access tokens for push Local Repository on GitHub.
- Learning Syntax of Markdown Language in GitHub.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->

**Date:7-Feb-2022**
<h3 align='center'>Introduction to budibase</h3>

Budibase is an all-in-one low-code platform for building, designing, and automating business apps, such as; admin panels, forms, internal tools, client portals, and more. Before Budibase, it could take developers weeks to build simple CRUD apps; with Budibase, building CRUD apps takes minutes.

Today i am installing docker for hosting app in budibase .It is successfully installed. But i got error during 'setting up budibase'.Not solved yet. I follow "https://github.com/Budibase/docs/tree/master/self-hosting" .
<br>

<!---------------------------------------------------------------------------------------------------------------------------->

**Date : 10-Feb-2022** 
<h3 align='center'>Introduction to Docker, Virtual Machine </h3>

**What is Docker?**
<p align="justify">Docker is popular virtualization software that helps its users in developing, deploying, monitoring, and running applications in a Docker Container with all their dependencies (frameworks, libraries, etc.) to run an application in an efficient and bug-free manner.Docker Containers are Light-weight, Applications run in isolation,Occupies less space, Easily portable and highly secure, Short boot-up time.</p>
- It can run multiple containers on a system.
- It can start multiple containers at a time on the Docker engine.
<br>

**What is Virtual Machine?**
<p align="justify">A Virtual Machine (VM) is a compute resource that uses software instead of a physical computer to run programs and deploy apps. One or more virtual “guest” machines run on a physical “host” machine.  Each virtual machine runs its own operating system and functions separately from the other VMs, even when they are all running on the same host. This means that, for example, a virtual MacOS virtual machine can run on a physical PC.</p>
- It can start only a single VM on a VMX.
- It can run only a limited number of VMs on a system.
<br>

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 11-Feb-2022** 

<h3 align='center'>Create a CRUD app in budibase</h3>

<p align="justify">Building apps with Budibase involves 4 simple steps:

Install Budibase - Use Budibase Cloud to get started in seconds, or self-host your apps using Docker, Kubernetes , or DigitalOcean.
Add data - You can connect to data sources like PostgreSQL, Rest APIs, MS SQL, MySQL and more, or start from scratch with Budibase's built-in database (Budibase DB, built on top of CouchDB).
Design your UI - Build beautiful, accessible user interfaces people enjoy using. Autogenerate CRUD screens from your data, or create custom screens from scratch. Use powerful components, such as tables, buttons, form inputs, to enrich your interface. Switch from light mode to dark mode with just a click.
Automate processes - In seconds, setup automations such as email alerts, Slack notifications, CRON actions, and more.</p>

For creating CRUD app click on "https://docs.budibase.com/docs/build-a-crud-app".<br>

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 12-Feb-2022**
<!----------------------------------------------------------------------------------------------------------------------------->
<h3 align='center'>Introduction to Selenium, Budibase</h3>
- Selenium is browser automation tool by which you can create a script which automatically done task like fill credential and click for search.
- Budibase is a development platform designed for speed and productivity. 
- <p align="justify">With Budibase, developers no-longer experience repetition, long-dev cycles. Instead, developers are more productive, happier, and can deliver applications they're proud of in minutes.</p>
- 


<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 14-Feb-2022**

<h3 align='center'>Understanding the concept of budibase app </h3>
I am currently working on budibase. Today i was reading the concept of apps that how they are created in Budibase.
I haven’t done anything extra on budibase except reading the documentation and understanding the concept of built-in apps in budibase

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 15-Feb-2022**

<h3 align='center'>Working on Job portal app in budibase</h3>
Today I am working on Job portal app. If we want to access a budibase app without login, you will need to make some "Public" screens, and browse directly to the URL for those screens.

You will also need to make sure that your public screens are only accessing tables/queries that have "Public" access. Beware that this will mean that all data in those tables will be public (if "Read" is set to Public).
And I successfully make all screens public.
I checked how all pages are created in job portal app. How it to be published. 


<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 17-Feb-2022**
<h3 align='center'>Create CRUD app using MySQL in budibase</h3>

Today I am creating CRUD App. For creating CRUD app click on "https://docs.budibase.com/docs/build-a-crud-app".<br>

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 18-Feb-2022**

<h3 align='center'>Creating Library Management App </h3>
<p align="justify">As per official documentation I create Library Management App. 
 - Install app on site then creating doctype.
 - Use Features like Naming Series, Permission Rules. Learn Controller methods, Doctype Features, Form Scripts.
 - Adding Web view for preview Articles on web.</p>

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 19-Feb-2022**

<h3 align='center'>Creating Library Management App in Frappe</h3>
<p align="justify">I learned some new commands of bench that are as following:

bench –version: To check the version of bench.

bench –site <site-name> list-apps: This will give the list of all apps that are installed on site.

bench –site <site-name> console: To access the python console.

bench –site <site-name> mariadb: To access the mariadb console.

bench backup: Ceate a backup of the default site.

bench –site <site-name> set-admin-password <password>: This will reset the administrator password.

bench remove-app <app-name>: This will remove app from bench.

I started building a simple Library Management System in which the Librarian can log in and manage Articles and Memberships. This will include:

Article: A Book or similar item that can be rented.
Library Member: A user who is subscribed to a membership.
Library Transaction: An Issue or Return of an article.
Library Membership: A document that represents an active membership of a Library Member.
Library Settings: Settings that define values like Loan Period and the maximum number of articles that can be issued at a time.</p>

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 21-Feb-2022**

<h3 align='center'>Introdution to TMUX and Mosh</h3>
<p align="justify">Today we were working on education domain and trying to understand the student module of education domain. Today we got to know two new tools which are really very helpful for the coders which are TMUX and MOSH. Mosh: Mosh is free and command-line software that is used to connect from a client computer to a server over the Internet to run a remote terminal. Mosh is more intelligent than SSH. While the SSH client waits for a TCP response from the server before showing your typing, Mosh will display your typing in real-time and even give underlined typing predictions. The mosh program will SSH to user@host to establish the connection. As you know, SSH may prompt the user for a password or use public-key authentication to log in. But mosh runs the mosh-server process (as the user) on the server machine. Mosh will run inside your Terminals such as xterm, gnome-terminal, urxvt, Terminal.app, iTerm, emacs, screen, or tmux.
Tmux: Tmux is a Linux application that allows multitasking in a terminal window. It stands for Terminal Multiplexing, and is based around sessions. Users can start a process, switch to a new one, detach from a running process, and reattach to a running process.</p>
 
<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 22-Feb-2022**


<h3 align='center'>Working on ERPGURU </h3>
<p align="justify">Today I started working on new platform frappe. It is open source. Today I am reading the documentation of frappe to understand the education domain. Today I have created some programs and courses now i am trying to understand how to enroll students in programs and courses.</p>


<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 23-Feb-2022**

<h3 align='center'>Working on erpGURU/h3>
Today sir has assigned the task to explore education domain. I am reading the documentation and trying to understand it. First for setup of education domain. We have to follow steps like Create progam, Courses, Students etc.
<p align="justify"> </p>

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 24-Feb-2022**

<!----------------------------------------------------------------------------------------------------------------------------->


<h3 align='center'> learning about the modules of education domain</h3>
<p align="justify"> I am learning about the modules of education domain.
Under faculty modules I have added teachers and checked the database entries .Today I have also learnt about GitHub basic commands like commit ,push.
</p>
<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 25-Feb-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
<h3 align='center'> Basic setup of Education domain</h3>

<p align="justify"> </p>
 Today I have done the basic setup of education.First I created Student, Student group etc.
The Student document will hold all the data of any Student in your Academy like their Personal Information, Photo, Date of Birth, Address, etc.
This form will also contain any additional details like the Student's Guardian and Sibling details.
A student group is a collection of students from the same batch or taking the same course.


<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 26-Feb-2022**

<!----------------------------------------------------------------------------------------------------------------------------->

<h3 align='center'>Basic setup of Education Student Module </h3>

<p align="justify"> I am understanding the concept of Student module.I created Student category ,Academic year, Academic Term  etc.
</p>
<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 28-Feb-2022**

<!----------------------------------------------------------------------------------------------------------------------------->

<h3 align='center'> Setup of Education Domain  </h3>
Today I am trying to understand how i can assign courses, programs, enroll
students in programs and how to alot instructors to the students
according to a school and done it on my local.
<p align="justify"> </p>

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 01-March-2022**

<!----------------------------------------------------------------------------------------------------------------------------->

<h3 align='center'> Course Sceduling Module</h3>
<p align="justify"> Today I implementing the course Schedule on my local. Using this, a Time table can be created in the Institute, where in each slot will be scheduled via Course schedule.We can mark attendance for a Student Group against a Course Schedule.</p>

<!----------------------------------------------------------------------------------------------------------------------------->


**Date : 02-March-2022**

<!----------------------------------------------------------------------------------------------------------------------------->

<h3 align='center'> Support Module</h3>
<p align="justify">I am exploring Managing issue web form.
Issue can be created in two ways. One is through the web portal after logged in and issue is created in the backend. Another one is through emails on support address and issue is created in the backend.
  </p>

<!----------------------------------------------------------------------------------------------------------------------------->


**Date : 03-March-2022**
<!----------------------------------------------------------------------------------------------------------------------------->
<h3 align='center'> Support Module</h3>
<p align="justify">Today I have explored following terms:-
 Issues
An incoming query from a Student. It’s usually done via email or from your website’s Contact section. It’s good practice to maintain a separate email (e.g., support@yourbusiness.com) to keep track of incoming customer requests. This even enables your ERP system to pick up emails and automatically turn them into support tickets.

Issue Type
Classifying issues into different categories (e.g., technical, functional, hardware, etc.) lets you easily assign the right employee to the support ticket. Each category is called an issue type.

Issue Priority
You can assign different priority levels to every support ticket. A basic system is Low -> Medium -> High -> Critical. Setting priorities helps the maintenance/support employees to tackle tickets in the right order. It also affects the Service Level Agreement (see below).

Service Level Agreement
A Service Level Agreement (or SLA) is a contract between the service provider (either internal or external) and the customer who has raised the support ticket. It is used to define the timeline in which the customer will receive the service, not how the service itself is delivered or provided. This timeline can vary depending on the priority level of the issue.
  </p>

<!----------------------------------------------------------------------------------------------------------------------------->


**Date : 04-March-2022**

<!----------------------------------------------------------------------------------------------------------------------------->

<h3 align='center'> Workflow for Issue </h3>
<p align="justify">Today I am reading about workflow of Issue.
Whenever a student sends a message to support email address or using their contact page, the system automatically creates a support ticket.
The support ticket is evaluated by the team and assigned a priority, based on which the SLA is sent out to the customer.
Depending on the issue type, the appropriate employee takes on the issue and does what they can to help resolve it.</p>

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 05-March-2022**

<!----------------------------------------------------------------------------------------------------------------------------->

<h3 align='center'> Meeting app</h3>
<p align="justify">Today vishal and pawan gave us a presentation of meeting app. They showed us how to create custom apps in erp and how to install it onto the site. And they also showed us the code of the app and structure and files of the meeting app. Working on instructure section of education module . </p>

<!----------------------------------------------------------------------------------------------------------------------------->


**Date : 07-March-2022**

<!----------------------------------------------------------------------------------------------------------------------------->

<h3 align='center'> Notice Board App</h3>
<p align="justify">Today we all created a notice board app within 30 minutes. It was a wonderful experience as we can created such apps within a short time period.We have created a notice board module. Then we have created a doctype named Notice board with some required
fields like title, content, date, signature, attachments. </p>

<!----------------------------------------------------------------------------------------------------------------------------->


**Date : 08-March-2022**

<!----------------------------------------------------------------------------------------------------------------------------->

<h3 align='center'> Assesement Module</h3>
<p align="justify">Today I implemented the assessment module in gne11.gndec.ac.in.
First I have created  Assessment Creteria . For example, if the assessment was conducted for english or other subject, then we can evaluate Student in English on various criteria like Writing, internal assessment(viva), Attendence etc.Assessment criteria can be used while scheduling assessment plan for
student group and course.
Then next , I have created Assessment group tree (hierarchy for examination conducted in school) for one batch i.e 2021-2022 . 
**Assessment plan**

Next I created Assessment plan which is schedule to conduct the examination/assessment of a particular course for a group of students in an on-going academic term. For creating Assessment plan the prerequisites is grading scale so, we need to create grading scale for it.

 </p>

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 09-March-2022**

<!----------------------------------------------------------------------------------------------------------------------------->

<h3 align='center'> Attendance module </h3>
<p align="justify">Today, I studied about how to mark attendance. There are two methods to mark attendance:- using Student attendance and Student Attendance tool. For marking attendance of single student we can use student attendance and for bulk entries, we can use student attendance tool.
 </p>

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 10-March-2022**

<!----------------------------------------------------------------------------------------------------------------------------->

<h3 align='center'>Web Form  </h3>
<p align="justify"> Today I have explored that There are two types of in-built interfaces . The Desk View and the Web View. Desk is for users who regularly interact , like employees of your organization.

Web View is for users who need to interact with an instance occasionally. Web forms are similar to the forms you generally fill in various websites on the internet. Webforms are part of the Web View interface.</p>

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 11-March-2022**

<!----------------------------------------------------------------------------------------------------------------------------->

<h3 align='center'> Web Form</h3>
<p align="justify">Today I am exploring that Frappe provides an easy way to generate forms for your website with very little configuration. These forms may be public (anyone can fill them up) or can be configured to require login.

  </p>

<!----------------------------------------------------------------------------------------------------------------------------->


**Date : 12-March-2022**

<!----------------------------------------------------------------------------------------------------------------------------->

<h3 align='center'>Setup of Assessment Module </h3>
<p align="justify">Today I have done the setup of Assessment module.I have created grading scale and assessment result as following:

Grading Scale

Grading scale define the threshold for the different grades obtained by the students, based on their scores in the assessment. For example , I have created grading scale of Students obtaining a score of 100%  would be graded as O, students obtaining a score of 80% and below would be graded A- and so on.
After creating Assessment plan for course 'English-4/A/MST -1'. Then  there is Assessment Result.

Assessment Result

Assessment Result is log of marks/grades earned by the student for
specific Assessment. Basically we can use Assessment Result Tool for
creating log of marks of multiple students at the same time . It is
based on Assessment plan.
</p>

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 14-March-2022**

<!----------------------------------------------------------------------------------------------------------------------------->

<h3 align='center'>Result creation of students</h3>
<p align="justify"> Today I am testing the assesment module, where the result of all the students in coursewise.For that first i have to create assessment plan for each course.Then get the reult of that particular assessment plan. </p>

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 15-March-2022**

<!----------------------------------------------------------------------------------------------------------------------------->

<h3 align='center'> Report Generation of student</h3>
<p align="justify"> In the education module Today I was trying to generate report card for students while creating report card I am able to show the courses and exams but not able to show the marks of students in the report card.I have assigned the marks to the particular students.</p>

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 16-March-2022**

<h3 align='center'> Workflow and Basic Setup Nankana Sahib Public School</h3>
<p align="justify">Today we all have done the basic setup again for Nankana Sahib Public School for Class 1 to Class 8 and imported students, instructors and enrolled them in programs, courses and assigned instructors to the programs. As it was very difficult for all of us to understand because there were many same enteries of two companies one of Nankana Sahib Public School and another of Guru Nanak Dev Engineering College and there were many enteries that we all have entered for testing purpose. So today we all deleted all the previous enteries to do the setup from scratch. It was very helpful for all of us as there were some doubts of us related to program enrollment , course enrollment and student group.</p>

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 17-March-2022**

<h3 align='center'> Course Scheduling </h3>
<p align="justify">Today we all have implemented course scheduling via course scheduling tool , assessment plan, attendance by using attendance tool, we were also exploring the student leave application but the problem is if we have added an application for leave and also approved it but after approving if an instructor is trying to add attendance of whole class via attendence tool then it marking everyone present including students with leave application. Today we all have explored learning management system "https://gne11.gndec.ac.in/lms" which is basically student interface. 
  
 <!----------------------------------------------------------------------------------------------------------------------------->
 

**Date : 18-March-2022**

<h3 align='center'>Gunicorn, Socket.io, Scaffhold</h3>
<p align="justify">Today we got to know three new terms that are used in frappe first is Gunicorn:-Gunicorn is built so many different web servers can interact with it. It also does not really care what you used to build your web application - as long as it can be interacted with using the WSGI interface.Gunicorn takes care of everything which happens in-between the web server and your web application.

Socket.io:-Socket.IO is a library that enables low-latency, bidirectional and event-based communication between a client and a server. It is built on top of the WebSocket protocol and provides additional guarantees like fallback to HTTP long-polling or automatic reconnection.

Scaffhold:-Scaffolding is a meta-programming method of building database-backed software applications. It is a technique supported by some model-view-controller frameworks, in which the programmer may write a specification that describes how the application database may be used. The compiler uses this specification to generate code that the application can use to create, read, update and delete database entries, effectively treating the template as a "scaffold" on which to build a more powerful application.</p>

<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 19-March-2022**

<!----------------------------------------------------------------------------------------------------------------------------->

<h3 align='center'>Creating workflow for Student Admission</h3>
<p align="justify">Today we were trying to create a workflow for student applicant as per the structure given by satinder sir . For that we created a user named admission checker and set permission for the user.

After that we have created states and transition rules in workflow it is working properly now we are trying to add fee section in student applicant list<p>

<!----------------------------------------------------------------------------------------------------------------------------->
          
**Date : 21-March-2022**
          
<!----------------------------------------------------------------------------------------------------------------------------->
          
 <h3 align='center'>Exploration of Account Settings</h3>
<p align="justify"> I have to explore Account Settings of company like Default Bank
Account, Default Cash Account, Default Receivable Account etc. 
 </p>
          
 <!----------------------------------------------------------------------------------------------------------------------------->
              
  **Date : 22-March-2022**
          
<!----------------------------------------------------------------------------------------------------------------------------->
          
 <h3 align='center'>Reading the excellent reports by seniors</h3>
<p align="justify">Today I was reading the three report that was written by our seniors. The report is based on the language translator in which a group is trying to understand the role of lex and parser. It was  quite interesting to read . This report hooked me till the end to read. I learned if we combine technical terms  with real life things we will remember the things and learn more.
 </p>
          
 <!----------------------------------------------------------------------------------------------------------------------------->
              
                  
 **Date : 23-March-2022** 
                  
<!----------------------------------------------------------------------------------------------------------------------------->
                  
 <h3 align='center'>Imported users from .csv file</h3>
 <p align="justify">Today I am working on employee or instructor data. First
I sorted all the data according to the need in a separate file. After
that we created another file to import the users with username and
password. We also tested the user login credentials with the password
that i give to them in the file and we are able to login with that id
password.</p>  
                   
<!----------------------------------------------------------------------------------------------------------------------------->

**Date : 24-March-2022**

<!----------------------------------------------------------------------------------------------------------------------------->

<h3 align='center'> Imported Employees from .csv file</h3>
<p align="justify"> Today I imported all the employees with another file
using data import tool. For this we needed the user id of all the
users so we exported all the user id's of user and added in the
employees file. </p>

<!----------------------------------------------------------------------------------------------------------------------------->
                  
**Date : 25-March-2022**

<!----------------------------------------------------------------------------------------------------------------------------->

<h3 align='center'>Editing of Instructor file from given csv file</h3>
<p align="justify"> 

Today I edited the file of instructors. In the original data of instructor, the courses and groups were in
different format so I edited all the data in the file as per courses
and instructor doctype requirements.
  </p>

<!----------------------------------------------------------------------------------------------------------------------------->
                  
**Date : 26-March-2022**

<!----------------------------------------------------------------------------------------------------------------------------->

<h3 align='center'>Imported Instructor from instructor file</h3>
<p align="justify"> Today I imported all the instructor with another file
using data import tool. For this we needed the employee id of all the
employee so we exported all the employee id's of user and added in the
employees file.  </p>

<!----------------------------------------------------------------------------------------------------------------------------->
                  
**Date : 28-March-2022**

<!----------------------------------------------------------------------------------------------------------------------------->

<h3 align='center'> Enrolment of instructor into courses instructor log</h3>
<p align="justify"> Today I am arranging the file of instructor . where in instructor log I gave the courses of respective instructor. </p>

<!----------------------------------------------------------------------------------------------------------------------------->
                  
**Date : 29-March-2022**

<!----------------------------------------------------------------------------------------------------------------------------->

<h3 align='center'>Import Instructor in NSPS</h3>
<p align="justify"> Successfully imported user, employee and instructor in NSPS. First I have created User, Employee. I edited the file of instructors. In the original data of instructor which was provided to us , the courses and groups were in
different format so I edited all the data in the file as per courses and instructor doctype requirements.  </p>

<!----------------------------------------------------------------------------------------------------------------------------->
                                  
**Date : 30-March-2022**

<!----------------------------------------------------------------------------------------------------------------------------->

<h3 align='center'>Students Vs Instructor Enrolment</h3>
<p align="justify">It has been found after adding instructors and students to the program
and course, that only those courses are visible to the students, in
which the enrollment has been done. But in the case of Instructors all
the courses are visible, and he/she is able to create/delete content
in all the courses/programs. We need to find the permissions of both
the users, and need to find a way to make the instructor update only
those courses to whom he/she may belong.
                  
<!----------------------------------------------------------------------------------------------------------------------------->
                  
**Date : 31-March-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
                  
   <h3 align='center'>Students Vs Instructor Enrolment</h3>
<p align="justify"> We were finding the solution for the task that instructor can only see
their own assigned programs and courses . We can do it by the user
permission list in which we can assign them a specific program. But it
is only applicable in desk. After this instructor is able to see his
own assigned programs in desk but on the lms all the programs are
visible to the instructor. </p>

<!----------------------------------------------------------------------------------------------------------------------------->
                  
 **Date : 1-April-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
                  
   <h3 align='center'>Permissions to instructor</h3>
<p align="justify"> Today I have given the permissions to Instructor so that Instructor can only see their own assigned programs and courses.After this Instructor is able to to see own assigned course . I have Check all the permissions for instructor by which he can access courses.  </p>

                  
<!---------------------------------------------------------------------------------------------------------------------------->
**Date : 2-April-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
                  
 <h3 align='center'>Students Vs Instructor Enrolment</h3>
<p align="justify"> We were finding the solution for the task that instructor can only see
their own assigned programs and courses . We can do it by the user
permission list in which we can assign them a specific program. But it
is only applicable in desk. After this instructor is able to see his
own assigned programs in desk but on the lms all the programs are
visible to the instructor. </p>

<!----------------------------------------------------------------------------------------------------------------------------->

 **Date : 4-April-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
                  
 <h3 align='center'>User Permissions</h3>
<p align="justify">After applying the user permission to the instructor for programs and courses instructor is able to see there current programs only. When instructor is trying to access the courses they are able to access it. But when they are trying to access the programs they are getting error/ Notification:- "Not allowed for Course: Math-6 in Row 2. Restricted field: courseUser "abc@gmail.com" (instructor) does not have access to this document

Insufficient Permission for Program Class-6" Now I am trying to understand how to resolve it. Because this error means that to give access to the instructor first we need to to give access of all the courses to the instructor even if they are not teaching all the courses which is unacceptable in technical terms. </p>

                  
<!---------------------------------------------------------------------------------------------------------------------------->

**Date : 5-April-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
                  
<h3 align='center'>Attendence Module </h3>
<p align="justify"> Today I am exploring that how a instructor can mark attendence of any student group. In the Student Attendance Tool, we can mark attendance based on
Student Group and Course Schedule.
In Course Schedule, we should first schedule the course with
instructor, room and time. After setup the course schedule, we can
mark attendance of all students that belongs to this course.</p>

                  
<!---------------------------------------------------------------------------------------------------------------------------->
**Date : 6-April-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
<h3 align='center'>Mark Attendence of student by different methods</h3>
<p align="justify">Today i have explored mark attendance based on Student Group, then further there are
three options i.e. Group based on: Batch, Course and Activity.

Based on Batch: We can mark attendance of all students of a group
based on batch that is section A or section B.
Based on Course: Here, we can mark attendance of all students of the
group i.e. based on course.
Based on Activity: Here, we can mark attendance based on the Activity group. </p>
        
                  
<!---------------------------------------------------------------------------------------------------------------------------->
                  
**Date : 7-April-2022**
                  
<h3 align='center'>Course schedule</h3>
<p align="justify">Today I have implemented course scheduling via course scheduling tool , assessment plan, attendance by using attendance tool, we were also exploring the student leave application but the problem is if we have added an application for leave and also approved it but after approving if an instructor is trying to add attendance of whole class via attendence tool then it marking everyone present including students with leave application. Today we all have explored learning management system  "https://gne11.gndec.ac.in/lms" which is basically student interface. </p>

 <!----------------------------------------------------------------------------------------------------------------------------->
 
 **Date : 8-April-2022**
3
<!----------------------------------------------------------------------------------------------------------------------------->
 
<h3 align='center'>Reading the files of LMS
</h3>
<p align="justify"> As by using user permissions still instructor was able to see all the programs and courses. To find the solution for this we are trying to understand the structure of lms for this i was reading all the files of lms present  in the programs and course file it is metioned that by default instructor has access to all the programs and courses.

  </p>                                                             
                  
<!---------------------------------------------------------------------------------------------------------------------------->
                 
 **Date : 9-April-2022**
 
<!----------------------------------------------------------------------------------------------------------------------------->

<h3 align='center'>Exploring LMS</h3>
<p align="justify">Today we all have explored learning management system  "https://gne11.gndec.ac.in/lms" which is basically student interface. Here we checked that we can only show the programs to the student.In which quiz , article, video content is show.</p>
<!---------------------------------------------------------------------------------------------------------------------------->

                  
**Date : 11-April-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
 
<h3 align='center'>Support Module on gne11</h3>
<p align="justify"> Today I am trying support module. Issue comes under support module.We can track incoming queries from your email using Support Tickets. You can keep track of Customer Issues linked with a specific Serial No and respond to them based on information. You can also make Maintenance Schedules for Serial NOs and keep a record of all Maintenance Visits made to your Customers.  </p>                                                             
                  
<!---------------------------------------------------------------------------------------------------------------------------->
**Date : 12-April-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
 
<h3 align='center'>Support Module</h3>
<p align="justify"> Today I create service level aggrement on gne11. A service level agreement (SLA) is a contract between a service provider (either internal or external) and the end user on the level of service expected from the service provider.

SLAs are output-based, their purpose is specifically to define the timeline in which the Customer will receive the service. SLAs do not define how the service itself is provided or delivered. </p>                                                             
                  
<!---------------------------------------------------------------------------------------------------------------------------->
**Date : 13-April-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
 
<h3 align='center'>Issue/query</h3>
<p align="justify"> An issue is an incoming query from a customer. It’s usually done via email or from website’s Contact section. It’s good practice to maintain a separate email (e.g.support@yourbusiness.com) to keep track of incoming requests. This even enables your ERP system to pick up emails and automatically turn them into support tickets.  </p>                                                             
                  
<!---------------------------------------------------------------------------------------------------------------------------->
            
**Date : 15-April-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
 
<h3 align='center'>Student Portal
</h3>
<p align="justify">Today I explored The portal is hosted on the /lms route. Here all the programs are shown in the form of cards. Each card is clickable and navigates to the corresponding program/course/topic/content. The portal is accessible even if a student has not logged in, however, the content (Articles, Videos, etc) can only be accessible after login and enrolling in the program.  </p>                                                             
                  
<!---------------------------------------------------------------------------------------------------------------------------->


                  
**Date : 16-April-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
                  
<h3 align='center'>Presentation of Nankana Sahib Public School Project
</h3>
<p align="justify"> Today we had a meeting with Satinder Sir and a teacher from Nankana Sahib Public School. In today's meetings we all presented what we have done till now. We showed them the whole workflow to add a student. For which first we need to add a student applicant and explained that there are two methods for this one is online by using web form and another is offline after the application is accepted we can enroll them in the programs by single-2 enrollment of every student and by using the program enrollment tool and we showed them the lms interface of student how student is going to access the programs and courses and quizzes.After student section we showed them the whole working of instructor how instructor can add content like articles, videos and quizzes in lms, mark the attendance of students etc. After Instructor we presented the HR module how to generate payrolls, salary slips, attendance of employees etc.</p>

                  
<!---------------------------------------------------------------------------------------------------------------------------->
                  
**Date : 18-April-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
 
<h3 align='center'>Helpdesk</h3>
<p align="justify">Today I tried to impliment helpdesk on gne11. where first I have created issue type. Issue Type:- An Issue can be classified using Issue Type. Examples of Issue Types are: 'Functional', 'Technical', 'Hardware', etc.
 In case of school the issue is related to Fee, Examination,  Updation in Id card etc.


Assignment rule: In this assignment can be done manually or auto role assignment. There we have to define Assignment condition.
You can also set up multiple auto assignments for each Document Type, the one with the highest Priority will be applied first.
                  
  </p>                                                             
                  
<!---------------------------------------------------------------------------------------------------------------------------->
**Date : 19-April-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
 
<h3 align='center'>Demonstration of Helpdesk</h3>
<p align="justify">Today first I have created assignment rule for issue. In this I assigned a specific issue to a person. But it is not assigned By auto role assignment :( . I am finding where it goes wrong. I have created two roles Mentor and HOD and give them required permissions.
Then I have created a workflow for issue. I defined the states like Open, Approved by Mentor, Closed etc and create transition rules for it and check the workflow with different roles like one student create issue then it goes to mentor, mentor can approve or reject that issue, then it will go to HOD,Till now it is working fine. </p>                                                             
                  
<!---------------------------------------------------------------------------------------------------------------------------->

**Date : 20-April-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
 
<h3 align='center'>Understanding the concept of workflow</h3>
<p align="justify">Today I am understanding the concept of Workflow. With workflows we can rewrite how a particular process/workflow is approved.Once a Workflow is created, you can take actions on it via Workflow Actions.

Workflow Actions is a single place to manage all the pending actions you can take on Workflows.
Workflow Actions will send email notifications only if the 'Send Email Alert' checkbox is ticked in the Workflow that you've created.

</p>                                                             
                  
<!---------------------------------------------------------------------------------------------------------------------------->
                  
**Date : 21-April-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
 
<h3 align='center'>Assignment Rule</h3>
<p align="justify">Today I am exploring Assignment rule. I am exploring that how we can use assignment rule in helpdesk.For assign the issue automatically amongst the employees who work on support, an Assignment Rule can be used.
 We can define the Assignment rule Select the condition for the assignment. We can write simple Python expressions for automatic assignment in the Assign Rule, Close Rule and Unassign Rule. We will have access to all the properties of the document and can use operators like >, <, ==, etc and also multiple conditions like and and or.
 
status == "Open"
issue_type == "Technical" and priority=="High" and status == "Open"</p>                                                             
                  
<!---------------------------------------------------------------------------------------------------------------------------->
                                                      
**Date : 22-April-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
 
<h3 align='center'>Stuck in Permissions</h3>
<p align="justify">
Today I was stuck in permissions. Some issues/query were visible and some were not.

I checked all permissions for users. After struggle of 2 hours I got to know that issue/query was created in Nankana sahib education trust company i.e. our parent company and I was user of child company so issues/query were not visible.

Then I tried by assigning company permissions to users, like I gave parent and child company to users and create issues/query with that.

Finally I conclude that when a user (who have not assigned any company) creates an issue then by default issue will go in parent company and if we assign any company to user then it will visible to user of that particular company.
</p>                                                             
                  
<!---------------------------------------------------------------------------------------------------------------------------->


**Date : 23-April-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
 
<h3 align='center'>Email Setup</h3>
<p align="justify">Today I am setup the Email on my local .An email domain is the name of the network/service you're using for your email account.
We can skip to Email Account creation if you are using one of the services listed here. We can configure our Email Domain for easy setup of all Email Accounts. </p>                                                             
                  
<!---------------------------------------------------------------------------------------------------------------------------->


**Date : 25-April-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
 
<h3 align='center'>Workflow for helpdesk</h3>
<p align="justify">Today First I have created workflow for issue/query. When I was implementing workflow on my local my laptop got stuck in between.

Then I start it on gne11.gndec.ac.in.I have define the states and actions in workflow </p>                                                             
                  
<!---------------------------------------------------------------------------------------------------------------------------->
**Date : 26-April-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
 
<h3 align='center'>Demonstrate the Helpdesk Workflow</h3>
<p align="justify">Today I am giving permission to all the users according to the workflow.First I have created two role Mentor and HOD.After that I have given the permission according to workflow. Check the workflow with different roles like one student create issue then it goes to mentor, mentor can approve or reject that issue, then it will go to HOD,Till now it is working fine.</p>                                                             
                  
<!---------------------------------------------------------------------------------------------------------------------------->


**Date : 28-April-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
 
<h3 align='center'>Presentation of souvenir </h3>
<p align="justify">Today My mates gave presentation to all juniors. They showed us all the requirements, specification and overall workflow of the project and what is the required output.</p>                                                             
                  
<!---------------------------------------------------------------------------------------------------------------------------->
              
 **Date : 29-April-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
 
<h3 align='center'>Comparing Workflow of Student applicant and Issue</h3>
<p align="justify">Today I am comparing the workflow of Student applicant and Issue. And Finding that we can use multiple Workflow for the system.</p>                                                             
                  
<!---------------------------------------------------------------------------------------------------------------------------->
                  
**Date : 30-April-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
 
<h3 align='center'>Hierarchy of NSET (Nankana Sahib Education Trust)
</h3>
<p align="justify">Today we have discussed the hierarchy and structure of Nanakana sahib
education trust, gndec, nsps.

Basic Structure:- First we have a parent company Nankana sahib
education trust and under these we have child companies Guru nanak dev
engineering college, Nankana sahib public school (21 branches), Guru
nanak dev polytechnic college, ITI.

Accounts Structure:- First we have a parent company NSET and it has a
bank account which will take care of all the accounts of child
companies. Under the parent company we have a child company gndec
which also has a fee account and a salary account all the tuition fee
of students will directly go to the fee bank account , and all the
amount of fee bank account will be transferred to the salary account
and all the employees will get their salaries from the salary account.
All the development fee will be directly transferred to the
development account. For the development company will get the
amount/fund from  the development account.
Roles  in NSET:- In the nankana sahib education trust we have
president , director, managerial staff and under the president we have
sub roles for other users, secretary, and trustees. and under the
managerial staff we have clerks and accountant. Only the received
amounts and all benefits should be visible to the instructor. Only the
accounts part should be visible to the director.Clerk is responsible
for all the inventories stocks. Clerk2 will be responsible for the
hostlers fee.And they should be able to see only their assigned
company details.

NSET:-
In NSET company we have a director role which should have access to
all the child companies. All the child companies GNDEC, NSPS have a
principal.After that other staff is divided into two sections one is
Non-teaching and other is teaching.Under the non-teaching staff we
have clerks, accountants, assistants and other staff. Teaching section
is further divided into Examination, student section(admissions etc),
Establishment, Department. The examination staff will take care of
examinations of companies, the student section will take care of the
students admissions,fees etc.In the departments we have the role of
HOD, section incharge, staff.</p>                                                             
                  
<!---------------------------------------------------------------------------------------------------------------------------->

                
**Date : 2-May-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
 
<h3 align='center'>Hackathon Day 1</h3>
<p align="justify">Roles for Nankana Sahib Education trust :-

Director:- Director will have all permissions like fees, salary,
accounts , total gain etc but with read only access.
Accountant:- will have permissions to see all the account information
of trust, nsps, gndec.     Accountant will have read, write access to
create the fee and salaries of the employee and also can create the
fee report and salary report.
HR:- HR will have permission to create the users and make them
employees, leave allocation, holiday list, salary of employee.
Superintendent

Roles and flow for Nankana Sahib Public School:-

Principal:- Will have only read only access to all the education
domain related information and HR related information.

 Accountants:- 1 For students fee and 1 for salaries of employees.
Teaching Incharge:-  Will do all the tasks of academic user like
course scheduling etc.

HR:- will create employees and instructors only for Nankana sahib
Public School, leave allocation, salary of employees etc. We need to
show all the reports like employees attendance report, salary report,
leave report etc to the HR..

Instructors:- will have access to student attendance, quiz, videos,
article, Diary, Student list etc.

Students:- will have access of only LMS and on lms they will have
access of programs, Courses, Quizzes, Videos, Articles, daily diary
and attendance.

Accountant:- will create the salaries of employees and fees of
students, will generate the balance sheet.

We need to generate all the reports and graphs for necessary
information for each role.
</p>                                                             
                  
<!---------------------------------------------------------------------------------------------------------------------------->
                  
**Date : 3-MAy-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
 
<h3 align='center'>Hackathon Day 2</h3>
<p align="justify">   Today, We created Director user of NSET, Superintendent of NSET,
Principal user of NSPS and HR user of NSPS on erp server and gave them
all the required permissions. And same roles are created on gne11.GNE,
whose credentials are shared in other mail. You can check that roles
with given credentials. Also we learn about Salary Structure and
Salary Component of employees. In meeting with Harpreet sir, we learn
about PF, Taxes, Funds, Earnings and Deductions etc. We will explore
it and implement on gne11.GNE.
</p>                                                             
                  
<!---------------------------------------------------------------------------------------------------------------------------->

 **Date : 4-May-2022**

<!----------------------------------------------------------------------------------------------------------------------------->

<h3 align='center'>Notice Board App </h3>
<p align="justify">First we created an app named Gndec_NoticeBoard and installed it on
gne11.gndec.ac.in. Then we created a doctype named Gndec_NoticeBoard
with field names title,content,attachment, signature etc.
As we want that Clerk will create notice and HOD will approve, reject
or reassign it. So we created two roles: HOD and Clerk and gave them
required permissions for Notices.
Then we created a workflow named Notice for Gndec_NoticeBoard. Here we
define states like Draft, Approves, Pending etc. and Transition Rules
like first Clerk will create a notice, after approved by clerk it will
go to HOD then HOD will approve it or reassign it to Clerk. If HOD
reassigns it then it will go to Clerk in Draft state, here clerk can
edit it and resend it to HOD. If HOD wants to reject it, then first he
needs to click on Pending then he can reject it, after rejecting by
HOD it will go to the Clerk and the clerk can delete it.
Then we test the workflow with different roles and it is working nicely. </p>

<!----------------------------------------------------------------------------------------------------------------------------->
                  
 **Date : 5-May-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
 
<h3 align='center'>Creating Presentation in Revel.js</h3>
<p align="justify"> Created Presentation for the Whole Project To so that we can present our work to the trusties so with the team we created a presentation which contains all the infomation related to the erp Syatem which deals with the all kind of accounting, maintaing all students,staff and employees and pushed on github.  </p>                                                             
                  
<!---------------------------------------------------------------------------------------------------------------------------->



**Date : 6-May-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
 
<h3 align='center'> Course Scheduling on gne11</h3>
<p align="justify">In course scheduling, when we are scheduling courses to Instructors of
full year using a course scheduling tool, it shows all the entries of
the whole year in the course schedule list.
These entries will be in thousands.
Earlier when we were scheduling courses, we just scheduled two or
three courses of whole year, and server was not responding.

  </p>                                                             
                  
<!---------------------------------------------------------------------------------------------------------------------------->

**Date : 8-May-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
 
<h3 align='center'>Scheduling Time-Table </h3>
<p align="justify">Today I have tried scheduling Time-Table with some dummy Entries on
https://gne11.gndec.ac.in/. If we want to see the Time-table of a particular instructor, then it
is available in that instructor's profile and also we can see that
from course scheduling list just by entering the instructor's name.</p>                                                             
                  
<!---------------------------------------------------------------------------------------------------------------------------->


**Date : 9-May-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
 
<h3 align='center'> Scheduling Time Table</h3>
<p align="justify">We are creating it using course scheduling tool. In this, we need Room, Time, Day of lecture. And Time of lectures is not given in the TT of NSPS.
You may set your own time in this case, set time of lectures between 8 am to 2 pm.

And In NSPS, they mark attendance once in a day(In morning by incharge). And the use of doing course scheduling is to mark attendance in every lecture like in our college. So for school, there is no use of course scheduling.
</p>                                                             
                  
<!---------------------------------------------------------------------------------------------------------------------------->

**Date : 10-May-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
 
<h3 align='center'>Arranging Time Table file </h3>
<p align="justify"> Today, After exploring, we thought there is no use of writing script. We think script is useful where we have to do the same things
again and again.
But in our case, we will have different time-table for different
schools,  so in script we will have to give input for each TT which is
the same thing doing entries one by one. I think csv is more productive than script.  So Today I have arranged Time Table csv file.
  </p>                                                             
                  
<!---------------------------------------------------------------------------------------------------------------------------->
**Date : 11-May-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
 
<h3 align='center'>Asset Module</h3>
<p align="justify">  Today I am done with the course scheduling. Now I am exploring the
asset module as it was assigned to me the other day.
Asset: We can maintain fixed asset records for Company assets like computers, furniture, cars, etc. and manage their depreciations, sale. It is any valuable item owned by a company.
Asset category: Asset Category based on the type of assets. For example, all desktops and laptops can be part of an Asset Category named 'Electronic Equipments'.

Types of assets:
Assets can be an existing asset which has been bought earlier and it can be a newly purchased item.
For new assets, we cannot create the asset record directly from the Asset form. We need to create a Purchase Receipt/Invoice for it.
Before creating an asset we need to create an item with 'is fixed asset' and create a purchase receipt against that item.
 </p>                                                             
                  
<!---------------------------------------------------------------------------------------------------------------------------->
                  
**Date : 12-May-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
 
<h3 align='center'>Asset Module</h3>
<p align="justify">  Asset Reports:

Asset Depreciation Ledger
This report shows the Purchase Amount, Depreciated Amount and
accumulated total depreciation for all the assets under the selected
date range. It also shows the current value and current depreciation
status of the Asset.

Fixed Asset Register
Fixed asset register provides a unified view of all the details
regarding current status of an asset. A Fixed asset register tracks
all the fixed assets that the you have created. This not only includes
assets that are currently in your possession, but also tracks those
assets that are disposed. </p>                                                             
                  
<!---------------------------------------------------------------------------------------------------------------------------->
**Date : 13-May-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
 
<h3 align='center'>Stock and Asset module </h3>
<p align="justify">Stock, Buying and Accounting modules are inter linked with
each other.
It is so complex. We are trying to understand terms like General
Ledger, Journal Entry, Purchase Receipt, Depreciation Ledger, Fixed
Asset Register etc.
Till now, we don't know which type of data is required. Sir we are
working on it.
</p>                                                             
                  
<!---------------------------------------------------------------------------------------------------------------------------->

**Date : 14-May-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
 
<h3 align='center'>Stock module</h3>
<p align="justify"> Today, we have created Item Groups, Items, Warehouses, Suppliers etc.

Item Group:
Create parent and child item groups for different categories of items.

Item:
Create items from Stock > Item. If we want to maintain the stock for
particular item then we have to enable "Maintain Stock" option while
creating Item. After creating item with "Maintain Stock" field
checked, the Stock Entry, Stock Ledger, Accounting Ledger will created
automatically.

Warehouse:
If "Perpetual Inventory" option enabled in warehouse, then accounting
entry is automatically done for every stock transaction.
If "Perpetual Inventory" disabled, user will have to manage the
account entries manually.

Supplier:
Create Supplier and add contact and email of supplier. We can make
User of this Supplier also. With this, Supplier will not have access
to desk, he can create Supplier Quotation etc from website only.

We have checked this by creating entries on gne11.gndec.ac.in
  </p>                                                             
                  
<!---------------------------------------------------------------------------------------------------------------------------->


**Date : 16-May-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
 
<h3 align='center'>Stock  Module</h3>
<p align="justify"> Today , We add item in the warehouse, we have to create stock. We have
following two ways to create stock;

If item is non serialized/non batched then we have to add entry in
Stock Reconciliation. If item is serialized and Serial Number Series
is defined for particular item, then also we can add entry here.
If item is serialized/batched then add entry in Stock Entry with Entry
Type "Material Receipt". Here we have to define serial number or batch
number of items.

After adding entry in Stock Reconciliation or Stock Entry, the item
with specified quantity will be added in stock. We can check it in
Stock Ledger Report.
  </p>                                                             
                  
<!---------------------------------------------------------------------------------------------------------------------------->



**Date : 17-May-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
 
<h3 align='center'>Buying  Module</h3>
<p align="justify"> Today, we have to create a "Material Request" with the
purpose "Purchase". Here we have to set the quantity of required items
and warehouse for which they are required.

We can create it manually or through re-order item in items i.e. If
item quantity goes below the re-order level of item then material
request will be created automatically.  </p>                                                             
                  
<!---------------------------------------------------------------------------------------------------------------------------->



**Date : 18-May-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
 
<h3 align='center'>Buying Module</h3>
<p align="justify">After creating Material Request, we can create "Request For Quotation"
from Material Request.
In this we can send the request to multiple suppliers for multiple
items. An email will be sent to the supplier with the "Supplier
Quotation" link. From this link, Suppliers can submit their
quotations. Then these quotations will be visible to us in the
"Supplier Quotation" list. It will be in draft state, we have to
submit it.   </p>                                                             
                  
<!---------------------------------------------------------------------------------------------------------------------------->



**Date : 19-May-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
 
<h3 align='center'>Buying  Module</h3>
<p align="justify"> From "Supplier Quotation", we have to create "Purchase Order" (A
Purchase Order is a binding contract with your Supplier that you
promise to buy a set of items under given conditions).
We can create "Purchase Receipt" after "Purchase Order". After
creation of Purchase Receipt, Items will be added in our warehouses.
We can check item's entry in Stock Ledger Report.  </p>                                                             
                  
<!---------------------------------------------------------------------------------------------------------------------------->



**Date : 20-May-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
 
<h3 align='center'>Buying  Module</h3>
<p align="justify"> We can create "Purchase Invoice" (
A Purchase Invoice is a bill you receive from your Suppliers against
which you need to make the payment) after "Purchase Receipt". Also we
can create it after "Purchase Order". In "Account Payable", we can
check Invoice Amount, Outstanding Amount, Paid amount etc.

After "Purchase Invoice" we can create "Payment". After paying,
Invoice status will be changed to "Paid" and also now this invoice
will not available in Account Payable Report.  </p>                                                             
                  
<!---------------------------------------------------------------------------------------------------------------------------->


 **Date : 21-May-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
 
<h3 align='center'>Asset Report
Inbox</h3>
<p align="justify">Today I explore reports of asset shows the Purchase Amount, Depreciated Amount and accumulated total depreciation for all the assets under the selected date range. It also shows the current value and current depreciation status of the Asset.


  </p>                                                             
                  
<!---------------------------------------------------------------------------------------------------------------------------->
**Date : 23-May-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
 
<h3 align='center'>Asset Category </h3>
<p align="justify">An Asset Category classifies different assets of a Company.

The first step towards asset management is creating an Asset Category based on the type of assets. For example, all your desktops and laptops can be part of an Asset Category named "Electronic Equipments".

In Asset Category, you can set default a depreciation method, periodicity and depreciation related accounts, which will apply to all the assets under the category.

 </p>                                                             
                  
<!---------------------------------------------------------------------------------------------------------------------------->


**Date : 24-May-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
 
<h3 align='center'> Asset Maintenance
</h3>
<p align="justify"> The Asset Maintenance Team is responsible for carrying out maintenance activities on the Asset.

The maintenance activities can be cleaning, polishing, servicing, or any other activity required to maintain the Asset in good condition.
 Go to the Asset Maintenance Team list, click on New.
Enter a name for the team.
Select a manager for the team.
In the Maintenance Team Members table, add the team members and select their maintenance roles.
Save.</p>                                                             
                  
<!---------------------------------------------------------------------------------------------------------------------------->
**Date : 25-May-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
 
<h3 align='center'>Asset Movement</h3>
<p align="justify">
Asset Movement refers to moving an Asset from one Location to another.

In ERPNext, you can track the location of an asset or to whom it is issued. For tracking, you need to create an Asset Movement transaction, whenever the asset is moved from one location to another. You can also keep a track of issuance of an asset to any employee.</p>                                                             
                  
<!---------------------------------------------------------------------------------------------------------------------------->
 
 **Date : 26-May-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
 
<h3 align='center'>Asset Maintenance Log</h3>
<p align="justify">Asset Maintenance Log logs the tasks carried out in an Asset Maintenance.

For each task in Asset Maintenance, Asset Maintenance Log is auto created to keep track of the upcoming maintenances. It will have a status, completion date and actions performed. Based on completion date here, next due date is calculated automatically and new Asset Maintenance Log is created.

</p>                                                             
                  
<!---------------------------------------------------------------------------------------------------------------------------->
**Date : 27-May-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
 Today I am finding  set up automatic assignment of documents to Users.

To assign the support tickets automatically amongst the employees who work on support, an Assignment Rule can be used.

</p>                                                             
                  
<!---------------------------------------------------------------------------------------------------------------------------->

**Date : 30-May-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
 
<h3 align='center'>Desk View</h3>
<p align="justify">We were trying by installing an app from this url
https://github.com/hashirluv/redtheme_v13b
With this colour of heading and navigation bar got changed.
  </p>                                                             
                  
<!---------------------------------------------------------------------------------------------------------------------------->
**Date : 31-May-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
 
<h3 align='center'>Desk View Inbox</h3>
<p>
- Sir assigned us (Me and Jaspreet) the task to beautify the desk view with bootstrap. So we are exploring about it.
- We found theme of desk. We install a theme from this url: https://github.com/hashirluv/r
- After installing this theme, colour of heading, navigation bar etc got changed.
- Then we tried some other themes also. We tried White Theme, Blue Theme etc.
- Then we understand the code and css files to change the view of desk. We can change only background colours, text colours, hover text colour etc with some changes in the css files.

  </p>                                                             
                  
<!---------------------------------------------------------------------------------------------------------------------------->
 
 **Date : 1-June-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
 
<h3 align='center'>Dashboard for erpGURU</h3>
<p>
- Now we (I and Jaspreet) have to create a new dashboard page according to the rquirement specified by sir.
- There should be links of Student, Program, Fee, Attendance etc. After clicking, it would ask for login
  </p>                                                             
                  
<!---------------------------------------------------------------------------------------------------------------------------->
 
  **Date : 2-June-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
 
<h3 align='center'>Dashboard for erpGURU</h3>
<p>
- Now we (I and Jaspreet) have to create a new dashboard page according to the rquirement specified by sir.
- There should be links of Student, Program, Fee, Attendance etc. After clicking, it would ask for login.
- So we explored about this and create a new webpage. (Go to Website > Webpage then create new webpage)
- Enter Title, Route etc. Select HTML in Content Type.
- Enter the following code in html:
  </p>                                                             
                  
<!---------------------------------------------------------------------------------------------------------------------------->
 **Date : 4-June-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
 
<h3 align='center'>Active and Deactive Students
</h3>
<p>
- We can check all active students and deactive students in the system.
- Deactive students are those who have not paid their fees after a particular date.
- We can check all active/deactive students from student list.
- Go to student list. Add a filter with “Enabled” equals “Yes” in the student list. Count of all active students will show there.
- To check Deactive students, change value of Enable to No. Then all deactive students will be visible.
- We can also check Gender wise Active or Deactive students by applying Gender equals Female or Male filter. </p>                                                             
                  
<!---------------------------------------------------------------------------------------------------------------------------->
 **Date : 6-June-2022**

<!----------------------------------------------------------------------------------------------------------------------------->
 
<h3 align='center'>Class and Section wise Active/Deactive Students
</h3>
<p>
- There is no Program field in the student doctype.
- So we have to customize the doctype and add a new field Program and link it to the Program DocType.
- After this, we can check count of active or deactive students class-wise and section-wise.
- For class-wise, add a filter of program for example Program like Class 8.
- For section-wise, add a filter of program. For example Program equals Class 8 A.

  </p>                                                             
                  
<!---------------------------------------------------------------------------------------------------------------------------->


                               
