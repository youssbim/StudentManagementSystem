# Student Management System

This application is a Student Management System built using Python and PyQt6. It allows users to manage student records by adding, editing, deleting, and searching for students. The system uses MySQL for data storage, providing a scalable solution for managing student information.

## Features

- **Add Student**: Users can register new students by providing their name, course, and mobile number.
- **Edit Student**: Users can update the details of existing students.
- **Delete Student**: Users can remove students from the database.
- **Search Student**: Users can search for students by their names.
- **View All Students**: Users can view a list of all registered students in a table format.
- **User-Friendly Interface**: The application has a simple and intuitive graphical user interface.

## Requirements

To run this application, ensure you have the following installed:

- Python 3.x
- MySQL Server

## Set up the MySQL database
```bash
CREATE TABLE students (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(100) NOT NULL,
    course VARCHAR(100) NOT NULL,
    mobile VARCHAR(15) NOT NULL
);
