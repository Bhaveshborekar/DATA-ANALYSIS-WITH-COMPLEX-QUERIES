# DATA-ANALYSIS-WITH-COMPLEX-QUERIES
COMPANY: CODTECH IT SOLUTION

NAME: BHAVESH PRAKASH BOREKAR

INTERN ID: CT08UQG

DOMAIN: SQL

DURATION: 4 WEEKS

MENTOR: NEELA SANTOSH

This SQL script demonstrates various advanced data analysis techniques using a STUDENTS table. Here's a brief breakdown of the queries:
1. Creating the Students Table:
•	The students table is created with the following columns: 
o	student_id (Primary Key)
o	name (Student Name)
o	score (Exam Score)
o	class (Subject/Exam Class)
o	exam_date (Date of the Exam)
2. Inserting Data:
•	Data for 7 students is inserted, each with a student_id, name, score, class, and exam date.
3. Advanced Data Analysis Queries:
•	Rank Students by Score in Each Class:
o	RANK() window function ranks students within each class based on their score in descending order. Tied students receive the same rank.
•	Subquery Example (Above Class Average):
o	This query uses a subquery to find students who scored above the average score in their respective class.
•	Common Table Expression (CTE) - Top 3 Students by Score in Each Class:
o	A CTE is used to rank students within each class, then select the top 3 ranked students in each class.
•	Window Function - Cumulative Score for Each Student:
o	The SUM() window function calculates the cumulative score for each student, ordered by exam date.
•	Subquery - Students Above Overall Average Score:
o	A subquery is used to find students who scored above the overall average score across all students.
•	CTE and Window Function - Students Above Class Average with Ranking:
o	A CTE calculates the class average score, and the RANK() function ranks students who scored above the class average, within their class.
•	Subquery - Best Scorer in Each Class:
o	A subquery identifies the highest score for each class, and then the main query finds the students with that score, i.e., the best scorer(s).
Summary:
•	RANK() and SUM() window functions help in ranking students and calculating cumulative scores.
•	Subqueries find students who scored above averages, both for their class and overall.
•	Common Table Expressions (CTEs) simplify complex queries like selecting top scorers and filtering students based on averages.

OUTPUT
![TASK2 1](https://github.com/user-attachments/assets/e29e83b8-a9fa-47bd-8198-cd4593518302)

![TASK2 2](https://github.com/user-attachments/assets/a5f778ec-9992-4f68-a4ae-5a9bf6b4e5c1)

![TASK2 3](https://github.com/user-attachments/assets/62a6e068-cb24-4a48-8b50-a0940396b1fb)

![TASK2 4](https://github.com/user-attachments/assets/42eb0e91-693d-4313-805d-5a7f55e181d2)

![TASK2 5](https://github.com/user-attachments/assets/42b2edb0-f705-4713-873b-11ef24c7d011)

![TASK2 6](https://github.com/user-attachments/assets/796a6a6c-c2c8-484b-9626-ed53b00138b4)

![TASK2 7](https://github.com/user-attachments/assets/91952623-0eb3-4ded-93e4-c0b608a1d21e)

![TASK2 8](https://github.com/user-attachments/assets/02992ade-4b08-449e-b946-9f95e03b1cd9)


