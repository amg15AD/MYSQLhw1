# MYSQLhw1 Worked on chapter 7.
 SELECT Id as EmployeeID, Name, Department, City, Title as Project, ClientId FROM Employee  INNER JOIN Projects  ON Employee.Id = Projects.EmployeeId; 
 Will add only matching rows to from both joins to the returning set. So if any rows match of Employee.Id match Projects.EmployeeId matching rows will be returned showig the columns provided. Also INNER JOIN & JOIN Both prformw the INNER JOIN operation.

 SELECT Id as EmployeeID, Name, Department, City, Title as Project, ClientId FROM Employee  LEFT OUTER JOIN Projects  ON Employee.Id = Projects.EmployeeId; Will return 
 
