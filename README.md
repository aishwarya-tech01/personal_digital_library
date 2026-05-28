
📚 Personal Digital Library-
= 📝 Project Overview
- This project is a Relational Database system designed to manage a personal collection of books. It allows users to track what they have read, rate their favorite books, and organize their library using structured SQL queries.

✨ Key Database Features
= Based on the current SQL implementation, the system supports:

- Table Creation: Automatically sets up a books table with unique IDs, titles, and authors.

- Reading Status: Tracks whether a book has been read (is_read column).

- Dynamic Updates: Includes functionality to ALTER tables (adding a rating system) and UPDATE specific records.

🛠️ Tech Stack
- Language: SQL (SQLite).

- Editor: Visual Studio Code.

- Concepts: CRUD operations (Create, Read, Update, Delete), Data Normalization, and ACID properties.

📊 Database Schema
- The books table consists of:
  title	   TEXT	       The name of the book (Required)
  author	 TEXT	       The author's name (Required)
  is_read	 INTEGER	   Boolean (0 for No, 1 for Yes)
  rating	 INTEGER	   User rating from 1 to 5 stars.

🚀 How to Use
- 1.Open the my_library.sql file in VS Code.
- 2.Run the script using a SQLite extension or command line to initialize the database.
- 3.Use the SELECT statements at the bottom of the script to view your organized library data.
