```
[
  {
    "questionId": "q07212025-11",
    "question": "Which SQL clause is used to filter groups of rows based on a condition, after the aggregation has been performed?",
    "subQuestion": "",
    "domain": "SQL Queries, Aggregation",
    "difficulty": "intermediate",
    "answers": {
      "a": "WHERE",
      "b": "GROUP BY",
      "c": "HAVING",
      "d": "ORDER BY"
    },
    "correctAnswer": ["c"],
    "references": [
      "https://www.geeksforgeeks.org/sql/sql-where-clause/",
      "https://www.devart.com/dbforge/sql/sqlcomplete/sql-aggregate-functions.html"
    ]
  },
  {
    "questionId": "q07212025-12",
    "question": "You have two tables, `Employees` (EmployeeID, Name, DepartmentID) and `Departments` (DepartmentID, DepartmentName). You want to retrieve a list of all employees and their respective department names. If an employee does not have a department assigned, they should still appear in the list with a NULL value for DepartmentName. Which type of JOIN should you use?",
    "subQuestion": "",
    "domain": "SQL Joins",
    "difficulty": "intermediate",
    "answers": {
      "a": "INNER JOIN",
      "b": "RIGHT JOIN",
      "c": "LEFT JOIN",
      "d": "FULL OUTER JOIN"
    },
    "correctAnswer": ["c"],
    "references": [
      "https://www.devart.com/dbforge/sql/sqlcomplete/sql-join-statements.html",
      "https://www.coursera.org/articles/sql-join-types"
    ]
  },
  {
    "questionId": "q07212025-13",
    "question": "To find the average salary of employees in each department, while only including departments where the average salary is greater than 60000, which combination of SQL clauses would be most appropriate?",
    "subQuestion": "",
    "domain": "SQL Queries, Aggregation",
    "difficulty": "intermediate",
    "answers": {
      "a": "SELECT, WHERE, ORDER BY",
      "b": "SELECT, GROUP BY, HAVING",
      "c": "SELECT, JOIN, WHERE",
      "d": "SELECT, DISTINCT, ORDER BY"
    },
    "correctAnswer": ["b"],
    "references": [
      "https://blog.devart.com/sql-aggregate-functions.html",
      "https://www.geeksforgeeks.org/sql/aggregate-functions-in-sql/"
    ]
  },
  {
    "questionId": "q07212025-14",
    "question": "You need to update the `status` of all orders that were placed before '2024-01-01' to 'Completed'. Which SQL DML statement, combined with the appropriate clause, would achieve this?",
    "subQuestion": "",
    "domain": "SQL DML, Filtering",
    "difficulty": "intermediate",
    "answers": {
      "a": "INSERT INTO Orders (status) VALUES ('Completed') WHERE order_date < '2024-01-01';",
      "b": "UPDATE Orders SET status = 'Completed' WHERE order_date < '2024-01-01';",
      "c": "DELETE FROM Orders WHERE order_date < '2024-01-01' SET status = 'Completed';",
      "d": "ALTER TABLE Orders MODIFY status = 'Completed' WHERE order_date < '2024-01-01';"
    },
    "correctAnswer": ["b"],
    "references": [
      "https://www.w3schools.com/sql/sql_update.asp",
      "https://www.geeksforgeeks.org/sql-update-statement/"
    ]
  },
  {
    "questionId": "q07212025-15",
    "question": "Which of the following SQL statements correctly uses a subquery to find employees whose salary is above the average salary of all employees?",
    "subQuestion": "",
    "domain": "SQL Subqueries",
    "difficulty": "intermediate",
    "answers": {
      "a": "SELECT * FROM Employees WHERE salary > (SELECT MAX(salary) FROM Employees);",
      "b": "SELECT * FROM Employees WHERE salary = (SELECT AVG(salary) FROM Employees);",
      "c": "SELECT * FROM Employees WHERE salary > (SELECT AVG(salary) FROM Employees);",
      "d": "SELECT * FROM Employees GROUP BY salary HAVING salary > AVG(salary);"
    },
    "correctAnswer": ["c"],
    "references": [
      "https://www.geeksforgeeks.org/sql-subqueries/",
      "https://learnsql.com/blog/sql-subquery/"
    ]
  }
]
```
