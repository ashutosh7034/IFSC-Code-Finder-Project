

# IFSC Code Finder Project

## Project Introduction

The **IFSC Code Finder Project** is a web-based application developed using **PHP** and **MySQL** that allows users to quickly find the IFSC (Indian Financial System Code) of any bank branch. In the current manual system, users have to visit a bank branch to get the IFSC code, which can be time-consuming. This project streamlines the process by enabling users to search for IFSC codes online based on bank name, branch name, and pincode/zipcode from anywhere. The system consists of two key modules: **User Module** and **Admin Module**.

## Project Requirements

- **Project Name**: IFSC Code Finder Project
- **Languages Used**:  
  - PHP (Version 5.6, 7.x)
- **Database**:  
  - MySQL 5.x
- **User Interface Design**:  
  - HTML, AJAX, JQUERY, JavaScript
- **Web Browser Compatibility**:  
  - Mozilla Firefox, Google Chrome, Internet Explorer (IE8+), Opera
- **Software Required**:  
  - XAMPP / WAMP / MAMP / LAMP

---

## Project Modules

### 1. User Module
The **User Module** allows users to search for IFSC codes quickly and easily using the following parameters:
- **Bank Name**
- **Branch Name**
- **Pincode/Zipcode**

Once the user enters the search criteria, the system retrieves the corresponding IFSC code from the database and displays it on the screen, providing a fast and convenient solution to the IFSC code search process.

### 2. Admin Module
The **Admin Module** allows the admin to manage the entire system, including the banks, states, cities, and branch details. Admins have full control over the data in the system and can perform CRUD operations (Create, Read, Update, Delete) on bank-related data.

- **Dashboard**:  
  The admin dashboard provides a summary of the number of banks, states, and cities stored in the system, along with details about various bank branches.

- **Add Pages**:  
  In this section, the admin can add new:
  - Banks
  - States
  - Cities
  - Branch details (including IFSC code)
  
  This feature allows the admin to keep the system updated with the latest banking information.

- **Manage Pages**:  
  The admin can manage (edit or delete) existing:
  - Banks
  - States
  - Cities
  - Branch details
  
  This section ensures that the system maintains accurate and up-to-date information about all bank branches.

- **Profile Management**:  
  Admins can update their profile information, including name, contact details, and other personal information.

- **Settings**:  
  In this section, the admin can:
  - Change their password for security reasons.
  - Recover a lost password if necessary.

---

## Features of the Project

- **Fast IFSC Code Search**:  
  Users can easily search for IFSC codes by entering bank name, branch name, and pincode, simplifying the process.

- **User-Friendly Interface**:  
  The interface is designed to be simple and intuitive for both users and admins.

- **Admin Control Panel**:  
  The admin has complete control over the data, including the ability to add new entries and manage existing ones.

- **Profile and Security Management**:  
  Admins can update their profile information and change their passwords for enhanced security.

---

## Installation Instructions

1. **Download and Install XAMPP, WAMP, MAMP, or LAMP**:
   - **XAMPP**: [Download Here](https://www.apachefriends.org/index.html)
   - **WAMP**: [Download Here](http://www.wampserver.com/en/)
   - **MAMP**: [Download Here](https://www.mamp.info/en/)
   - **LAMP**: Install as per your Linux distribution guidelines.

2. **Clone or Download the Project Repository**:
   ```bash
   git clone https://github.com/yourusername/ifsc-code-finder.git
   ```

3. **Move the Project to Your Server Root Directory**:
   - XAMPP: `C:/xampp/htdocs/`
   - WAMP: `C:/wamp/www/`
   - MAMP: `/Applications/MAMP/htdocs/`
   - LAMP: `/var/www/html/`

4. **Create the Database**:
   - Open **phpMyAdmin** in your browser (usually `http://localhost/phpmyadmin`).
   - Create a new database, e.g., `ifscdb`.
   - Import the provided SQL file (`ifscdb.sql`) into the new database.

5. **Configure the Project**:
   - Open the project’s configuration file (`config.php`) and update the database credentials:
     ```php
     $host = 'localhost';
     $user = 'root';  // or your MySQL username
     $password = '';  // or your MySQL password
     $dbname = 'ifsc_finder_db';  // your database name
     ```

6. **Run the Project**:
   - Open your browser and navigate to `http://localhost/your_project_folder/`.

---

## License
This project is open-source and available under the [MIT License](LICENSE).
