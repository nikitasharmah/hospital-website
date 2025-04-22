# Hospital Management System

A comprehensive hospital website developed as part of an academic mini project. This system offers an integrated platform for managing patients, appointments, staff, and internal hospital operations through dynamic web interfaces.

**Project Overview**

This project simulates a real-world hospital management scenario with multiple access roles including patients, receptionists, and administrators. It supports essential features like secure logins, patient records, staff directories, and appointment scheduling — all handled dynamically via PHP and MySQL.

**Key Features**

- Patient sign-up with auto-generated ID  
- Doctor directory and appointment scheduling  
- Secure login panels for admins and receptionists  
- CRUD operations for patients, doctors, and staff  
- Contact form for patient queries  
- Modular frontend using HTML and CSS  
- Server-side scripting with PHP and MySQL  
- Compatible with local server environments (XAMPP)

**Technologies Used**

- Frontend: HTML5, CSS3  
- Backend: PHP  
- Database: MySQL  
- Local Server: XAMPP (Apache + MySQL)

**How to Run Locally**

1. Install XAMPP if not already installed.  
2. Copy the entire project folder to:  
   `C:\xampp\htdocs\hospital-website`  
3. Start Apache and MySQL using the XAMPP Control Panel.  
4. Import the `hospital.sql` file in phpMyAdmin to create the necessary database.  
5. Open your browser and navigate to:  
   `http://localhost/hospital-website/mainpage.php`

Note: This project uses PHP and must be run in a local server environment like XAMPP.

**Project Contributors**

- Nikita Sharma – Frontend Developer  
  (UI/UX Design, HTML Structure, CSS Styling, Layout Planning)  
- Nidhi Shenoy – Backend Developer  
  (PHP Scripting, Database Integration, Login & Session Management)

**Project Structure**

- `mainpage.php` – Landing page  
- `login.php`, `logout.php` – Authentication handlers  
- `connection.php` – Database connection setup

**Patient Management**

- `add_patient.php`, `add_patient2.php` – Registration forms  
- `add_patient_pros.php`, `add_patient_pro

