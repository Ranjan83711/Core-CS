# DBMS & SQL: Practice MCQs (200 questions)

**Bihar STET Paper 2 (Computer Science)**

There are 10 topics with 20 questions each. The answer is shown right under each question, so you can revise in one read. Target: 17/20 or better.

SQL topics E, F, G and J carry the most marks in recent papers, so do these first.

---

## A. DBMS Basics & Architecture

**1.** A DBMS is:
(A) software that stores, modifies and retrieves data  (B) a programming language  (C) a collection of queries  (D) a piece of hardware

✅ **Ans: (A) software that stores, modifies and retrieves data** — (PYQ 2023, 2025)

**2.** DBA stands for:
(A) Data Bank Administrator  (B) Database Administrator  (C) Data Administrator  (D) Database Analyst

✅ **Ans: (B) Database Administrator** — (PYQ 2025)

**3.** Which of these is a **disadvantage** of a DBMS?
(A) Reduced redundancy  (B) Data consistency  (C) Data security  (D) Higher cost and complexity

✅ **Ans: (D) Higher cost and complexity**

**4.** What are the three levels of data abstraction?
(A) physical, network, view  (B) file, record, field  (C) physical, logical (conceptual), view (external)  (D) none of these

✅ **Ans: (C) physical, logical (conceptual), view (external)**

**5.** Which level describes how the data is actually stored?
(A) View  (B) Logical  (C) Physical  (D) Conceptual

✅ **Ans: (C) Physical** — (PYQ 2025, asked twice)

**6.** Which level describes *what* data is stored and how the data items are related?
(A) Physical  (B) Logical/Conceptual  (C) View  (D) Internal

✅ **Ans: (B) Logical/Conceptual**

**7.** The three-schema architecture was proposed by:
(A) ANSI/SPARC  (B) IEEE  (C) ISO  (D) W3C

✅ **Ans: (A) ANSI/SPARC**

**8.** Physical data independence means:
(A) the conceptual schema can change without affecting the views  (B) nothing can change  (C) none of these  (D) the physical storage can change without changing the conceptual schema

✅ **Ans: (D) the physical storage can change without changing the conceptual schema**

**9.** Compared with physical data independence, logical data independence is:
(A) harder to achieve  (B) easier to achieve  (C) the same  (D) impossible

✅ **Ans: (A) harder to achieve**

**10.** The overall design of a database is called its:
(A) instance  (B) schema  (C) tuple  (D) domain

✅ **Ans: (B) schema**

**11.** The data stored in a database at a particular moment is called:
(A) the schema  (B) an instance  (C) metadata  (D) the domain

✅ **Ans: (B) an instance** — Also called a snapshot

**12.** "Data about data" is called:
(A) raw data  (B) information  (C) metadata  (D) an instance

✅ **Ans: (C) metadata**

**13.** A data dictionary stores:
(A) metadata such as definitions of tables, columns and constraints  (B) user data  (C) logs only  (D) backups

✅ **Ans: (A) metadata such as definitions of tables, columns and constraints** — Also called the system catalog

**14.** Which of these is **not** a DBMS?
(A) MySQL  (B) Oracle  (C) PostgreSQL  (D) Python

✅ **Ans: (D) Python**

**15.** A NoSQL database is one that:
(A) does not use the relational (table) model  (B) has no DBMS  (C) is not stored on any device  (D) is obsolete

✅ **Ans: (A) does not use the relational (table) model** — (PYQ 2025)

**16.** Which of these is a NoSQL database?
(A) MySQL  (B) MongoDB  (C) Oracle  (D) DB2

✅ **Ans: (B) MongoDB** — Cassandra and Redis are also NoSQL

**17.** A major problem of traditional file-processing systems is:
(A) data redundancy and inconsistency  (B) concurrency control  (C) security  (D) integrity constraints

✅ **Ans: (A) data redundancy and inconsistency** — "Storing space" is not a limitation (PYQ 2025)

**18.** Data redundancy means:
(A) deleting data  (B) encrypting data  (C) storing the same data in more than one place  (D) compressing data

✅ **Ans: (C) storing the same data in more than one place**

**19.** Menu- and form-based query interfaces are mainly meant for:
(A) naive (end) users  (B) the DBA  (C) database designers  (D) application programmers

✅ **Ans: (A) naive (end) users**

**20.** A collection of related records is a:
(A) field  (B) file/table  (C) byte  (D) character

✅ **Ans: (B) file/table** — A file is a collection of records (PYQ 2024)

---

## B. Data Models & ER Model

**1.** The ER model is a:
(A) high-level conceptual data model  (B) physical data model  (C) network model  (D) file format

✅ **Ans: (A) high-level conceptual data model**

**2.** Who proposed the ER model?
(A) E.F. Codd  (B) Boyce  (C) Peter Chen  (D) Ullman

✅ **Ans: (C) Peter Chen** — 1976

**3.** In an ER diagram, a rectangle represents an:
(A) entity set  (B) attribute  (C) relationship  (D) weak relationship

✅ **Ans: (A) entity set**

**4.** In an ER diagram, an ellipse (oval) represents an:
(A) entity  (B) attribute  (C) relationship  (D) key

✅ **Ans: (B) attribute**

