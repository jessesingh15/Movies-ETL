# Movies-ETL
## Purpose and Overview of Analysis
Created an automed pipeline with data from Wikipedia, Kaggle metadata, and MovieLens rating data. This was used to create a model for predicting ratings of a movie or show to determine whether it should be featured on the clients online streaming service.
## Results
- Wrote an ETL function to read three data files. The function takes the Wikipedia JSON, the Kaggle metadata, and MovieLens csv files and creates three separate DataFrames.
- Extracted and Transform the Wikipedia data. Filtered out the TV shows, consolidated the redundant data, removed the duplicates, and formatted the Wikipedia data.
- Extracted and Transform the Kaggle and rating data Again. Consolidated the redundant data, removed the duplicates, formatted and grouped the data. The Kaggle and rating data were then merged with the Wikipedia movies DataFrame.
- Loaded the data into a PostgreSQL Database.
