Popularity of Hack

Meta/Facebook has developed a new programing language called Hack.To measure the popularity of Hack they ran a survey with their employees. The survey included data on previous programing familiarity as well as the number of years of experience, age, gender and most importantly satisfaction with Hack. Due to an error location data was not collected, but your supervisor demands a report showing average popularity of Hack by office location. Luckily the user IDs of employees completing the surveys were stored.
Based on the above, find the average popularity of the Hack per office location.
Output the location along with the average popularity.

![image](https://user-images.githubusercontent.com/50389985/229360126-bcadca41-bd25-4e53-9f60-0371ca952604.png)


SELECT a.location, AVG(b.popularity)
FROM facebook_employees AS a
JOIN facebook_hack_survey AS b
ON a.id = b.employee_id
GROUP BY a.location;

![image](https://user-images.githubusercontent.com/50389985/229360147-3ba258a8-30e6-44be-b631-f36b2c5cf422.png)
