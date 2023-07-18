# Blood Bank Management System using SQL

## Introduction
Patients require blood to survive operations, cancer treatments, chronic diseases, and traumatic traumas. This lifesaving care begins with a thoughtful contribution from one individual. The demand for blood is never-ending. The Blood Bank Management System is designed to streamline the process of managing blood donations, tracking donors and recipients, and ensuring efficient blood supply management.

The main benefit of having a database for blood bank administration is the quick and easy retrieval of information. Manual procedures can be eliminated, leading to time savings and improved quality and consistency of information.

## Problem Statement
The Blood Bank Management System aims to address the following challenges:
- Efficient management of blood donations, including donor registration.
- Management of recipients requiring blood.
- Maintaining an adequate blood supply inventory.
- Quick and easy retrieval of information related to donors, recipients, blood types, and donations.

## Components
The Blood Bank Management System consists of the following components:

1. ER Diagram:
   - The ER diagram represents the relationships between different entities in the system.
   - It helps in understanding the structure and relationships of the database.
   - Here's an example ER diagram for the Blood Bank Management System:

   <img width="500" alt="image" src="https://github.com/priyajotgill2003/Bloodbank-Management-System-DBMS-/assets/72308930/d3b861eb-062b-4b5d-9603-8c0fbb180633">


2. Database Tables:
   - The ER diagram is used to create database tables that store the information.
   - Each entity in the diagram corresponds to a table in the database.
   - Here's an example of creating a `donors` table using SQL:

   ```sql
   CREATE TABLE donors (
     donor_id INT PRIMARY KEY,
     donor_name VARCHAR(50),
     blood_type VARCHAR(5),
     contact_number VARCHAR(15)
   );

3. SQL/PLSQL Queries:
   - The Blood Bank Management System supports various queries to retrieve information and perform operations.
   - Here are some example queries:

     <img width="500" alt="image" src="https://github.com/priyajotgill2003/Bloodbank-Management-System-DBMS-/assets/72308930/9ec6b5c8-0bf5-4e45-bb91-e92c3e337da9">

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please feel free to open an issue or submit a pull request.



