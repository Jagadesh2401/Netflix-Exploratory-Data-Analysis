# Netflix Exploratory Data Analysis (EDA)
This project performs a comprehensive exploratory data analysis on the Netflix titles dataset to identify trends in content types, release years, and audience ratings.

## 📌 Project Overview
The analysis explores the Netflix catalog to uncover patterns in media distribution and production. Key objectives include:

Comparing the volume of Movies versus TV Shows.

Identifying primary target audiences through content rating distributions.

Visualizing content growth and release trends over time.

Analyzing data quality and handling missing values.

## 🛠️ Technologies Used
Python: Core programming language.

Pandas: Data manipulation and missing value analysis.

Matplotlib & Seaborn: Statistical data visualization.

NumPy: Numerical operations and data handling.

## 📊 Key Insights from Analysis
Based on the EDA results, the following findings were identified:

Content Volume: Netflix contains significantly more movies than TV shows.

Missing Data: The dataset has notable missing values in the director (29.9%), cast (9.3%), and country (9.4%) columns.

Release Trends: Most content currently on the platform was released after 2010.

Audience Ratings: The content is primarily targeted at mature audiences, with "TV-MA" being the most frequent rating.

## 📂 Project Structure
Netflix_EDA.ipynb: The Jupyter Notebook containing all Python code and visualizations.

netflix_titles.csv: The source dataset containing over 8,800 entries.

images/: A directory automatically created to store exported plots, such as movies_vs_tvshows.png.

## 🚀 Analysis Workflow
Data Loading: Importing the CSV and inspecting metadata via df.info() and df.describe().

Missing Value Analysis: Calculating the percentage of null values across all 12 columns.

Visual Exploration:

Count Plots: Comparing the distribution of "Movie" and "TV Show" types.

Histograms: Visualizing the distribution of release years.

Heatmaps: Analyzing correlations between numerical features.

Feature Engineering: Extracting numerical values from the duration column for deeper analysis.

## 📌 Final Summary
The Netflix dataset is highly categorical.

Content on the platform is heavily skewed toward modern releases.

Key features have been identified that could support future prediction tasks or recommendation engines.
