# CS157A-Proj1-Spring2021
## Sqlite3 build mod 

**Standard #1:** If a user inserts more columns into a table than the number of columns in a table, then the operation is shut down and user is given an error that specifies how many column values they were inserting and how many the columns the table actually has.

**Improvement to Standard #1:** The sqlite3.c file is modded to provide metadata information about the table schema so that the user can refine their insertion statement without peeking at the table's schema

**Standard #2:** An ORDER BY clause will sort in ascending order by default, meaning query output will be sorted in ascending order of the given column (or primary key) if the sorting order isn't declared explicitly in the query.

**Modification to Standard #2:** The sqlite3.c file has been modded to make descending order the default sorting order of SQLite.
