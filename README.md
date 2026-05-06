# Project Overview
This project focuses on performing data cleaning, preprocessing, and statistical analysis on the Google Play Store dataset. The goal is to transform raw, inconsistent data into a structured format and extract meaningful insights.

## Objectives
- Clean and preprocess raw dataset
- Handle missing values and duplicates
- Convert inconsistent data types into usable formats
- Perform exploratory data analysis (EDA)
- Generate statistical summaries for insights

## Dataset Description
The dataset contains information about mobile applications on the Google Play Store, including:

- App Name
- Category
- Rating
- Reviews
- Size
- Installs
- Type (Free/Paid)
- Price
- Content Rating
- Genres

## Technologies Used
- Python
- Pandas
- NumPy
- Jupyter Notebook

## Data Cleaning Steps
- Removed duplicate records
- Identified and handled missing values
- Converted columns like:
- Reviews → Numeric
- Installs → Cleaned and converted to integer
- Price → Converted to float
- Fixed inconsistent data formats
- Removed invalid/non-numeric entries

## Exploratory Data Analysis
- Checked dataset shape and structure
- Viewed sample records using:
  head(), tail(), sample()
- Analyzed data types and null values using info()
- Generated statistical summaries using describe()
- Identified duplicate rows
- Explored distribution of features

## Key Insights
- Most app ratings are concentrated between 4.0–4.5, indicating limited variation in user ratings
- App installs show a highly skewed distribution, where a small number of apps dominate downloads
- Free apps significantly outnumber paid apps and achieve much higher install counts
- Found weak correlation between ratings and installs, suggesting popularity depends on multiple   factors beyond user ratingspp trends

## Learning
- Gained hands-on experience in data cleaning and preprocessing, handling missing values,           duplicates, and inconsistent formats
- Improved skills in Pandas and NumPy for efficient data manipulation and transformation
- Learned how to convert raw data into analysis-ready structured datasets
- Developed strong exploratory data analysis (EDA) skills to identify patterns, trends, and        anomalies
- Understood the importance of data quality in real-world datasets before performing analysis or   modeling
- Practiced deriving actionable insights from data rather than just performing calculations
