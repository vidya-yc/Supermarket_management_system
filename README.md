Supermarket Management System (Mini Project - Java + MySQL)

A functional and user-friendly Supermarket Management System developed using Java and MySQL as a mini project. It helps automate essential operations such as product inventory, billing, and customer management.

🎯 Project Objective

To create a simple and efficient supermarket system that handles:

Inventory management

Billing and receipt generation

Customer purchase tracking

Product and sales database integration

📄 Key Features

💳 Billing Module: Calculates total price, applies discounts, and generates final bill

📦 Inventory Control: Add, update, and delete product records

👥 Customer Tracking: Manage customer data and purchase history

🔄 Database Integration: Real-time interaction with MySQL database

📅 Sales Reports: Generate simple sales summaries (if implemented)

⚙️ Tech Stack

Programming Language: Java

Database: MySQL

Tools Used: Eclipse / IntelliJ IDEA / NetBeans (replace based on your IDE)

Database Connector: JDBC (Java Database Connectivity)

🚀 How to Run

Clone the repository:

git clone https://github.com/yourusername/supermarket-management-java.git

Open the project in your preferred Java IDE.

Import the MySQL database from the provided .sql file.

Update the database connection details in the code:

String url = "jdbc:mysql://localhost:3306/supermarket";
String username = "root";
String password = "your_password";

Run the Main.java file.

📊 Database Structure

Products Table: Product ID, Name, Quantity, Price

Customers Table: Customer ID, Name, Contact Info

Transactions Table: Transaction ID, Customer ID, Product ID, Quantity, Total Price
