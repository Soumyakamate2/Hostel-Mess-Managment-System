🏨 Hostel Mess Management System

A PHP–MySQL based web application designed to streamline hostel mess operations, including student registration, meal booking, menu management, and admin control. The system provides a clean, user-friendly interface with automated PDF/CSV reporting, secure authentication, and modern UI components.

🚀 Features
Student Module

Student registration & login

View daily/weekly mess menu

Book meals online

Check booking history

Change password

Submit feedback

Admin Module

Approve/Reject student registrations

Add/Edit/Delete mess menu

Track daily meal bookings

Download PDF/CSV reports

Upload student list via CSV

View student details & feedback

Manage user accounts

🛠️ Technologies Used

Frontend: HTML5, CSS3, Bootstrap, JavaScript, jQuery
Backend: PHP
Database: MySQL
Other Libraries: Select2, Datepicker, FPDF (PDF generation), FontAwesome
Server: Apache (XAMPP/WAMP/LAMP)

📂 Folder Structure
/css          -> Stylesheets
/js           -> Scripts
/vendor       -> Select2, Datepicker, jQuery libraries
/php-files    -> Backend PHP scripts (login, signup, menu, admin functions)

⚙️ Installation / Setup

Download or clone the repository

Move the project folder into your server directory:

htdocs (XAMPP)

www (WAMP)

Import the SQL file into MySQL database

Update database credentials in dbh.php

Start Apache & MySQL servers

Run the project in a browser:

http://localhost/your-folder-name/

🔐 Login Credentials

Default credentials can be set in the database under the admin table.

📑 Reports Supported

Meal Booking Report (PDF)

Menu Report (PDF)

Student List Report (CSV/PDF)

🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

📄 License

This project is open-source and free to use.
