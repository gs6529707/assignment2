# assignment2
Craigslist Vehicles Data Cleaning
Overview
This code is a Jupyter notebook (Assignment_2.ipynb) designed to clean and preprocess a dataset related to Craigslist car and truck listings. The primary goal is to prepare the data for analysis or machine learning tasks by handling missing values, standardizing formats, and ensuring data quality.

Steps
Upload Kaggle API Key:

The code prompts the user to upload their Kaggle API key for authentication.
Install Dependencies:

Imports necessary libraries such as Pandas and NumPy.
Download Dataset:

Downloads the dataset from Kaggle using the Kaggle API key.
The dataset used is related to Craigslist cars and trucks data.
Data Loading:

Loads the data into a Pandas DataFrame for further processing.
Data Cleaning:

Removes unnecessary columns and rows based on missing values.
Handles missing values in specific columns such as "odometer," "condition," "paint_color," "transmission," and more.
Uses statistical measures and common values to fill missing data where appropriate.
Categorical Data Handling:

Utilizes cross-tabulation to impute missing "model" values based on "year" and "manufacturer."
Fills missing values in other categorical columns like "manufacturer," "type," "size," and "drive" using the most common values.
Final Check:

Displays the cleaned dataset and checks for any remaining missing values.
Usage
Ensure you have the necessary dependencies installed.
Upload your Kaggle API key for authentication.
Run the notebook step by step to clean and preprocess the Craigslist vehicles dataset.
Note
This code assumes the dataset is available on Kaggle (austinreese/craigslist-carstrucks-data).
