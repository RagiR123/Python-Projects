Credit Card Customer Analysis & Credit Risk Insights
Project Overview

Analyzed credit card customer and repayment data using Python, statistical analysis, and data visualization to identify customer characteristics, income patterns, credit repayment behavior, and relationships between demographic and financial attributes.
The project combines Application Record and Credit Record datasets to transform raw data into a clean, analysis-ready dataset and generate business-oriented insights relevant to credit risk analysis, customer segmentation, and data-driven decision-making.

Business Objectives : 
Analyze customer demographics, income, employment, family, and housing characteristics.
Understand credit repayment status and customer credit behavior.
Compare applicant characteristics across different demographic groups.
Identify relationships between customer attributes.
Analyze income distribution and identify potential outliers.
Apply statistical tests to validate relationships and differences in the data.
Generate insights that can support credit risk and customer analysis.

Data Preparation & Cleaning :
Loaded and explored the Application Record and Credit Record datasets.
Examined dataset dimensions, data types, statistical summaries, and data structure.
Identified missing values and duplicate records.
Handled missing occupation values by categorizing them as "Unknown".
Merged application and credit data using Customer ID.
Prepared a clean and analysis-ready dataset for further analysis.

Feature Engineering :
Created analytical features from the raw data:
Age – calculated from recorded birth-date information.
Employment Years – converted employment duration into years while handling the dataset's special missing-value representation.
Income Category – segmented applicants into Low, Lower-Middle, Middle, Upper-Middle, and High income groups.

Performed EDA on:
Gender
Income type
Education level
Family status
Housing type
Number of children
Age
Income
Employment experience
Email registration
Occupation type
Credit repayment status

Data Visualization :
Created visualizations using Matplotlib and Seaborn, including:
Count plots for categorical variables.
Histograms for age and income distributions.
Credit repayment status visualizations.
Occupation and income-category analysis.
Boxplots for income outlier detection.
Correlation heatmap for numerical variables.
These visualizations helped convert raw customer data into clear trends, patterns, and business insights.

Statistical Analysis :
Chi-Square Test :
Analyzed the relationship between gender and car ownership.
Chi-square statistic: 153,486.31
p-value: < 0.001
Cramér's V: 0.361
The test identified a statistically significant association between gender and car ownership, with Cramér's V indicating a moderate effect size.

Independent Samples T-Test :
Tested whether average income differs between male and female applicants.
t-statistic: 196.38
p-value: < 0.001
The analysis identified a statistically significant difference in average income between the two groups.

Created a correlation matrix to examine relationships among:
Income
Age
Number of children
Family members
Employment experience
This helped identify potential relationships between demographic characteristics and financial attributes.

Outlier Detection :
Applied the Interquartile Range (IQR) method to identify unusual income values.
The analysis included:
Q1 and Q3 calculation
IQR calculation
Lower and upper bounds
Identification of income outliers
Percentage of observations classified as outliers
Boxplot visualization

Tools & Technologies :
Python, Pandas, NumPy, Matplotlib, Seaborn, SciPy, Jupyter Notebook

Skills :
Data Cleaning & Preprocessing
Exploratory Data Analysis (EDA)
Data Transformation
Feature Engineering
Data Integration & Merging
Statistical Analysis
Hypothesis Testing
Correlation Analysis
Outlier Detection
Data Visualization
Insight Generation

Output :
Generated a cleaned and feature-engineered dataset:
credit_cleaned.csv
The dataset can be used for further analysis, visualization, or BI dashboard development.

Business Value :
The project demonstrates how customer demographic, financial, and credit-history data can be transformed into actionable business insights. The analysis can support customer segmentation, credit risk analysis, customer profiling, reporting, and data driven decision making.
