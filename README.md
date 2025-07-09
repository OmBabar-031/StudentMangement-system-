

# Student Management System

A simple **Java Console-based Student Management System** built using **Object-Oriented Programming (OOP)** principles, **JDBC**, and **PostgreSQL**. This project supports basic **CRUD operations** on student records such as adding, viewing, updating, and deleting.

---

 ** Feature 

- Add new student
- View all students
- Update student details
- Delete student record
- Connects to **PostgreSQL** database using **JDBC**
- Menu-driven console interface

---

## 💻 Technologies Used

- **Java (OOP Concepts)**
- **JDBC (Java Database Connectivity)**
- **PostgreSQL Database**
- **Maven (for dependency management)**

---

##  How to Run This Project

###  Prerequisites

- Java JDK (8 or higher)
- PostgreSQL installed and running
- Maven installed
- IDE or terminal
- Java Multithreading
- Java File I/O
  

###  Project Setup

1. Clone the repository:

`bash
git clone https://github.com/ombabar-031/Student Management-Java.
git cd Student Management-Java


2. Configure PostgreSQL

Create a table using the SQL below:


CREATE TABLE students (
    id SERIAL PRIMARY KEY,
    name VARCHAR(100),
    age INT,
    course VARCHAR(100)
);



3. Update database credentials in the DBConnection.java file:

String url = "jdbc:postgresql://localhost:5432/student_db";
String username = "your_username";
String password = "your_password";



4. Compile and run the project using Maven:

mvn compile
mvn exec:java -Dexec.mainClass="Main"


---

📂 Project Structure

Student-Management-System/
│
├── src/
│   ├── DBConnection.java
│   ├── Student.java
│   ├── StudentDAO.java
│   ├── Main.java
│
├── pom.xml
└── README.md



## Author

Om Babar
GitHub: @ombabar-xxxx
Email: ombabar672@gmail.com


---


