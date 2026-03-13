# QuizHub - Online Quiz Management System

<p align="center">
  <img src="https://img.shields.io/badge/PHP-%3E%3D7.0-blue?style=flat-square" alt="PHP Version">
  <img src="https://img.shields.io/badge/MySQL-Supported-blue?style=flat-square" alt="MySQL Supported">
</p>

🎯 QuizHub – Online Quiz Management System

QuizHub is a web-based quiz management platform designed to streamline the process of creating, managing, and attempting quizzes in an educational environment. The system provides separate dashboards for Admin, Teachers, and Students, enabling efficient course management, quiz creation, and performance tracking.

The platform helps educators create structured assessments while allowing students to evaluate their knowledge through interactive quizzes.

📌 Project Overview

The system allows administrators to manage users, teachers to create quiz content, and students to participate in quizzes. It provides a centralized environment where learning assessments can be conducted digitally.

The application is built using PHP and MySQL, making it lightweight and easy to deploy on local or cloud servers.

🚀 Key Features

🛡️ Admin Module

The administrator controls and manages the entire system.

Features:

Admin dashboard with statistics

Manage teachers and students

Approve or reject teacher registrations

Manage courses

Manage question bank

Monitor quiz history

Manage user feedback

Edit profile and account settings

👨‍🏫 Teacher Module

Teachers can create and manage quizzes and course content.

Features:

Teacher dashboard

Create and manage courses

Add, edit, and delete quiz questions

Upload course images

Organize questions by course

Track student participation

👩‍🎓 Student Module

Students can enroll in courses and attempt quizzes.

Features:

Student dashboard

View available courses

Attempt quizzes

View quiz history

Track scores and performance

Submit feedback

🧑‍💻 Technologies Used

Frontend

HTML5

CSS3

JavaScript

Backend

PHP

Database

MySQL

Server Environment

XAMPP / WAMP / LAMP

📂 Project Structure
QuizHub/
│
├── admin/                # Admin dashboard and management

├── assets/
│   ├── css/              # Stylesheets
│   └── js/               # JavaScript files

│
├── config/
│   └── db.php            # Database connection

│
├── teacher/              # Teacher module
├── student/              # Student module

│
├── available-courses.php
├── about.php
├── index.php             # Homepage

│
└── database.sql          # Database file

⚙️ Installation & Setup

Follow these steps to run the project locally.

1️⃣ Clone the Repository

git clone https://github.com/your-username/quizhub.git

2️⃣ Move the Project Folder

Move the project folder to:

xampp/htdocs/

3️⃣ Setup Database

Open phpMyAdmin

Create a new database

quizhub

Import the provided SQL file

4️⃣ Configure Database Connection

Open:

config/db.php

Update credentials if needed:

$host = "localhost";

$user = "root";

$password = "";

$database = "quizhub";

5️⃣ Run the Project

Open your browser and visit:

http://localhost/QuizHub

📊 System Workflow

Admin registers and manages teachers and students

Teachers create courses and quiz questions

Students enroll in courses and attempt quizzes

The system records quiz results and history

🔮 Future Improvements

Online timer-based quizzes

AI-based performance analysis

Mobile application support

Video learning integration

Multi-language support

Cloud deployment

👨‍💻 Author

Sudhan Angadi

GitHub:
https://github.com/Sudhii07


📜 License

This project is created for educational and academic purposes.
