# Hospital Management System

## Developed By  
Md Sumon Hossain (Roll: 1907109)  

---

## Project Overview  
This project is a **Hospital Management System** implemented using SQL. It covers the core database design and management features necessary for handling customers, orders, payments, product categories, and furniture (hospital assets) within a hospital or healthcare-related environment.

The system includes:

- Database schema creation with tables and relationships
- Data Definition Language (DDL) scripts
- Data Manipulation Language (DML) scripts for inserting, updating, searching, and deleting data
- Payment and order processing logic
- Category and inventory management

---

## Table Structure Summary

| Table Name      | Description                                  |
|-----------------|----------------------------------------------|
| `customer`      | Stores patient/customer personal details     |
| `customer_order`| Records orders placed by customers            |
| `payment`       | Payment details linked to customers and orders|
| `category`      | Product or asset categories                    |
| `furniture`     | Hospital furniture and assets                  |
| `order_details` | Items linked to each order                      |

---

## Features

- Enforced relational integrity with foreign keys and cascade deletes
- Constraints on numeric fields (e.g., amount and price limits)
- Sample scripts for creating tables and performing CRUD operations
- Example queries to retrieve and manage data

---

## Usage

1. **Database Setup**  
   Execute the provided SQL scripts in order to create the tables and populate the database with initial data.

2. **Scripts Included**  
   - `1.DDL.sql`: Table creation scripts  
   - `2.DMLinsertvalues.sql`: Insert data into tables  
   - `3.DMLSearchupdatedelete.sql`: Search, update, and delete queries  
   - `4.DMLAll.sql`: Combined data manipulation queries  
   - `5.DMLjoinandview.sql`: Join queries and view creation  
   - Other supporting SQL scripts (`lab9.sql`, `plsql.sql`, `tigger.sql`)

3. **How to Run**  
   Use your SQL environment or client (such as Oracle SQL Developer, MySQL Workbench, or others) to run these scripts sequentially.

---

## Technologies Used

- SQL (Oracle/MySQL syntax adaptable)
- Relational database design principles
- Constraints and indexing

---

## Future Improvements

- Integrate front-end application for easier interaction
- Implement user authentication and role management
- Add reporting and analytics features
- Move to a hybrid blockchain for security enhancement (planned)

---

## License

This project is for educational purposes and developed by Md Sumon Hossain.

---

## Contact

For any queries or contributions, please contact:  
Md Sumon Hossain  
Email: (mdsumonhossainsumon429848@gmail.com)  
GitHub: [https://github.com/Sumon-59](https://github.com/Sumon-59)

---

Thank you for visiting!

