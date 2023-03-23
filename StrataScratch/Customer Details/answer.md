Customer Details

Q
Find the details of each customer regardless of whether the customer made an order. Output the customer's first name, last name, and the city along with the order details.
You may have duplicate rows in your results due to a customer ordering several of the same items. Sort records based on the customer's first name and the order details in ascending order.
![image](https://user-images.githubusercontent.com/50389985/227086547-1ff7a082-a025-46eb-908a-af488cb47e68.png)

A
select c.first_name, c.last_name, c.city, o.order_details
from customers c
left join orders o
on c.id = o.cust_id
order by c.first_name, o.order_details;

![image](https://user-images.githubusercontent.com/50389985/227086579-a7d4210f-d1cc-4864-b031-d41182492482.png)


https://platform.stratascratch.com/coding/9891-customer-details?code_type=3
