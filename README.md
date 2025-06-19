📝 Project Description:
The Student Information Management System is a menu-driven C program designed to manage and organize student data effectively. It provides functionalities such as adding, searching, updating, and deleting student records. Each student record includes personal details like first and last name, roll number, CGPA, and associated course IDs.

This system operates through a simple CLI (Command Line Interface), making it suitable for educational institutions or basic student databases. Data is stored using structures and maintained in memory during execution.

key Highlights:

Structured Data Storage:

Student records are stored using a custom struct, containing fields for name, roll number, CGPA, and an array for course IDs.

Modular Design:

The program is built with clear modular functions: add_student(), find_rl(), find_fn(), del_s(), up_s(), etc., each handling a specific task for maintainability and clarity.

Search Capabilities:

Students can be searched by roll number, first name, or course ID, demonstrating the use of string and integer comparison, along with looping logic.

Update & Deletion Support:

Student data can be modified or removed based on roll number, showing use of in-place record editing and data shifting in arrays.

Memory-Safe & Efficient:

Designed for up to 50 students, the program manages memory using fixed-size arrays, avoiding dynamic allocation for simplicity.

Course Enrollment Mapping:

Each student can be associated with up to 5 course IDs, which helps simulate course enrollments.

