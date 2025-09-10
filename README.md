Student Management System
Project Description

Student Management System is a desktop application to manage students’ information, including subjects and grades. Built with Tkinter and SQLite, it displays student data in a TreeView table, allowing easy adding, editing, and deleting of records. Ideal for teachers or small schools to manage student data efficiently.

Features

Add new students with complete details (name, ID, subjects, grades)

View all students and their grades in a TreeView table

Edit and delete student records

Data stored securely in SQLite

Simple and user-friendly interface with Tkinter

Installation
Prerequisites

Python 3.x

Required modules:

pip install tk
pip install pillow

Steps

Clone the repository:

git clone <your-repo-link>
cd StudentManagementSystem


Run the application:

python main.py

Project Structure
StudentManagementSystem/
│
├─ main.py           # Main execution file
├─ database.db       # SQLite database file
├─ ui.py             # User interface components
├─ models.py         # Classes and database management
└─ README.md         # Project description and instructions

Usage

Launch the program (python main.py)

Add new students via the input form

View students’ information in the TreeView table

Select a record to edit or delete

Future Enhancements

Search and filter students by name, ID, or grade

Add progress charts for visual tracking

Export data to Excel or PDF

Multi-user login and management
