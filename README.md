# DSA-PROJECT-University-Management-System
This program models a University Management System with menu-driven options. Users can add or remove departments, manage students, courses, and instructors, and assign them to specific courses. The system supports functions like enrolling students in courses, displaying department details, and managing course instructors within departments.
# University Management System

## Description
This University Management System is a console-based application designed to manage university entities including departments, students, and courses. The system offers menu-driven options to facilitate operations such as adding/removing departments, managing student admissions, assigning instructors, enrolling students in courses, and more.

## Features
- **Department Management**: Add, remove, and display university departments.
- **Student Management**: Admit, remove, and list students in the university.
- **Course Management**: Add/remove courses to departments, and display available courses.
- **Enrollment and Assignment**: Enroll students to specific courses, and assign instructors to courses.

## Usage
1. Clone the repository and compile the program.
2. Run the `main` executable to interact with the University Management System.
3. Follow on-screen instructions to navigate through the menu options.

### Main Menu Options
1. **Add Department**: Create a new department in the university.
2. **Remove Department**: Remove an existing department by its name.
3. **Show Departments**: Display all departments within the university.
4. **Admit Student**: Add a new student with details including name, age, ID, CGPA, and admission date.
5. **Remove Student**: Remove a student by their student ID.
6. **Show Students**: Display a list of all admitted students.
7. **Access Departments**: Access a specific department to manage courses, instructors, and enrollments.
0. **Exit**: Exit the University Management System.

### Department Menu Options
- **Add Course**: Add a new course to a department by specifying course details.
- **Remove Course**: Remove a course by its code.
- **Show Courses**: Display all courses offered by the department.
- **Show Instructors**: Display a list of instructors assigned to the department's courses.
- **Access Courses**: Enter course-specific options to view enrolled students or instructors.

### Course Menu Options
- **Show Enrolled Students**: Display all students enrolled in a selected course.
- **Show Instructors**: Display instructors for the selected course.

## Requirements
- C++ compiler

## Compilation
Compile all source files using a C++ compiler:
```bash
g++ main.cpp Student.cpp Person.cpp Teacher.cpp Course.cpp CourseList.cpp StudentList.cpp StudentQueue.cpp Department.cpp University.cpp -o UniversityManagementSystem


This README gives a comprehensive overview of the University Management System program, detailing its purpose, features, usage, and instructions for compiling and running the program.
