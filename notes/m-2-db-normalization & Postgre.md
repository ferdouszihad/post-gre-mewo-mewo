# m-2-db-normalization & Postgre

## 6-1 Understanding Anomalies

- What is Anomalies
- insertion Anomalis
- Deletion ANomalis
- Update Anomalis
- The Conccept of Normalization

## 6-2 Functional Dependency

- Concept of Functional Dependency
- T1.x == T2.x && T1.y == T2.y

## 6-3 ~ 6-5 Normalization up to 3NF

- Concept of Normalization
- Rules of 1NF
  - Atomicity -> Each column should have single values
  - Unique Collum Name
  - Positional Dependency of Data
  - Collumn should contain same type of data
  - Table must have a Primary Key

```bash
YOu have to learn normalization from outer resources . Instructor failed to explain perfectly
```

## 6-6 ~ 6-7 The Concept of Junction Table

- How to create Junction Table
- How to distribute table into subtable and solve many to many relation

## 6-8 PostGre Installation

- What is SQL
- What is PostGreSQL
- Why PostGreSQL
- Installation

## 6-9 PostGre Terminals

- select version(); // SHow Current Version
- \l //Show list of Databases
- \c `db_name` // Connect with a database
- \d // To show data on a database
- \dn // to schema in a table
- create Table `T_name`(`colName` `type`) // To create Table
- \dt // only show tables
- \d+ // show datas in a details format
- \conninfo //connection info
- \q //quit
