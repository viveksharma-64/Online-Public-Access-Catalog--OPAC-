📚 Online Public Access Catalog (OPAC)

An Online Public Access Catalog (OPAC) built using PHP + MySQL, designed for educational institutes and libraries to manage books, users, and circulation activities.
The system provides separate modules for Admin and Students, enabling smooth digital library management.

🚀 Features
🔹 Admin Module

Admin login & authentication

Add / Edit / Delete books

Manage book categories

View issued books

Approve / Reject issue requests

Approve / Reject renewal & return requests

Manage student accounts

View student history

Handle recommendations & messages

Dashboard with book and user stats

🔹 Student Module

Student login

Search for books

View book details

Request issue / renewal / return

View issue status & history

Receive admin messages

Profile management

🔹 General Features

Clean user interface with Bootstrap

Organized module structure

SQL database scripts included

Easy deployment on XAMPP/WAMP

Separate Admin & Student views

🛠️ Technology Stack
Component	Technology
Backend	PHP (Procedural)
Frontend	HTML, CSS, Bootstrap, JavaScript, jQuery
Database	MySQL (SQL files provided)
Server	XAMPP / WAMP / Localhost
Libraries	jQuery UI, Flot Charts
📁 Project Structure (Analyzed from your ZIP)
opac/
│── admin/              → Admin dashboard & functionalities  
│── student/            → Student-side portal  
│── database/           → SQL files for MySQL database setup  
│── css/                → Stylesheets  
│── images/             → UI assets  
│── dbconn.php          → Database connection file  
│── index.php           → Login page  
│── terms.html          → Terms page  
│── see.php             → General handler  

🗄️ Database

Your project includes the following SQL dump files:

LMS_user.sql – Student data

LMS_book.sql – Books table

LMS_author.sql – Authors table

LMS_record.sql – Issue/Return records

LMS_message.sql – Messages

LMS_recommendations.sql – Book recommendations

LMS_renew.sql – Renew requests

LMS_return.sql – Return requests

Import all .sql files into a MySQL database named opac or lms.

🔧 Installation (Localhost – XAMPP)
1️⃣ Install XAMPP

Download from: https://www.apachefriends.org/

2️⃣ Move Project

Copy the extracted folder to:

C:\xampp\htdocs\opac

3️⃣ Start Apache & MySQL

Open XAMPP → Start Apache and MySQL

4️⃣ Import Database

Go to phpMyAdmin

Create a new DB (name: opac)

Import all SQL files from /database folder

5️⃣ Update DB Connection

Check dbconn.php:

$servername = "localhost";
$username = "root";
$password = "";
$dbname = "opac";

6️⃣ Run in Browser
http://localhost/opac

🔐 Default Credentials (Common for OPAC Templates)

If your version uses predefined logins:

Admin Login

Username: admin

Password: admin123 (or blank depending on DB)

Student Login

You can create students via Admin panel

Or through the LMS_user.sql imported data

If not sure, I can extract exact login credentials from your SQL files—just say “find login details”.



📄 License

 MIT License

🤝 Contributing

Pull requests are welcome.
For major changes, open an issue to discuss what you’d like to improve.

🙌 Author

Vivek Sharma
GitHub: https://github.com/viveksharma-64
