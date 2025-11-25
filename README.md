Food Order Management System
A Java-based console application for managing restaurant food orders with complete CRUD operations and file-based data persistence.

Features
Order Management: Create, read, update, and delete food orders

Menu System: Interactive console-based interface

Data Persistence: Automatic file-based storage of orders

Input Validation: Robust error handling and user input validation

Order Tracking: Comprehensive order history management

Technologies Used
Java SE 8+

Object-Oriented Programming

File I/O Operations

Collections Framework

Exception Handling

Project Structure
text
food_order/
├── FoodOrder.java           # Food order entity class
├── FoodOrderManagement.java # Main application controller
└── README.md               # Project documentation
Installation
Clone the repository

bash
git clone https://github.com/DAKSH2305/vityarthi_project_java.git
cd vityarthi_project_java/food_order
Compile the Java files

bash
javac *.java
Run the application

bash
java FoodOrderManagement
Usage
After starting the application, you'll see a menu with the following options:

View all orders

Add new order

Update existing order

Delete order

Search orders

Exit system

Follow the on-screen prompts to manage food orders. All data is automatically saved to a file for persistence.

Class Overview
FoodOrder.java
Represents a food order with properties like order ID, customer name, items, and total amount. Includes constructors, getters/setters, and utility methods.

FoodOrderManagement.java
Main application class that handles:

User interface and menu navigation

Order CRUD operations

File I/O for data persistence

Input validation and error handling

Development
This project demonstrates:

Object-oriented design principles

File handling and data persistence

Collection management with ArrayList

Console-based user interfaces

Comprehensive exception handling

Contributing
Contributions are welcome! Please feel free to submit pull requests or open issues for any improvements.
Output :


![fo1](https://user-images.githubusercontent.com/106819662/196504053-5261a2ae-476b-4302-9c6a-c2adeb213858.png)


![fo2](https://user-images.githubusercontent.com/106819662/196504087-dd9a5a73-ed2e-4e79-b2af-1ab86967a601.png)
