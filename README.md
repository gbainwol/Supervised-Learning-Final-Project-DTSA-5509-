# Supervised-Learning-Final-Project-DTSA-5509-
The repository for my final project. 

Fantasy Football Predictions: Weekly Starts and Sits Prediction Model
Overview
This repository houses our project on predicting weekly starts and sits for Fantasy Football players, focusing on Wide Receivers, Running Backs, and Tight Ends. As an amalgamation of Fantasy Football passion and data science expertise, this project aims to provide insights that outperform standard projections.

Project Workflow
Data Exploration: We began with an extensive dataset of 17,400 entries and 53 columns, offering a deep dive into various metrics related to Fantasy Football. We pulled this from the nflreadr package in R. We also used R for the Data Cleaning but our analysis and modeling is done in python. 

Data Segmentation: Recognizing the unique patterns and metrics associated with different football positions, we segmented our data by positions: Wide Receivers, Running Backs, and Tight Ends. I also pulled QB data because it may be a influencing factor for our model. 

Data Cleaning & Preprocessing: To ensure the quality of our analyses, we underwent a rigorous data cleaning process. We saved the initial dataset as a CSV for reference and carried out position-specific data cleaning. I decided to only use data from 2020 forward due to the nature of short careers in the NFL. I created many csv files with scoring data, player statistics, active players, Defensive statistics broken down by rush, pass, and down efficiency. We filtered out the unnecessary data and created custom comprehensive datasets for our models.
