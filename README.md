# Food_Establishment_Data_Analysis
An analysis of NoSQL data of food establishment ratings. This project involves using Jupyter Notebook to import data as a json file and creating and storing it in a new database in MongoDB. This project also includes database updates and an exploratory analysis of the data.

Original code sources: 
Data Analytics course Module 12 Challenge Starter_Code files, Data Analytics course instructor, Andrew Hoang's, speed run Zoom recording for Module 12 Challenge

See uk_food_establishments_setup.ipynb Jupyter Notebook for data importing, database connection, and setup with PyMongo, Pretty Print, and Mongo Client. A new document was added to the database as well, with some cleaning updates.

See uk_food_establishments_analysis.ipynb Jupyter Notebook for an exploratory analysis of the data that uses the same setup as the previous notebook as well as creates multiple Pandas DataFrames from various queries in order to answer the following questions:

    Which establishments have a hygiene score equal to 20?
    Which establishments in London have a RatingValue greater than or equal to 4?
    What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
    How many establishments in each Local Authority area have a hygiene score of 0?
