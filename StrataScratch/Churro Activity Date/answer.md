# Churro Activity Date
---
### Question:

Find the activity date and the pe_description of facilities with the name 'STREET CHURROS' and with a score of less than 95 points.

![image](https://user-images.githubusercontent.com/50389985/227765629-ceccdb12-1099-4f47-86a1-07552a97735a.png)

### Answer:

>select activity_date, pe_description
>from los_angeles_restaurant_health_inspections
>where facility_name = 'STREET CHURROS'
>and score < 95;

![image](https://user-images.githubusercontent.com/50389985/227765645-419d891e-ee61-4edb-b461-23014a3cb6c8.png)