**5.** In an ER diagram, a diamond represents a:
(A) entity  (B) attribute  (C) relationship set  (D) multivalued attribute

✅ **Ans: (C) relationship set**

**6.** A double ellipse represents a:
(A) derived attribute  (B) key attribute  (C) composite attribute  (D) multivalued attribute

✅ **Ans: (D) multivalued attribute**

**7.** A dashed ellipse represents a:
(A) derived attribute  (B) multivalued attribute  (C) key attribute  (D) weak entity

✅ **Ans: (A) derived attribute**

**8.** A double rectangle represents a:
(A) strong entity set  (B) weak entity set  (C) relationship  (D) attribute

✅ **Ans: (B) weak entity set** — Its relationship is shown as a double diamond

**9.** An underlined attribute name is a:
(A) primary key  (B) foreign key  (C) derived attribute  (D) multivalued attribute

✅ **Ans: (A) primary key**

**10.** A set of entities of the same type that share the same attributes is a(n):
(A) relation set  (B) tuple  (C) entity set  (D) ER model

✅ **Ans: (C) entity set** — (PYQ 2025)

**11.** "Age" worked out from "Date of Birth" is a:
(A) derived attribute  (B) multivalued attribute  (C) composite attribute  (D) key attribute

✅ **Ans: (A) derived attribute**

**12.** "Name" split into first, middle and last name is a:
(A) simple attribute  (B) composite attribute  (C) derived attribute  (D) multivalued attribute

✅ **Ans: (B) composite attribute**

**13.** A person can have several phone numbers. "Phone" is therefore a:
(A) single-valued attribute  (B) derived attribute  (C) multivalued attribute  (D) key attribute

✅ **Ans: (C) multivalued attribute**

**14.** Specialization is:
(A) a top-down process that divides a higher-level entity into lower-level sub-entities  (B) bottom-up  (C) aggregation  (D) none of these

✅ **Ans: (A) a top-down process that divides a higher-level entity into lower-level sub-entities** — (PYQ 2023, 2025)

**15.** Generalization is:
(A) top-down  (B) a bottom-up process that combines lower-level entities into a more general entity  (C) aggregation  (D) none of these

✅ **Ans: (B) a bottom-up process that combines lower-level entities into a more general entity**

**16.** Aggregation means:
(A) splitting an entity  (B) joining tables  (C) none of these  (D) treating a relationship set as a higher-level entity

✅ **Ans: (D) treating a relationship set as a higher-level entity**

**17.** One department has many employees. This relationship is:
(A) 1:1  (B) 1:M  (C) M:N  (D) M:1

✅ **Ans: (B) 1:M** — (PYQ 2024)

**18.** Students enrol in many courses, and each course has many students. This relationship is:
(A) 1:1  (B) 1:M  (C) M:N  (D) none of these

✅ **Ans: (C) M:N**

**19.** The hierarchical model organises data as a:
(A) tree  (B) graph  (C) table  (D) set of objects

✅ **Ans: (A) tree** — Main DBMS types: relational, hierarchical, network (PYQ 2025)

**20.** The network model organises data as a:
(A) tree  (B) graph of records with many-to-many links  (C) table  (D) set of objects

✅ **Ans: (B) graph of records with many-to-many links**

---

## C. Relational Model & Keys

**1.** Who proposed the relational model?
(A) E.F. Codd  (B) Peter Chen  (C) Dijkstra  (D) Boyce

✅ **Ans: (A) E.F. Codd** — 1970

**2.** A relation is also called a:
(A) attribute  (B) schema  (C) data type  (D) table

✅ **Ans: (D) table** — (PYQ 2025)

**3.** A row of a relation is called a:
(A) attribute  (B) tuple  (C) domain  (D) degree

✅ **Ans: (B) tuple**

**4.** A column of a relation is called an:
(A) tuple  (B) attribute  (C) cardinality  (D) record

✅ **Ans: (B) attribute** — (PYQ 2020)

**5.** The number of attributes in a relation is its:
(A) cardinality  (B) domain  (C) degree  (D) tuple count

✅ **Ans: (C) degree** — (PYQ 2024)

**6.** The number of tuples in a relation is its:
(A) degree  (B) cardinality  (C) domain  (D) key

✅ **Ans: (B) cardinality**

**7.** The set of allowed values for an attribute is its:
(A) domain  (B) tuple  (C) key  (D) relation

✅ **Ans: (A) domain**

**8.** A primary key is:
(A) a unique, non-NULL identifier for each record  (B) allowed to be NULL  (C) allowed to have duplicates  (D) the same as a foreign key

✅ **Ans: (A) a unique, non-NULL identifier for each record** — (PYQ 2025)

**9.** A candidate key is:
(A) any set of attributes  (B) a minimal superkey that could be chosen as the primary key  (C) a foreign key  (D) a non-key attribute

✅ **Ans: (B) a minimal superkey that could be chosen as the primary key** — The primary key is a chosen candidate key (PYQ 2020)

**10.** Candidate keys that are not chosen as the primary key are called:
(A) alternate keys  (B) foreign keys  (C) super keys  (D) composite keys

✅ **Ans: (A) alternate keys**

**11.** A superkey is:
(A) always minimal  (B) a foreign key  (C) none of these  (D) any set of attributes that uniquely identifies each tuple

