# C-Student-Record_system
Student Record Management System (C Program)

This is a simple Student Record Management System written in C. It allows users to add, view, update, search, and delete student records stored in text files.
The system supports three types of users:

Admin – Full access (Add, Display, Search, Update, Delete)

Staff – Limited access (Add, Display, Search, Update)

Guest – View only (Display, Search)

✨ Features
✔ Login System

Username & password verification from credentials.txt

Automatically loads role: admin / staff / guest

✔ Student Management

Add new student (Roll No, Name, Marks)

Display all students

Search student by roll number

Update student details

Delete student record

✔ File Handling

Students are stored in:
students.txt
Credentials are stored in:
credentials.txt

 File Structure
project-folder/
│
├── main.c              # Source code
├── students.txt        # Student records (auto-created)
├── credentials.txt     # Login credentials file
└── README.md           # Project documentation

Sample Credentials

Add this inside credentials.txt:

admin admin123 admin
staff staff123 staff
guest guest123 guest

🛠 How to Run
Using GCC
gcc main.c -o srms
./srms

 Technologies Used

C Language

File Handling

Conditional Statements

Loops & Functions
Purpose

This project is ideal for:

College mini-projects

Understanding file handling in C

Learning role-based access systems

Practicing real-world C applications
