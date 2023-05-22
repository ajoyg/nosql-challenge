# NoSQL Challenge
Evaluate the food hygiene rating for vatious establishments across the United Kingdom fo Eat Safe, Love magazine. UCB Module 12 NoSQL challenge.

### Part 1 : Database and Jupyter notebook setup
1. The first step of the analysis is to import the establishment.json file from the Resources folder, the command line interface to import the file into a Mongo database is specified in the No_SQL_setup.ipynb Jupyter notebook.

### Part 2: Update the database
2. The script in the notebook updates the database with a new halal restaurant- Penang Flavours just openned in Greenwich, this restaurant is included in the analysis.
3. The script also updates fields like Business TYpe ID and covverts other fields to decimals and integers for further analysis.

### Part 3: Exploratory Analysis
The Jupyter notebook No_SQLanalysis.ipynb analyzes the following<br>
4. Establishments have a hygiene score equal to 20.
5. Establishments in London have a RatingValue greater than or equal to 4.
6. Top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours".
7. Establishments in each Local Authority area have a hygiene score of 0. The results are sorted from highest to lowest, along with the top ten local authority areas.