✅ **Ans: (D) any set of attributes that uniquely identifies each tuple**

**12.** A foreign key is:
(A) an attribute that refers to the primary key of another table  (B) a unique key  (C) a NOT NULL constraint  (D) an index

✅ **Ans: (A) an attribute that refers to the primary key of another table** — It links two tables (PYQ 2025 A-R)

**13.** A primary key made of two or more attributes is a:
(A) foreign key  (B) alternate key  (C) composite key  (D) surrogate key

✅ **Ans: (C) composite key**

**14.** Which is the best primary key for a student table?
(A) Name  (B) Admission number  (C) City  (D) Age

✅ **Ans: (B) Admission number** — (PYQ 2019)

**15.** Which is the best primary key for a bank customer table?
(A) Name  (B) Address  (C) Account number  (D) Balance

✅ **Ans: (C) Account number** — (PYQ 2020)

**16.** Entity integrity means:
(A) a primary key value cannot be NULL  (B) every foreign key must match  (C) values must be unique  (D) none of these

✅ **Ans: (A) a primary key value cannot be NULL**

**17.** Referential integrity means:
(A) the primary key cannot be NULL  (B) a foreign key value must match an existing primary key value (or be NULL)  (C) values must be unique  (D) none of these

✅ **Ans: (B) a foreign key value must match an existing primary key value (or be NULL)**

**18.** NULL means:
(A) zero  (B) a blank space  (C) an unknown or missing value  (D) an error

✅ **Ans: (C) an unknown or missing value**

**19.** A table has 5 columns and 10 rows. What are its degree and cardinality?
(A) degree 5, cardinality 10  (B) degree 10, cardinality 5  (C) 50 and 50  (D) 15 and 15

✅ **Ans: (A) degree 5, cardinality 10**

**20.** Which constraint blocks duplicate values but still allows NULL?
(A) PRIMARY KEY  (B) NOT NULL  (C) CHECK  (D) UNIQUE

✅ **Ans: (D) UNIQUE** — Blocks duplicates (PYQ 2025)

---

## D. Relational Algebra

**1.** Selection (σ) picks:
(A) rows  (B) columns  (C) tables  (D) keys

✅ **Ans: (A) rows** — Like WHERE

**2.** Projection (π) picks:
(A) rows  (B) columns  (C) both  (D) neither

✅ **Ans: (B) columns** — Like the SELECT column list

**3.** For a union, the two relations must:
(A) have the same name  (B) be union-compatible (same degree and matching domains)  (C) have the same rows  (D) none of these

✅ **Ans: (B) be union-compatible (same degree and matching domains)**

**4.** R has 3 tuples and S has 4 tuples. How many tuples does R × S have?
(A) 7  (B) 12  (C) 3  (D) 4

✅ **Ans: (B) 12** — 3 × 4

**5.** R has degree 3 and S has degree 2. What is the degree of R × S?
(A) 5  (B) 6  (C) 3  (D) 2

✅ **Ans: (A) 5** — 3 + 2

**6.** A natural join matches tuples on:
(A) all attributes  (B) no condition  (C) common attributes with equal values  (D) primary keys only

✅ **Ans: (C) common attributes with equal values**

**7.** The set difference R − S gives the tuples:
(A) that are in both  (B) in S but not in R  (C) in R but not in S  (D) in either

✅ **Ans: (C) in R but not in S**

**8.** Intersection (R ∩ S) gives the tuples:
(A) in either relation  (B) in neither  (C) in R only  (D) in both relations

✅ **Ans: (D) in both relations**

**9.** Which symbol is the rename operator?
(A) ρ (rho)  (B) σ  (C) π  (D) ⋈

✅ **Ans: (A) ρ (rho)**

**10.** Which symbol stands for join?
(A) ∪  (B) ⋈  (C) −  (D) ×

✅ **Ans: (B) ⋈**

**11.** The division operation is used for queries that contain:
(A) "for all"  (B) "some"  (C) none of these  (D) a count

✅ **Ans: (A) "for all"**

**12.** Which of these is a unary operation?
(A) Union  (B) Join  (C) Selection  (D) Cartesian product

✅ **Ans: (C) Selection** — σ, π and ρ are unary

**13.** An outer join:
(A) keeps only matching tuples  (B) also keeps unmatched tuples, filling the gaps with NULLs  (C) keeps nothing  (D) keeps duplicates only

✅ **Ans: (B) also keeps unmatched tuples, filling the gaps with NULLs**

**14.** A left outer join keeps every tuple of the:
(A) right relation  (B) both relations  (C) left relation  (D) neither relation

✅ **Ans: (C) left relation**

**15.** Relational algebra is a:
(A) non-procedural language  (B) procedural query language  (C) programming language  (D) none of these

✅ **Ans: (B) procedural query language** — It says *how* to get the result

**16.** Relational calculus is:
(A) non-procedural  (B) procedural  (C) hardware  (D) none of these

✅ **Ans: (A) non-procedural** — It says *what* result you want

**17.** The SQL WHERE clause corresponds to which operation?
(A) Projection  (B) Union  (C) Selection  (D) Rename

✅ **Ans: (C) Selection**

**18.** The column list after SQL SELECT corresponds to which operation?
(A) Selection  (B) Projection  (C) Join  (D) Division

✅ **Ans: (B) Projection**

