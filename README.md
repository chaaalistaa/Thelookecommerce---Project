# Comprehensive Analysis and Optimization Strategies for TheLook E-Commerce

# **1. Introduction**
- Dataset Overview: The "TheLook" eCommerce dataset hosted on Google   BigQuery is designed to analyze customer behavior, sales trends, and operational insights for a fictional clothing retailer.
Objective: Highlight goals such as identifying sales trends, understanding customer behaviors, enhancing customer retention, and driving repeat purchases.

# **2. Dataset & Tools Details:**
- Data source: https://console.cloud.google.com/marketplace/product/bigquery-public-data/thelook-ecommerce
- Available tables and key fields, such as:
  - Users: Customer demographics and traffic sources.
  - Orders: Purchase details, order status, and timestamps.
  - Events: Web traffic and session activity.
  - Products: Product categories, prices, and distribution details.
  - Order Items: Purchase-level granularity.
  - Distribution Centers: Inventory and shipment data.

**Tools** 
- BigQuery: For querying and analysis.
- Visualization Tools: Integration with Looker for data visualization.
  
# **3. Analysis Objectives**
**A. E-commerce A Trends (2019-2024):**
  - In-Depth InsightsE-commerce A has demonstrated remarkable growth from 2019 to 2024, particularly in revenue, profit, and order volume.
  - Gender distribution is evenly split, with 50% male and 50% female, reflecting the platform’s broad appeal.

**B. Customer Profile**
  - Demographics
    - Age and Gender: The primary customer base consists of young adults and middle-aged individuals (20-59 years old).
      
- Geographical Distribution:
  - Users are spread across 15 countries, with the top 5 countries being:
    1. China
    2. USA
    3. Brazil
    4. South Korea
    5. France

  - User Growth Over Time:
    - 2019: Started with approximately 16,500 users.
    - 2021-2023: Experienced a decline due to market competition and global challenges (e.g., pandemic).
    - 2024: Witnessed a surge, driven by innovative products and enhanced marketing strategies.

<img width="371" alt="{3BFF1BD0-9D7E-46BC-99AD-2B9118142D07}" src="https://github.com/user-attachments/assets/112291d5-09b3-4c31-b042-4545fb9431d4">

**C. Traffic Insights:**

  - Traffic Sources:
    - The majority of visitors come from email campaigns, attracting over 1 million users. Other significant sources includes:
      1. AdWords
      2. YouTube ads
      3. Facebook campaigns
      4. Organic search
        
  - Visit Timing:
    - Peak visiting hours are between 1:00 AM and 8:00 AM, primarily on Thursdays, Fridays, and Saturdays.
    - This pattern suggests that users prefer browsing or shopping outside regular working hours, likely after completing their daily routines.
    - Peak visiting hours are between 1:00 AM and 8:00 AM, primarily on Thursdays, Fridays, and Saturdays.
    - This pattern suggests that users prefer browsing or shopping outside regular working hours, likely after completing their daily routines.

  - Purpose of Visits:
    - Most visitors are drawn to the platform by product promotions disseminated through these traffic sources.
   
  ![image](https://github.com/user-attachments/assets/f8fc5682-7643-4594-af9f-0467acde4db7)

    
**D. Purchase Behavior:**
- Shopping Habits:
  - Average products per order: 1 product.
  - Average spending per order: $86.66.
  - Repeat purchases typically occur every 1 year.
    
- Repeat Customer Frequency:
  - Currently, 29,814 customers have made more than one purchase within a 5-year period.
  - Challenge: This represents a low percentage compared to the total user base, indicating a need for strategies to boost customer loyalty and retention.

 <img width="646" alt="{39155B12-94C7-446B-9254-13ABC4CE5C9C}" src="https://github.com/user-attachments/assets/7b60ab22-9bad-4a8b-b3d2-e0f9c0ad1e77">

**E. Highest Revenue:**

<img width="451" alt="{78AEFE6C-CB5D-449A-AA71-5F190076026D}" src="https://github.com/user-attachments/assets/eed67d5b-6ce1-4056-a63e-d14f6cadbc58">

- Traffic Source:
  - The highest revenue is generated by purchases originating from search traffic, followed closely by organic traffic.
  - These two sources are the most significant drivers of revenue, showcasing the importance of optimizing visibility in search engines and maintaining strong organic presence.

**F. Loyalty and Churn Customer**
1. Most Spending Customers Insights from the Data:
  - A small percentage of customers contribute disproportionately to overall revenue.

2. Returning vs. Churning Customers
  -  Returning customers: Represent a consistent revenue stream but make up a relatively small portion of the overall user base.
  -  Churning customers: A significant number of users do not return after their first purchase, contributing to revenue leakage.

3. Non-Purchasing Users:
  - A considerable number of users browse the platform without completing a purchase.
  - This segment represents untapped potential, likely driven by barriers such as pricing, lack of trust, or unclear value propositions.

<img width="449" alt="{6718CEA7-2B63-4391-93DA-464B3077C883}" src="https://github.com/user-attachments/assets/d4965d20-2d2c-4ea2-a8b2-5a3dca52fc3b">

