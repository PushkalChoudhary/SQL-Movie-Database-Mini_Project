# SQL Movie Project

![PostgreSQL](https://img.shields.io/badge/Database-PostgreSQL-blue)
![SQL](https://img.shields.io/badge/Language-SQL-lightgrey)
![Project Status](https://img.shields.io/badge/Status-Completed-brightgreen) 

##  Project Overview

This project is a **mini-SQL-based movie database system** that simulates a real-world OTT or cinema platform. I designed this project to apply my SQL skills in **data modeling, querying, and analysis**.

It includes multiple related tables like movies, genres, actors, users, ratings, and their relationship. I then performed a set of **analytical SQL queries** to generate insights from this relational schema.

---

## Database Schema

This project uses **7 relational tables**, designed with proper foreign key relationships and constraints:

- `movies` — list of movies with release year and duration  
- `genres` — types of genres like Drama, Action, etc.  
- `actors` — list of popular actors  
- `users` — mock users with country details  
- `ratings` — user reviews and ratings of movies  
- `movie_genres` — junction table for movie-genre many-to-many relationship  
- `movie_actors` — junction table for movie-actor many-to-many relationship  

Foreign key constraints and composite primary keys are implemented, and data has been added for testing using `INSERT` statements.

---

## Technologies Used

- PostgreSQL
- SQL
- pgAdmin

---

## Some queries I created to demonstrate analysis:

1. Top 5 rated movies
2. Highly-rated movies by Indian users
3. Genre-wise movie count
4. Actor who acted in most movies
5. Average rating given by each user
6. Rank movies by release year
7. Classify movies as Classic, Modern, or New
8. Movie recommendation of the day

---

## ERD

![ER Diagram](https://github.com/PushkalChoudhary/SQL-Movie-Database-Mini_Project/blob/acb7e9d3d6871e5ba5aa7f30f42059b4bfb63b6f/Script%20and%20ERD/SQL_Movie_Project_ERD.jpg)

---

## How to Run

1. Import the `SQL_Movie_Project.sql` file into your PostgreSQL database.
2. Run all `CREATE TABLE` and `INSERT INTO` statements.
3. Execute the queries at the bottom of the file to explore the data and results.

---

## File Included

- `SQL_Movie_Project.sql`

---

## What I Learned

This project helped me:

- Strengthen my understanding of **relational modeling**
- Apply **complex SQL queries** in a realistic schema
- Explore **data analysis** using SQL alone
- Practice writing **readable, structured SQL code**

---
