# Food_Establishment_Data_Analysis
An analysis of NoSQL data of food establishment ratings. This project involves using Jupyter Notebook to import data as a json file and creating and storing it in a new database in MongoDB. This project also includes database updates and an exploratory analysis of the data.

Original code sources: 
Data Analytics course Module 12 Challenge Starter_Code files, Data Analytics course instructor, Andrew Hoang's, speed run Zoom recording for Module 12 Challenge

References
UK Food Standards AgencyLinks to an external site. (2022). UK food hygiene rating data API. https://ratings.food.gov.uk/open-data/en-GBLinks to an external site.. Contains public sector information licensed under the Open Government Licence v3.0Links to an external site.
Accessed Sept 9, 2022 and Sept 12, 2022 with the establishment settings as follows: longitude=51.5072, latitude=-0.1276, maxdistancelimit=4567, pagesize=10000, sortoptionkey=distance, pagenumber=(1,2,3,4,5,6,7,8).

See uk_food_establishments_setup.ipynb Jupyter Notebook for data importing, database connection, and setup with PyMongo, Pretty Print, and Mongo Client. A new document was added to the database as well, with some cleaning updates.

See uk_food_establishments_analysis.ipynb Jupyter Notebook for an exploratory analysis of the data that uses the same setup as the previous notebook as well as creates multiple Pandas DataFrames from various queries in order to answer the following questions:

    Which establishments have a hygiene score equal to 20?
    Which establishments in London have a RatingValue greater than or equal to 4?
    What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
    How many establishments in each Local Authority area have a hygiene score of 0?
