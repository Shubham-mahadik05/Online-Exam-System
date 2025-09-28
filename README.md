# 📝 Online Exam System

An **Online Exam Management System** built using **HTML, CSS, JavaScript, PHP, and MySQL**.  
It allows students to take exams online and administrators to create/manage exams, questions, and results.  
The project runs on **XAMPP** server environment.

---

## 🚀 Features

- 👨‍🏫 **Admin Panel**  
  - Add, update, and delete exams.  
  - Manage question banks (MCQs).  
  - View and analyze student performance.  

- 👩‍🎓 **Student Panel**  
  - Register and login securely.  
  - Take exams with real-time timer.  
  - Instant score and result generation.  

- 📊 **System**  
  - Automated evaluation of exams.  
  - User-friendly interface with HTML, CSS, and JS.  
  - Database-driven with MySQL.  

---

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** PHP  
- **Database:** MySQL  
- **Server:** XAMPP (Apache + MySQL)  

---

## 📂 Project Structure
online-exam-system/
│── config/ # Database connection files
│── admin/ # Admin panel (exam & question management)
│── student/ # Student panel (exam interface)
│── assets/ # CSS, JS, images
│── index.php # Landing page
│── login.php # User login
│── register.php # User registration
│── result.php # Result display
│── README.md # Project documentation

Install XAMPP
Download and install XAMPP
.

Move Project Folder
Place the project folder in:

C:\xampp\htdocs\online-exam-system


Setup Database

Start Apache and MySQL from XAMPP Control Panel.

Open http://localhost/phpmyadmin/.

Create a new database (e.g., exam_db).

Import the provided SQL file (exam_db.sql).

Configure Database Connection
In config/db.php, update:

$servername = "localhost";
$username   = "root";   // default MySQL user
$password   = "";       // default is empty
$dbname     = "exam_db";


Run the Project
Open in browser:

http://localhost/online-exam-system/

🔑 Default Credentials (Demo)

Admin

Username: admin

Password: admin123

Student

Username: student1

Password: student123

(You can change credentials from database or registration page.)