**19.** A theta join is a join with:
(A) only an equality condition  (B) no condition  (C) an outer condition  (D) any comparison condition (θ)

✅ **Ans: (D) any comparison condition (θ)**

**20.** An equi-join uses:
(A) only `<`  (B) any condition  (C) no condition  (D) only the equality (=) condition

✅ **Ans: (D) only the equality (=) condition**

---

## E. SQL: DDL / DML / DCL / TCL & Constraints

**1.** SQL stands for:
(A) Structured Query Language  (B) Simple Query Language  (C) Systematic Query Logic  (D) Standard Query Level

✅ **Ans: (A) Structured Query Language** — (PYQ 2025)

**2.** Which is a DDL command?
(A) INSERT  (B) CREATE  (C) UPDATE  (D) SELECT

✅ **Ans: (B) CREATE** — Also ALTER, DROP, TRUNCATE (PYQ 2024)

**3.** Which is a DML command?
(A) ALTER  (B) DROP  (C) UPDATE  (D) CREATE

✅ **Ans: (C) UPDATE** — (PYQ 2025)

**4.** Which is a DCL command?
(A) SELECT  (B) UPDATE  (C) DELETE  (D) GRANT

✅ **Ans: (D) GRANT** — (PYQ 2019)

**5.** Which is a TCL command?
(A) COMMIT  (B) CREATE  (C) GRANT  (D) INSERT

✅ **Ans: (A) COMMIT** — Also ROLLBACK, SAVEPOINT

**6.** Querying data and inserting, deleting and modifying tuples is provided by:
(A) DDL  (B) DCL  (C) DML  (D) TCL

✅ **Ans: (C) DML** — (PYQ 2025, asked 3 times)

**7.** ALTER TABLE is used to:
(A) change the structure of a table  (B) change the data  (C) delete rows  (D) run a query

✅ **Ans: (A) change the structure of a table**

**8.** DROP TABLE:
(A) removes rows only  (B) removes the table structure along with its data  (C) removes one column  (D) none of these

✅ **Ans: (B) removes the table structure along with its data** — Removes a relation (PYQ 2025)

**9.** TRUNCATE TABLE:
(A) removes the whole table  (B) removes one row  (C) removes all rows but keeps the table structure  (D) none of these

✅ **Ans: (C) removes all rows but keeps the table structure** — It is DDL and can't be rolled back

**10.** `DELETE FROM emp;` (with no WHERE clause):
(A) deletes all rows  (B) gives an error  (C) deletes the table  (D) deletes only the first row

✅ **Ans: (A) deletes all rows** — The table remains

**11.** REVOKE is used to:
(A) give privileges  (B) commit changes  (C) create a table  (D) take back privileges

✅ **Ans: (D) take back privileges**

**12.** ROLLBACK:
(A) undoes changes that have not been committed  (B) saves changes  (C) deletes a table  (D) grants rights

✅ **Ans: (A) undoes changes that have not been committed**

**13.** CRUD stands for:
(A) Copy, Replace, Update, Delete  (B) Create, Read, Update, Delete  (C) Cache, Read, Update, Delete  (D) Collect, Read, Use, Discard

✅ **Ans: (B) Create, Read, Update, Delete** — (PYQ 2025)

**14.** The NOT NULL constraint means:
(A) the column cannot be left empty  (B) values must be unique  (C) a default value is used  (D) a condition is checked

✅ **Ans: (A) the column cannot be left empty**

**15.** The CHECK constraint:
(A) makes values unique  (B) creates a foreign key  (C) makes sure values satisfy a condition  (D) sets a default

✅ **Ans: (C) makes sure values satisfy a condition**

**16.** The DEFAULT constraint:
(A) supplies a value when none is given  (B) makes values unique  (C) creates a primary key  (D) checks a condition

✅ **Ans: (A) supplies a value when none is given**

**17.** A PRIMARY KEY constraint is equivalent to:
(A) UNIQUE only  (B) NOT NULL only  (C) CHECK  (D) UNIQUE + NOT NULL

✅ **Ans: (D) UNIQUE + NOT NULL**

**18.** Which command adds a new column to an existing table?
(A) ALTER TABLE … ADD  (B) UPDATE  (C) INSERT  (D) MODIFY TABLE

✅ **Ans: (A) ALTER TABLE … ADD**

**19.** Which command renames a table in MySQL?
(A) UPDATE  (B) ALTER TABLE … RENAME TO (or RENAME TABLE)  (C) CHANGE  (D) MOVE

✅ **Ans: (B) ALTER TABLE … RENAME TO (or RENAME TABLE)**

**20.** Which of these is **not** a DDL command?
(A) CREATE  (B) ALTER  (C) DROP  (D) INSERT

✅ **Ans: (D) INSERT** — INSERT is DML

---

## F. SQL: SELECT, WHERE, Operators, LIKE, ORDER BY

**1.** Which statement retrieves data from a table?
(A) SELECT  (B) GET  (C) FETCH  (D) FIND

✅ **Ans: (A) SELECT** — (PYQ 2019, 2025)

**2.** Which clause filters rows?
(A) ORDER BY  (B) GROUP BY  (C) WHERE  (D) HAVING

✅ **Ans: (C) WHERE**

