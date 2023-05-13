# nosql-challenge
Repository for Module 12 Challenge

README
This project examines a database called “uk_food” and a collection called “establishments.json”.
The file “NoSQL_setup_starter.ipynb” is loaded and updated as follows:
•	A new entry is added and updated:
•	Items from Dover Local Authority are dropped.
•	Latitude and longitude are converted to decimal numbers.
•	“RatingValue” is converted to  integer numbers.

The file “NoSQL_analysis_starter.ipynb” is used to perform exploratory analysis and to answer the following questions:
1.	Which establishments have a hygiene score equal to 20?
2.	Which establishments in London have a RatingValue greater than or equal to 4?
3.	What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
4.	How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.

Files:
NoSQL_setup_starter.ipynb
	-Loads database and prepares it as described above.
NoSQL_analysis_starter.ipynb
	-Preforms analysis as described above
README:
	-This file explaining project.
Resources/ establishments.json:
	-The data loaded for this analysis.
