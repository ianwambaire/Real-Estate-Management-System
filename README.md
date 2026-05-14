# Real Estate Management System

A web-based real estate management platform designed to simplify property management processes such as tenant management, rent tracking, property listings, and utility payment monitoring. The system provides an organized and user-friendly interface for managing real estate operations efficiently.

## Features

- User authentication system
- Property listing management
- Tenant management
- Rent payment tracking
- Utility payment management
- Dashboard for property overview
- Responsive user interface
- Organized property and tenant records

## Technologies Used

- HTML5
- CSS3
- JavaScript
- PHP
- MySQL

## Project Structure

```bash
Real-Estate-Management-System-main/
│
├── index.php
├── login.php
├── register.php
├── dashboard.php
├── properties.php
├── tenants.php
├── payments.php
├── utilities.php
├── database.php
│
├── assets/
├── css/
├── js/
└── images/
```

## Installation and Setup

1. Clone the repository

```bash
git clone https://github.com/your-username/Real-Estate-Management-System.git
```

2. Move the project folder into your web server directory

For XAMPP:

```bash
htdocs/
```

3. Start Apache and MySQL from XAMPP

4. Create a MySQL database

- Open phpMyAdmin
- Create a new database
- Import the SQL file if available

5. Configure the database connection

Update the database credentials inside:

```bash
database.php
```

6. Run the project

Open your browser and visit:

```bash
http://localhost/Real-Estate-Management-System-main/
```

## System Modules

### Authentication Module
Handles user login, registration, and session management.

### Property Management Module
Allows users to manage property listings and related information.

### Tenant Management Module
Stores and manages tenant records and rental information.

### Payment Management Module
Tracks rent and utility payments.

### Dashboard Module
Provides an overview of properties, tenants, and payments.

## Future Improvements

- Online payment integration
- Property image upload functionality
- Maintenance request system
- Advanced reporting and analytics
- Email and SMS notifications
- Improved mobile responsiveness

## Author

Ian Wambaire

## License

This project is for educational and learning purposes.
