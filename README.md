# Soldier Management System

A PostgreSQL 18 practice project developed by the Avengers Group to manage fictional soldiers, ranks, units, missions, and mission assignments. The project demonstrates basic relational database design and SQL queries using pgAdmin 4.

## Database Tables

- **ranks** — military rank names and levels.
- **units** — unit names and locations.
- **missions** — mission details and start/end dates.
- **soldiers** — soldier details, service numbers, statuses, ranks, and units.
- **soldier_missions** — soldiers assigned to missions and their roles.

## SQL Features

The project uses primary and foreign keys, `NOT NULL`, `UNIQUE`, `CHECK`, and default values. It includes `INSERT`, `SELECT`, `WHERE`, `IN`, `BETWEEN`, `JOIN`, `GROUP BY`, `ORDER BY`, `EXPLAIN`, an index on soldiers' last names, and the `v_soldier_profile` view.

## Sample Data

The SQL script includes **6 ranks, 6 units, 5 missions, 33 fictional soldiers, and 13 mission assignments**. The first 30 soldiers are illustrative practice records, not the lecturer's original seed data.

## How to Run

1. Open **pgAdmin 4** and connect to **PostgreSQL 18**.
2. Create and select a **new empty database**.
3. Open the **Query Tool** and load `SoldierManagementSystem.sql`.
4. Execute the script and review the query results.

> **Note:** The script uses PostgreSQL syntax, not MySQL 8 syntax. It creates tables without `IF NOT EXISTS`, so run it in an empty database. The script was reviewed but not independently executed on the user's server.

## Purpose

This repository is for learning and practicing SQL database creation, relationships, data retrieval, indexing, and views. All soldier and mission information is fictional.
