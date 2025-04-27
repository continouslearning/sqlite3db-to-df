# Create & Access SQLite Database Using Python

![cognitiveclass.ai logo](https://cognitiveclass.ai/images/logo.png)

**Estimated Time Needed:** 15 minutes

---

## Objectives
After completing this lab, you will be able to:
- Create a database
- Create a table
- Insert data into the table
- Query data from the table
- Retrieve the result set into a pandas DataFrame
- Close the database connection

---

## Introduction
**SQLite** is a lightweight, serverless, self-contained SQL database engine. It is widely used for applications that require simple, fast, and local data storage.

---

## Tasks Overview

### Task 1: Create a Database
- Install and import the `sqlite3` library.
- Establish a connection to a new SQLite database named `INSTRUCTOR.db`.
- Create a cursor object to execute SQL commands.

### Task 2: Create a Table
- Drop the `INSTRUCTOR` table if it already exists (to avoid duplication).
- Create a new table named `INSTRUCTOR` with fields:
  - ID (Primary Key)
  - First Name (FNAME)
  - Last Name (LNAME)
  - City (CITY)
  - Country Code (CCODE)

### Task 3: Insert Data into the Table
- Insert individual records into the `INSTRUCTOR` table.
- Use a multi-row insert command to add multiple entries at once.

### Task 4: Query Data from the Table
- Retrieve and display all data from the table.
- Fetch and display a limited number of rows.
- Query and display only specific columns (e.g., first names).
- Perform an update operation to modify an instructor's city.

### Task 5: Retrieve Data into Pandas
- Use the Pandas library to fetch the table content into a DataFrame.
- Perform basic DataFrame operations like viewing data and checking shape.

### Task 6: Close the Database Connection
- Properly close the SQLite connection to free up resources.

---

## Summary
In this exercise, you:
- Created and connected to an SQLite database.
- Created a table, inserted, and queried data.
- Retrieved data into a pandas DataFrame for further manipulation.
- Ensured good practices by closing the database connection after operations.

---