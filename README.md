# nosql_challenge
## Background Overview
Hypothetical Case: "The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles."

## Objectives
* Part 1: Database and Jupyter Notebook Set Up
  * Import the needed libraries: PyMongo and Pretty Print.
  * Create an instance of the Mongo Client.
  
* Part 2: Update the Database
  * Find specific BusinessTypeID
  * Update new restaurant name
  * Convert strings to decimal and integer values.
    
* Part 3: Exploratory Analysis
  * Which establishments have a hygiene score equal to 20?
  * Which establishments in London have a RatingValue greater than or equal to 4?
  * What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added?
  * How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.

## Summary
Successfully completed challenge assignment, obtaining 100/100 score. 

## References
UK Food Standards AgencyLinks to an external site. (2022). UK food hygiene rating data API. https://ratings.food.gov.uk/open-data/en-GBLinks to an external site.. Contains public sector information licensed under the Open Government Licence v3.0Links to an external site.
Accessed Sept 9, 2022 and Sept 12, 2022 with the establishment settings as follows: longitude=51.5072, latitude=-0.1276, maxdistancelimit=4567, pagesize=10000, sortoptionkey=distance, pagenumber=(1,2,3,4,5,6,7,8).

Codes developed in support from UCB Extension in-class reference examples and online questions searches including Stack Overflow forums.  
