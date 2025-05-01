## IT3232-Day-04-Map-Controller-created
# Project Overview

The project follows a standard Spring Boot application structure with the following key components:

# Models

- Student.java: Represents a student entity with attributes like name, age, department, registration number, and GPA.
- Course.java: Represents a course entity with attributes like name, code, description, duration, and year.
  
# Controllers

- MapController.java: Handles CRUD operations for student entities.
- CourseController.java: Handles CRUD operations for course entities.

  # API Endpoints

  # Student Management (/app)
  
:---| Method	:---:| Endpoint	---:| Description
:--- GET	:---: /app/mapstudent/{id}	---: Get a student by registration number
:--- GET	:---: /app/mapstudentAll	---: Get all students
:--- POST	:---: /app/add	---: Add a new student
:--- DELETE	:---: /app/delStu/{reg}	---: Delete a student by registration number
:--- PUT	:---: /app/update/{reg}	---: Update a student by registration number
