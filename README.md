# 📦 E-Commerce Database Project (MySQL)
This project is a fully designed E-Commerce Database System created using MySQL.
It focuses on clean database design, proper relationships, realistic sample data, and a normalized structure similar to real-world e-commerce systems.

# 🚀 Features
✔️ Complete MySQL Database
A structured and optimized database including:<br>
    • CUSTOMERS <br>
    
    • CATEGORY <br>
    
    • PRODUCT <br>
    
    • ORDERS <br>
    
    • ORDER_ITEMS <br> 

# ✔️ Realistic Sample Data
All tables include well-planned sample entries that simulate an actual e-commerce environment.

# ✔️ Proper Relationships & Constraints
    • Foreign keys applied
    • Enum used for order status
    • Data types chosen thoughtfully
    • Normalized schema (Order → Order Items)

# ✔️ Clean & Professional File Structure
    Includes separate files for:
    • Database schema
    • Insert statements
    • Queries performed for analysis

# 📁 Project Structure
/Ecommerce-Database-Project
│
├── ecommerce_schema.sql      # Database creation + sample data inserts
├── ecommerce_queries.sql     # All SQL queries performed (not in README)
└── README.md                 # Documentation

# 🧱 Database Schema Overview
# 🔹 CUSTOMERS
    Stores customer information such as:
    • ID
    • Name
    • City
    • Registration date

#🔹 CATEGORY
    Contains product categories like:
    • Electronics
    • Grocery
    • Home Appliances
    • Clothes

#🔹 PRODUCT
    Stores product details:
    • Name
    • Category (linked via FK)
    • Price
    • Stock

#🔹 ORDERS
    Stores customer order details:
    • Order date
    • Customer ID
    • Status (Completed / Incomplete)

#🔹 ORDER_ITEMS (Normalized)
    Stores items inside each order:
    • Product
    • Quantity
    • Unit price

This normalization allows:
    • Multiple products per order
    • Quantity & price tracking
    • Proper invoice calculation

# 💡 Key Highlights of This Project
🔹 Proper use of Primary Keys & Foreign Keys
🔹 Clean normalization to 3NF
🔹 Realistic sample data representing real e-commerce scenarios
🔹 Easy to run and understand
🔹 Ideal for:
    • Academic submissions
    • MySQL portfolio projects
    • Internship / job demonstration
    • Data analyst practice

# 🧑‍💻 How to Run the Project
    1.	Install MySQL Server

    2.	Open MySQL Workbench / Command Line

    3.	Run the schema file:
    SOURCE ecommerce_schema.sql;

    4.	To run all queries (optional):
    SOURCE ecommerce_queries.sql;

# 📚 Learning Outcomes
By exploring this project, you demonstrate understanding of:
    •	Database design
    •	SQL schema creation
    •	Foreign key relationships
    •	Normalization concepts
    •	Data types and constraints
    •	Real-world e-commerce data modeling
This is highly valuable for Data Analyst, Database Developer, and Software Engineering interviews.

# 👨‍💻 Author
![banner](banner.jpg)

Mahesh Kshirsagar
📧 maheshkshirsagar510@gmail.com


