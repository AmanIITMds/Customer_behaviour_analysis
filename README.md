# Customer_behaviour_analysis
## 📌 Project Overview
This project analyzes customer shopping behavior using transactional data from 3,900 purchases across various product categories. The primary goal is to uncover insights into spending patterns, customer segments, product preferences, and subscription behavior to guide strategic business decisions.
+1

## 📂 Dataset Summary

Total Records: 3,900 rows 


Total Features: 18 columns 

Key Features:


Demographics: Age, Gender, Location, Subscription Status 


Purchase Details: Item Purchased, Category, Purchase Amount, Season, Size, Color 


Behavior: Discount Applied, Promo Code Used, Previous Purchases, Frequency, Review Rating, Shipping Type 


Missing Data: 37 missing values were identified in the Review Rating column.

## 🛠 Tech Stack & Methodology
1. Python (Data Cleaning & EDA)

Data Loading: Imported dataset using pandas.


Cleaning: Imputed missing values in Review Rating using the median rating of each product category.


Standardization: Renamed columns to snake case for better readability.

Feature Engineering:

Created age_group by binning customer ages.

Derived purchase_frequency_days from purchase data.

Dropped redundant columns (e.g., promo_code_used).


Integration: Loaded cleaned data into PostgreSQL for analysis.

2. SQL (Business Analysis)
Structured queries were executed to answer key business questions regarding revenue, product ratings, and shipping preferences.

3. Power BI (Dashboarding)
An interactive dashboard was built to visualize metrics such as total customers, average purchase amount, and revenue distribution.

## 📊 Key Insights
Revenue & Demographics

Gender: Male customers generated significantly higher revenue ($157,890) compared to Female customers ($75,191).
+1


Age Groups: "Young Adults" contributed the highest revenue ($62,143), followed closely by "Middle-aged" customers ($59,197).


Subscription Status: Non-subscribers account for the majority of revenue ($170,436) compared to subscribers ($62,645).

Product Analysis

Top Rated Products: Gloves (3.86), Sandals (3.84), and Boots (3.82) received the highest average ratings.

Discount Dependency: Hats and Sneakers had the highest percentage of discounted purchases, at approx. 50% and 49.66% respectively.
+1

Top Sellers by Category:


Accessories: Jewelry (171 orders) 


Clothing: Blouse (171 orders) 


Footwear: Sandals (160 orders) 


Outerwear: Jacket (163 orders) 

Customer Segments & Shipping

Segmentation: The majority of customers are classified as "Loyal" (3,116), followed by "Returning" (701) and "New" (83).


Shipping: Customers using Express shipping spend slightly more on average ($60.48) than those using Standard shipping ($58.46).

## 📈 Dashboard Highlights
The Power BI dashboard visualizes the following high-level metrics:


Total Customers: 3.9K 


Average Purchase Amount: $59.76 


Average Review Rating: 3.75 


Subscriber Split: 73% Non-Subscribers vs. 27% Subscribers.
+1

## 💡 Business Recommendations

Boost Subscriptions: Promote exclusive benefits to convert non-subscribers.


Loyalty Programs: Reward repeat buyers to maintain the high volume of "Loyal" segment customers.


Review Discount Policy: Balance sales boosts with margin control, particularly for high-discount items like Hats and Sneakers.
+1


Product Positioning: Highlight top-rated and best-selling products in marketing campaigns.


Targeted Marketing: Focus efforts on high-revenue age groups (Young Adults) and Express-shipping users.
