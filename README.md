# Assignment: Sakila
Objectives:
Practice SQL queries
Using the Sakila database, complete the below queries.

You can get the Sakila database and ERD here (https://s3.amazonaws.com/General_V88/boomyeah2015/codingdojo/curriculum/content/chapter/sakila-data.sqland & http://s3.amazonaws.com/General_V88/boomyeah/company_209/chapter_3569/handouts/chapter3569_5431_sakila-db-model.png), please use these for reference.

Note
Earlier in this section, we recommended for students name their tables all lower case and have a primary key called 'id' in each table. These are the rules we follow, however not all developers follow these rules. The SQL file you'll be working with does NOT follow the rules we discussed, including naming the fields lower case. We still want you to follow the rules we taught, but use this as an opportunity to get comfortable with other SQL files that do not completely follow the rules of normalization.

Queries
1. What query would you run to get all the customers inside city_id = 312? Your query should return customer first name, last name, email, and address.

2. What query would you run to get all comedy films? Your query should return film title, description, release year, rating, special features, and genre (category).

3. What query would you run to get all the films joined by actor_id=5? Your query should return the actor id, actor name, film title, description, and release year.

4. What query would you run to get all the customers in store_id = 1 and inside these cities (1, 42, 312 and 459)? Your query should return customer first name, last name, email, and address.

5. What query would you run to get all the films with a "rating = G" and "special feature = behind the scenes", joined by actor_id = 15? Your query should return the film title, description, release year, rating, and special feature. Hint: You may use LIKE function in getting the 'behind the scenes' part.

6. What query would you run to get all the actors that joined in the film_id = 369? Your query should return the film_id, title, actor_id, and actor_name.

7. What query would you run to get all drama films with a rental rate of 2.99? Your query should return film title, description, release year, rating, special features, and genre (category).

8. What query would you run to get all the action films which are joined by SANDRA KILMER? Your query should return film title, description, release year, rating, special features, genre (category), and actor's first name and last name.
