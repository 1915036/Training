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
