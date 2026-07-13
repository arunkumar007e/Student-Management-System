# Student Management System

A lightweight, console-based Student Management System built using **Java** and **MySQL**. This application allows users to manage student records efficiently by performing core CRUD operations, along with advanced sorting and searching functionalities.

---

## 🚀 Features

* **Add New Student:** Insert new student records into the database.
* **View Student Data:** Display a complete list of all registered students.
* **Update Student Data:** Modify existing details of a student using their unique ID.
* **Delete Student Data:** Remove student records from the system.
* **Search Students:** Quick lookup for specific student profiles.
* **Advanced Sorting:** Sort student records dynamically by:
    * Major
    * Last Name
    * First Name

---

## 📊 Database Schema

The application interacts with a MySQL table containing the following fields:

| Column Name | Data Type | Description |
| :--- | :--- | :--- |
| `Student_ID` | INT (Primary Key) | The unique identifier for each student |
| `first_name` | VARCHAR | The first name of the student |
| `last_name` | VARCHAR | The last name of the student |
| `major` | VARCHAR | The student's academic major |
| `Phone` | VARCHAR | The contact phone number |
| `GPA` | DOUBLE/DECIMAL | The Grade Point Average of the student |
| `DOB` | DATE | The student's Date of Birth |

---

## 🛠️ Requirements

Before running the project, ensure you have the following installed:
* **Java Development Kit (JDK):** Version 8 or higher
* **MySQL Server:** Version 5.7 or higher
* **MySQL Connector/J:** Java Database Connectivity (JDBC) driver
* A Java IDE (like IntelliJ IDEA, Eclipse, or VS Code) or a command-line build tool.

---

## ⚙️ Installation & Setup

### 1. Clone the Repository
```bash
git clone [https://github.com/your_username/student-management-system.git](https://github.com/your_username/student-management-system.git)
cd student-management-system
