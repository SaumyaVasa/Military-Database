# Military Database

## Project Overview

This project is a comprehensive database system designed for military operations and personnel management. It was developed as part of the IT-214 Database Management Systems course.

Our goal was to create a realistic, efficient, and well-structured database that captures various aspects of military information, such as personnel records, equipment, operations, wars fought, awards, and current statuses. The project also includes a Java console application for interacting with the database, ensuring flexible and user-friendly access.

---

## Features

- **Realistic Data Modeling:** 
  - Real military equipment, historical wars, awards, and personnel details.
- **Normalization:**
  - Properly normalized schema to eliminate redundancy and ensure data integrity.
- **User Interaction:**
  - Java console application for authorized users to perform operations on the database.
- **Random Data Generation:**
  - Python scripts used for populating large datasets with realistic random values.
- **Detailed Documentation:**
  - Complete documentation of schema, tables, relationships, and constraints.

---

## Technical Challenges & Solutions

- **Cyclic Foreign Key Constraints:**
  - Resolved by restructuring the schema and using SQL `ALTER` commands.
- **Connection Limits:**
  - Encountered issues with connection limits during user account sharing; solved by duplicating the database and adjusting connection settings.
- **Iterative Design:**
  - Multiple revisions of ER diagrams and schema to eliminate anomalies and redundancies.

---

## Tools & Technologies

- **Database Management System:** PostgreSQL
- **Programming Languages:** Java, Python
- **Development Tools:** pgAdmin, SQL, Java IDEs
- **Documentation:** Detailed written reports and ER diagrams

---

## How to Run

### Requirements

- PostgreSQL installed and running
- Java Development Kit (JDK)
- Python (optional, for data generation scripts)

### Steps

1. **Database Setup**
    - Create the database in PostgreSQL.
    - Run SQL scripts (provided in the repo) to create tables, relationships, and constraints.

2. **Data Population**
    - Execute Python scripts (if included) to generate random data.
    - Alternatively, manually insert real data as provided in documentation.

3. **Java Console Application**
    - Compile the Java application.
    - Configure database connection details (username, password, DB URL) in the code or a configuration file.
    - Run the console app to interact with the database.

---

## Learnings

- Importance of data integrity and constraint management
- Real-world considerations in designing user-centric databases
- Technical skills in handling cyclic foreign key problems
- Practical experience integrating Java applications with a PostgreSQL backend
- Efficient techniques for generating large datasets using Python

---

## Authors

This project was collaboratively developed as part of the IT-214 Database Management Systems course.

---

## License

[Specify your license here, e.g., MIT, GPL, etc.]

