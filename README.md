# Celestial Bodies Database

A PostgreSQL database project for storing information about galaxies, stars, planets, and moons.

This project was developed as part of the freeCodeCamp Relational Database Certification.

## Technologies

- PostgreSQL
- SQL

## Database Structure

```text
Galaxy
  └── Star
       └── Planet
            └── Moon
````

## Concepts

* Tables
* Primary Keys
* Foreign Keys
* Relationships
* SQL Queries
* Data Types
* Constraints

## Project File

`universe.sql` contains the database structure and data.

## How to Run

```sql
CREATE DATABASE universe;
```

```bash
psql -U postgres -d universe -f universe.sql
```

## Learning Outcome

Practiced relational database design, SQL queries, primary and foreign keys, and PostgreSQL.

## Certification

freeCodeCamp Relational Database Certification
