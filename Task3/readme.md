Task 3 – Android App Market Analysis

Data Analytics Internship – Oasis Infobyte

Objective

The objective of this task is to analyze the Google Play Store dataset to understand app market dynamics. The goal is to clean and prepare the data, explore category-level trends, calculate key app metrics, analyze user sentiment, and create visualizations that highlight patterns in the Android app ecosystem.

Datasets Used
1. apps.csv

Contains app details such as category, rating, reviews, size, installs, price, and update information.

2. user_reviews.csv

Contains translated user reviews along with sentiment, polarity, and subjectivity.

Tools & Technologies Used

Python, Jupyter Notebook, Pandas, NumPy, Matplotlib, VS Code

Steps Performed
1. Data Loading

Loaded both CSV files using pandas and reviewed basic structure, data types, and sample records.

2. Data Cleaning

Removed unnecessary columns, handled missing ratings, and cleaned Size, Installs, and Price into correct numeric formats.
Cleaned user reviews by removing rows without text.
This ensured consistency and accuracy across datasets.

3. Category Exploration

Analyzed how apps are distributed across categories and calculated category-wise averages for rating, installs, and size.

4. Metrics Analysis

Computed mean, median, minimum, and maximum for Rating, Size, Installs, and Price to understand general app characteristics.

5. Sentiment Analysis

Examined user sentiments (Positive, Negative, Neutral) and calculated average polarity and subjectivity to understand user feedback.

6. Interactive Visualizations

Created bar charts, scatter plots, and distribution plots to visually represent category trends, install patterns, pricing, and sentiment.

Key Insights

Most apps are free, lightweight, and have strong ratings.

Communication and Social apps lead in total installs.

User sentiment is largely positive based on review polarity.

App popularity varies widely, with only a small group achieving massive downloads.

Games are popular but tend to be larger in size.

Project Files

Task3_Android_App_Analysis.ipynb – Notebook with complete analysis

readme.md – Documentation (this file)

Outcome

Successfully completed cleaning, exploration, metric computation, sentiment evaluation, and visualizations for the Google Play Store dataset. This task enhanced skills in data processing, visualization, and insight generation using Python.
