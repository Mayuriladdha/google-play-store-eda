# Google Play Store Apps: Exploratory Data Analysis (EDA)

## Problem Statement
Which app categories, types, and features are associated with higher ratings and installs on the Google Play Store?

This project aims to analyze Google Play Store applications to identify factors influencing app ratings, popularity, user engagement, and market performance. The analysis helps uncover trends that can provide useful insights for app developers and businesses.

## Dataset
- **Source:** Kaggle – Google Play Store Apps Dataset
- **Dataset Size:** To be confirmed from the actual CSV file.
- **Format:** CSV
- **Key Columns:** App, Category, Rating, Reviews, Installs, Type, Price, Content Rating, Genres, Size, Last Updated, Android Version.

## Approach

### 1. Data Cleaning
- Identified and handled missing values, particularly in the Rating column.
- Checked for and removed duplicate app records.
- Cleaned and standardized categorical variables.
- Converted Installs and Price columns into appropriate numeric formats.
- Processed app Size values and handled inconsistent entries.
- Corrected data types to ensure accurate analysis.

### 2. Exploratory Data Analysis (EDA)
- **Univariate Analysis:** Examined app categories, ratings, installs, prices, and content ratings.
- **Bivariate Analysis:** Explored relationships between ratings and reviews, app categories and installs, and free versus paid applications.
- **Multivariate Analysis:** Investigated relationships among app ratings, installs, reviews, pricing, and categories.

### 3. Data Visualization
- Histograms to analyze rating and app-size distributions.
- Bar charts to identify the most popular app categories.
- Box plots to compare ratings and pricing across categories.
- Heatmaps to examine correlations between numerical variables.
- Count plots to compare free and paid applications.

## Key Insights
- Identified the category with the highest number of applications.
- Analyzed the average app rating across the dataset.
- Compared free and paid applications based on their distribution and ratings.
- Identified categories with the highest number of installs.
- Explored the relationship between user reviews, ratings, and app popularity.
- Examined pricing patterns and their relationship with app performance.

*Numerical findings and percentages will be added after calculating the results from the dataset.*

## Charts

![Category Distribution](images/category-distribution.png)

![Ratings Distribution](images/ratings.png)

![App Installs by Category](images/installs-by-category.png)

![Free vs Paid Apps](images/free-vs-paid.png)

## Tech Stack
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

## Project Objectives
- Understand the Google Play Store app ecosystem.
- Apply data cleaning and preprocessing techniques.
- Analyze factors associated with app ratings and popularity.
- Identify trends across app categories and pricing models.
- Develop analytical and data visualization skills.

## Conclusion
This project uses exploratory data analysis to understand the Google Play Store application ecosystem. By examining app categories, ratings, reviews, installs, and pricing, the analysis aims to identify patterns associated with application popularity and user engagement.

The findings can help app developers and businesses make more informed decisions about app development, positioning, and market opportunities.


## Author
**Mayuri Laddha** · [LinkedIn](https://www.linkedin.com/in/mayuri-laddha-135938404) · [GitHub](https://github.com/Mayuriladdha)
