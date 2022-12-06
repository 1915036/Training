# Training


# Day-1(12/07/2022)
 - ## *Installation of the Linux*
*Today I made a bootable **usb drive** by downloading the **linux ubuntu ISO** in that and runnind it in on my machine. with the help of this link https://ubuntu.com/download/desktop/thank-you?version=22.04&architecture=amd64 and download iso file, ubuntu desktop(20.04 LTS)*
 
 # Day-2(13/07/2022)
*the very next task was install the **Lamp** on the Linux ubuntu .*
*As we know the meaning of lamp is(LAMP = Linux + Apache + MySql + PHP)*
So firstly update and upgrade you system and the install, 
- Install the **Apache 2 webserver**.\
using cammand:
  ***sudo apt install apache2*** 
- then install, **Install the MySQL database server** \
using cammand:
**sudo apt install mysql-server** 
 - then install,**Install PHP** \
using cammand:
***sudo apt install php***\
and check the version of php with the cammand:**php -v** \

# Day-3(14/07/2022)

 ***install frappe***
install the frappe in ubuntu with the help of instruction in the link.
*https://github.com/D-codE-Hub/Guide-to-Install-Frappe-ERPNext-in-Ubuntu-22.04-LTS*

# Day-4(18/07/2022)
As the frappe was installed,the futher reading process about the usage of the framework and the LIBRARY MANAGEMENT SYSTEM was initialted and doctype were created.

# Day-7(20/07/2022)
Today i completed some steps of LIBRARY MANAGEMENT SYSTEM like- create a doctype,doctype feature,controllers method.
# Date:28 Aug 2022
Today Satinder sir assign a moodle task to my team(Jasjit,Komalpreet,Ranvir).The task was that we have to make a query in mysql to get the grade report of the user in moodle corresponding to their course.
# Dtae 29 Aug 2022
To complete the task (grade report),firstly i install local moodle on my system and it take some time.Then i start working on it and explore the feature of it ,because it was my first time to do something on moodle.
# Date 30 Aug 2022
As i mention that i, installed the moodle on my system last day what today when i start working on it it show the error like (403 Forbidden)
then  my friend Pranvir help me in this and tell me the solution tahat i have to stop the nginx.service and restart the  apache2.service.
and it really solve my problem,thanku pranvir for your help. So we start our work on moodle grade report.
# Date 31 Aug to 7 Sep 2022
In order to accomplished our task ,we need user(student) name,grade,id,couse name.So start exploring the moodle database to get the valuses from the moodle database tables.
1. mdl_grade_grades: In this table we get the id,rawgrademax,finalgrade.
2. mdl_user: In this table we get the firstname of user,last name of user,username.
3. mdl_course: In this we get id of course,fullname,shortname.
- After getting all values we disscus our mentor and set the final table ,so that we make our single final query.The final table that we have to make contain the feild of uasername,firstname,lastname,course name,id.
- We succesfilly make the query with the help of Satinder sir,and the last sir tell us to check the finaloutput that ,is it was actually meet our requirement.At that time taht was correct  but when we test it by adding more course then it does not give the update couse and update grade of user.
- Then we try to solve the problem and our other training friend help us to overcome the getting error.

# Daily-Work (1-09-22)

- Today @HS Rai sir give one task to me that we have to do some work on QT(Qt is cross-platform software for creating graphical user interfaces as well as cross-platform applications that run on various software and hardware platforms such as Linux, Windows). The first we have to learn about the QT how to use it and how it work. For this i install it in my system and start exploring about it.Then we install QT creator in which we write our program to create the GUI.Qt Creator creates several files for you. The HelloWorld.qmlproject file is the project file, where the relevant project configuration is stored. This file is managed by Qt Creator, so don’t edit it yourself. Another file, HelloWorld.qml, is our application code. Open it and try to understand what the application does before you read on.

# Daily-Work (2-09-22)

- In this period we learn about the QT and run a simple program (Hello) on it.
- Beside this i am also workinfg on to get the user data from database.The question was that how to fetch the data from two table in mysql database.Because we have to fetch the user name and corresponding courses which are stored in two different tables.

# Daily-Work (10-08-22)

- On this day sir give me new task of FET.FET(FET-6.7.5) is free software for automatically scheduling the timetable of a school, high-school or university. It uses a fast and efficient timetabling algorithm.

# Dailt-Work (11-8-2022)

- Today i am also working on FET and tried to generate the timetable using random data.

# Daily-Work (12-8-2022)

