# Find the most profitable company in the financial sector of the entire world along with its continent

---

### Question

Find the most profitable company from the financial sector. Output the result along with the continent.

Table
![image](https://user-images.githubusercontent.com/50389985/226329870-e55c4d68-23e0-452b-9e73-e04349be3cc0.png)

### Answer

>select company, continent
>from forbes_global_2010_2014
>where sector = 'Financials'
>order by profits desc
>limit 1

![image](https://user-images.githubusercontent.com/50389985/226329946-846f1021-2dc6-48ba-849c-d41aa3bea23c.png)
