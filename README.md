# 📚 City Library Digital Management System  
### Java Programming – Assignment 4

This project implements a **console-based Library Management System** using Java.  
It follows all assignment requirements including **Object-Oriented Programming, File Handling, Collections Framework, Sorting, Searching, and Exception Handling**.

The system allows librarians to add books, register members, issue books, manage returns, and maintain a digital record of library operations.

---

## ⭐ Features

### 🟦 Book Management  
- Add new books  
- Auto-generated Book IDs  
- Track title, author, category, and issue status  
- Store/Load book data from `books.txt`

### 🟩 Member Management  
- Add library members  
- Validate email format  
- Auto-generated Member IDs  
- Store/Load members in `members.txt`

### 🟧 Issue & Return System  
- Issue books to members  
- Prevent double-issuing  
- Maintain a **waiting list queue** for already issued books  
- Auto-assign the book to next member in queue when returned

### 🟥 Searching & Sorting  
- Search books by **Title**, **Author**, or **Category**  
- Sort books by **Title**, **Author**, or **Category**  
  - Uses Comparable & Comparator

### 🟨 Persistent Storage  
All data is saved in files:
