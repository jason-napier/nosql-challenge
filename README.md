# UK Food Standards Agency Food Hygiene Rating Analysis
Repository for Module 12 Challenge

## Overview

This project involves analyzing food hygiene ratings from various establishments across the United Kingdom. The data, provided by the UK Food Standards Agency, will be explored and analyzed to aid the editorial team of Eat Safe, Love magazine in deciding future article focus areas.

## Purpose
The file “NoSQL_analysis_starter.ipynb” is used to perform exploratory analysis and to answer the following questions:
1.	Which establishments have a hygiene score equal to 20?
2.	Which establishments in London have a RatingValue greater than or equal to 4?
3.	What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
4.	How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.

## Files
NoSQL_setup_starter.ipynb
	-Loads database and prepares it as described above.
NoSQL_analysis_starter.ipynb
	-Preforms analysis as described above
README:
	-This file explaining project.
Resources/ establishments.json:
	-The data loaded for this analysis.
 
## Notes
Special thanks to Tim Matanick and Em Greene for collaberation.

## References
UK Food Standards AgencyLinks to an external site. (2022). UK food hygiene rating data API. https://ratings.food.gov.uk/open-data/en-GBLinks to an external site.. Contains public sector information licensed under the Open Government Licence v3.0Links to an external site.
Accessed Sept 9, 2022 and Sept 12, 2022 with the establishment settings as follows: longitude=51.5072, latitude=-0.1276, maxdistancelimit=4567, pagesize=10000, sortoptionkey=distance, pagenumber=(1,2,3,4,5,6,7,8).
