# Average Salaries
---
### Question:

Compare each employee's salary with the average salary of the corresponding department. Output the department, first name, and salary of employees along with the average salary of that department.

![image](https://user-images.githubusercontent.com/50389985/229360053-217b3b25-1124-47d9-981d-888b97ed01e4.png)

### Answer:

> select department, first_name, salary, avg(salary) over> (partition by department)
> from employee;

![image](https://user-images.githubusercontent.com/50389985/229360072-5339b49c-53c2-438b-bba0-994cd44446ec.png)
