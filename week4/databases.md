#### Databases!

A database is an organised collection of data, which is usually stored and accessed electronically from a computer. The ones we have been learning about are relational databases and these consist of a series of tables, which hold data as rows and columns. The tables can be linked by the use of primary keys and foreign keys.

Primary keys - are the unique indentifier for each row in a table.
Foreign keys - are used to reference data that is one table to data that is another table.
Example - you have two tables, one that stores names and addresses, the other just stores phone numbers. Table1 has 3 columns: id, name, address. id is the primary key. Table2 has 2 columns: Table1_id, phone_no. Table1_id is the foreign key. Say you wanted someone's phone number. You would search for their name in Table1 and using the id, you would then search Table2 for their phone number.

By storing the data in this way, it prevents the tables from having to do too much work and keeps the database easier to manage.

To manage the data within a database we use Structured Query Language (SQL). Although SQL is relatively standard, depending on which database you are using, there will be some minor changes needed. We used postgre and this requires the ; at the end otherwise it won't work but some others don't need. However, the basic language is the same and for me that's important, as that'll make the transition between databases easier.
