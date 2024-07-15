# Recipe-Rescue


<b> Table1: User </b>

-user ID

-email

-password

-ingredients in fridge and pantry

-dietary restrictions

<b> Table2: Recipes </b>

-user ID

-meal name

-ingredient list

-cooking instructions

Relationship: 
the user ID is the primary key and foreign key for both tables. The User table has a one-to-many relationship with the Recipes table.

Steps to seed data to DB:

1. Make DB on Google Cloud.

2. Download data to folder.

3. Run the following command: mysql -u root -h "INSERT DB IP HERE" -p < database-file.sql
