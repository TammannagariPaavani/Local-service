SERVEASE is a responsive web-based Service Provider Management System developed using PHP, MySQL, HTML, CSS, and JavaScript. The main goal of this project is to make it easy for users to find service providers, book appointments, and manage their bookings through a simple and user-friendly interface.

The system also includes separate dashboards for Service Providers and Administrators to manage services, appointments, users, and other activities efficiently.

Features
User
User Registration & Login
Search Available Services
Book Appointments
View My Bookings
Manage Profile
Forgot Password
Contact & Inquiry Form
Service Provider
Provider Dashboard
Add New Services
Edit Existing Services
Manage Appointments
Admin
Secure Admin Login
Manage Users
Manage Service Providers
Approve or Reject Provider Requests
Manage Services
Payment Management
View Contact Messages
Technologies Used
Frontend
HTML5
CSS3
JavaScript
Backend
PHP
Database
MySQL
Server
XAMPP
Tools
Visual Studio Code
phpMyAdmin
Project Structure
SERVEASE/
│
├── admin/
│   ├── add_service.php
│   ├── admin-dashboard.php
│   ├── admin-login.php
│   ├── admin-logout.php
│   ├── approved.php
│   ├── control-list.php
│   ├── delete.php
│   ├── edit.php
│   ├── payment-action.php
│   ├── payments.php
│   ├── providers.php
│   ├── reject.php
│   ├── requests.php
│   ├── services.php
│   └── users.php
│
├── backend/
├── css/
├── image/
├── about.php
├── add-service.php
├── book-appointment.php
├── contact.php
├── contact_submit.php
├── edit-service.php
├── forgot-password.php
├── index.php
├── inquiry-thread.php
├── login.php
├── logout.php
├── my-bookings.php
├── profile.php
├── provider-dashboard.php
├── register.php
├── reset_password.php
├── save-provider.php
├── serch.php
├── services.php
└── README.md
Installation
1. Clone the Repository
git clone <repository-link>
2. Open the Project
cd SERVEASE
3. Start XAMPP
Open the XAMPP Control Panel.
Start Apache and MySQL.
4. Move the Project

Copy the project folder to:

C:\xampp\htdocs\SERVEASE
5. Import the Database
Open phpMyAdmin.
Create a new database (for example, servease).
Import the provided SQL file into the database.
6. Run the Project

Open your browser and visit:

http://localhost/SERVEASE/
Future Improvements

Some features that can be added in future versions include:

Online Payment Gateway
Email Notifications
Service Ratings & Reviews
Real-Time Chat Support
OTP Verification
Responsive Admin Dashboard
Advanced Search & Filters
Author

Tammannagari Paavani

License

This project was developed for educational purposes to practice full-stack web development using PHP and MySQL
