# student_PHP

This project is a web-based grading system developed using PHP and MySQL. It allows administrators, teachers, and staff to manage student records, grades, and reports efficiently.

Features

User authentication (login/logout)

Manage student records

Add and update grades

Generate student reports

Curriculum and subject management

Statistical analysis of grades

User role management

Installation

Prerequisites

Apache/Nginx server

PHP 7.x or later

MySQL database

Composer (optional for dependency management)

Setup Instructions

Clone or extract the project files into your web server's root directory (e.g., htdocs for XAMPP or www for WAMP).

Create a database in MySQL and import the grading/database/grading_db.sql file.

Configure database settings in connect.php and db.php.

Start your local server and navigate to http://localhost/grading/.

Log in using the provided credentials or create a new account.

File Structure

index.php - Main entry point (Login page)

home.php - Dashboard

auth.php - Handles authentication

db.php & connect.php - Database connection

students.php - Student record management

grades.php - Grade entry and retrieval

reports/ - Reporting and analytics

assets/ - CSS, JS, fonts, and third-party libraries

database/ - SQL scripts for database setup

Usage

Log in with admin credentials.

Add new students and manage records.

Assign subjects and enter grades.

Generate reports and track student progress.

Manage academic year and curriculum.

Contributing

To contribute to this project, fork the repository and create a pull request with your changes.

License

This project is open-source and can be modified freely.
