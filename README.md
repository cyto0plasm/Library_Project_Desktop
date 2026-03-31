# 📚 LMS — Library Management System

A desktop application built with **C++** and **CLI WinForms**, designed to manage library operations including book inventory, student records, and loan tracking.
made it to help a friend out.
---

## 🛠 Tech Stack

![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![CLI](https://img.shields.io/badge/CLI-4D4D4D?style=for-the-badge&logo=windows-terminal&logoColor=white)
![WinForms](https://img.shields.io/badge/WinForms-.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
---

## 🔑 Core Features

- **Library Management** — Manage library books and loaners
- **Book & Inventory** — Add, update, and track books across the system
- **Student Management** — Register and manage student profiles
- **Loan System** — Issue, track, and return book loans with due-date handling

---

## 🏗 Architecture

The project follows the **MVC pattern**, separating concerns across:

- **Models** — Core entities: Libraries, Users, Books, Students, Loans
- **Views** — WinForms-based UI components
- **Controllers** — Business logic layer handling data flow between models and views

---

## 📁 Project Structure

```
LMS/
├── Models/
│   ├── Library
│   ├── User
│   ├── Book
│   ├── Student
│   └── Loan
├── Views/
└── Controllers/
```

---

## 👤 Author

> _Add your name, contact, and LinkedIn here_


this is a library Management System .
its built with .NET Framework v 4.8 ,
using c++ CLR ,
and database Of Sqlite (included as .dll)connected to the file lib.db ,
its built  with the design pattern MVC(Model-View-Controller)->Manual working .

before You try to use this project on your pc you will have to do some refrence to a certain library.
if you dont you wont and cant use the code .
in your project directory there is a folder named lib ->that has 4 files inside for sqlite Library.
you will reftrence this in your project to be able to use sqlite.

after you refrence it you are all set to start cleen-build before running the application .

Good Luck.
