<img src="OCMS.png" />
    
# Project Summary: Online Course Management System
The Online Course Management System is designed to streamline the management of online courses, facilitating interactions between students, instructors, and course materials. This system aims to provide a comprehensive platform that includes features for enrollment tracking, course material management, and user authentication, ensuring an efficient and organized learning environment.

This is a simple **Online Course Management System** built using Python and SQLite. The system allows you to manage students, instructors, courses, course materials, and enrollments. It provides basic CRUD (Create, Read, Update, Delete) operations and can export data to a CSV file.

# Project Description
This project encompasses the development of a robust online course management system that addresses the needs of educational institutions and learners. Key functionalities include:

- Course Management: Instructors can create, update, and manage course details, while students can enroll in courses and access materials.

- Student and Instructor Management: The system maintains records of students and instructors, allowing for easy tracking of enrollment and performance.

- Course Materials: A dedicated section for course materials ensures that all relevant resources are easily accessible to students.

- Search Functionality: Users can search for courses, materials, and enrollment records based on various criteria.
    
- Data Validation: Ensures that user inputs are accurate and consistent.

- Export Functionality: Users can export data to CSV files for reporting and analysis.

- User Authentication: A simple login system secures access to the system, protecting sensitive information.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
  - [Main Menu](#main-menu)
  - [Add Operations](#add-operations)
  - [Update Operations](#update-operations)
  - [View/Search Operations](#viewsearch-operations)
  - [Delete Operations](#delete-operations)
  - [Export Data](#export-data)
- [Contributing](#contributing)

## Getting Started

### Prerequisites

To run this project, you need to have Python installed on your machine. You can download Python from [here](https://www.python.org/downloads/).

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/KOTAnthony/onlinecoursemgtsys/
   cd onlinecoursemgtsys
2. **Install the required packages:**
The project uses only the built-in sqlite3 and csv modules, so no additional packages are required.
3. **Run the program:**
   ```bash
   python main.py

## Usage
### Main Menu

When you run the program, you'll be presented with the main menu. From here, you can navigate to different sections of the system:

    Add: Add new records to the database.
    Update: Update existing records.
    View or search: View records or search for specific records.
    Delete: Delete records from the database.
    Export to csv file: Export all data to a CSV file.
    Exit: Exit the program.

### Add Operations

The system allows you to add the following records:

    Student
    Instructor
    Course
    Course Material
    Enrollment

You will be prompted to enter the necessary details for each type of record.

### Update Operations

You can update existing records in the following categories:

    Student
    Instructor
    Course
    Course Material
    Grade (for enrollments)

You can choose to update specific fields or leave them blank to keep the current value.

### View/Search Operations

You can view or search records in the database. The available options are:

    View Enrollment History: View all enrollments.
    View Course Material: View materials for a specific course.
    Search Records: Search for specific records in any table.

### Delete Operations

You can delete records from the following categories:

    Course Material
    Enrollment


### Export Data

The system allows you to export all the data to a CSV file. The CSV file will include data from all the tables in the database (student_info, instructor_info, course_info, course_material_info, and enrollment_info).

## Contributing

Contributions are welcome! If you have any ideas or improvements, feel free to fork the repository and submit a pull request.

# Conclusion
The Online Course Management System is a comprehensive solution for managing online courses effectively. With features that enhance the user experience and streamline administrative tasks, this project aims to support educational institutions in providing high-quality online learning. Future improvements will focus on enhancing search functionality, implementing thorough data validation, and refining the user interface for better usability. Thank you for your interest in the Online Course Management System!