- Today I have successfully generate the time table and also shown to Rai sir but he told me that use `import` and `export` data commands and learn its documentation.

# Daily-Work (13-8-2022)

- Listening all the presenation given by other GD members.

# Daily-Work (15-8-2022)
Learing about `import` and `export` commands. Rai sir given me one google sheet which contains the real data of civil department and told me that generates its timetable.

# Daily-Work (16-8-2022)

- Today i have generated the civil department timetable then rai sir said me find that where all these files stored and where its source code is present.

# Daily-Work (17-8-2022)

- Learing about `import` and `export` commands. Rai sir given me one google sheet which contains the real data of civil department and told me that generates its timetable.
I have found that where source code is present and then rai sir said that also find now if once timetable is generated  after that we change some infomation in its csv files ,is it also reflect in generated timetable or not?
 
#Daily-Work (18-8-2022)

- Today i have started working on rai sir task but after done all testing i have reached that thers is not reflect of modify information in generated timetable and wanted to modify then generate the same timetable again.

# Dailt-Work (19-8-20222)

- Today was my task to enable the `Level-5` or `Level-7`. `Level-2` is by default set. 
`Level-7` is used to highlight the words. Till evening i have enables it successfully.

# Daily-Work (20-8-2022)

- Today's in morning Rai sir told me again now without using GUI of `FET` software generate the timetable. On the backend fet will run and takes the csv files (user will upload) and genearate the timetable in the backend and give the link of generated timetbale as a output.

# Daily-Work (22-8-2022)

- Today Satinder sir given me work of moodle.I have to created a Courses cateogries there using CSV files of NSPS.

# Daily-Work (23-8-2022)

- I have done one blunder mistake while creating the course categories which is told by satinder sir to me and said create the categories of courses again.

# Daily-Work (24-8-2022)

- I have created all the courses again and also putt the subjects in each category.This task took complete one day.

# Daily-Work (25-8-2022)

- Today Satinder sir given a task to me and jasjit to find the information from database regarding to the NSPS grade report. A grade report is contains the fields of `Name of course` , `Email address` , `Course grade` etc.

# Daily-Work (26-8-2022)

- Today we learnt first about the sql queries and watched one tutorial for it and explore about the general log file and error log file along what is the importance over all of these files. After wacthed the tutorial got some idea and executed some queries.

# Daily-Work (27-8-2022)

- Finally we took our first step towards the task. To complete the task (grade report),firstly i install local moodle on my system and it take some time.Then i started working on it and explore the feature of it ,because it was my first time to do something on moodle.

# Daily-Work (29-8-2022)

- In order to accomplished our task ,we need user(student) name,grade,id,couse name.So start exploring the moodle database to get the valuses from the moodle database tables.

mdl_grade_grades: In this table we get the id,rawgrademax,finalgrade.
mdl_user: In this table we get the firstname of user,last name of user,username.
mdl_course: In this we get id of course,fullname,shortname.

# Daily-Work (30-8-2022)

- Today we had a discussion with our mentor releted the values and we set the final table ,to make single final query. The final table that we have to make contain the feild of uasername,firstname,lastname,course name,id.

# Daily-Work (31-8-2022)

- We succesfilly make the query with the help of Satinder sir, and at last sir tell us to check the final output, is it was actually meet with our requirement. At that time it was correct but when we test it by adding more courses then it was not giving the update couse and update grade of user.

# Daily-Work (1-9-2022)

- Today i had a task to resolve the problem. For that i took help from my other training friends. We all start working on it and also finding the solution with diffrent diffrent approaches.

# Daily-Work (2-9-2022)

- Today i went to satinder sir to discuss the problem. Sir gave some idea about it we again start to working on it and applied several queries but didn't work anything till evening.

# Daily-Work (3-9-2022)

- On this day i try below query-

`SELECT u.firstname , u.lastname , u.email , u.username, c.fullname as course_name,  
ROUND(gg.finalgrade,2) Grade, concat(uo.url, c.id) as url FROM mdl_course AS
c JOIN  url_of_course AS uo JOIN mdl_context AS ctx ON c.id = ctx.instanceid 
JOIN mdl_role_assignments AS ra ON ra.contextid = ctx.id JOIN mdl_user 
AS u ON u.id = ra.userid JOIN mdl_grade_grades AS gg ON gg.userid = u.id JOIN 
mdl_grade_items AS gi ON gi.id = gg.itemid JOIN mdl_course_categories 
AS cc ON cc.id = c.category WHERE gi.courseid = c.id AND gi.itemtype = 'course';`

