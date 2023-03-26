Find libraries who haven't provided the email address in circulation year 2016 but their notice preference definition is set to email

Q
Find libraries who haven't provided the email address in circulation year 2016 but their notice preference definition is set to email.
Output the library code.

![image](https://user-images.githubusercontent.com/50389985/227765749-d8264355-e499-41b5-97a0-abd28a5f9752.png)

A
select distinct home_library_code from library_usage where circulation_active_year =2016 and provided_email_address=0  and notice_preference_definition='email' ;

![image](https://user-images.githubusercontent.com/50389985/227765766-b82fe186-a3a0-498a-840c-5394141d12a7.png)
