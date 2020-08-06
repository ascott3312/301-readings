# DATABASE NORMALIZATION

## Processs
 1. Database normalization is a process used to organize a database into tables and columns.  The main idea with this is that a table should be about a specific topic and only supporting topics included. Take a spreadsheet containing the information as an example, where the data contains salespeople and customers serving several purposes:   

 1. Reasons for Database Normalization
There are three main reasons to normalize a database.  The first is to minimize duplicate data, the second is to minimize or avoid data modification issues, and the third is to simplify queries. 

 1. The first thing to notice is this table serves many purposes including:

    - As a DBA this raises a red flag.  In general I like to see tables that have one purpose.  Having the table serve many purposes introduces many of the challenges; namely, data duplication, data update issues, and increased effort to query data.

 1. Definition of Database Normalization
 - There are three common forms of database normalization: 1st, 2nd, and 3rd normal form. They are also abbreviated as 1NF, 2NF, and 3NF respectively. 
 summarize the various forms:

 - First Normal Form – The information is stored in a relational table with each column containing atomic values. There are no repeating groups of columns.
 
 - Second Normal Form – The table is in first normal form and all the columns depend on the table’s primary key.
 
 - Third Normal Form – the table is in second normal form and all of its columns are not transitively dependent on the primary key
