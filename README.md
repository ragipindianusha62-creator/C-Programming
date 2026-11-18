Library Records & Borrowing Management System in C

Project Overview

The Library Records & Borrowing Management System is a console-based mini project developed using the C programming language. It helps manage library book records and borrowing activities efficiently.

The system allows users to add books, display book details, search for books, borrow books, and return borrowed books.

Objectives

- To maintain library book records.
- To simplify book searching.
- To manage book borrowing and returning.
- To store book information permanently using file handling.
- To understand structures, functions, and file operations in C.

Features

1. Add Book – Add new books with ID, title, and author name.
2. Display Books – View all available and borrowed books.
3. Search Book – Search for a book using its ID.
4. Borrow Book – Borrow an available book by entering the student name.
5. Return Book – Return a borrowed book and update its status.
6. Exit – Close the application.

Technologies Used

- Programming Language: C
- Compiler: GCC
- Operating System: Linux
- File Handling: Binary File Handling

C Concepts Used

- Structures ("struct")
- Functions
- Arrays and Strings
- Pointers
- Conditional Statements
- Loops
- File Handling ("fopen", "fread", "fwrite", "fseek", "fclose")

Project Structure

Library-Management-System/
│
├── library.c
├── library.dat
└── README.md

"library.dat" is created automatically when the first book is added.

How to Compile and Run

Step 1: Clone the Repository

git clone YOUR_GITHUB_REPOSITORY_URL

Step 2: Open the Project Directory

cd Library-Management-System

Step 3: Compile the Program

gcc library.c -o library

Step 4: Run the Program

./library

Sample Output

===== LIBRARY MANAGEMENT SYSTEM =====
1. Add Book
2. Display Books
3. Search Book
4. Borrow Book
5. Return Book
6. Exit

Enter your choice: 1
Enter Book ID: 101
Enter Book Title: C Programming
Enter Author Name: Dennis Ritchie

Book added successfully!

Advantages

- Easy to use.
- Reduces manual record maintenance.
- Provides quick book searching.
- Prevents duplicate book IDs.
- Saves records using file handling.

Future Enhancements

- Student registration and login.
- Borrowing history.
- Book return due dates.
- Late-return fine calculation.
- Admin login system.

Conclusion

The Library Records & Borrowing Management System provides a simple way to manage library records using C programming. This project demonstrates practical implementation of structures, functions, and file handling.

Author

Anusha
