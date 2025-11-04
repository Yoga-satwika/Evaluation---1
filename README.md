# Evaluation---1

# SQL

# DDL (Data Definition Language)
  
  DDL is used to define and manage database structures — such as tables, indexes, and schemas.

# Main DDL Commands 

  CREAT - Creates new database objects (like tables, views, or indexes). 

  Example:-  
             
          CREATE TABLE Students (ID INT, Name VARCHAR(50));

  ALTER - Modifies the structure of an existing table (add, delete, or change columns).

  Example:- 

          ALTER TABLE Students ADD Email VARCHAR(100);

  DROP - Deletes an entire database object permanently.

  Example:- 

           DROP TABLE Students;

 TRUNCATE - Deletes all records from a table but keeps the table structure.

 Example:- 

          TRUNCATE TABLE Students;

 RENAME - Changes the name of a database object.

 Example:- 

         RENAME TABLE Students TO Learners;

* DDL commands are auto-committed, meaning changes are permanent once executed.

* They cannot be rolled back (undone).

* DDL affects the structure, not just the data.


  
