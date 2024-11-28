# Database Project: Car Dealership Management System

This project provides a comprehensive database schema and SQL scripts for a **Car Dealership Management System**. The database is designed to manage various aspects of vehicle sales, including vehicle details, transactions, payments, and employee management.

---

## Features

### 1. **Complex Schema**
- Includes multiple tables with relationships, constraints, and sequences to ensure data integrity and consistency.

### 2. **Data Manipulation**
- SQL scripts for performing operations such as inserts, updates, and deletes.

### 3. **Advanced SQL Techniques**
- Demonstrates the use of:
  - Subqueries (both synchronized and unsynchronized)
  - Grouping and aggregation functions
  - String functions
  - Date functions
  - `CASE` expressions
  - Common Table Expressions (CTEs) using the `WITH` clause
  - Functions like `NVL` and `DECODE`

---

## Database Schema

The database schema consists of the following tables:

- **MOTOR**: Stores information about different types of motors.
- **CARBURANT**: Stores information about different types of fuel.
- **MOTOR_CARBURANT**: Associates motors with their respective fuel types.
- **MOTOR_ELECTRIC**: Stores information about electric motors.
- **CAROSERIE**: Stores information about different types of car bodies.
- **ADRESA**: Stores addresses for showrooms.
- **SHOWROOM**: Stores information about different showrooms.
- **SHOWROOM_NUMERE_TELEFON**: Stores phone numbers for showrooms.
- **VEHICUL**: Stores information about vehicles.
- **ANGAJAT_SHOWROOM**: Stores information about showroom employees.
- **MECANIC**: Stores information about mechanics.
- **VANZATOR**: Stores information about salespersons.
- **CLIENT**: Stores information about clients.
- **CLIENT_NUMERE_TELEFON**: Stores phone numbers for clients.
- **VEHICUL_DETINUT_CLIENT**: Stores information about vehicles owned by clients.
- **PLATA**: Stores information about payments.
- **TRANZACTIE**: Stores information about transactions.
- **SERVICE**: Stores information about services performed on vehicles.

---

## SQL Scripts

The project includes the following types of SQL scripts:

1. **Table Creation**
   - Scripts to create tables with appropriate constraints and relationships.
2. **Data Insertion**
   - Scripts to insert sample data into the tables.
3. **Data Manipulation**
   - Scripts to update and delete data based on specific conditions.
4. **Complex Queries**
   - Examples of advanced SQL queries demonstrating:
     - Subqueries
     - Grouping, aggregation, and functions
     - `CASE`, `NVL`, `DECODE`
     - Common Table Expressions (CTEs)

---

## Documentation

Refer to the **142_Opran_Andrei-proiect.docx** file for a detailed description of the database. The document serves as a comprehensive manual covering the following aspects:
- Database design
- Usage guidelines
- Examples of queries and use cases

---

## Diagram

![diagrama coloane datagrip](https://github.com/AndreiFishe/Proiect-BD/assets/116067445/e7767df0-f614-4345-9bbc-cfe9b28582c8)

This diagram provides a visual representation of the database schema, showing the relationships between different tables.

---

## Getting Started

Follow these steps to set up and explore the database:

1. **Set Up the Database**
   - Run the table creation scripts to establish the database schema.
2. **Insert Sample Data**
   - Populate the tables with sample data using the provided scripts.
3. **Explore the Queries**
   - Use the provided SQL queries to analyze and manipulate the data.

---

## Conclusion

This project showcases a **robust and well-designed database** for managing Car Dealerships. It highlights the use of advanced SQL techniques and provides a solid foundation for further development and customization.

For more details, refer to the comprehensive manual provided in the project documentation.


