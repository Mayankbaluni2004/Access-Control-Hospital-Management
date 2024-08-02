# Access Control Hospital Management System

A Java and SQL-based system to manage hospital operations with secure access control.

## Features

- **User Authentication:** Secure login for staff.
- **Patient Management:** Manage patient records.
- **Appointment Scheduling:** Handle doctor-patient appointments.
- **Role-Based Access:** Different permissions for various roles.

## Technologies

- **Java:** Backend
- **SQL:** Database
- **NetBeans:** IDE
- **XAMPP:** MySQL server

## Setup

### Prerequisites

- JDK
- NetBeans IDE
- XAMPP or MySQL server

### Steps

1. **Set Up Database:**
   - Start XAMPP and MySQL.
   - Create `hospital_management` database in phpMyAdmin.
   - Import SQL script:
     ```sh
     mysql -u root -p hospital_management < database/hospital_management.sql
     ```

2. **Configure Database Connection:**
   - Update database URL, username, and password in the configuration file.
     ```java
     String url = "jdbc:mysql://localhost:3306/hospital_management";
     String user = "root";
     String password = "yourpassword";
     ```

3. **Run Project:**
   - Open in NetBeans and run.

## Usage

1. **Login:** Use default credentials for different roles.
2. **Navigate:** Use the dashboard to manage patients, appointments, and staff.
3. **Role-Based Access:** Features vary by user role.
