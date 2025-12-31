# Employee-Management-System-SQL-Database-Project

🏢 **Overview**

This project demonstrates the design and implementation of a relational database system for managing employees and departments within an organization. It highlights schema design, referential integrity, normalization, and SQL query development to deliver actionable business insights.

🎯 **Objective**

To build a normalized, scalable database that supports employee and department management, ensuring data integrity and enabling analytical queries for HR and business decision-making.

🗂️ **Database Design**

**Departments Table**

-	DepartmentID (Primary Key, Auto Increment)
-	DepartmentName (e.g., HR, Finance, IT, Sales, etc.)
-	Location (City where department is based)
-	HeadOfDepartment (Name of department head)
-	AnnualBudget (Budget allocation for the department)

**Employees Table**

-	EmployeeID (Primary Key, Auto Increment)
-	FirstName, LastName (Employee details)
-	DepartmentID (Foreign Key → Departments)
-	Salary (Stored as DECIMAL(10,2) for precision)
-	DateOfJoining (Tracks employee tenure)
-	Email (Unique contact identifier)

🔑 **Key Features**

-	Referential Integrity → Foreign key ensures employees are linked to valid departments.
-	Realistic Dataset → 10 departments across Indian cities and 40+ employees with diverse salaries and join dates.
-	Business Logic Queries →
-	Department-wise employee count
-	Average salary by department
-	Employees who joined before 2020
-	Department budget vs. total salaries

🛠️ **Tools & Technologies**

-	SQL (MySQL) → Schema creation, constraints, queries, and analytics.
-	Normalization → Efficient storage and reduced redundancy.
-	Referential Integrity → Consistency between employees and departments.

📊 **Outcomes**

-	Delivered a normalized, scalable database for employee management.
-	Enabled complex queries (JOINs, aggregates, window functions) for insights.
•	Created a portfolio-ready project showcasing SQL expertise in schema design, data integrity, and analytics.

