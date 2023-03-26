Count the number of user events performed by MacBookPro users

Q
Count the number of user events performed by MacBookPro users.
Output the result along with the event name.
Sort the result based on the event count in the descending order.

![image](https://user-images.githubusercontent.com/50389985/227765533-896736bb-e6a6-47f9-9198-ec20c293c340.png)

A
select event_name, count(*) as count
from playbook_events
where device = 'macbook pro'
group by event_name
order by count(device) desc;

![image](https://user-images.githubusercontent.com/50389985/227765559-86fe0d94-8221-4a06-8ab0-8a29d3524e62.png)
