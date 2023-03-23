Salaries Differences

Q
Write a query that calculates the difference between the highest salaries found in the marketing and engineering departments. Output just the absolute difference in salaries.
![image](https://user-images.githubusercontent.com/50389985/227085908-14bc2547-7cc5-4a1c-aaa0-416461083d20.png)

A
select abs(max(a.salary) - max(b.salary)) as sal_diff
from db_employee a, db_employee b
where a.department_id = 4 and b.department_id = 1;
![image](https://user-images.githubusercontent.com/50389985/227085978-0c05ac1a-8ce8-4c15-8b5b-5472d6f8f25c.png)


