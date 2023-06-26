![alt text](https://github.com/Gbekoilias/Digital_Music_Data_Analysis/blob/main/Digital%20Music%20Cover%20Photo.jpg)
# Music_Store_Data_Analysis 🗂️
SQL project to analyze 📊 online music 🎶 store data

This project is for beginners in SQL to analyze the music playlist 🔀 database. You can examine the dataset with SQL and help the store understand its business  growth by answering simple questions❓.
## Database and Tools
* pg_admin v7.4
* PostgreSQL


## Data Sourcing and Structure
All data was obtained from [here](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbGlZaldRMzRPSkdkMlA0QmxxczZiY2NtZlNJUXxBQ3Jtc0tucDVZcTcyLXR4OWwtMGtxcjd0OXRzY1BESWdJNGY3SnQwNzlBSjlEVk5tUkRha29iVlphclpsQkphMENtYmR6WWsyOWxNUXFud0NZUE81bFN3bWkxQ1JkVGZkNkw4UGptMzRXUUdyS1VFOFpKNWZxcw&q=https%3A%2F%2Fbit.ly%2F3wYyp88&v=VFIuIjswMKM)
The Data base contain music labels and profiles of 11 tables namely, album, artist, customer, employee, genre, invoice, invoice_line, media_type, playlist, playlist_track and track
Each table contain at least a primary key and at least a foreign key as shown in the ER diagram below

![alt text](https://github.com/Gbekoilias/Digital_Music_Data_Analysis/blob/39408fb76b8e14855c4be881188d920942730569/MusicDatabaseSchema.png)

## Queestion set 1-Easy
### Who is the senior most employee based on job title?
![alt text](https://github.com/Gbekoilias/Digital_Music_Data_Analysis/blob/1bc5fa49270085166b648eb1b85e2d6c0da7f1be/screenchots/Screenshot%20(32).png)

### Which countries have the most Invoice?
![alt text](https://github.com/Gbekoilias/Digital_Music_Data_Analysis/blob/77fd9a742ba6a8ec9b3d0587e64e59ec42274def/screenchots/Screenshot%20(33).png)

### What are top 3 values of total invoice?
![alt text](https://github.com/Gbekoilias/Digital_Music_Data_Analysis/blob/77fd9a742ba6a8ec9b3d0587e64e59ec42274def/screenchots/Screenshot%20(34).png)

###  Which city has the best customers? We would like to throw a promotional Music Festival in the city we made the most money. Write a query that returns one city that has the highest sum of invoice totals. Return both the city name & sum of all invoice totals
![alt text](https://github.com/Gbekoilias/Digital_Music_Data_Analysis/blob/77fd9a742ba6a8ec9b3d0587e64e59ec42274def/screenchots/Screenshot%20(35).png)

###  Who is the best customer? The customer who has spent the most money will be declared the best customer. Write a query that returns the person who has spent the most money
![alt text](https://github.com/Gbekoilias/Digital_Music_Data_Analysis/blob/77fd9a742ba6a8ec9b3d0587e64e59ec42274def/screenchots/Screenshot%20(36).png)
