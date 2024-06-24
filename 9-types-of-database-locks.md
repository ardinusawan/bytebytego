In database management, locks are mechanisms that prevent concurrent access to data to ensure data integrity and consistency. 
 
Here are the common types of locks used in databases: 
 
1. Shared Lock (S Lock) 
It allows multiple transactions to read a resource simultaneously but not modify it. Other transactions can also acquire a shared lock on the same resource. 
 
2. Exclusive Lock (X Lock) 
It allows a transaction to both read and modify a resource. No other transaction can acquire any type of lock on the same resource while an exclusive lock is held. 
 
3. Update Lock (U Lock) 
It is used to prevent a deadlock scenario when a transaction intends to update a resource. 
 
4. Schema Lock 
It is used to protect the structure of database objects. 
 
5. Bulk Update Lock (BU Lock) 
It is used during bulk insert operations to improve performance by reducing the number of locks required. 
 
6. Key-Range Lock 
It is used in indexed data to prevent phantom reads (inserting new rows into a range that a transaction has already read). 
 
7. Row-Level Lock 
It locks a specific row in a table, allowing other rows to be accessed concurrently. 
 
8. Page-Level Lock 
It locks a specific page (a fixed-size block of data) in the database. 
 
9. Table-Level Lock 
It locks an entire table. This is simple to implement but can reduce concurrency significantly.

Source: https://www.linkedin.com/posts/alexxubyte_systemdesign-coding-interviewtips-activity-7211031615462895616-678T?utm_source=share&utm_medium=member_desktop
