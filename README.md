Amigos Hospital

Project Description:
The login page with employee form and employee details is an essential tool for hospital to manage their employees. It allows the admin to easily add new employees to the system and we provide medical inventory details and the manager can access and view the details of existing employees.

Software Requirements: 
1. Operating System: Windows 8 and above 
2. Frontend Technology: Html, CSS, Bootstrap, Java Script 
3. Backend Technology: Python (https://www.python.org/downloads/) 
4. Framework: Django 
5. Database: MySQL (https://www.mysql.com/downloads/) 
6. IDE: VS Code (https://code.visualstudio.com/download)

Modules should be installed in python:
1. C:\Users\USER>pip install django
2. C:\Users\USER>pip install mysql.connector
3. C:\Users\USER>pip install mysql
4. C:\Users\USER>pip install pillow

Run the Project:
1. Open Code in Visual studio 
2. Open settings.py file and enter your database credentials in DATABASE block and create the database in Mysql with name mentioned in settings.py. 
•	create  database quality ;
3. Go to Terminal > New Terminal
4. Enter command in terminal: python manage.py makemigrations
5. Enter command in terminal: python manage.py migrate
makemigrations and migrate are commands that are used to interact with Django models.
•	makemigrations: This command prepares makemigrations file for our new model, or creates a new migrations file for any changes if the models have been modified. This command does not create or affect these changes to the database.
•	migrate: migrate command runs the instructions defined in the recent migrations file on the database.
5. Enter command in terminal: python manage.py runserver
6. Open the URL in browser and the web application runs in browser.
