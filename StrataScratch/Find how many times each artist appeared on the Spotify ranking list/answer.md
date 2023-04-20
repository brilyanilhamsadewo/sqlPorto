# Find how many times each artist appeared on the Spotify ranking list

---

### Question

Find how many times each artist appeared on the Spotify ranking list
Output the artist name along with the corresponding number of occurrences.
Order records by the number of occurrences in descending order.

![image](https://user-images.githubusercontent.com/50389985/229297123-757c327b-55af-41f7-b29e-17ad3a380b9b.png)

### Answer

>select artist, count(*)
>from spotify_worldwide_daily_song_ranking
>group by artist
>order by count(*) desc;

![image](https://user-images.githubusercontent.com/50389985/229297135-0d3a9732-4c4c-4163-aa58-477f711a9c49.png)
