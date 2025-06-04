# CodeAlpha_EDA
Exploratory Data Analysis (EDA) of Netflix's "Best Movie by Year" dataset, including data cleaning, visualization, and trend analysis by genre, year, and score.
## 📊 Netflix Best Movies by Year – Exploratory Data Analysis (EDA)
 This project performs Exploratory Data Analysis (EDA) on Netflix’s “Best Movie by Year” dataset to uncover trends, patterns, and insights related to genres, production houses, and IMDB scores over time.
# 📁 Dataset Overview
Source: https://www.kaggle.com/datasets/hanyjr/netflix-datasets

Columns:

index: Row index

TITLE: Movie title

RELEASE_YEAR: Year of release

SCORE: IMDB or rating score

MAIN_GENRE: Primary genre

MAIN_PRODUCTION: Main production company

# ✅ Objectives
Inspect and clean the dataset

Visualize distribution of genres, scores, and production houses

Analyze score trends over the years

Identify any anomalies or data quality issues

Generate insights for further modeling or storytelling

## 🧹 Data Cleaning
Removed rows with missing SCORE

Filled missing MAIN_PRODUCTION values with 'Unknown'

Converted RELEASE_YEAR to integer

Reset DataFrame index after cleaning

# 📊 Key Analyses & Visuals
Distribution of IMDB scores

Most common genres and production companies

Year-wise trends in movie ratings

Average scores by genre

Outlier detection using boxplots

# 🛠️ Tools & Libraries
Python 

Pandas

Seaborn

Matplotlib

SciPy (for hypothesis testing)

# 📈 Sample Insights
Certain genres (e.g., Drama) have higher average scores over time.

IMDB scores remained fairly stable with slight fluctuations.

A few production houses repeatedly appear among top-rated movies.

# 🚀 How to Use
Clone this repo

Run the notebook on Kaggle or locally (Jupyter/Colab)

Explore the visualizations and modify the code for deeper analysis










