# nosql-challenge

This assignment showcases database management using MongoDB

Restaurant data collected from the UK Food Standards Agency and can be found in the json file titled 'establishments.json'

This file was first imported into a MongoDB database titled 'uk_food', consisting of a collection titled 'establishments'. This step was completed using mongoimport. 

The imported database was then manipulated to add additional data as well as remove the Local Authority of Dover using the pymongo library to establish a MongoDB client in Python. The script for completing these steps can be found in the jupyter notbook file titled 'NoSQL_setup_starter.ipynb'.

Further analysis was completed on the MonogoDB collection titled 'establishments'. The analysis queried to filter by various criteria and create respective pandas dataframes for each query. These exercises can be found in the file titles 'NoSQL_analysis_starter.ipynb'.