**3.** Which keyword removes duplicate rows from the output?
(A) UNIQUE  (B) DISTINCT  (C) DIFFERENT  (D) ONLY

✅ **Ans: (B) DISTINCT**

**4.** Which clause sorts the result?
(A) SORT BY  (B) ORDER BY  (C) GROUP BY  (D) ARRANGE

✅ **Ans: (B) ORDER BY**

**5.** By default, ORDER BY sorts in:
(A) ascending order  (B) descending order  (C) random order  (D) no order

✅ **Ans: (A) ascending order**

**6.** Wildcards are used with:
(A) IN  (B) BETWEEN  (C) IS  (D) LIKE

✅ **Ans: (D) LIKE** — (PYQ 2025)

**7.** The `%` wildcard stands for:
(A) zero or more characters  (B) exactly one character  (C) a digit  (D) none of these

✅ **Ans: (A) zero or more characters**

**8.** The `_` wildcard stands for:
(A) zero or more characters  (B) exactly one character  (C) a digit  (D) a space

✅ **Ans: (B) exactly one character**

**9.** Which condition finds names that start with 'A'?
(A) `LIKE 'A%'`  (B) `LIKE '%A'`  (C) `= 'A*'`  (D) `LIKE '_A'`

✅ **Ans: (A) `LIKE 'A%'`**

**10.** Which is **not** a valid relational operator in SQL?
(A) `>`  (B) `<=`  (C) `=>`  (D) `<>`

✅ **Ans: (C) `=>`** — (PYQ 2025)

**11.** How is "not equal to" written in SQL?
(A) `<>` or `!=`  (B) `=!`  (C) `><`  (D) `==`

✅ **Ans: (A) `<>` or `!=`**

**12.** `BETWEEN 10 AND 20`:
(A) excludes 10 and 20  (B) includes only 10  (C) includes both 10 and 20  (D) includes only 20

✅ **Ans: (C) includes both 10 and 20** — Inclusive

**13.** How do you test for NULL?
(A) `= NULL`  (B) `== NULL`  (C) `EQUALS NULL`  (D) `IS NULL`

✅ **Ans: (D) `IS NULL`**

**14.** The IN operator:
(A) matches any value in a list  (B) checks a range  (C) matches a pattern  (D) checks for NULL

✅ **Ans: (A) matches any value in a list**

**15.** `SELECT *` means:
(A) all columns  (B) all tables  (C) the first column  (D) a row count

✅ **Ans: (A) all columns**

**16.** Which keyword gives a column an alias?
(A) ALIAS  (B) AS  (C) NAME  (D) RENAME

✅ **Ans: (B) AS**

**17.** What is the precedence of the logical operators, from highest to lowest?
(A) NOT, AND, OR  (B) OR, AND, NOT  (C) AND, OR, NOT  (D) all equal

✅ **Ans: (A) NOT, AND, OR**

**18.** In MySQL, `LIMIT 3`:
(A) skips 3 rows  (B) returns 3 columns  (C) returns at most 3 rows  (D) gives an error

✅ **Ans: (C) returns at most 3 rows**

**19.** `SELECT ename FROM emp WHERE sal > 5000 ORDER BY ename DESC;` returns:
(A) names of employees earning more than 5000, in reverse alphabetical order  (B) the same names in ascending order  (C) all names  (D) an error

✅ **Ans: (A) names of employees earning more than 5000, in reverse alphabetical order**

**20.** Which clause names the table(s) to read from?
(A) WHERE  (B) SELECT  (C) INTO  (D) FROM

✅ **Ans: (D) FROM**

---

## G. Aggregates, GROUP BY, HAVING, Joins & Views

**1.** Which aggregate counts the values in a column, ignoring NULLs?
(A) LEN()  (B) COUNT(column)  (C) NUMBER()  (D) NUM()

✅ **Ans: (B) COUNT(column)** — (PYQ 2025)

**2.** `COUNT(*)` counts:
(A) all rows, including those with NULLs  (B) non-NULL values only  (C) distinct values  (D) columns

✅ **Ans: (A) all rows, including those with NULLs**

**3.** A Score column holds 50, 35, 10, 51, 70. Which function returns 10?
(A) MAX  (B) MIN  (C) SUM  (D) AVG

✅ **Ans: (B) MIN** — (PYQ 2025)

**4.** For the same column, what does SUM(Score) return?
(A) 216  (B) 206  (C) 70  (D) 43.2

✅ **Ans: (A) 216** — 50 + 35 + 10 + 51 + 70

**5.** For the same column, what does AVG(Score) return?
(A) 216  (B) 10  (C) 43.2  (D) 70

✅ **Ans: (C) 43.2** — 216 / 5

**6.** Conditions on groups are applied using:
(A) WHERE  (B) ORDER BY  (C) LIMIT  (D) HAVING

✅ **Ans: (D) HAVING** — (PYQ 2025)

**7.** Aggregate functions can be used with ___ but not with ___.
(A) WHERE, HAVING  (B) GROUP BY, HAVING  (C) HAVING, WHERE  (D) SELECT, HAVING

✅ **Ans: (C) HAVING, WHERE** — HAVING, WHERE (PYQ 2025)

**8.** GROUP BY is used to:
(A) sort rows  (B) filter rows  (C) join tables  (D) collect rows with the same values so aggregates can be applied

