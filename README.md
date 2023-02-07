# school_management_by_django
 We will be using Django (python open-source framework) and Sqlite3 database to implement this project
 
 
Project Functionalities:
Add attendance
Add marks
Add notice
Check attendance
Check notice
Check marks

#School Management System Project Prerequisites -
To install the required libraries, please use pip installer from the terminal:

Steps to Create School Management Project in Python Django-----

1. Start Project
Django itself creates a project and an app with all the necessary files if we run the command

2. Writing Models
In this school management system project, we have created 3 models. In other words, we have created 3 tables to store the details of student’s attendance, marks, and the notice (if any) drafted by the school authorities.

3. forms.py
Django does not create this file, so we have to create this new file in the app folder and then you can type the following code in forms.py.

Forms.py is required to implement CRUD functionality i.e. for creating, retrieving, updating and deleting objects from the database. So we have created a form for each model we have defined.

4. admin.py
Django provides an inbuilt admin panel for online school management project (for every project). We have to register the models we have created on admin panel so that we can access the data from admin panel also. But for that we require a staff user, to create a superuser (admin) run the command

5. urls.py
We have defined the url patterns in this file.

6. views.py:
The very first function is home which renders all the entries from Attendance, Marks, and Notice table and pass them to home.html. Home.html (which is the home page of school management project) displays all the information in tabular form.

7. Home.html:


8. Admin Home Page AdminHome.html:

9. Student Home Page studentHome.html: this is the login page which contain navbar

10. AddAttendance page AddAttendance.html :In this page we have 4 column student name ,id,lecture attended,total lecture and a submit button

11. Add Notice Page AddNotice.html: In this page we have created the column to type the message or a submit button .on clicking the button this msg stored the database

12. Add Marks Page AddMarks.html: In this page we have created the 7 attributes student name,id,physics maks, chemistry marks, maths marks, english marks... Now, the user can fill their inforamation and then submit it this information store in database

10. We can see the navigation bar for both the users are different.

11. The next function in this file is addAttendance which uses addAttendanceform to create a new record in attendance table. This function is only for admin of school management project. If any other user attempts to access this, the user will get redirected to respective home page.

12. AddAttendance.html
13. AddNotice.html
14. AddMarks.html

15. Templates ###############
16. Login.html
17. Register.html
18. Links.html
19. navbar.html

Summary
We have successfully developed the online school management system python django project. We have used popular django framework for web development which provides tons of functionalities and templates to make the development easy.


