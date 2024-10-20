# Walmart Customer Purchase Behavior Analysis

## Table of Contents
1. [About Walmart](#about-walmart)
2. [Business Problem](#business-problem)
3. [Data Overview](#data-overview)
4. [Objectives](#objectives)
5. [Data Cleaning and Preprocessing](#data-cleaning-and-preprocessing)
6. [Visual Analysis](#visual-analysis)
7. [Missing Value & Outlier Detection](#missing-value--outlier-detection)
8. [Analysis](#analysis)
   - [Gender Analysis](#gender-analysis)
   - [Marital Status Analysis](#marital-status-analysis)
   - [Age Group Analysis](#age-group-analysis)
   - [Confidence Interval Calculation](#confidence-interval-calculation)
9. [Recommendations](#recommendations)
10. [Conclusion](#conclusion)
11. [References](#references)

## About Walmart
Walmart Inc. is one of the world’s largest retail giants, serving over 100 million customers globally through its extensive network of supercenters, discount department stores, and grocery shops in the United States. Walmart is dedicated to leveraging data analytics to enhance customer experiences and improve sales. With millions of customers visiting their stores and shopping online, Walmart continually seeks innovative ways to understand and enhance customer shopping experiences.

## Business Problem
The management team at Walmart aims to gain deeper insights into customer purchase behavior, particularly during high-traffic sales events like Black Friday. They seek to understand how demographic factors such as gender, age, and marital status influence spending habits. 

A key question being investigated is:
**"Do women spend more on Black Friday than men?"**  
With a balanced customer base of 50 million males and 50 million females, the analysis aims to provide actionable insights that can inform strategic business decisions and improve marketing strategies.

## Data Overview
The dataset used for this analysis consists of the following features:
- **User_ID**: A unique identifier for each customer.
- **Product_ID**: A unique identifier for each product sold.
- **Gender**: The gender of the customer (Male/Female).
- **Age**: The age group of the customer.
- **Occupation**: A masked representation of the customer’s occupation.
- **City_Category**: The classification of the city (A, B, C).
- **Stay_In_Current_City_Years**: The number of years the customer has lived in their current city.
- **Marital_Status**: The marital status of the customer (Married/Unmarried).
- **Product_Category**: A masked representation of the product category.
- **Purchase**: The total amount spent by the customer.

### Dataset Characteristics
- **Total Records**: 550,068
- **Total Features**: 10
- **Demographic Diversity**: The dataset represents a wide range of demographic segments, making it suitable for comprehensive analysis.

## Objectives
The primary objectives of this analysis are:
1. To compare total purchase amounts between male and female customers during peak sales events.
2. To analyze spending patterns based on marital status and age groups.
3. To calculate confidence intervals for spending averages using the Central Limit Theorem (CLT).
4. To provide actionable recommendations for improving sales and customer satisfaction.

## Data Cleaning and Preprocessing
The data cleaning process involved several key steps to ensure the integrity of the analysis:
- **Data Type Conversion**: Categorical variables were appropriately converted to 'category' type for efficient data handling.
- **Missing Values**: A thorough check confirmed the absence of missing values in the dataset.
- **Duplicate Records**: Duplicate records were identified and removed to maintain data accuracy.
- **Descriptive Statistics**: Summary statistics were generated to provide insights into the distributions and characteristics of the data.

## Visual Analysis
Visual analysis was conducted to explore relationships between various features and purchase amounts:
- **Distribution Plots**: Histograms and boxplots illustrated the distribution of purchase amounts.
- **Categorical Analysis**: The impact of categorical features such as marital status, age, and city category on purchase amounts was visualized through bar charts and pie charts.

## Missing Value & Outlier Detection
The analysis included a thorough examination for outliers and missing values:
- **Outlier Detection**: Statistical methods were employed to identify outliers in the purchase amount data.
- **Outlier Impact**: Significant outliers were identified, leading to considerations for further analysis and potential exclusion to maintain data integrity.

## Analysis
### Gender Analysis
A detailed statistical analysis was conducted to compare purchase behaviors between male and female customers:
- **Mean and Standard Deviation**: Calculated for each gender to gain insights into average spending.
- **Confidence Intervals**: Established for mean purchase amounts to reveal significant differences in spending behaviors.

### Marital Status Analysis
An examination of purchasing behaviors based on marital status was performed:
- **Statistical Comparison**: Mean purchase amounts for married and unmarried customers were analyzed with confidence intervals calculated to determine the significance of observed differences.

### Age Group Analysis
The impact of age on purchasing behavior was explored:
- **Segmentation**: Customers were segmented into distinct age groups for focused analysis of spending patterns.

### Confidence Interval Calculation
To provide deeper insights, confidence intervals were calculated for population spending averages using the Central Limit Theorem (CLT):
- Sample averages were leveraged to compute confidence intervals (CIs) at various levels (e.g., 90%, 95%, 99%).
- The analysis included checking for overlaps in confidence intervals to determine significant differences in spending between genders.

## Recommendations
Based on the analysis findings, several recommendations can be made:
1. **Targeted Marketing Campaigns**: Develop campaigns tailored to female customers during key sales periods.
2. **Personalized Offers**: Create personalized offers for different marital statuses and age groups to increase engagement and drive sales.
3. **Enhanced Customer Insights**: Implement ongoing data analysis to refine customer segmentation and adapt marketing strategies accordingly.

## Conclusion
This analysis of customer purchase behavior at Walmart provides valuable insights into the spending patterns of different demographic groups. The findings highlight significant differences between genders and marital statuses, informing strategic decisions to enhance customer engagement and drive sales. By leveraging data-driven insights and statistical analysis, Walmart can optimize its marketing efforts and improve overall customer satisfaction.

## References
- Walmart Inc. Official Website
- Data Science and Analytics Literature
- Statistical Analysis Textbooks
