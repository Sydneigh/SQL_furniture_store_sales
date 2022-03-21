# SQL_furniture_store_sales

 This project required me to create a database, insert data and categorise it using GROUP BY, HAVING, AND and OR functions in SQLite.
I used a future store sales database to inquire highly popular payment types per country. The below picture is the database schema creation  and insertion of rows.

![sql query_database schema](https://user-images.githubusercontent.com/96391154/159232473-ba9c7cf3-a064-4497-b9a3-c04b7d971377.png)

![creating database schema](https://user-images.githubusercontent.com/96391154/159232504-a7370342-8d9d-4cf1-872f-d8cf475d61e0.png)

Next step was to view all the data in a user friendly table using AS function.

![sql query](https://user-images.githubusercontent.com/96391154/159233076-1e95ada8-fb83-4b3b-9854-8b88eb5002b7.png)

My final step was to use the CASE function on my database. I made a case for a highly popular payment type to have more than 15 transaction amounts and an average payment type to have less than 10 transaction amounts. I then grouped the data by country and payment type. The result shows that a highly popular payment type in the US is Visa. 

![payment type popularity ](https://user-images.githubusercontent.com/96391154/159235473-e53e7fef-6129-4c7a-a66d-51883a6e2dd7.png)

