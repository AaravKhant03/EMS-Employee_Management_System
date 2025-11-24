# Employee Management System (CLI)

A command-line based system to securely manage employee records, salary updates, and performance reviews using MySQL database integration.

## Overview
This application allows authenticated users to register, login, and perform operations on employee data. It is designed as part of AIML curriculum project requirements with modular design, secure storage, validation, and logging.

## Features
- Secure user registration and login with hashed passwords
- Add new employees with validation rules
- View all employees formatted in a table
- Update salary with percentage calculations
- Insert employee performance review data
- Display total employee count
- Automatic database and table creation
- Logging for system monitoring and debugging

## Technologies Used
- Python 3
- MySQL Database
- mysql-connector-python package
- hashlib for encryption
- getpass for secure password input
- logging module

## Installation & Setup

### Install required package
```
pip install mysql-connector-python
```

### Start MySQL server before running the program

You will be prompted to enter MySQL root password:
```
Enter your MySQL 'root' password:
```

### Run the application
```
python employee_management_system.py
```

## Project Structure
```
Employee_Management_System/
│
├── employee_management_system.py
├── system.log                (auto generated)
└── README.md
```

## How to Use
After login, select an option from the menu:
```
1. Add New Employee
2. View All Employees
3. Update Employee Salary
4. View Employee Count
5. Add Performance Review
6. Logout
```

Follow input instructions. All stored data persists in MySQL.

## Testing Instructions
- Create a new user → login
- Add employee records (valid + invalid inputs)
- Test salary update & confirm new values
- Add multiple performance reviews
- Restart program and confirm persisted data
- Validate error handling by wrong inputs

## Future Enhancements
- Search, Sorting and Filtering options
- GUI or Web-based interface
- Admin vs Employee role access
- Reporting (CSV/PDF export)
- Machine Learning insights for performance

## Developer
Aarav Khant  

