# Movies-ETL
## Overview
Amazing Prime, a streaming service for movies and TV shows, aimed to develop an algorithm to predict which low-budget movies will become increasingly popular, so that they can buy the streaming rights at a bargain price. They sponsored a hack-a-thon to rapidly mobilize predictions for the popular titles. However, in order to do so, they needed our help to create an automated pipeline that takes in new movie data, performs the appropriate transformations, and loads the data into existing tables. 

In this task, we needed to create the data sets for the hack-a-thon. We used data from three main sources: Wikipedia data, scraped from the web in JSON format, rating data from the MovieLens website, and Kaggle metadata.

ETL (Extract, Transform, and Load) is a process for collecting, cleaning, and saving data. The Extract step reads data from disparate data sources, while the Transform step converts the data into a useful format, and the Load step writes the data into the target database or data warehouse. In this analysis, we followed the ETL process which entailed: extracting the Wikipedia, Kaggle and ratings data, transforming the datasets through data cleaning and merging, and loading the cleaned dataset into a SQL database.

In working with the automated ETL pipeline, we can ensure that the dataset remains updated on a daily basis, as the transformed data is loaded into existing tables.

## Summary
In this repository, the ETL pipeline is detailed within the four attached jupyter notebook files, as well as images of the PgAdmin interface which indicate that the complete tables were added to our PostgreSQL database.


