# Bihar STET Paper 2 (Computer Science): DBMS & SQL PYQ Bank

**Papers covered:** the same 8 papers as the earlier chapters.

| Year | Paper | DBMS/SQL questions found |
|---|---|---|
| 2019 | Second sitting (Sets A/H) | 4 |
| 2020 | Re-exam (Set B) | 4 |
| 2023 | 12 Sep, Shift 1 | 3 |
| 2024 | 11 Jun (memory-based list) | 5 |
| 2025 | 3 Nov Shift 1 | 8 |
| 2025 | 3 Nov Shift 2 | 8 |
| 2025 | 4 Nov Shift 2 | 11 |
| 2025 | 7 Nov Shift 1 | 9 |
| **Total** | | **≈52** |

> **This is the biggest-scoring chapter so far.** Each 2025 shift had **8–11 DBMS/SQL questions**, more than Computer Networks or OS.
> About 60% of them are **SQL commands and clauses** in the CBSE Class 11–12 style (MySQL, aggregate functions, DDL/DML, HAVING vs WHERE).
> Some questions repeat almost word-for-word: "DML lets you query/insert/delete/modify tuples" (3 times), the physical level (2), specialization (2), and HAVING (2).

**Notes on answers**
- The questions are paraphrased.
- The 2023 answers come from the official key.
- For 2025, the answers were worked out from the options, because only the options could be read.
- Not asked yet: **normalization, relational algebra and SQL joins**. They're standard syllabus, so they're covered in the practice set.

---

## 1. Topic frequency

| Rank | Topic | Times asked | Years |
|---|---|---|---|
| 1 | **SQL command types** (DDL/DML/DCL, CRUD, SQL full form) | 11 | 2019, 2024, 2025 ×4 |
| 2 | **SQL queries & clauses** (SELECT, UPDATE, DROP, INSERT INTO, LIKE, HAVING, relational operators) | 12 | 2019, 2024, 2025 ×4 |
| 3 | **DBMS basics** (what a DBMS is, DBA, types of DBMS, DBMS software type, examples, NoSQL, file system vs DBMS, records) | 11 | 2020, 2023, 2024, 2025 ×4 |
| 4 | **Keys & relational model** (primary key ×4, candidate key, UNIQUE, relation = table, degree, attribute, foreign key) | 10 | 2019, 2020, 2024, 2025 ×3 |
| 5 | **SQL functions** (MIN, COUNT, POWER) | 3 | 2025 ×3 |
| 6 | **ER model** (entity set, specialization ×2, 1:M relationship) | 4 | 2023, 2024, 2025 ×2 |
| 7 | **Data abstraction levels** (physical level) | 2 | 2025 |
| 8 | **MySQL specifics** (date format, unquoted FLOAT, PHP–MySQL connection) | 3 | 2025 |
| 9 | **Transactions & recovery** (locks, redo logs) | 2 | 2023, 2025 |

---

## 2. Questions by topic (with answers)

### A. SQL command types (DDL/DML/DCL/TCL)
| # | Asked (paraphrased) | Answer | Year |
|---|---|---|---|
| 1 | Which language lets you query data and insert, delete and modify tuples? | **DML** | 2025 ×3 (3 Nov S1 twice, 7 Nov) |
| 2 | Which is a DML command? (UPDATE, CREATE, ALTER, DROP) | **UPDATE** | 2025 (3 Nov S2) |
| 3 | Which is a DCL command? (UPDATE, SELECT, DELETE, GRANT) | **GRANT** | 2019 |
| 4 | Name a DDL command | CREATE / ALTER / DROP | 2024 |
| 5 | CRUD stands for | **Create, Read, Update, Delete** | 2025 (3 Nov S1) |
| 6 | SQL stands for | Structured Query Language | 2025 (3 Nov S2) |
| 7 | Which is a valid SQL command? (cin, cout, tuple, select) | **SELECT** | 2019 |

### B. SQL queries & clauses
| # | Asked | Answer | Year |
|---|---|---|---|
| 1 | Statement to retrieve data | **SELECT** | 2019, 2025 (3 Nov S2) |
| 2 | Clause to retrieve specific rows (options: SEARCH, FETCH, SELECT, FIND) | **SELECT** (rows are filtered with WHERE) | 2025 (4 Nov) |
| 3 | Statement to change existing data | **UPDATE** (not ALTER) | 2025 (7 Nov) |
| 4 | Command to remove a relation (table) | **DROP TABLE** | 2025 (4 Nov) |
| 5 | What INSERT INTO is used for | Adding new rows/records | 2024 |
| 6 | Keyword used with wildcards | **LIKE** | 2025 (4 Nov) |
| 7 | Clause that applies conditions to groups | **HAVING** | 2025 (3 Nov S1) |
| 8 | Aggregates can be used with ___ but not with ___ | **HAVING, WHERE** | 2025 (7 Nov) |
| 9 | Invalid relational operator (>, <=, =>, <>) | **=>** | 2025 (7 Nov) |
| 10 | Constraint that blocks duplicate values | **UNIQUE** | 2025 (4 Nov) |
| 11 | A-R: records can come from more than one table / a foreign key links tables | **Both true, and R explains A** | 2025 (7 Nov) |

### C. SQL functions
| # | Asked | Answer | Year |
|---|---|---|---|
| 1 | Scores 50, 35, 10, 51, 70: which query outputs 10? | **SELECT MIN(Score)…** | 2025 (3 Nov S1) |
| 2 | Aggregate that counts values while ignoring NULLs | **COUNT()** | 2025 (7 Nov) |
| 3 | Expression giving the square root of 16 | **POWER(16, 0.5)** (also SQRT(16)) | 2025 (4 Nov) |

