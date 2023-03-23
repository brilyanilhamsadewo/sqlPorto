Number Of Bathrooms And Bedrooms

Q
Find the average number of bathrooms and bedrooms for each city’s property types. Output the result along with the city name and the property type.

![image](https://user-images.githubusercontent.com/50389985/227085352-c64f01a1-2e3f-4eb4-8ba8-7e820d8b265a.png)


A
select city, property_type, avg(bathrooms) as n_bathrooms_avg, avg(bedrooms) as n_bedrooms_avg
from airbnb_search_details
group by city, property_type;

![image](https://user-images.githubusercontent.com/50389985/227085437-7d9fcb63-2b44-42d2-9cad-993827934dd8.png)


https://platform.stratascratch.com/coding/9622-number-of-bathrooms-and-bedrooms?code_type=3
