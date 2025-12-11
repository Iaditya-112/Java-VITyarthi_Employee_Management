🎯 Employee Management System

A simple, clean & powerful Java Swing desktop app to manage employees like a pro!

Welcome to my Employee Management System — a full desktop application built with Java Swing + MySQL.
Whether it’s adding new employees, updating their details, or removing old entries, this app handles it all smoothly. ✔️

🚀 Features at a Glance
🔐 Login & Authentication

Simple Swing-based login screen

Credentials stored & verified via MySQL

Prevents unauthorized access (because data safety matters 😎)

➕ Add New Employees

Add name, age, phone, salary, email & department

Auto-generated Employee ID (no need to remember random IDs!)

Validations to avoid messy inputs

Secure database storage

📊 Manage Existing Employees

View everything in a clean table

Search by Employee ID, Name, or Department

Update details anytime

Delete records with a confirmation prompt (no accidental chaos ✌️)

🎨 Modern-ish Swing UI

Built with:

JFrame, JPanel, JButton

JTable for listing employees

JOptionPane for alerts

A neat navigation flow that won’t confuse you

🗄️ Database Handling

MySQL backend connected with JDBC

Uses PreparedStatement → protects against SQL injection

Graceful error handling

💻 Tech Stack
Component	What I Used
Language	Java (JDK 8+)
GUI	Swing / AWT
Database	MySQL
Connector	JDBC
IDE	NetBeans / IntelliJ / Eclipse
Extra Library	rs2xml.jar (convert ResultSet → JTable)
📁 Project Structure
Employee-Management-System/
│── src/
│   └── employee/
│       ├── Login.java
│       ├── AddEmployee.java
│       ├── ViewEmployee.java
│       ├── UpdateEmployee.java
│       ├── RemoveEmployee.java
│       ├── SplashScreen.java
│       └── DatabaseConnection.java
│── lib/
│   ├── mysql-connector.jar
│   └── rs2xml.jar
│── images/
│── database.sql
│── README.md
│── LICENSE

🧑‍💻 How to Run It
1️⃣ Install Required Tools

Java JDK 8 or above

MySQL Server

An IDE (I used NetBeans)

2️⃣ Set Up MySQL
CREATE DATABASE employee_management;
USE employee_management;


Then import the provided database.sql file.

3️⃣ Update JDBC Credentials

Inside DatabaseConnection.java:

String url = "jdbc:mysql://localhost:3306/employee_management";
String user = "root";
String password = "your_password";


Don’t forget to add the MySQL connector JAR to your project libraries!

4️⃣ Run the App

Open project

Clean & build

Run Login.java

That’s it! 🎉

📝 Future Plans (a.k.a. “Things I’d Love to Add Soon”)

Attendance tracking

Payroll integration

Data export to PDF & Excel

Different user roles (Admin / HR / Staff)

Cloud database support
