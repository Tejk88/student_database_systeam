# student_database_systeam
STUDENT DATABASE SYSTEM
Language Used: C
Purpose: To manage student records efficiently by allowing users to perform CRUD (Create, Read, Update, Delete) operations with sorting and data persistence.

Project Overview
The Student Database Management System (SDBMS) is a console-based application built in C that allows users to store and manage student records. It provides functionalities such as adding new students, deleting or modifying existing records, displaying sorted data, and saving data persistently using file handling. The system is menu-driven, making it user-friendly for non-technical users.

Features & Functionalities
1) Adding Student Records
Users can input student details such as:
Roll Number (Unique ID)
Name
Age
Marks
The system validates the inputs to prevent incorrect data (e.g., negative marks, duplicate roll numbers).
2) Displaying Student Records
Users can view all stored student details in a structured format.
The system supports sorted display based on:
Roll Number
Name
Marks (ascending/descending order)
3) Modifying Existing Records
Allows users to update student details.
Ensures that updates don’t break data integrity (e.g., prevents changing roll numbers to an already existing one).
4) Deleting Student Records
Users can remove records using the roll number.
If a record is not found, the system displays an appropriate message.
5) Sorting Student Records
Sorting is implemented using Bubble Sort, Quick Sort, or any other algorithm based on user selection.
Sorting is available by:
Name (Alphabetical)
Roll Number (Ascending)
Marks (Highest to Lowest)
6) Data Persistence Using File Handling
Student records are stored in a file (e.g., students.txt) to ensure data is retained even after the program is closed.
The system reads data from the file at startup and writes changes when records are added, modified, or deleted.
7) Menu-Driven Interface
A simple text-based menu allows users to navigate through options easily.
Input validation ensures incorrect choices don’t crash the program.
-->Technologies & Concepts Used
✅ Programming Language: C
✅ Data Structures: Arrays, Structs, Pointers
✅ Algorithms: Sorting (Bubble Sort, Quick Sort), Searching (Linear Search)
✅ File Handling: Read, Write, Append Operations
✅ Memory Management: Dynamic memory allocation (malloc, free)
