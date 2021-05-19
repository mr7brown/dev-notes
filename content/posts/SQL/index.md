---
title: "SQL Notes"
date: 2021-05-18
slug: "/curses-counter-curses-and-more"
canonicalUrl: "https://random-blog-about-curses.com"
---

## General SQL Notes

* SQL works off a relational set of rules. This nmeans that the data is often organized in multiple tables that all reference/interact with each other.
  * One example of this is a SQL database with customer information. Rather than having a single table that contains this data, the data can be stored across multiple tables and contain a key that links the information. This is useful because it allos you to have a a more varired data set, while still remaining searchable.

## Syntax

### General

* A semicolon must be placed at the end of the statement.

### SQL Statement

Is an expression that tells the database what you want it to do.

#### Commands & Keywords

* **SELECT -** Retrieves one or more rows from one or more tables.
  * Identifiers are seperated by commas.
* **INSERT INTO -** Adds one or more rows into a table.
  * Example: 
  ```
  INSERT INTO contacts (first_name, last_name) VALUES ('Ashton','Brown');
  ```
* **UPDATE -** Modifies one or more existing rows in a table.
  * Example: 
  ```
  UPDATE contacts SET lasname = 'George' WHERE id=1;
  ```
* **DELETE -** Deletes an existing row in a table.
  * Example:
  ```
  DELETE FROM contacts WHERE id=2;
  ```

#### Identifiers

### Clauses

* In a clause one example is a select clause:

```
SELECT first_name FROM person;
```


