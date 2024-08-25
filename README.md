# Online-Exam-System

## To Develop Online Examination System in Python using Django Framework

### Language: 
- Python
- Django
- SQLite3
- HTML
- CSS
- JavaScript
- jQuery
- Ajax
- Pillow Library
- asgiref Library
- Django-widget-tweaks
- pytz Library
- Fontawesome
- Bootstrap

## About the Online Exam System

This Online Exam System Project has 3 types of user roles as I mentioned above. It gives access to the school management, faculties, and students. Each user role contains different permission or restriction to the project features and functionalities. The Student and Faculties are required to register or signup first on the site. The Faculty Accounts requires an admin validation before they can gain access to features and functionalities of its role.

In this system, the Admin Users have the privilege to access and manage most of the features and functionalities. They are the ones who validate the new teachers/faculties system account. They can also update the information of both Students and Faculty details and credentials.

The Faculties/Teachers have the privilege to manage the list of courses and questions. He/She can add a new course, delete a course, add questions to the course, and delete questions.

The Students can list all available examinations to take. In order for them to take the exam, they will simply click the 'Attend Exam Button' beside the exam name and the page will be redirected to the instruction page. Students can only select 1 answer to the options per question. Then, after the student finished answering and reviewing their answers, they can simply click the Submit Answer Button below the questionnaire. After the student answer sheet is submitted, the system will automatically check and computes the total score of the student.


## Features
### Admin
- Login
- Dashboard
  - Displays the Summary of the Uploaded Images
- Manage Courses
  - Add New Course
  - List All Courses
  - Delete Course
- Manage Questions
  - Add New Question
  - List All Questions
  - Delete Question
- Manage Teachers
  - List All Teachers
  - Validate Teacher
  - Update Teacher Details
  - Delete Teacher
  - List Teachers Salaries
- Manage Students
  - List All Students
  - Update Student Details
  - Delete Student
  - List Students Salaries
- Logout

### Faculties
- Login and Registration
- Dashboard
  - Displays the Summary of the Uploaded Images
- Manage Courses
  - Add New Course
  - List All Courses
  - Delete Course
- Manage Questions
  - Add New Question
  - List All Questions
  - Delete Question
- Logout

### Students
- Login and Registration
- Dashboard
  - Displays the Summary of the Uploaded Images
- List Examination
- List Courses
- List Exam Results
- Take Exam
- Logout

## Download/Install the following
- [Python](https://www.python.org/downloads/) [Installation Process](https://github.com/desihacker08/Online-Exam-System/blob/Coad/OnlinExaminationSystem/FileInstallation.md#python-install)
- PIP (for  python modules installation)
  -  [Windows](https://github.com/desihacker08/Online-Exam-System/blob/Coad/OnlinExaminationSystem/FileInstallation.md#pip-install)

## Setup/Installation
1. Download the source code file from github.
2. Open your Terminal/Command Prompt window.
 (make sure to add "python" and "pip" in your environment variables) if not download then follow this step [click]()
3. Change the working directory to the extracted source code folder. i.e.cd C:\Users\Path\Online-Exam-System\
4. Run the following commands:
  - `pip install -r requirements.txt`
  - `python manage.py migrate`
5. Create a Superuser by executing the following command:
  - `python manage.py createsuperuser`
6. Run the project by executing the following command:
  - `python manage.py runserver`
7. Keep the terminals open and running.
8. Open a web browser and browse http://localhost:8000/ or http://127.0.0.1:8000/


That's it! I hope this will help you with what you are looking for. Maybe you'll find this Online Exam System useful and can help you with your future Python Django Projects.

## Enjoy :)
