# Smartwatch Data Analysis Project

##  Project Overview

This project focuses on Smartwatch data analysis using real-world
e-commerce data. The goal of this project is to perform data cleaning,
exploration, visualization, and insight generation from smartwatch
product data.

The dataset includes: - Product Name - Brand - Price - Original Price -
Discount - Ratings - Reviews - Sponsored Status - F-Assured Status -
Colour - Size

------------------------------------------------------------------------

##  Project Objectives

-   Perform data cleaning and preprocessing
-   Handle missing values
-   Detect and analyze outliers
-   Perform Univariate, Bivariate, and Multivariate Analysis
-   Generate meaningful business insights

------------------------------------------------------------------------

##  Tools & Technologies Used

-   Python
-   Pandas
-   NumPy
-   Matplotlib
-   Seaborn
-   Jupyter Notebook / Google Colab

------------------------------------------------------------------------

##  Data Analysis Steps

### 1️ Data Cleaning

-   Removed duplicates
-   Handled missing values
-   Converted price columns to numeric format
-   Extracted separate columns for Colour and Size using Regex

### 2️ Exploratory Data Analysis (EDA)

#### 🔹 Univariate Analysis

-   Price Distribution
-   Ratings Distribution
-   Discount Distribution
-   Brand Frequency

#### 🔹 Bivariate Analysis

-   Price vs Ratings
-   Price Category vs Ratings
-   Brand vs Average Rating
-   Sponsored vs Non-Sponsored comparison

#### 🔹 Multivariate Analysis

-   Brand + Price + Ratings relationship
-   Discount impact on Ratings

------------------------------------------------------------------------

##  Outlier Detection

IQR Formula: IQR = Q3 - Q1

Lower Bound: Q1 - 1.5 \* IQR

Upper Bound: Q3 + 1.5 \* IQR

Outliers are values below the lower bound or above the upper bound.

------------------------------------------------------------------------

##  Key Insights

-   Most smartwatches are budget-friendly.
-   High discounts do not always guarantee high ratings.
-   Sponsored products are not always higher rated.
-   F-Assured products tend to gain more customer trust.

------------------------------------------------------------------------

##  Business Recommendations

-   Focus on competitive pricing in the budget segment, as most
    customers prefer affordable smartwatches.
-   Improve product quality rather than relying only on high discounts
    to attract customers.
-   Enhance product descriptions and verified badges (like F-Assured) to
    build customer trust.
-   Brands with lower ratings should analyze customer reviews to improve
    features and service quality.
-   Use rating and review insights to optimize marketing strategies.

------------------------------------------------------------------------

##  Learning Outcomes

Through this project, I learned:

-   Practical data cleaning and preprocessing techniques
-   Handling missing values and duplicates
-   Detecting outliers using IQR method
-   Performing Univariate, Bivariate, and Multivariate Analysis
-   Creating meaningful visualizations
-   Converting raw data into business insights
-   Applying statistical concepts in real-world datasets

------------------------------------------------------------------------

##  Future Improvements

-   Build a machine learning model to predict product ratings.
-   Perform sentiment analysis on customer reviews.
-   Automate data scraping for real-time analysis.
-   Create an interactive dashboard using Power BI or Tableau.
-   Compare smartwatch data across multiple e-commerce platforms.

-----------------------------------------------------------------------

##  Conclusion

This project demonstrates strong understanding of: - Data Cleaning -
Data Visualization - Statistical Analysis - Business Insight Generation