It executed successfully getting the final output which mathes with requirements.

# Daily-Work (4-9-2022)

- After this having a task to put the incremental backup so that automatically values will be fetched from the database and update on moodle (gradebook) respectively.

# Daily-Work (5-9-2022)

- Today i have a task to learnt about the incemental backup. For that i refers some tutorial from youtube and followed them. I learnt of its importance and significance.

# Daily-Work (6-9-22)

- Today @HS Rai sir give one task to me that we have to do some work on QT(Qt is cross-platform software for creating graphical user interfaces as well as cross-platform applications that run on various software and hardware platforms such as Linux, Windows). The first we have to learn about the QT how to use it and how it work. For this i install it in my system and start exploring about it.

# Daily-Work (7-9-22)

- Then we install QT creator in which we write our program to create the GUI.Qt Creator creates several files for you. The HelloWorld.qmlproject file is the project file, where the relevant project configuration is stored. This file is managed by Qt Creator, so don’t edit it yourself. Another file, HelloWorld.qml, is our application code. Open it and try to understand what the application does before you read on.


# Daily-Work ((8-10)-09-22)

- In this period we learn about the QT and run a simple program (Hello) on it.
- Beside this i am also workinfg on to get the user data from database.The question was that how to fetch the data from two table in mysql database.Because we have to fetch the user name and corresponding courses which are stored in two different tables.

# Daily-Work (14-9-22)

- Today We start a ndew Project named CMC( Construction & Maintenance Cell).First of all we need to understand the structure of CMC, The CMC will be a company under NSET, parallel to GNDEC. IMO it must be a service based company, what is your opinion, and other domains available.It will have sales, purchase, stock, accounting etc.So, It is a service based company.

# Daily-Work (15-9-22)

- Create a company at gne2 and set its domain to service. We will test over gne2.But We have a maintenance module.Here we can make others doctype related to maintenance.So, the Company Name : Construction & Maintenance Cell, Parent Company : NSET, Domain Name : Services

# Daily-Work (16-9-22)

- Create a dashboard for the maintenance request.
In which cmc user see the requests by date wise and see no. of requests per day.

# Daily-Work (17-9-22)

- In the web form, "justification for request"  field needs to be optional, not mandatory. And it needs to be "draft" upto the level of HoD, which means that HoD/OIc/Caretaker/Warden will be able to change it. No change will took place once the higher authority forwarded the request.

# Daily-Work (18-9-22)

- Today, I am working on Dashboard. Start learning about the Dashboard and make test dashboard.Becauses ,I have to make a Dadboard of all Higher Authorities like SDO,CMC -Head, HOd's of all Departments.

# Daily-Work (19-9-22)

- Today we are working on the workflow of CMC project. We made the flowchart of CMC Project.
- steps: student | employee -> HoD -> SDO -> O/Ic Incharge 
- But there migh be Student -> Caretaker -> Warden -> SDO or Lab Attendant | Lab Technician -> Lab Incharge -> HoD ... In case of rejected, all must see the status, and in case of any additional query it may be sent back from where is was forwarded.

# Daily-Work (20-9-22)

- Today i work with Satinderpal sir , sir said us to make a courses on guru.gndec.ac.in.So we make it on the site.

# Daily-Work (21-9-22)

- Solved the problem regarding the moodle like user are not enroll in the courses and their attebdance.

# Daily-Work (22-9-22)

- Beside the CMC project I also work on the NSPS project(School project).Firstly we visit the school and get the information about the courses or subject and teacher or student data of school.

# Daily-Work (23-9-22)

- According to the information we upload the courses and user in the gne1.gndec.ac.in which is official moodle site of School.

# Daily-Work ((24-29)-9-22)

- Working on gne1.gndec.ac.in and visit the school regulary.Solves the teachers problems, help them to access the gne1.gndec.ac.in and how to add the activity in it and turm the edit mode on to do some work.

# Daily-Work (30-9-22)

- Today we (I and Pranvir ) are going to implement stock items in
erp.gndec.ac.in and also creating a dashboard of SDE which is only
visible to SDE only.

# Daily-Work (1-10-22)

- We are going to add stock items to erp.gndec.ac.in and make a
dashboard for SDE which is only visible to SDE.

# Daily-Work (2-10-22)

- Today we have to fullfil the requirement that are pending that thses are disscussed with Rai sir.
- I changed the Nature of work according to the requirements.

# Daily-Work (3-10-22)

- Estimate work is done on erp.gndec.ac.in according to the requirements.

# Daily-Work (4-10-22)

