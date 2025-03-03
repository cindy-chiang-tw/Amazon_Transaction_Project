# Amazon Consumer Behavior & Purchase Analysis

# Project Overview

This project analyzes consumer behavior and purchasing patterns using an Amazon dataset. By leveraging Malloy, we explore key insights such as revenue distribution, purchasing habits, and survey responses linked to consumer demographics. The analysis aims to uncover trends that can inform business strategies, marketing decisions, and customer engagement improvements.

# Why This Project is Important

Understanding how consumers interact with e-commerce platforms like Amazon is crucial for businesses and researchers. Our analysis provides insights into:

Revenue trends by category and region

Consumer spending behavior based on demographics

The impact of life changes on purchasing habits

The relationship between survey responses and spending patterns

These findings can help businesses tailor marketing strategies, optimize inventory management, and enhance customer experience.

# Data Cleaning & Preprocessing

Before running the analysis, we conducted the following data cleaning steps:

Handling Missing Values: Removed or imputed missing values in key fields such as purchase price, quantity, and survey responses.

Standardizing Date Formats: Ensured consistency in Order Date format for time-series analysis.

Removing Duplicates: Checked for and removed duplicate entries in both purchase and survey datasets.

Categorization: Standardized category names for consistent aggregation.

Merging Datasets: Linked purchase and survey data using Survey ResponseID to enable cross-analysis.

# Key Findings

1. Total Purchases per State
![image](https://github.com/user-attachments/assets/80fd4cc6-07ea-4163-85c4-d77418a0809a)
2. Average Spending Amount by Product Category and Age
![image](https://github.com/user-attachments/assets/42921ea6-5de2-4be5-a7c7-66101aa2c517)
3. Most Purchased Product Categories
![image](https://github.com/user-attachments/assets/17574f8a-9bf5-422a-b937-d1d89d0fcb8e)
4. Total Revenue per State
![image](https://github.com/user-attachments/assets/e16b93d7-658e-4a3e-ae59-6dcb9bc8fd7c)
5. Top 10 Best-Selling Products by Quantity
![image](https://github.com/user-attachments/assets/692c6a3a-d0fc-4623-8f0e-eeadd280faa2)


# How to Build on This Work

Extending the Analysis

Incorporate additional datasets (e.g., Amazon reviews, third-party seller data) for deeper insights.

Use machine learning models to predict consumer purchasing behavior.

Conduct a sentiment analysis on product categories to correlate reviews with purchase behavior.

Running the Queries

Clone this repository:

git clone https://github.com/your-repo-name.git
cd your-repo-name

Install required dependencies (if applicable).

Use Malloy to run the provided queries and generate reports.

# Acknowledgments

Special thanks to our professor for guidance on this project. Also, thanks to open-source contributors for their tools and documentation that made this analysis possible.

