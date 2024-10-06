# Credit EDA & Credit Score Calculation with Python

## Problem Statement
This project involves conducting a thorough **Exploratory Data Analysis (EDA)** and deep analysis of a dataset containing basic customer details and comprehensive credit-related information. The goal is to create new, informative features, calculate a **hypothetical credit score**, and uncover meaningful patterns, anomalies, and insights that will guide potential risk mitigation strategies and improve creditworthiness assessments.

## Dataset
- Dataset link: [Download Dataset](https://drive.google.com/file/d/1pljm6_3nxcFS9UMIFm124HBsjNZP6ACA/view?usp=sharing)
- Data Dictionary: [View Data Dictionary](https://docs.google.com/spreadsheets/d/1ZuK6o1MXFLmnhkFuDEedasDfVqu9ISPV/edit#gid=688359417)

## Project Expectations
This project focuses on a deep dive into customer credit data with the aim to:
1. Perform detailed **Exploratory Data Analysis (EDA)** to understand patterns and insights.
2. Engineer new, valuable features relevant to credit risk analysis.
3. Develop a methodology for calculating a **hypothetical credit score** using a set of relevant features.
4. Provide meaningful analysis that uncovers hidden patterns, informs credit risk, and guides strategic decisions.

## Key Steps and Suggestions

### 1. Exploratory Data Analysis (EDA)
- Perform a **comprehensive EDA** to explore the structure, characteristics, distributions, and relationships in the dataset.
- **Address missing values** and handle any inconsistencies, mismatches, or outliers in the data.
- Use visualizations such as **histograms, scatter plots, box plots, and correlation matrices** to uncover patterns and insights related to customer behavior and credit risk.

### 2. Feature Engineering
- **Create new features** derived from the dataset using domain knowledge and EDA insights. These features should provide additional context for credit score calculations.
- Consider aggregating data at the customer level, using metrics such as average credit utilization, delinquency counts, or other relevant aggregated statistics.
  
### 3. Hypothetical Credit Score Calculation
- **Develop a methodology** to calculate a hypothetical credit score for each customer, inspired by **FICO scores**.
- Choose **5 to 10 relevant features** that best capture creditworthiness (such as credit utilization ratio, payment history, loan-to-income ratio, etc.).
- **Explore weighting schemes** to assign scores to features and calculate a final credit score for each customer.
- Provide clear documentation and reasoning behind the feature selection and the weighting methodology used in score calculation.

### 4. Analysis and Insights
- Add valuable insights obtained from both EDA and credit score calculations.
- Explore whether **credit scores** and **aggregated features** can be calculated over different time periods (e.g., last 3 months, last 6 months) to assess recency-based credit behavior metrics.
  
## Tools and Technologies
- **Python**: Used for data analysis, feature engineering, and credit score calculation.
- **Pandas and Numpy**: For data manipulation and feature engineering.
- **Matplotlib and Seaborn**: For creating visualizations to assist with EDA.
- **Scikit-learn**: May be used for modeling and testing different credit score calculation techniques.

## Conclusion
This project aims to provide a clear methodology for calculating a **hypothetical credit score** based on a deep analysis of customer credit data. By performing thorough EDA and leveraging new features, this project will provide actionable insights into **creditworthiness** and potential **risk factors**. The results will help guide decision-makers in assessing and mitigating credit risk more effectively.
