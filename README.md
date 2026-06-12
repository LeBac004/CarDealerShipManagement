# Car Store Management System

## Overview

Car Store Management System is a small web-based project developed as part of my learning process in web development and database management. This project was completed in a short period of time, so some features are still basic and may not be fully optimized.

The main purpose of this project is to practice building a simple management system with user authentication, car management, customer management, and basic sales/contract handling.

This project will continue to be improved and upgraded in the future as I learn more about software development, security, backend structure, and user interface design.

## Features

* User login and logout
* Role-based access for admin and sales users
* Add, edit, and delete car information
* Manage customer information
* Create sales contracts
* Store data using MySQL database
* Basic image upload for car products
* Simple dashboard and management pages

## Technologies Used

* PHP
* MySQL
* HTML
* CSS
* Bootstrap
* JavaScript
* XAMPP / phpMyAdmin
* Visual Studio Code

## Project Structure

```text
CarStoreManager/
│
├── login.php
├── logout.php
├── validation.php
├── homepage.php
├── addcar.php
├── edit.php
├── deletecar.php
├── customer.php
├── contract.php
├── connection.php
├── data.sql
└── README.md
```

## How to Run

1. Clone this repository:

```bash
git clone https://github.com/yourusername/CarStoreManager.git
```

2. Move the project folder to the XAMPP `htdocs` directory.

```text
C:/xampp/htdocs/CarStoreManager
```

3. Start Apache and MySQL in XAMPP.

4. Open phpMyAdmin and create a new database.

5. Import the `data.sql` file into the database.

6. Update the database connection information in `connection.php` if needed.

7. Open the project in your browser:

```text
http://localhost/CarStoreManager
```

## Future Improvements

This project is still under development. Some planned improvements include:

* Improve user interface and responsive design
* Add better form validation
* Improve database structure
* Add password hashing instead of basic password storage
* Add search and filter functions
* Add better sales and contract reports
* Improve security using prepared statements across all database queries
* Refactor code for better organization
* Add more detailed documentation and screenshots

## Note

This is a small student project created in a short time for learning and practice purposes. The project is not yet a complete production-ready system, but it will be continuously updated and improved in the future.
