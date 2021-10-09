# SQL_Functions
SQL_Functions

A function is a set of SQL statements that perform a specific task. 
Functions foster code reusability. If you have to repeatedly write large SQL scripts to perform the same task, 
you can create a function that performs that task. 
Next time instead of rewriting the SQL, you can simply call that function. 
A function accepts inputs in the form of parameters and returns a value. 
SQL Server comes with a set of built-in functions that perform a variety of tasks.

Of course, you could create a stored procedure to group a set of SQL statements and execute them,
however, stored procedures cannot be called within SQL statements. 
Functions, on the other hand, can be. Also, another issue with functions is that they have to be called for each row. 
Therefore, if you are using functions with large data sets, you can hit performance issues.


