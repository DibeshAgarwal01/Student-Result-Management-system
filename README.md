# Student Result Management System (SRMS)

The **Student Result Management System (SRMS)** is a web-based application built using **PHP** and **MySQL** designed to manage student details and their academic results. The system consists of two main modules: **Admin** and **Student**.

## Features

### Admin Features:
- **Dashboard** for easy navigation.
- **Manage Classes**: Add, update, or delete classes.
- **Manage Subjects**: Add, update, or delete subjects.
- **Subject Combination**: Add, update, and activate/inactivate subject combinations for each class.
- **Student Management**: Register new students and edit their information.
- **Result Management**: Declare and modify student results.
- **Notice Management**: Add, delete, and manage notices.
- **Admin Profile**: Change admin password.

### Student Features:
- **Result Search**: Students can search and view their results by entering their roll number.
- **Notice Viewing**: Students can view notices posted by the admin.

## Technologies Used
- **Frontend**: HTML, JavaScript, AJAX, jQuery
- **Backend**: PHP 5.6, 7.x, 8.x
- **Database**: MySQL 5.x, 8.x
- **Server**: XAMPP, WAMP, MAMP, or LAMP

## System Requirements
- **Web Browser**: Mozilla Firefox, Google Chrome, Internet Explorer 8+, Opera
- **Software**: XAMPP, WAMP, MAMP, or LAMP (any of these can be used)

## How to Run This Project

1. **Download and Unzip** the project file on your local system and copy the `srms` folder.
2. **Move the `srms` folder** into your web server's root directory (e.g., `htdocs` for XAMPP or `www` for WAMP).

### Database Configuration

1. Open **phpMyAdmin** on your local server.
2. Create a new database called `srms`.
3. Import the `srms.sql` file (found inside the zip package) into the `srms` database.

### Accessing the Application

- **For Student Panel:**
  - Open your browser and go to `http://localhost/srms`.
  - **Student Details**:
    - **Name**: Anuj Kumar
    - **Roll ID**: 10861
    - **Class**: Fourth (C)

- **For Admin Panel:**
  - Open your browser and go to `http://localhost/srms/admin`.
  - **Login Credentials**:
    - **Username**: admin
    - **Password**: Test@123
