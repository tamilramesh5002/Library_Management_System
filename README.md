____**Library Management System**____

 A Modular C Programming Project Using Data Structures

 1. Project Overview

The Library Management System is a menu-driven software application developed using the C programming language to manage and maintain library book records efficiently.
The application implements a Singly Linked List for dynamic record management and uses file handling to maintain persistent storage of book information. 
Its modular architecture separates individual operations into dedicated header files, improving code organization, readability, and maintainability.
The system provides essential functionalities, including book insertion, deletion, searching, updating, displaying, and record storage.

 2. Key Features

- Book Management: Add new book records with unique identification details.
- Record Display: Display available book information.
- Book Search: Retrieve specific records using Book ID.
- Record Modification: Update existing book details.
- Book Deletion: Remove selected records from the linked list.
- Persistent Storage: Save book records using file handling.
- Data Retrieval: Load previously stored records.
- Modular Implementation: Organize functionalities using separate header files.

 3. Technical Specifications

 Category and Implementation 

 Programming Language - C 
 Data Structure - Singly Linked List 
 Memory Management - Dynamic Memory Allocation 
 Storage Mechanism - File Handling 
 Programming Approach - Modular Programming 
 Interface - Menu-Driven Console Application 
 Compiler - GCC 

 4. Project Architecture

The application follows a modular design in which each header file is responsible for a specific functionality.

Library-Management-System/
│
├── main.c
│
├── Header Files/
│   ├── add.h
│   ├── mainmenu.h
│   ├── print.h
│   ├── read.h
│   ├── remove.h
│   ├── save.h
│   ├── search.h
│   ├── struct.h
│   └── update.h
│
└── README.md

 Header File Responsibilities

File Name and Functionality 

struct.h - Defines the book structure and linked list node. 
mainmenu.h - Handles menu operations and user navigation. 
add.h - Implements book insertion functionality. 
print.h - Displays stored book records. 
read.h - Retrieves book records from file storage. 
remove.h - Implements book deletion functionality.
save.h - Handles persistent storage of book records. 
search.h - Implements book searching functionality. 
update.h - Modifies existing book information. 

 5. Data Structure Implementation

 Singly Linked List

A Singly Linked List is implemented to maintain book records dynamically.

Each node contains the following fields:

- Book ID
- Book Name
- Author Name
- Next Pointer

Advantages:
- Dynamic memory allocation.
- Efficient insertion and deletion without shifting elements.
- Flexible memory utilization.
- Sequential traversal of book records.

 6. Core Programming Concepts

This project demonstrates practical implementation of the following C programming concepts:

- Structures and User-Defined Data Types
- Pointers and Pointer Manipulation
- Dynamic Memory Allocation (`malloc` and `free`)
- Singly Linked List Operations
- File Handling and Data Persistence
- Modular Programming
- Function Implementation
- Conditional Statements and Looping
- Searching, Insertion, Deletion, and Updating Operations

 7. Compilation and Execution

 Prerequisites
- GCC Compiler
- C Development Environment
- Basic knowledge of C programming

Compile

bash
gcc main.c -o library


Execute

Linux / Ubuntu:
bash
./library


Windows:
bash
library.exe


 8. Learning Outcomes

Developing this project provided practical experience in:

- Implementing dynamic data structures in C.
- Managing memory using pointers and dynamic allocation.
- Designing modular applications using header files.
- Performing linked list operations.
- Implementing file-based data persistence.
- Developing structured, menu-driven applications.
- Understanding the relationship between data structures and real-world software applications.

 9. Future Enhancements

- Book issue and return management.
- Student/member management.
- Book availability tracking.
- Fine calculation for overdue books.
- Improved input validation and error handling.
- User authentication and access control.

 10. Author

 Tamil R

Electronics and Communication Engineering

GitHub:https://github.com/tamilramesh5002



*Developed as a practical implementation of C programming, data structures, dynamic memory management, and file handling.*
