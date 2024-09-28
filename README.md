# LITA-Class-Documentation
### Project Title: SQL Veiws
SQL views are virtual tables that simplify complex queries, gives you the flexibility to include only the details you want to share.
-  Customization: You can add and remove columns easily : just select the view created, right click, select design.
-  Visual Appeal: The connecting lines and dynamic movement are oddly satisfying.
-  User Friendly: Simply check and uncheck boxes to add or remove columns.
-  Easy creation: Just like pivot tables in Excel, its quite easy to create
(vemployee--- is the name of the view I want to create, you can name it anything, even Gloria)
-  security: Control access o sensitive data.
-  Performance: Optimize queries for faster retrieval. So, even if you lost your query you can retrieve it from the view, amazing right? No scrolling to number 33333 to get that code.
-  Consistency: Ensures everyone uses same logic for reporting.

### Tools Used
SQL [Download Here](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)
### Query used to create SQL veiw
```SQL CREATE VIEW vemployee AS
SELECT employee.staffid FROM employee```