### D. DBMS basics
| # | Asked | Answer | Year |
|---|---|---|---|
| 1 | What a DBMS is | **Software that stores, modifies and retrieves data** | 2023, 2025 (3 Nov S1) |
| 2 | DBMS full form | Database Management System | 2020 |
| 3 | DBA stands for | **Database Administrator** | 2025 (4 Nov) |
| 4 | A DBMS is which kind of software? | **System software** (the usual answer in MCQ banks). Some books call it application software, so read the options carefully. | 2025 (4 Nov) |
| 5 | Three main types of DBMS | **Relational, hierarchical, network** | 2025 (3 Nov S2) |
| 6 | Which is a database? (MySQL, Informix, SQL Server) | **All of the above** | 2025 (7 Nov) |
| 7 | A NoSQL database is one that | **Does not use the relational (table) model** | 2025 (3 Nov S1) |
| 8 | Which is **not** a limitation of a file system? | **Storing space** (redundancy, inconsistency and data dependence are limitations) | 2025 (3 Nov S1) |
| 9 | A file is a collection of related | **Records** | 2024, 2025 |

### E. Keys & relational model
| # | Asked | Answer | Year |
|---|---|---|---|
| 1 | What a primary key is | **A unique identifier for each record** | 2025 (4 Nov) |
| 2 | Primary key of a student table (UID, admission no., account no., PAN) | **Admission number** | 2019 |
| 3 | Primary key of a bank customer table | **Account number** | 2020 |
| 4 | A primary key is also called a | **Candidate key** (the candidate key that was chosen) | 2020 |
| 5 | A relation is also called a | **Table** | 2025 (4 Nov) |
| 6 | Column/field of a table is called | **Attribute** | 2020 |
| 7 | Number of attributes in a relation | **Degree** (number of rows = cardinality) | 2024 |

### F. ER model
| # | Asked | Answer | Year |
|---|---|---|---|
| 1 | Top-down approach that splits a higher-level entity into sub-entities | **Specialization** (bottom-up = generalization) | 2023, 2025 (7 Nov) |
| 2 | Set of entities of the same type with the same attributes | **Entity set** | 2025 (4 Nov) |
| 3 | 1:M relationship | One entity is linked to many (e.g. department → employees) | 2024 |

### G. Data abstraction
| # | Asked | Answer | Year |
|---|---|---|---|
| 1 | Level that describes how data is actually stored | **Physical level** | 2025 (3 Nov S2, asked twice in the same paper) |

### H. MySQL specifics
| # | Asked | Answer | Year |
|---|---|---|---|
| 1 | MySQL default date format | **YYYY-MM-DD** | 2025 (7 Nov) |
| 2 | Value type that shouldn't be in quotes | **FLOAT** (numbers aren't quoted. DATE, CHAR and VARCHAR are.) | 2025 (3 Nov S2) |
| 3 | How PHP connects to MySQL | A connect function (**mysqli_connect()** / PDO) | 2025 (4 Nov) |

### I. Transactions & recovery
| # | Asked | Answer | Year |
|---|---|---|---|
| 1 | What a DBMS uses to keep transactions intact and consistent | **Locks** | 2023 |
| 2 | To hand control back, the old backup site sends ___ to the old primary | **Redo logs** | 2025 (3 Nov S2) |

---

## 3. Must-revise checklist

1. **DBMS basics:** DBMS vs file system (redundancy, inconsistency, data dependence), DBA, schema vs instance, metadata/data dictionary, 3-level architecture (physical, logical/conceptual, view/external), data independence, types (hierarchical, network, relational, object-oriented, NoSQL).
2. **ER model:** entity, entity set, attributes (simple, composite, derived, multivalued, key), weak entities, relationships (1:1, 1:M, M:N), the diagram symbols, specialization (top-down), generalization (bottom-up), aggregation.
3. **Relational model:** relation = table, tuple = row, attribute = column, degree vs cardinality, domain, NULL; keys (super, candidate, primary, alternate, foreign, composite); entity and referential integrity.
4. **SQL categories:**
   - DDL: CREATE, ALTER, DROP, TRUNCATE, RENAME
   - DML: SELECT, INSERT, UPDATE, DELETE
   - DCL: GRANT, REVOKE
   - TCL: COMMIT, ROLLBACK, SAVEPOINT
5. **SQL clauses:** SELECT, FROM, WHERE, GROUP BY, HAVING, ORDER BY (ASC is the default), DISTINCT, LIKE (% and _), IN, BETWEEN (inclusive), IS NULL, AS, LIMIT.
6. **Aggregates:** COUNT(*) vs COUNT(col), SUM, AVG, MIN, MAX. They ignore NULLs, and they go in HAVING, not WHERE.
7. **Constraints:** PRIMARY KEY (UNIQUE + NOT NULL), UNIQUE, NOT NULL, CHECK, DEFAULT, FOREIGN KEY.
8. **MySQL functions:** POWER, SQRT, MOD, ROUND, UPPER/LOWER, LENGTH, SUBSTR/MID, NOW, CURDATE; date format YYYY-MM-DD.
9. **Joins & relational algebra:** σ (rows), π (columns), ×, ∪, −, ⋈; inner, left and right joins, self join; UNION vs UNION ALL.
10. **Normalization:** FDs, anomalies, 1NF (atomic values), 2NF (no partial dependency), 3NF (no transitive dependency), BCNF (every determinant is a key).
11. **Transactions:** ACID, COMMIT/ROLLBACK, locks (shared/exclusive), 2PL, dirty read, lost update, log-based recovery (undo = old values, redo = new values), checkpoints.
12. **Python–MySQL (CBSE):** mysql.connector, connect(), cursor(), execute(), fetchone/fetchall, commit(), rowcount.

Practice set: `03b_DBMS_SQL_Practice_MCQs.md`
