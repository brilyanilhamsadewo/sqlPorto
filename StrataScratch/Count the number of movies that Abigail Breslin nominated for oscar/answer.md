Count the number of movies that Abigail Breslin nominated for oscar

oscar_nominees
![image](https://user-images.githubusercontent.com/50389985/226307655-7cf907fe-e6ab-4e4c-8cce-7d1bb5d4e5cf.png)

Query
select nominee, count(movie) as movie_count
from oscar_nominees
where nominee = "Abigail Breslin";

![image](https://user-images.githubusercontent.com/50389985/226307817-094b90ca-9ca2-4aa9-8242-449617d6af3f.png)
