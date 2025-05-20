Library Management System Database

Project Description
This project is a relational database schema for a Library Management System built using MySQL. It manages core entities like Books, Authors, Publishers, Members, and Loans. The schema also handles many-to-many relationships, such as Books belonging to multiple Genres.

This database design enforces data integrity with appropriate primary keys, foreign keys, unique constraints, and not-null constraints. It supports key library operations such as tracking book loans and cataloging book genres.

Features
Authors, Publishers, and Books tables to catalog books and their metadata.

Members table to store library user information.

Loans table to track which members borrowed which books and their return dates.

Genres and BookGenres tables to categorize books with flexible many-to-many relationships.

Enforced referential integrity via foreign keys.

Unique constraints on critical fields like ISBN and email.
