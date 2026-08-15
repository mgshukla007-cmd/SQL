__MySQL__ : 
- It is an open source relational database that uses structured query language to interact with databases.
- It stores data in form of table and can be modified using SQL.

__Q. Why MySQL?__
- Easy to use
- Cost effective
- Secured
- Platform friendly

  __SQL__ -( `Structured Query Language`) - is programming language designed for retrieval and management of data in a relational database.
  All relational database management systems RDBMS like MySQL use this language for interaction.

  __What SQL does?__
  - Creates new database and tables
  - Executes queries against a database
  - used to retrieve, insert and update records into a database
  - SQL used to create stored procedures and views in a database
  - can also set permissions on `tables`, `procedures` and `views`.(Database objects)
 
    'Data'--defined as--> 'Table' --defined as--> 'Database'
 
    __SQL Commands__
-:Types of SQL commands:-
1. DDL (Data Definition Language)
    - Create
      Used to create a database or a table
    - Alter
      Used to modify, rename, delete(or drop), add a **column**
    - Drop
      Used to drop (delete) a table or a database.
    - Truncate
      Used to delete each record in a table. The deleted data will not come back. Just the structure of table will remain.(Names of Columns)
    - Rename
      Can rename the name of a table or a database.
2. DML (Data Manipulation Language)
    - Select
      Used to select records from the table or based on condition
    - Insert
      Used to add a record in a table
    - Update
      To update(change) any record in a table or from the table.
    - Delete
      Used to delete a record from the table on any specific condition or on any given condition.

DML made any change can be reverted back or simply undo works here or Rollback is possible.
      
3. DCL (Data Control Language)
    - Grant
      Used to give access or permission.
    - Revoke
      To take back the access or to restrict.
4. TCL (Transaction Control Language)
    - Commit
      2 options : ON - can not undo if used (applicable even for DML)
                  OFF - can undo if this is used
    - Rollback
      Undo.
    - Save Point
      We need to give saveprint points time to time
      Using this we can work on any single saveprint point
      Eg. From 1,2 and 3, if we want to undo only 2, we can rollback it without letting anything else get disturbed.

---
---

# MySQL Workbench
SQL in Laptop

- double hyphen (`--`) to write a comment (just like `#` in Python).
- Semicolon (`;`) to be written after each command.
- semi colon (`;`) denotes completion of a command
- `Ctrl` + `Enter` to __execute a command__ (Just like `Shift` + `Enter` in Python)

__MySql Worlbench__: It is graphical tool developed  by `Oracle`, which is used to work with `MySQL server` and `Databases`.
   - MySQL  provides `Data Modeling`, `SQL Development`, `Various administrations tools` for configration.
## 1.__DDL__: (Data)


  
