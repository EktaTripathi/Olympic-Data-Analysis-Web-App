# Olympic Data Analysis Web App
This repository contains code for an interactive web application built with Streamlit for analyzing Olympic data. The app offers various features for exploring and visualizing insights from the "120 years of Olympic history: athletes and results" dataset sourced from Kaggle.

# Dataset
The analysis is based on the "120 years of Olympic history: athletes and results" dataset available on Kaggle. This dataset provides comprehensive information about Olympic athletes, events, and results spanning over a century of Olympic history.
[click here](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results)

# Features
- Medal Tally: View medal tallies for different countries by selecting specific years or overall statistics.
- Overall Analysis: Explore top statistics including the number of editions, host cities, participating nations, sports, events, and athletes over the years.
- Country-wise Analysis: Analyze medal tallies, successful athletes, and sport performance for individual countries.
- Athlete-wise Analysis: Investigate the distribution of age, height, and weight among athletes, as well as the participation of men and women over the years.

# Data Preprocessing
The preprocessor.py file contains code for preprocessing the dataset, including filtering for Summer Olympics, merging with region data, dropping duplicates, and one-hot encoding medals.

# Helper Functions
The helper.py file consists of helper functions used for data analysis and visualization, such as fetching medal tallies, generating data over time, identifying successful athletes, and more.

# Usage
To run the application locally:

1. Clone the repository to your local machine.
2. Install the required dependencies by running pip install -r requirements.txt.
3. Run the Streamlit app using the command streamlit run app.py.
4. Access the application through your web browser.