✅ **Ans: (D) collect rows with the same values so aggregates can be applied**

**9.** What is the correct order of clauses in a SELECT statement?
(A) SELECT, WHERE, FROM, ORDER BY, GROUP BY  (B) SELECT, FROM, HAVING, WHERE, GROUP BY  (C) SELECT, FROM, WHERE, GROUP BY, HAVING, ORDER BY  (D) FROM, SELECT, ORDER BY, WHERE

✅ **Ans: (C) SELECT, FROM, WHERE, GROUP BY, HAVING, ORDER BY**

**10.** Aggregate functions (other than COUNT(*)) ignore:
(A) zeros  (B) NULL values  (C) duplicates  (D) negative numbers

✅ **Ans: (B) NULL values**

**11.** Which operation combines rows from two tables based on a related column?
(A) JOIN  (B) UNION  (C) GROUP BY  (D) INTERSECT

✅ **Ans: (A) JOIN**

**12.** An INNER JOIN returns:
(A) all rows of the left table  (B) only the rows that match in both tables  (C) all rows of both tables  (D) nothing

✅ **Ans: (B) only the rows that match in both tables**

**13.** A LEFT JOIN returns:
(A) only the matching rows  (B) all rows of the right table  (C) all rows of the left table plus the matching rows of the right  (D) nothing

✅ **Ans: (C) all rows of the left table plus the matching rows of the right** — Unmatched right-side values become NULL

**14.** Tables with 4 rows and 5 rows are joined with no condition. How many rows does the result have?
(A) 20  (B) 9  (C) 4  (D) 5

✅ **Ans: (A) 20** — Cartesian product

**15.** An equi-join uses the operator:
(A) =  (B) <  (C) >  (D) LIKE

✅ **Ans: (A) =**

**16.** A self join is:
(A) a join of two different tables  (B) not possible  (C) a union  (D) a table joined with itself

✅ **Ans: (D) a table joined with itself** — Uses table aliases

**17.** UNION removes:
(A) duplicate rows  (B) nothing  (C) NULLs  (D) columns

✅ **Ans: (A) duplicate rows**

**18.** UNION ALL:
(A) removes duplicates  (B) keeps duplicates  (C) gives an error  (D) sorts the rows

✅ **Ans: (B) keeps duplicates**

**19.** A subquery is:
(A) a query written inside another query  (B) a join  (C) a view  (D) an index

✅ **Ans: (A) a query written inside another query**

**20.** A view is:
(A) a physical table  (B) an index  (C) a virtual table based on a query  (D) a trigger

✅ **Ans: (C) a virtual table based on a query**

---

## H. Normalization & Functional Dependency

**1.** The main aim of normalization is to:
(A) reduce redundancy and update anomalies  (B) increase redundancy  (C) speed up hardware  (D) encrypt data

✅ **Ans: (A) reduce redundancy and update anomalies**

**2.** 1NF requires:
(A) no partial dependency  (B) atomic (indivisible) values in every column  (C) no transitive dependency  (D) none of these

✅ **Ans: (B) atomic (indivisible) values in every column**

**3.** 2NF requires:
(A) atomic values only  (B) no transitive dependency  (C) 1NF + no partial dependency on part of a composite key  (D) no multivalued dependency

✅ **Ans: (C) 1NF + no partial dependency on part of a composite key**

**4.** 3NF requires:
(A) no partial dependency only  (B) atomic values only  (C) no multivalued dependency  (D) 2NF + no transitive dependency

✅ **Ans: (D) 2NF + no transitive dependency**

**5.** A relation is in BCNF if:
(A) every determinant is a candidate key  (B) it has no keys  (C) it has only one column  (D) none of these

✅ **Ans: (A) every determinant is a candidate key** — Stricter than 3NF

**6.** The functional dependency X → Y means:
(A) X uniquely determines Y  (B) Y determines X  (C) X and Y determine each other  (D) none of these

✅ **Ans: (A) X uniquely determines Y**

**7.** A partial dependency is when a non-key attribute depends on:
(A) another non-key attribute  (B) only part of a composite key  (C) the whole key  (D) none of these

✅ **Ans: (B) only part of a composite key**

**8.** A transitive dependency is when a non-key attribute depends on the key:
(A) through part of the key  (B) on the whole key directly  (C) through another non-key attribute  (D) none of these

✅ **Ans: (C) through another non-key attribute** — A → B → C, where B is non-key

**9.** Insertion, update and deletion anomalies are caused by:
(A) redundancy  (B) indexing  (C) views  (D) encryption

✅ **Ans: (A) redundancy**

**10.** 4NF deals with:
(A) partial dependency  (B) multivalued dependency  (C) transitive dependency  (D) atomic values

✅ **Ans: (B) multivalued dependency**

**11.** 5NF deals with:
(A) join dependency  (B) multivalued dependency  (C) partial dependency  (D) none of these

✅ **Ans: (A) join dependency** — Also called PJNF

**12.** Armstrong's axioms are:
(A) union only  (B) commutativity  (C) reflexivity, augmentation, transitivity  (D) none of these

✅ **Ans: (C) reflexivity, augmentation, transitivity**

**13.** "If A → B, then AC → BC" is the rule of:
(A) augmentation  (B) reflexivity  (C) transitivity  (D) decomposition

