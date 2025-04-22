# Hospital Management System

A comprehensive hospital website developed as part of my academic mini project. This system offers an integrated platform for managing patients, appointments, staff, and internal hospital operations through dynamic web interfaces.

**Project Overview**

This project simulates a real-world hospital management scenario with multiple access roles including patients, receptionists, and administrators. It supports essential features like secure logins, patient records, staff directories, and appointment scheduling. 

**Key Features**

- Patient sign-up with auto-generated ID  
- Doctor directory and appointment scheduling  
- Secure login panels for admins and receptionists to add/update/delete records 
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
  (UI Design, HTML Structure, CSS Styling, Layout Planning)  
- Nidhi Shenoy – Backend Developer  
  (PHP Scripting, Database Integration, Login & Session Management)

**Project Structure**

- `mainpage.php` – Landing page  
- `login.php`, `logout.php` – Authentication handlers  
- `connection.php` – Database connection setup

**Patient Management**

- `add_patient.php`, `add_patient2.php`, `add_admin_patient.html` – Patient registration forms  
- `add_patient_pros.php`, `add_patient_pros2.php` – Patient registration processing scripts
- `update_patient.php`, `update_patient_pros.php`, `delete_patient.php`, `delete_patient_pros.php`–  Patient record modifications  
- `view_appt.php` – View scheduled appointments

**Doctor Management**

- `doctors.php` – List of doctors  
- `add_doctor.php`,`add_doctor_pros.php`,`update_doctor.php`,`update_doctor_pros.php`, `delete_doctor.php`, `delete_doctor_pros.php` – Doctor data handling

**Receptionist Management**

- `add_recep.php`,`add_recep_pros.php`,`update_recep.php`,`update_recep_pros.php`, `delete_recep.php`,`delete_recep_pros.php` – Receptionist data handling

**Appointment System**

- `appointment.php`- Book Appointment
- `add_appt.php`,`add_appt_pros.php`, `add_appt_pros2.php`, `delete_appt.php`, `delete_appt_pros.php` – Appointment data handling

**Admin & User Dashboard**

`home_user.php`, `left.php` – User dashboard layout and sidebar
`home_admin.php`, `left_admin.php`, `admin_right.php` – Admin panel layout and functionality

**Billing and Invoices**

- `view_invoice.php` – Invoice generation and display

**Query Handling**

- `ins_query.php`, `ins_query_pros.php` – Query related scripts

**Images**

- `/images/` – Contains logos, icons, and UI images

**Disclaimer**

This project was created solely for academic purposes to demonstrate core web development concepts in a real-world simulation. It does not contain or represent any actual patient data or healthcare workflows.

Feel free to clone, fork, or extend this project for educational exploration.


