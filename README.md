## Practical SQL: A Beginner's Guide to Storytelling with Data

[PracticalSQL](https://www.nostarch.com/practicalSQL) teaches you how to use the database programming language SQL (Structured Query Language) to find the story in your data. Author [Anthony DeBarros](https://www.anthonydebarros.com), a longtime data analyst, journalist and coder, starts readers off with SQL basics, using the open-source database PostgreSQL and its visual interface, pgAdmin. You’ll cover the fundamentals of databases and the SQL language, then build skills by analyzing data from the U.S. Census and other government agencies. With exercises and real-world examples in each chapter, this book is appropriate for beginners as well as those who know some SQL and want to go deeper.

Practical SQL is [available in PDF, .mobi, .epub, and classic print formats](https://www.nostarch.com/practicalSQL).

Questions? Feel free to email [practicalsqlbook@gmail.com](mailto:practicalsqlbook@gmail.com)

## What's Here

**Code**: All SQL code or command-line listings from each chapter, organized in chapter folders.

**Data**: CSV files for you to import, also organized by chapter. **NOTE!** See the warning below about opening CSV files in Excel and text editors in the section on Getting the Code and Data.

**Exercises**: The "Try It Yourself" questions and answers for each chapter, listed separately. Try working through the questions before peeking at the answers!

**FAQ, Updates, and Errata**: Answers to frequently asked questions,  updates, and corrections are noted at [faq-updates-errata.md](https://github.com/anthonydb/practical-sql/blob/master/faq-updates-errata.md).

**Resources**: Updates to the book's Appendix on Additional PostgreSQL Resources at [resources.md](https://github.com/anthonydb/practical-sql/blob/master/resources.md).

## Chapters

* Chapter 1: Creating Your First Database and Table
* Chapter 2: Beginning Data Exploration with SELECT
* Chapter 3: Understanding Data Types
* Chapter 4: Importing and Exporting Data
* Chapter 5: Basic Math and Stats with SQL
* Chapter 6: Joining Tables in a Relational Database
* Chapter 7: Table Design That Works for You
* Chapter 8: Extracting Information by Grouping and Summarizing
* Chapter 9: Inspecting and Modifying Data
* Chapter 10: Statistical Functions In SQL
* Chapter 11: Working With Dates and Times
* Chapter 12: Advanced Query Techniques
* Chapter 13: Mining Text to Find Meaningful Data
* Chapter 14: Analyzing Spatial Data with PostGIS
* Chapter 15: Saving Time with Views, Functions, and Triggers
* Chapter 16: Using PostgreSQL from the Command Line
* Chapter 17: Maintaining Your Database
* Chapter 18: Identifying and Telling the Story Behind Your Data
* Appendix: Additional PostgreSQL Resources

## Getting the Code and Data on Your Computer

**Non-GitHub Users**

You can obtain all the code and data at once by downloading this repository as a .zip file. To do that:

* Select the **Clone or Download** button at top right.
* Select **Download ZIP**
* Unzip the file on your computer. Place it in a directory that's easy to remember so you can reference it during the exercises that include importing data to PostgreSQL.

**Warning about CSV files!**: Opening CSV files with Excel could lead to data loss. Excel will remove leading zeros from numbers that are intended to be stored as text, such as zip codes. If you wish to view the contents of a CSV file, only do so with a plain-text editor and be careful not to save the file in an encoding other than UTF-8 (e.g., `Notepad.exe` on Windows defaults to ANSI).

**GitHub Users**

GitHub users may want to clone the repository locally and occasionally perform a `git pull` to receive any updates.
