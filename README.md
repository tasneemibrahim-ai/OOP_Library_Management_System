# 📚 Library Management System

A **Java Swing** desktop application built with **Object-Oriented Programming (OOP)** principles
to automate and simplify day-to-day library operations.

## 🛠️ Tech Stack
| Layer | Technology |
|-------|-----------|
| Language | Java |
| GUI Framework | Java Swing (AWT) |
| Database | MySQL (via WAMP Server) |
| IDE | NetBeans IDE |
| DB Driver | MySQL JDBC Connector |

## ✨ Features
- 🔐 **User Authentication** — Secure Login, Sign Up & Forgot Password flows
- 📖 **Book Management** — Add, view, and manage book records
- 🎓 **Student Management** — Add, update, and remove student records
- 📤 **Issue Book** — Issue books to students with date tracking
- 📥 **Return Book** — Process book returns and calculate fines
- 📊 **Statistics Dashboard** — View library usage and inventory stats
- 🗂️ **Record Viewer** — Browse full book and student detail tables

## 🗃️ Project Structure
├── code/Library-Management-System/src/
  ├── LibraryManagementSystem.java/ # Entry point
  ├── Login_user.java # Authentication
  ├── Signup.java / Forgot.java # Registration & recovery
  ├── Home.java # Main dashboard
  ├── AddBook.java / BookDetails.java
  ├── AddStudent.java / StudentDetails.java
  ├── IssueBook.java / ReturnBook.java
  ├── Statistics.java
  └── conn.java # MySQL DB connection
├── Diagrams/ # UML / system diagrams
└── Documentation/ # Project docs & reports

## ⚙️ Setup & Run
1. Install **NetBeans IDE** and **WAMP Server**
2. Start WAMP and import the `project2` MySQL database
3. Open the project in NetBeans and build it (`build.xml`)
4. Run `LibraryManagementSystem.java`
