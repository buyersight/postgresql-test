# postgresql-test

TASK:

The db_init.sql file contains the schema for two tables: Authors and Books. Please examine the two database table creates as well as the sample data and perform the following task:

Get a list of all authors, the price of their most expensive book, and the number of books they have written which have a price greater than $10 in descending order of the number of books written.

- The first column should be AUTHOR_NAME and should include the first letter of the author's first name and their last name (e.g. 'M FRIED')
- If two or more authors have written the same number of books, the query should order them by the price of the most expensive book in descending order
- If two or more authors have written the same number of books and the price of their most expensive book is the same, then order them by the author's last name alphabetically
- If the author has not written any books with a price greater than $10, do not display the author

You may use a site like [SQL Fiddle](http://sqlfiddle.com/#!17) or [DB Fiddle](https://www.db-fiddle.com/) to test and run your solution.

Email your solution to us in a file named `solution.txt` to [jobs@buyersight.io](mailto:jobs@buyersight.io)