✅ **Ans: (A) augmentation**

**14.** X → Y is a trivial dependency when:
(A) X ⊆ Y  (B) X and Y are disjoint  (C) none of these  (D) Y ⊆ X

✅ **Ans: (D) Y ⊆ X**

**15.** A good decomposition should be:
(A) lossless and dependency-preserving  (B) lossy  (C) random  (D) none of these

✅ **Ans: (A) lossless and dependency-preserving**

**16.** Denormalization is done to:
(A) reduce redundancy  (B) improve query/read performance  (C) add anomalies  (D) none of these

✅ **Ans: (B) improve query/read performance**

**17.** Every relation in BCNF is also in:
(A) 3NF  (B) 4NF  (C) 5NF  (D) none of these

✅ **Ans: (A) 3NF**

**18.** Attribute closure (X⁺) is used to find:
(A) indexes  (B) views  (C) candidate keys  (D) joins

✅ **Ans: (C) candidate keys**

**19.** A column that stores several phone numbers in one cell violates:
(A) 1NF  (B) 2NF  (C) 3NF  (D) BCNF

✅ **Ans: (A) 1NF** — Values must be atomic

**20.** A relation in 1NF with a single-attribute primary key is automatically in:
(A) 3NF  (B) BCNF  (C) 4NF  (D) 2NF

✅ **Ans: (D) 2NF** — Partial dependency needs a composite key

---

## I. Transactions, Concurrency & Recovery

**1.** ACID stands for:
(A) Atomicity, Consistency, Isolation, Durability  (B) Accuracy, Consistency, Integrity, Durability  (C) Atomicity, Concurrency, Isolation, Data  (D) none of these

✅ **Ans: (A) Atomicity, Consistency, Isolation, Durability**

**2.** Which property means "all or nothing"?
(A) Consistency  (B) Atomicity  (C) Isolation  (D) Durability

✅ **Ans: (B) Atomicity**

**3.** Which property means committed changes survive a crash?
(A) Atomicity  (B) Isolation  (C) Durability  (D) Consistency

✅ **Ans: (C) Durability**

**4.** Which property means concurrent transactions don't interfere with each other?
(A) Isolation  (B) Durability  (C) Atomicity  (D) Consistency

✅ **Ans: (A) Isolation**

**5.** What does a DBMS use to keep transactions intact and consistent?
(A) Pointers  (B) Cursors  (C) Locks  (D) Triggers

✅ **Ans: (C) Locks** — (PYQ 2023)

**6.** A shared (S) lock allows:
(A) reading only, and many transactions can hold it together  (B) writing  (C) both reading and writing  (D) none of these

✅ **Ans: (A) reading only, and many transactions can hold it together**

**7.** An exclusive (X) lock allows:
(A) many writers at once  (B) nothing  (C) reading only  (D) reading and writing by a single transaction

✅ **Ans: (D) reading and writing by a single transaction**

**8.** What are the two phases of two-phase locking (2PL)?
(A) Growing and shrinking  (B) Read and write  (C) Commit and abort  (D) none of these

✅ **Ans: (A) Growing and shrinking**

**9.** 2PL guarantees:
(A) freedom from deadlock  (B) conflict serializability  (C) no rollbacks  (D) none of these

✅ **Ans: (B) conflict serializability** — Deadlock is still possible

**10.** A dirty read is:
(A) reading data that has not been committed  (B) reading committed data  (C) reading the same data twice  (D) none of these

✅ **Ans: (A) reading data that has not been committed**

**11.** The lost-update problem is caused by:
(A) concurrent writes without control  (B) commits  (C) logs  (D) indexes

✅ **Ans: (A) concurrent writes without control**

**12.** COMMIT:
(A) undoes changes  (B) locks data  (C) makes the changes permanent  (D) creates a table

✅ **Ans: (C) makes the changes permanent**

**13.** SAVEPOINT:
(A) marks a point that you can partly roll back to  (B) commits  (C) deletes data  (D) grants rights

✅ **Ans: (A) marks a point that you can partly roll back to**

**14.** In log-based recovery, UNDO uses the:
(A) old values (before-image)  (B) new values  (C) both  (D) neither

✅ **Ans: (A) old values (before-image)**

**15.** In log-based recovery, REDO uses the:
(A) old values  (B) neither  (C) index  (D) new values (after-image)

✅ **Ans: (D) new values (after-image)**

**16.** To hand control back, the old backup site sends ___ to the old primary.
(A) redo logs  (B) undo logs  (C) primary logs  (D) all of these

✅ **Ans: (A) redo logs** — (PYQ 2025)

**17.** Checkpoints mainly reduce:
(A) storage  (B) recovery time (less of the log to scan)  (C) CPU use  (D) none of these

✅ **Ans: (B) recovery time (less of the log to scan)**

**18.** Deadlocks between transactions can be handled with:
(A) wait-die / wound-wait timestamp schemes  (B) normalization  (C) indexing  (D) views

✅ **Ans: (A) wait-die / wound-wait timestamp schemes**

**19.** In a serial schedule, transactions run:
(A) interleaved  (B) in parallel  (C) one after another, without interleaving  (D) none of these

✅ **Ans: (C) one after another, without interleaving**

