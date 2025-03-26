Library Management System - Structured Programming in C++

Overview
This C++ library management system implements structured programming concepts to manage book inventory and student borrowing processes. The system features separate login portals for students and administrators with distinct functionalities for each user type.


Key Features:

User Authentication

Dual login system (Student & Admin)

Password protection for admin access

Student registration for new users

Password change functionality


Student Functions:

View available books list

Search for books by various criteria

Borrow and return books

View currently borrowed books

Edit personal information


Admin Functions:

Add new books to inventory

Remove books from system

Modify book details (title, author, category, etc.)

Manage student accounts


Data Management:

Uses structs for data organization: Student: ID, name, borrowed books, Book: Code, title, category, author, edition, availability status

File I/O operations for data persistence

Array-based storage system


Technical Implementation:

Pure C++ using structured programming paradigm

No object-oriented features (classes/inheritance)

Modular functions for each operation

Menu-driven console interface

Standard libraries: <iostream>, <fstream>, <string>, <string>


Program Flow:

Login screen (Student/Admin selection)

Authentication (existing user login or new registration)

Role-specific menu options

Data processing based on user selection

File updates upon changes


Future Enhancements:

Basic GUI implementation (using console graphics)

Overdue book tracking

Book reservation system

Enhanced search filters

Reporting features for admins


How to Use:

Compile: g++ library_system.cpp -o library

Run: ./library

Follow on-screen instructions

Note: This project demonstrates structured programming concepts using C++ without OOP features, as per academic requirements.
