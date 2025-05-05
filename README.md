Prompt 1: Create Schema
Initialize a new schema named finalproject in MySQL Workbench to store all project-related tables and data.

Prompt 2: Create Tables
Create three tables:

users – Stores user information (name, address, etc.)

locations – Stores coordinates and descriptions for people or photos

photographs – Links photos to location IDs

Prompt 3: Alter Tables
Modify key fields in each table to enforce NOT NULL constraints, improving data integrity.

Prompt 4: Create Index
Add a unique index to users.userid and create a meaningful index on photographs.photoid for optimized lookup.

Prompt 5: Enter Data
Insert sample records into the users table and confirm entries using SELECT *.

Prompt 6: Count Rows
Use SELECT COUNT(*) to confirm the number of user records.

Prompt 7: Add Column
Add a userid column to the photographs table to link each photo to a user.

Prompt 8: Column Integrity Issue
Evaluate and fix the newly added column to ensure it enforces proper data constraints (e.g., NOT NULL, foreign key).

Prompt 9: Populate Tables
Insert location data into the locations table and associate photos with locations and users in the photographs table.

Prompt 10: Retrieve User Names
Query the users table to display all users.

Prompt 11: Who's Taking Pictures?
Join users and photographs tables to identify which users have taken photos.

Prompt 12: Unique Photographers
Modify the previous query to return only distinct user names of those who’ve taken at least one photo.
