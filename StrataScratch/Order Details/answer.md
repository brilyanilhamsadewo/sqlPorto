# Order Details

----

### Question

Find order details made by Jill and Eva.
Consider the Jill and Eva as first names of customers.
Output the order date, details and cost along with the first name.
Order records based on the customer id in ascending order.

![image](https://user-images.githubusercontent.com/50389985/226330913-697afcfc-c617-4db5-818e-9cd8fcb28c79.png)

### Answer

>select c.first_name, o.order_date, o.order_details, o.total_order_cost 
>from customers c
>join orders o
>on c.id = o.cust_id
>where c.first_name = 'Jill'
>or c.first_name = 'Eva'
>order by o.cust_id asc;

![image](https://user-images.githubusercontent.com/50389985/226330993-046f5967-d19c-4d7b-bcb8-2c384aa056cc.png)