- Me checked if we select items for estimate then it will also reduces in stock.
- Now our task is to create a button in the CMC request form for SDE
only in which SDE will manage the realtime stock items.

# Daily-Work (5-10-22)

- We have two options:
First:
We can add a custom button in the cmc request form using the form
script. The link which is following is:
https://frappeframework.com/docs/v13/user/en/api/form
 But here we have an issue of permissions. Because Custom button is
not a field in a doctype and in my knowledge we are only able to gives
permissions to doctype fields to show that fields to some specific
users so here we goes to our Second option

Second:
We can create a field which is of type "Button". I know this is a
silly question but how can we add links behind the Button type fields
in frappe??
I searched this on Google and found that we need to write custom
scripts to make this button working. But I didn't get the correct
syntax for this.

# Daily- Work (6-10-22)

- we checked that if we select items for estimate then it will also reduces in stock.So when our stock becomes completely empty then we need to send
quotations for required items. So now our next task is to send quotations and restore our stock again.

# Daily-Work ((7-12)-10-22)

- Today Task was to do a Company Setup. So we are going to do the company setup.The company we are going to create  is Manufacturing company.
- Our Company name is "Unique Number Ltd" under Domain "Manufacturing".
- Company (Unique Number Ltb) is successfully created on gne2. Now we are going to do our next step.
- Our next step is to define tax of a company under the section of chart of account.
- In the section of Chart and Account , we select our company and come under the source of funds section . Here we do some changes in the CGST and SGST according to requirements which come under the Duties and Taxes.
- We created incoming CGST and incoming SGST under Application of assets section in the chart of accounts for buying purposes and defined CGST and SGST under Source of funds section for selling purpose.
- We need to create a journal entry to show the amount in the chart of accounts. But when we make a general entry it shows the error which says set the fiscal year first.
- In this we firstly add the sales order which include the information
about the customer,item and delivery date.
- Sales Invoice done.Payment of this order is also done

# Daily-Work (13-10-22)

- Dashboard for principal is created on erp.gndec.ac.in
- After this we disscuss the project with sir and there many thing which are need to be add in the project like.

# Daily-Work (14-10-22)
 
 1) "new request" button in cmc request.
 7) item name in estimate automatically fetched.
 - these tasks have been completed.

# Daily-Work (15-10-22)

 2) sorting complaint number in my requests
 - Tasks is completed.

# Daily-Work (16-10-22)

- We (Me and Komalpreet) are going to make new departments which are
left and will also update the csv file accordingly and upload it in
erp.gndec.ac.in.

# Daily-Work (17-10-22)

- Employees also created successfully.On erp.gndec.ac.in
- Task was completed: Image size limit can change as we tested on gne2.gndec.ac.in.
It can be changed through the backend. To change the image size limit,
go to /sites and open "common_site_config.json".
change max_file_size: 500000.

# Daily-Work (18-10-22)

- Working on Home page.
1)  I add a nav bar.(About, Departments, Notice board, Faculties).

# Daily-Work (19-10-22)

- Working on Education Domain . 
- I work on education domain t done the project regarding the Student Enrollment.
- Firstly under stand the whole process and had meeting with sir.

# Daily-Work (20-10-22)

- Understand the Fee structure  in Edcation Domain.
- Student Enrollment Process.

# Daily-Work ((21-30)-10-22)

- Create ourses in the education domain.
- Create Fee structure (Fee component, Student Category, Program)
- Add student and instructor in the list.

# Daily-Work ( 1-11-22)

- Rai sir told us to replace the estimate by quotation.
- Our approach is that we are going to create a button named "quotation
estimate" which will be shown to the SDE. With the help of this
button, SDE will be able to handle quotations(estimate), sales order,
sales invoice(Bill).

# Daily- Work (2-11-22)

- We successfully created a quotation. Now we are going to create a
sales order of that quotations, in which we add our items which we
want. And here we also apply a Tax on items, discounts and on them.

# Daily-Work (3-11-22)

-  we can update the quotation values in the estimate table.For this sdo willlick on a button named "Quotation/Estimate" in the cmc requestform and redirect to the quotation form. And then the estimate table values will be autofetch from the quotation table.

# Daily-Work (4-11-22)

- We created 2 Doctypes named:
1) final testing
2) DemoQuotation2

We added the same child table "estimate duplicate" in both doctypes as
we mentioned above. But according to that we didn't get the results.

# Daily-Work (5-11-22)

- Make a new flowchart of CMC Estimate/Quotations according to
@Satinder sir idea .


