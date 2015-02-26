# What is this SQL thing, anyway?

SQL stands for *Structured Query Language* – see, you're halfway through the first sentence of this course, and you're already half asleep! So let's try again. Simply put, SQL is a way for us humans to communicate with databases. "Database" is a pretty generic term for the many different database software systems that are available, so here are just a few examples:

* MySQL
* PostgreSQL
* Microsoft SQL Server
* Oracle
* Microsoft Access

And, even though there are a large number of database systems that are developed by many different companies and organizations, SQL is a *standard* that may be used to communicate with any of them.

Let's dive right in.

# The Basics

Databases store data in tabular format. If you've ever used Microsoft Excel, Google Sheets, or any other spreadsheet application to store a list of anything, you've probably invented a way to organize data that is very similar to how databases do it – perhaps, it looked something like this:

* Your data is stored in a grid format
* The columns of the grid represent the interesting attributes of the thing you are storing
* There is a row in the grid for each one of the things

For example, if I were to build a spreadsheet of my favorite movies, it might look something like this:

---------------------------------------
|# |Title       |Year         |Rating |
---------------------------------------
|1 |Star Wars   |1977         |PG     |
|2 |Apollo 13   |2004         |PG     |
|3 |The Matrix  |2007         |R      |
---------------------------------------