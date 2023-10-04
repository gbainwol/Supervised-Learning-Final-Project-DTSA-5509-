# Supervised-Learning-Final-Project-DTSA-5509-
The repository for my final project. 

Fantasy Football Predictions: Weekly Starts and Sits Prediction Model
Overview
This repository houses our project on predicting weekly starts and sits for Fantasy Football players, focusing on Wide Receivers, Running Backs, and Tight Ends. As an amalgamation of Fantasy Football passion and data science expertise, this project aims to provide insights that outperform standard projections.

Project Workflow
Data Exploration: We began with an extensive dataset of 17,400 entries and 53 columns, offering a deep dive into various metrics related to Fantasy Football. We pulled this from the nflreadr package in R. We also used R for the Data Cleaning but our analysis and modeling is done in python. 

Data Segmentation: Recognizing the unique patterns and metrics associated with different football positions, we segmented our data by positions: Wide Receivers, Running Backs, and Tight Ends. I also pulled QB data because it may be a influencing factor for our model. 

Data Cleaning & Preprocessing: To ensure the quality of our analyses, we underwent a rigorous data cleaning process. We saved the initial dataset as a CSV for reference and carried out position-specific data cleaning. I decided to only use data from 2020 forward due to the nature of short careers in the NFL. I created many csv files with scoring data, player statistics, active players, Defensive statistics broken down by rush, pass, and down efficiency. We filtered out the unnecessary data and created custom comprehensive datasets for our models.

The Report can be found here: [DTSA_5509_FINAL_REPORT ](https://github.com/gbainwol/Supervised-Learning-Final-Project-DTSA-5509-/blob/4919c97b2d14476334897fb605358d25d7b78d1c/Final_Project.pdf)

The first notebook can be found at: [SupervisedLearningFinalProjectpart1.ipynb](https://github.com/gbainwol/Supervised-Learning-Final-Project-DTSA-5509-/blob/da89dac3c7acaabe42d3f4cccac54fc37f7ef0b4/SupervisedLearningFinalProjectpart1.ipynb)

The second notebook can be found at: [DTSA_5509_Final_Project(4).ipynb](https://github.com/gbainwol/Supervised-Learning-Final-Project-DTSA-5509-/blob/a76a561b13d802962da81a1e7f0419dee9a80210/DTSA_5509_Final_Project%20(4).ipynb)

CSV files used for modeling can be found here [project csvs](https://github.com/gbainwol/Supervised-Learning-Final-Project-DTSA-5509-/tree/eba234a51dae044f489d0f816bff16c4d3b3cd1b/project_csvs)

CSV files used to create dataset and for data exploration and backfilling [CSVs_created](https://github.com/gbainwol/Supervised-Learning-Final-Project-DTSA-5509-/tree/8af9ca2fc6be1b3b57486dcfaedb63bd5b3d5aa9/csvs_created)


 # Description of Notebooks 

## First Notebook:

  
- Introduction: An overview of the project.
- Problem Statement: The specific challenges and issues addressed in the project.
- Goal: The objectives of the project.
- Metrics of Interest: Metrics used to evaluate the performance of the prediction model.
- ESPN Player Projection Metrics: A discussion of the metrics provided by ESPN for player projections.
- Hypothesis: The assumptions made or theories proposed that the project aims to test or validate.
- Further Readings on Fantasy Points: Additional resources and readings related to fantasy points.
- Scoring by Format for Fantasy Football: An explanation of different scoring formats in fantasy football, including PPR (Point Per Reception), Half PPR, and TE Premium.
- Notable Quote Regarding the Calculation of Weighted Opportunity: A quote or insight related to the calculation of weighted opportunities in fantasy football.
#### Creating the Datasets
- Player_stats Columns: Description or manipulation of the columns in the player stats dataset.
####  Data Cleaning
- Sorting Data for Active Players: Process of filtering and sorting data to focus on active players.
- Count of Active Players: A count or analysis of active players included in the dataset.
- Further Data Cleaning: Additional steps taken to clean and prepare the data for analysis.


## Second Notebook:

- Introduction: An overview of the project.
- Problem Statement: The specific challenges and issues addressed in the project.
- Goal: The objectives of the project.
- Metrics of Interest: Metrics used to evaluate the performance of the prediction model.
- ESPN Player Projection Metrics: A discussion of the metrics provided by ESPN for player projections.
- Hypothesis: The assumptions made or theories proposed that the project aims to test or validate.
- Further Readings on Fantasy Points: Additional resources and readings related to fantasy points.
- Further Briefing on Project: Additional explanation or context about the project.
- Scoring by Format for Fantasy Football: An explanation of different scoring formats in fantasy football, including PPR (Point Per Reception), Half PPR, and TE Premium.
- Notable Quote Regarding the Calculation of Weighted Opportunity: A quote or insight related to the calculation of weighted opportunities in fantasy football.
#### Dataset Creation
The process and steps involved in creating the dataset used for the project.
### Exploratory Data Analysis (EDA)
- Analysis to understand the data and its characteristics. It includes the calculation of weighted opportunity for all active running backs, wide receivers, and tight ends, and the production of an average for the offensive and defensive team statistics to produce a ranking/rating.
#### ARB Dataset:
- EDA specific to the dataset of active running backs.
#### AWR Dataset:
- EDA specific to the dataset of active wide receivers.

#### ATE Dataset:
 - EDA specific to the dataset of active tight ends.
## Modeling
- The section where the supervised prediction model is developed, trained, and validated.
##  Conclusion
- Final thoughts, findings, and insights derived from the project.
