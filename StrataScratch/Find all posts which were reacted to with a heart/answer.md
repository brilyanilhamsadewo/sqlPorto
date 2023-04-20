# Find all posts which were reacted to with a heart

---

### Question

Find all posts which were reacted to with a heart. For such posts output all columns from facebook_posts table.

![image](https://user-images.githubusercontent.com/50389985/227220224-6e3aa8aa-7074-4392-8bf7-c95913d34f71.png)

### Answer

>select * from facebook_posts
>where post_id IN (select post_id from facebook_reactions WHERE reaction = 'heart')

![image](https://user-images.githubusercontent.com/50389985/227220316-c8244640-843e-4293-9b58-df7d9c88a4ed.png)
