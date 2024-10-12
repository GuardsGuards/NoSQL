Module 12 Challenge - NoSQL UK Food Establishments Analysis
Overview
This project involves working with data from the UK Food Standards Agency to help journalists and food critics from the magazine Eat Safe, Love identify establishments to feature in their articles. The goal is to use MongoDB, PyMongo, and Jupyter Notebook to query and update food hygiene ratings data, followed by exploratory data analysis to answer key questions provided by the magazine.

Features
Part 1: Database Setup
MongoDB Setup: A NoSQL database named uk_food with a collection called establishments is created.
Data Import: Data is imported from the establishments.json file into MongoDB.
Database Connection: A MongoDB client instance is created to interact with the database using PyMongo and Pretty Print (pprint).
Data Validation: The database, collection, and sample documents are verified.
Part 2: Database Updates
Add New Establishment: A new halal restaurant, "Penang Flavours", is added to the database.
Update BusinessTypeID: The BusinessTypeID for "Restaurant/Cafe/Canteen" is updated for the new restaurant.
Remove Dover Establishments: All establishments within the Dover Local Authority are removed.
Convert Data Types: Data types for latitude, longitude, and RatingValue are converted to decimals and integers respectively.
Part 3: Exploratory Analysis
Hygiene Scores: Query to find establishments with a hygiene score of 20.
London Establishments: Query to find establishments in London with a RatingValue of 4 or higher.
Top 5 Establishments: Identifies the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, near the new restaurant "Penang Flavours".
Hygiene Score 0: Aggregates the number of establishments with a hygiene score of 0 in each Local Authority area, sorted from highest to lowest.
