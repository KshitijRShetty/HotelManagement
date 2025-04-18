# HotelManagement
This project is a basic Hotel Room and Food Billing System developed using MySQL DBMS and Python. It is designed to run in Python's interactive mode, making it lightweight and easy to understand for beginners.

Key Functionalities:
-Customer Registration:
 Collects and stores guest details, including name, contact, address, and ID information.

-Room Booking:
 Offers different types of rooms and tracks their availability. Updates room status (vacant/occupied) and applies accommodation charges accordingly.

-Food Ordering:
 Allows guests to order meals (breakfast, lunch, snacks, dinner) and calculates total meal cost from predefined menus.

-Billing:
 Calculates and displays the final bill including accommodation, meals, and applicable taxes.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------

Programming Language: Python 3
Database Management System: MySQL 8.0
Database Connector: MySQL Connector/Python
File Handling: Text files for menu display (e.g., breakfast, lunch)

* NOTE *
This project reads menu files (e.g., BREAKFAST.txt, LUNCH.txt, etc.) from a local directory.
Please update the file paths in the code (under the meals function) to match the location of your menu files on your system.
Example:
f = open("C:\\Your\\Path\\To\\BREAKFAST.txt", "r")
