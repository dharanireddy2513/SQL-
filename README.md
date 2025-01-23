# SQL-
SELECT Distinct - Use DISTINCT to ensure each author appears only once in the result.
OREDER BY - Use ORDER BY id ASC to sort the output by id in ascending order.
If they give you a table in that you have to give the values which are greater than this number , then WHERE LENGTH(content) > the number .

If you are given two tables with employee details . You need to show unique_id and name from those tables ,then selecting the e.name ,eu.unique _id from the emplyee.e  using the LEFT JOIN and ON .  
FROM Employees e: Selects the Employees table as the base table.
LEFT JOIN EmployeeUNI eu ON e.id = eu.id: Joins the EmployeeUNI table on the id column, ensuring all rows from the Employees table are included, with NULL for unique_id when no match is found.
SELECT e.name, eu.unique_id: Retrieves the employee name from the Employees table and the unique_id from the EmployeeUNI table.
