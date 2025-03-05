# Amazon Consumer Behavior & Purchase Analysis

# Project Overview

This project analyzes consumer behavior and purchasing patterns using an Amazon dataset. By leveraging Malloy, we explore key insights such as revenue distribution, purchasing habits, and survey responses linked to consumer demographics. The goal is to provide data-driven insights that can inform business strategies, marketing decisions, and customer engagement improvements.

# Why This Project is Important

Understanding how consumers interact with e-commerce platforms like Amazon is crucial for businesses and researchers. Our analysis provides insights into:

* **Total Revenue by region**

* **Consumer spending behavior based on demographics**

* **Most Purchased Product Categories**
  
* **Total Purchase by region**

* **Top 10 Best-Selling Products by Quantity**

These findings can help businesses tailor marketing strategies, optimize inventory management, and enhance customer experience.

# Data Cleaning & Preprocessing

**Before running the analysis, we conducted the following data cleaning steps:**

Handling Missing Values: Filtering missing values in key fields such as purchase price, quantity, and survey responses.

Standardizing Date Formats: Ensured consistency in Order Date format for time-series analysis.

Merging Datasets: Linked purchase and survey data using Survey ResponseID to enable cross-analysis.

# Key Findings

* **Total Purchases per State**
![image](https://github.com/user-attachments/assets/80fd4cc6-07ea-4163-85c4-d77418a0809a)  
  The heatmap analysis reveals significant variations in purchasing activity across U.S. states. **California, Texas, and Florida exhibit the highest purchase volumes**, likely due to their large populations, diverse consumer bases, and strong economic activity. These states also have major metropolitan areas with high concentrations of e-commerce users. Conversely, states with smaller populations, such as Wyoming and Vermont, show significantly lower purchase totals, which aligns with their lower number of potential consumers and less urbanized infrastructure.

  Additionally, factors like income levels, internet penetration, and regional shopping preferences may contribute to these differences. For example, urban areas with younger, tech-savvy populations may drive higher online sales compared to rural regions where traditional brick-and-mortar shopping remains prevalent. The color gradient visually represents this distribution, with darker shades indicating states with the highest transaction volumes.

  Understanding these regional trends can help businesses optimize marketing campaigns, tailor product offerings, and refine logistics strategies to target high-demand areas effectively.
* **Average Spending Amount by Product Category and Age**
![image](https://github.com/user-attachments/assets/42921ea6-5de2-4be5-a7c7-66101aa2c517)  
  The analysis of average spending by product category and age group reveals significant variations in purchasing behavior. The **35–44 age group** stands out as the highest spenders, particularly on high-ticket or niche products such as the **Ball Launcher**, which shows an exceptionally high average spending amount. Other expensive items, including personal computers, televisions, and elliptical trainers, attract spending across multiple age groups, indicating their broad appeal. **Younger consumers (18–24)** tend to spend less overall but show a preference for tech-related products like wireless devices and personal computers, suggesting that affordability and functionality drive their purchasing decisions. Meanwhile, **older age groups (55+)** allocate more spending towards practical and health-related items, such as wheelchairs and home goods, reflecting their lifestyle needs. The notably high spending on the Ball Launcher suggests a trend in premium pet care products, highlighting an emerging market segment. These insights emphasize the importance of age-specific marketing strategies, where businesses can optimize pricing, tailor promotions, and enhance product offerings to better align with the purchasing behaviors of different demographics.
* **Most Purchased Product Categories**  
![image](https://github.com/user-attachments/assets/17574f8a-9bf5-422a-b937-d1d89d0fcb8e)  
  The analysis of the most purchased product categories reveals that books dominate consumer purchases, with **nearly 80,000 transactions**, far surpassing other product categories. This suggests a **strong demand** for reading materials, potentially driven by academic, self-improvement, or leisure interests, presenting opportunities for publishers and e-commerce platforms to enhance book promotions through personalized recommendations or bundle deals. Shirts and health/personal care items rank as the second and third most purchased categories, indicating that fashion and self-care remain top consumer priorities, making them ideal for targeted marketing and subscription-based sales models. The popularity of tech accessories like cell phone cases highlights a trend in frequent device upgrades and customization, suggesting opportunities for brands to capitalize on accessory bundles or limited-edition designs. In contrast, physical movie media, tea, waste bags, and snack items exhibit lower purchase volumes, potentially reflecting consumer shifts toward digital entertainment and evolving dietary preferences. Businesses in these areas may need to adapt their strategies by focusing on digital product offerings or innovative marketing approaches to maintain relevance. Overall, the data provides valuable insights for businesses to refine their inventory management, pricing models, and marketing efforts to align with evolving consumer behaviors.
* **Total Revenue per State**  
![image](https://github.com/user-attachments/assets/e16b93d7-658e-4a3e-ae59-6dcb9bc8fd7c)
  Based on the revenue map of the United States, several key observations emerge. California and Texas stand out as the darkest blue states, indicating they have the highest total revenue among all states. These two large, economically diverse states are likely driving significant economic activity, which is reflected in their revenue levels. Other states in moderate to dark blue shades, such as Florida, New York, and Illinois, also appear to have substantial revenue contributions. The variation in color intensity suggests considerable economic disparities between states, with some states in lighter shades representing lower total revenue. This could be due to differences in population size, industrial composition, local economic conditions, and the presence of major corporations or industry clusters. The map provides a quick visual representation of economic output and fiscal strength across different regions of the United States.
* **Top 10 Best-Selling Products by Quantity**  
![image](https://github.com/user-attachments/assets/692c6a3a-d0fc-4623-8f0e-eeadd280faa2)  
  The bar chart reveals the sales quantities of the top 10 products, with the Amazon.com Gift Card clearly dominating the sales landscape. It has sold approximately 11,000 units, which is more than double the sales of the next best-selling product, the Amazon Reload. The significant gap between the top two products suggests that gift cards are an extremely popular and convenient sales item, potentially serving as both a product and a marketing tool. The subsequent products, including various Amazon-related cards and gift cards from other brands like Google Play and iTunes, show a gradual decline in sales volume. This pattern indicates that digital and flexible payment options are highly attractive to consumers, with gift cards providing an easy gifting solution and flexible spending option across different platforms and services.


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



