Amazon Consumer Behavior & Purchase Analysis

Project Overview

This project analyzes consumer behavior and purchasing patterns using an Amazon dataset. By leveraging Malloy, we explore key insights such as revenue distribution, purchasing habits, and survey responses linked to consumer demographics. The analysis aims to uncover trends that can inform business strategies, marketing decisions, and customer engagement improvements.

Why This Project is Important

Understanding how consumers interact with e-commerce platforms like Amazon is crucial for businesses and researchers. Our analysis provides insights into:

Revenue trends by category and region

Consumer spending behavior based on demographics

The impact of life changes on purchasing habits

The relationship between survey responses and spending patterns

These findings can help businesses tailor marketing strategies, optimize inventory management, and enhance customer experience.

Data Cleaning & Preprocessing

Before running the analysis, we conducted the following data cleaning steps:

Handling Missing Values: Removed or imputed missing values in key fields such as purchase price, quantity, and survey responses.

Standardizing Date Formats: Ensured consistency in Order Date format for time-series analysis.

Removing Duplicates: Checked for and removed duplicate entries in both purchase and survey datasets.

Categorization: Standardized category names for consistent aggregation.

Merging Datasets: Linked purchase and survey data using Survey ResponseID to enable cross-analysis.

Key Findings

1. Revenue & Purchasing Trends

The top 10 best-selling products contributed to over 40% of total revenue.

The highest revenue-generating categories were electronics, books, and household items.

Seasonal trends showed a spike in purchases during Q4, likely due to holiday shopping.

2. Consumer Behavior Insights

Higher-income consumers spent significantly more on electronics and luxury goods.

Amazon usage frequency was highest among young adults aged 25-34.

Users with disabilities had unique spending patterns, indicating potential areas for inclusive marketing.

3. Survey Insights & Business Impact

Over 60% of respondents expressed concerns about selling their data, which may impact Amazon’s data monetization strategies.

Consumers experiencing major life changes (e.g., moving, job changes) exhibited increased spending.

Small business owners heavily relied on Amazon, indicating opportunities for tailored B2B services.

How to Build on This Work

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

Acknowledgments

Special thanks to our professor and course team for guidance on this project. Also, thanks to open-source contributors for their tools and documentation that made this analysis possible.

