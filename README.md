# SQL-Task-01
>> Overview
This project defines a relational database schema for managing a library. It includes tables for books, authors, members, librarians, and loan tracking.

>> Tools
MySQL
MySQL Workbench (for schema design and execution)

>> Tables & Purpose
Authors: Stores author details
Books: Book data
BookAuthors: Many-to-many link between books and authors
Members: People who borrow books
Librarians: Staff/ Admins of library which manages loan
Loans: Tracks borrowed books and return status

>> Relationships
Books ↔ Authors: Many-to-many (BookAuthors)
Books ↔ Loans: One-to-many
Members ↔ Loans: One-to-many
Librarians ↔ Loans: One-to-many

>> Features
Tracks who borrows what and when
Prevents duplicates using primary/unique keys
Ensures data integrity using foreign keys

