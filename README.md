# Semester-2-Epita-project-

Technical Documentation of My Semester 2 Project

I’ve developed this project using a combination of PHP, HTML, CSS, and JavaScript. The main goal is to allow the EPITA International Programs Staff, to extract and manage data about students, courses, populations, and their grades from the system’s database.

1-Backend (PHP):

The core of my project is built using PHP. It serves the purpose of connecting the frontend with the MySQL database. Here are the major components of the backend:

- “db.php”: This file handles the database connection using PDO(PHP Data Objects), ensuring secure and efficient interaction with MySQL.

- “auth_check.php” and “auth_checker.js”: These are responsible for user authentication. The PHP file checks the credentials stored in the database, while the JavaScript ensures the login process on the client side.

- “get_...” files: These are PHP scripts that retrieve specific data from the database, such as students, courses, grades, and population details. 
For instance, “get_students_by_discipline.php” fetches students based on their discipline (the name of the file speaks for itself), while “get_grades.php” returns students’ grades.

-2. Frontend (HTML, CSS, JavaScript):

The frontend is structures using a mix of HTML, CSS, and JavaScript, focusing on making the UI (User Interface) intuitive and responsive.

- HTML (“index.html”): These files define the structure and layout of the web pages, displaying the data retrieved from the database. They include tables for listing courses, students, and other content, as well as forms for adding or editing information. 

- JavaScript (“script.js”): These files manage the dynamic aspects of the user interface, like adding new courses or students and appending rows to tables dynamically.

- CSS (“styles.css”): The styles files are responsible for the look and feel of the application, keeping the interface clean and user-friendly.

3- AJAX:

I’m using AJAX (through JavaScript) for smooth interaction without reloading the page. This allows the user to, for example, add a course or delete a student and see the updates immediately without leaving the page.

This structure makes the application modular and easy to maintain. The goal is to keep everything straightforward for future improvements while focusing on ease of use for the end-users.
![image](https://github.com/user-attachments/assets/2705f598-cd7e-42bc-88a7-a6dd62a089fa)

