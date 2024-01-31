# nosql-challenge
This repository contains code for the following requirement.

Import the data provided in the establishments.json file from your Terminal. Name the database uk_food and the collection establishments.

Find the BusinessTypeID for "Restaurant/Cafe/Canteen" and return only the BusinessTypeID and BusinessType fields.
Update the new restaurant with the BusinessTypeID you found.
Use update_many to convert latitude and longitude to decimal numbers.
Use update_many to convert RatingValue to integer numbers.

Answer the following questions
--------------------------------
Which establishments have a hygiene score equal to 20?
Which establishments in London have a RatingValue greater than or equal to 4?
What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.