**20.** The states of a transaction include:
(A) active, partially committed, committed, failed, aborted  (B) running and waiting only  (C) ready only  (D) none of these

✅ **Ans: (A) active, partially committed, committed, failed, aborted**

---

## J. MySQL Functions & Python/PHP Connectivity

**1.** What is MySQL's default date format?
(A) DD-MM-YYYY  (B) MM-DD-YYYY  (C) YYYY-MM-DD  (D) YYYY-DD-MM

✅ **Ans: (C) YYYY-MM-DD** — (PYQ 2025)

**2.** Which type of value is **not** enclosed in quotes in MySQL?
(A) DATE  (B) VARCHAR  (C) FLOAT  (D) CHAR

✅ **Ans: (C) FLOAT** — Numbers are not quoted (PYQ 2025)

**3.** How do CHAR and VARCHAR differ?
(A) CHAR is fixed-length, VARCHAR is variable-length  (B) CHAR is variable-length, VARCHAR is fixed-length  (C) they are the same  (D) none of these

✅ **Ans: (A) CHAR is fixed-length, VARCHAR is variable-length**

**4.** Which expression gives the square root of 16?
(A) POWER(16, 2)  (B) POWER(16, 0.5)  (C) MOD(16)  (D) POWER(16, 1)

✅ **Ans: (B) POWER(16, 0.5)** — Or SQRT(16) (PYQ 2025)

**5.** What does MOD(17, 5) return?
(A) 2  (B) 3  (C) 5  (D) 17

✅ **Ans: (A) 2**

**6.** What does ROUND(15.678, 1) return?
(A) 15.6  (B) 16  (C) 15.7  (D) 15.68

✅ **Ans: (C) 15.7**

**7.** What does UPPER('bihar') return?
(A) BIHAR  (B) bihar  (C) Bihar  (D) an error

✅ **Ans: (A) BIHAR**

**8.** What does LENGTH('STET 2026') return?
(A) 8  (B) 7  (C) 10  (D) 9

✅ **Ans: (D) 9** — The space counts

**9.** What does SUBSTR('COMPUTER', 4, 3) return?
(A) MPU  (B) PUT  (C) UTE  (D) OMP

✅ **Ans: (B) PUT** — C-O-M-**P-U-T**-E-R: starts at position 4

**10.** NOW() returns:
(A) the current date and time  (B) the date only  (C) the time only  (D) the year only

✅ **Ans: (A) the current date and time** — CURDATE() = date only

**11.** Which command lists all databases?
(A) `SHOW DATABASES;`  (B) `LIST DATABASES;`  (C) `DISPLAY DB;`  (D) `VIEW DATABASES;`

✅ **Ans: (A) `SHOW DATABASES;`**

**12.** Which command selects a database to work in?
(A) `OPEN db;`  (B) `SELECT DB db;`  (C) `USE db;`  (D) `GO db;`

✅ **Ans: (C) `USE db;`**

**13.** Which command shows the structure of a table?
(A) `DESCRIBE table;` (or `DESC`)  (B) `SHOW table;`  (C) `STRUCT table;`  (D) `VIEW table;`

✅ **Ans: (A) `DESCRIBE table;` (or `DESC`)**

**14.** Which Python module connects to MySQL?
(A) sqlite  (B) os  (C) csv  (D) mysql.connector

✅ **Ans: (D) mysql.connector**

**15.** Which method runs an SQL statement from Python?
(A) `cursor.execute()`  (B) `run()`  (C) `query()`  (D) `fetch()`

✅ **Ans: (A) `cursor.execute()`**

**16.** `fetchall()` returns:
(A) one row  (B) all the remaining rows, as a list of tuples  (C) a row count  (D) none of these

✅ **Ans: (B) all the remaining rows, as a list of tuples**

**17.** `fetchone()` returns:
(A) the next row as a tuple  (B) all rows  (C) a count  (D) a list of rows

✅ **Ans: (A) the next row as a tuple** — Returns None when there are no more rows

**18.** After an INSERT or UPDATE from Python, which call saves the change?
(A) `close()`  (B) `fetch()`  (C) `connection.commit()`  (D) `execute()` again

✅ **Ans: (C) `connection.commit()`**

**19.** The `cursor.rowcount` attribute gives the:
(A) number of rows affected or fetched  (B) number of columns  (C) number of tables  (D) number of bytes

✅ **Ans: (A) number of rows affected or fetched**

**20.** How does PHP connect to MySQL?
(A) by including a file  (B) by embedding SQL only  (C) through JDBC  (D) with `mysqli_connect()` or PDO

✅ **Ans: (D) with `mysqli_connect()` or PDO** — (PYQ 2025)

---

### Score tracker

| Topic | Attempt 1 | Attempt 2 |
|---|---|---|
| A. DBMS basics | /20 | /20 |
| B. ER model | /20 | /20 |
| C. Relational model & keys | /20 | /20 |
| D. Relational algebra | /20 | /20 |
| E. DDL/DML/DCL & constraints | /20 | /20 |
| F. SELECT & operators | /20 | /20 |
| G. Aggregates, GROUP BY, joins | /20 | /20 |
| H. Normalization | /20 | /20 |
| I. Transactions & recovery | /20 | /20 |
| J. MySQL & connectivity | /20 | /20 |
| **Total** | **/200** | **/200** |
