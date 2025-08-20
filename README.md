🚆 Railway Management System

📌 Overview

The Railway Management System is a desktop-based application developed using Java Swing for the frontend and MySQL for the backend database.
This project is designed to help railway authorities and passengers manage train schedules, bookings, and related information efficiently.

🎯 Features
	•	👤 User Management – Register, log in, and manage passenger details
	•	🚉 Train Management – Add, update, or delete train information
	•	📅 Schedule Management – Manage train timings and routes
	•	🎟 Ticket Booking & Cancellation – Book tickets, generate booking IDs, and cancel if needed
	•	🔍 Search & View – Search trains by source, destination, and date
	•	📊 Admin Panel – Manage users, trains, and overall system

🛠️ Tools & Technologies
	•	Frontend: Java Swing (GUI)
	•	Backend Database: MySQL
	•	Connector: JDBC (Java Database Connectivity)
	•	IDE: NetBeans / IntelliJ IDEA / Eclipse

⚙️ Installation & Setup
	1.	Clone the Repository

git clone https://github.com/yourusername/railway-management-system.git
cd railway-management-system


	2.	Database Setup (MySQL)
	•	Install MySQL and create a new database (e.g., railway_db).
	•	Import the provided SQL script:

mysql -u root -p railway_db < railway_db.sql


	3.	Configure Database Connection in Java
	•	Update the DBConnection.java file with your MySQL username and password:

String url = "jdbc:mysql://localhost:3306/railway_db";
String user = "root";
String password = "your_password";


	4.	Run the Application
	•	Open the project in your IDE.
	•	Compile and run the Main.java file.

