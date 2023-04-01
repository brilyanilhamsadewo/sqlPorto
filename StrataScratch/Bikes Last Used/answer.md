Bikes Last Used

Find the last time each bike was in use. Output both the bike number and the date-timestamp of the bike's last use (i.e., the date-time the bike was returned). Order the results by bikes that were most recently used.
![image](https://user-images.githubusercontent.com/50389985/229297068-65f45cf5-8eb6-4d28-95db-81bc865ee33d.png)


select bike_number, max(end_time)
from dc_bikeshare_q1_2012
group by bike_number
order by end_time desc;
![image](https://user-images.githubusercontent.com/50389985/229297086-1ef12259-c085-4ed4-9f31-5b7b3ae499b3.png)

