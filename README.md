* Online Library Management System (C++)

* Introduction
This project is an "Online Library Management System" implemented using **Object-Oriented Programming (OOP) in C++**.  
The system models real-world entities such as "Book" and "User", with core operations like borrowing, returning, and tracking books.  

The purpose of this project is to demonstrate "encapsulation, abstraction, and modular class design" in C++.

---

*  System Design

* 1. Book Class
- "Data Members"
  - `id` → unique book identifier  
  - `title` → book title  
  - `author` → author name  
  - `isAvailable` → true if book is available, false otherwise  
- "Member Functions"
  - `borrowBook()` → mark book as borrowed  
  - `returnBook()` → mark book as returned  
  - Getters for `id`, `title`, and `author`

* 2. User Class
- "Data Members"
  - `userId` → unique user identifier  
  - `name` → user’s name  
  - `borrowedBooks` → list of borrowed book IDs  
- "Member Functions"
  - `borrowBook(int bookId)` → add a borrowed book  
  - `returnBook(int bookId)` → return a borrowed book  
  - `viewBorrowedBooks()` → display all borrowed books  

---
*  Features
- Add new books to the system  
- Borrow and return books  
- Prevent borrowing unavailable books  
- Track borrowed books per user  
- Display a user’s borrowed books  

---
*  Test Cases
*Positive
- Borrow a book that is available  
- Return a book that was borrowed  
- View borrowed books list  

* Negative
- Borrow a book that is already borrowed  
- Return a book that was never borrowed  
- Search for a non-existent book  

---


