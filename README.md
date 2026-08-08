# 📚 Library Management System

A simple and user-friendly **Library Management System developed using Java**. The application allows users to add, view, search, issue, and return books through a menu-driven console interface.

## 📌 Project Overview

The Library Management System is a beginner-friendly Java project designed to demonstrate **Object-Oriented Programming (OOP)** concepts, collections, loops, conditional statements, and basic library operations.

The system maintains a list of books and tracks whether each book is **available or issued**.

## ✨ Features

* ➕ Add new books
* 📖 View all books
* 🔍 Search books by title
* 📕 Issue books
* 📗 Return books
* 📊 Display book availability status
* 🚫 Prevent issuing an already issued book
* ⚠️ Validate book availability
* 📋 Menu-driven interface
* 🔄 Multiple operations in one session

## 🛠️ Technologies Used

* **Java**
* **OOP (Object-Oriented Programming)**
* **ArrayList**
* **Scanner**
* **Switch Case**
* **Loops**
* **Conditional Statements**

## 📂 Project Structure

```text id="x3n8lk"
library-management-system-java/
│
├── Main.java
├── README.md
└── .gitignore
```

## ⚙️ Requirements

To run this project, you need:

* **Java JDK 8 or later**
* VS Code / IntelliJ IDEA / Eclipse
* Command Prompt or Terminal

## ▶️ How to Run

### 1. Clone the Repository

```bash id="w5k5ro"
git clone https://github.com/yourusername/library-management-system-java.git
```

### 2. Open the Project

Open the project folder in **VS Code**, **IntelliJ IDEA**, or **Eclipse**.

### 3. Compile the Program

Open the terminal inside the project folder:

```bash id="6m8n7p"
javac Main.java
```

### 4. Run the Program

```bash id="h4g2lp"
java Main
```

## 🖥️ Sample Output

```text id="9r7k0q"
=================================
      LIBRARY MANAGEMENT SYSTEM
=================================
1. Add Book
2. View Books
3. Search Book
4. Issue Book
5. Return Book
6. Exit
=================================

Enter your choice: 1

Enter Book ID: 101
Enter Book Title: Java Programming
Enter Author Name: James Gosling

Book added successfully!
```

### 📖 View Books

```text id="h7x3n1"
Enter your choice: 2

========== BOOK LIST ==========
--------------------------------
Book ID     : 101
Title       : Java Programming
Author      : James Gosling
Status      : Available
```

### 📕 Issue Book

```text id="k8c5sd"
Enter your choice: 4

Enter Book ID to issue: 101

Book issued successfully!
```

### 📗 Return Book

```text id="f2m8za"
Enter your choice: 5

Enter Book ID to return: 101

Book returned successfully!
```

## 🔄 Main Operations

| Option | Operation   | Description                         |
| -----: | ----------- | ----------------------------------- |
|      1 | Add Book    | Adds a new book to the library      |
|      2 | View Books  | Displays all books and their status |
|      3 | Search Book | Searches for a book by title        |
|      4 | Issue Book  | Changes book status to issued       |
|      5 | Return Book | Changes book status to available    |
|      6 | Exit        | Closes the application              |

## 📚 Java Concepts Demonstrated

This project demonstrates:

* Classes and Objects
* Constructors
* ArrayList
* Methods
* Variables and data types
* `for` loop
* `do-while` loop
* `switch-case`
* `if-else`
* Scanner for user input
* Boolean values
* Basic data management
* Book issue and return logic

## 🎯 Learning Objective

The main objective of this project is to understand **Java OOP concepts, collections, control statements, user input, and basic management-system development** through a practical library application.

## 🚀 Future Enhancements

The project can be improved by adding:

* 👤 Student/member management
* 🆔 Library member IDs
* 📅 Book issue and return dates
* ⏰ Due-date tracking
* 💰 Fine calculation
* 🗄️ MySQL database integration
* 🔐 Admin login
* 📊 Borrowing history
* 🖥️ GUI using Java Swing or JavaFX
* 🔍 Search by author or book ID
* 📚 Book categories
* 📈 Library statistics

## 🎓 Possible Book Categories

The system can be extended to manage:

* ☕ Java
* 💻 Programming
* 🗄️ Database
* 🌐 Web Development
* 🧠 Data Structures
* 🖥️ Operating Systems
* 🌐 Computer Networks
* 🤖 Artificial Intelligence

## ⚠️ Disclaimer

This project is created **for educational and academic purposes**. It is a basic console-based simulation and is not intended for use as a production library management system.

## 👩‍💻 Author

**Akshaya**

Computer Science & Engineering Student

## 📜 License

This project is created for **educational and academic purposes**.
