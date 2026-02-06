# Internship-Task13

# 🗄️ Java Developer Internship – Task 13  
## JDBC – Java Database Connectivity with MySQL


## 📌 Task Objective
The objective of this task is to demonstrate **Java Database Connectivity (JDBC)** by connecting a Java application to a **MySQL database** and performing **CRUD operations** using `PreparedStatement`.


## 🛠 Tools Used
- **Language:** Java  
- **IDE:** IntelliJ IDEA / Eclipse  
- **Database:** MySQL (Free)  
- **API:** JDBC  
- **Driver:** MySQL Connector/J  
- **JDK Version:** Java 17 / Java 21  


## 📂 Project Structure
Java-Internship-Task-13
│
├── src
│ └── JdbcDemo.java
│
└── README.md



## 🧩 Features Implemented
- Connected Java application to **MySQL database**
- Loaded JDBC driver and established connection
- Performed **CRUD operations**:
  - Create (INSERT)
  - Read (SELECT)
  - Update (UPDATE)
  - Delete (DELETE)
- Used **PreparedStatement** to prevent SQL Injection
- Retrieved records using **ResultSet**
- Handled database exceptions gracefully
- Closed database connection properly


## ▶️ How to Run the Program
1. Create database and table in MySQL
2. Add MySQL JDBC driver to the project
3. Run the Java program

       ```bash
       javac JdbcDemo.java
       java JdbcDemo
   
## 💻 Sample Console Output

Database connected successfully.

Record inserted.

--- Student Records ---

1 | Akshu | akshu@gmail.com | 90

Record updated.

Record deleted.

Database connection closed.

## 🧠 Key JDBC Concepts Demonstrated

🔹 What is JDBC?

JDBC is an API that allows Java applications to connect and interact with databases.

🔹 Statement vs PreparedStatement

PreparedStatement is faster and more secure as it prevents SQL Injection.

🔹 SQL Injection

A security vulnerability where malicious SQL code is injected through user input.

🔹 Why Connection Pooling?

Improves performance by reusing database connections.

## 🎯 Learning Outcomes

Learned how to connect Java with a relational database

Performed CRUD operations using JDBC

Understood the importance of PreparedStatement

Gained hands-on experience with database exception handling

Improved understanding of backend data persistence
