
# E-Commerce Store Data Analysis Project

## **Project Overview**
The goal of this project is to perform an Exploratory Data Analysis (EDA) on an e-commerce store's past data to uncover trends and patterns in customer behavior, purchasing habits, marketing impact, pricing effectiveness, and product quality. The insights derived will inform strategic recommendations to improve business operations, customer retention, and profitability.

---

## **Data Source**
The dataset consists of historical transaction records from the e-commerce store, including:
- **Customer Demographics**: Age, income level, and satisfaction scores.
- **Purchase Information**: Purchase amount, product category, and return rate.
- **Marketing Data**: Social media influence scores and engagement metrics.
- **Shipping Preferences**: Shipping methods selected per purchase.
- **Discount Usage**: Discount sensitivity and impact on returns.

---

## **Tools Used**
- **Microsoft Excel**:
  - For data cleaning, transformation, and analysis.
  - Created calculated columns, Pivot Tables, and charts.
- **Data Visualization**:
  - Bar charts, stacked column charts, scatter plots, and line graphs were used to illustrate insights.
- **Markdown Documentation**:
  - Used GitHub-friendly Markdown for this project report.

---




## **Analysis and Insights**

### **1. Customer Demographics and Purchase Behavior**
#### **Steps Taken**
- Grouped customers into two age groups: **Young (below 35 years)** and **Old (above 36 years)** using the formula:
  ```excel
  =IF(Age<35, "Young", "Old")
  ```
- Compared spending, product category preferences, and income contributions using Pivot Tables.
- Visualized findings with bar charts comparing spending, preferences, and income levels.

![Screenshot 2025-03-24 213605](https://github.com/user-attachments/assets/be6c8f23-93f3-4397-9725-6ab90d05685f)


#### **Findings**
- **Spending**: Old customers spent more ($7,292.13) than Young customers ($6,550.28).
- **Product Categories**: Electronics was the most popular category for both groups.
- **Income Level**: High-income customers drove most of the spending for both age groups.

#### **Recommendations**
- Focus marketing efforts:
  - **Young Customers**: Promote electronics and provide targeted offers for high-income individuals.
  - **Old Customers**: Highlight premium or luxury products.
- Expand adjacent product categories related to Electronics for cross-selling opportunities.

---

### **2. Customer Loyalty and Retention Analysis**
#### **Steps Taken**
- Calculated return rates and grouped customers into three categories:
  - **No Returns**: `Return_Rate = 0`
  - **Low Returns**: `Return_Rate < 0.2`
  - **Frequent Returns**: `Return_Rate >= 0.2`
  - Formula used:
    ```excel
    =IF(Return_Rate=0, "No Returns", IF(Return_Rate<0.2, "Low Returns", "Frequent Returns"))
    ```
- Analyzed the relationship between customer satisfaction and brand loyalty using correlation and scatter plots.


![Screenshot 2025-03-24 214100](https://github.com/user-attachments/assets/21220096-767f-4c03-b028-6607a99a9cfc)


#### **Findings**
- Customers with **No Returns** had the highest total purchases ($98,755.66).
- Categories with the highest returns:
  - **Jewelry & Accessories** and **Electronics** had high return volumes.
- High satisfaction scores correlated with greater brand loyalty.

#### **Recommendations**
- Address high-return categories by improving product quality and descriptions.
- Retain No Return customers with exclusive offers or loyalty programs.
- Proactively support dissatisfied or frequent returners to enhance satisfaction.

---

### **3. Pricing and Discounts Effectiveness**
#### **Steps Taken**
- Grouped customers into discount sensitivity levels: **Very Sensitive**, **Somewhat Sensitive**, and **Not Sensitive**.
- Analyzed the effect of discounts on return rates and income levels.


![Screenshot 2025-03-24 214350](https://github.com/user-attachments/assets/7606e7bb-2f8d-45ce-b9cc-420e3ae5d6f0)



#### **Findings**
- **Spending**: Very Sensitive customers spent the most ($96,526.47).
- **Return Rates**: Discounted items had slightly lower return rates (0.938 vs. 0.971).
- **Income Level**: High-income customers showed strong interest in discounts, using them for 51.50% of purchases.

#### **Recommendations**
- Focus discount campaigns on Very Sensitive customers.
- Optimize pricing strategies for products with historically low return rates.
- Develop exclusive bundles for high-income customers to maximize sales.

---

### **4. Purchase Behavior and Preferences**
#### **Steps Taken**
- Analyzed the relationship between purchase categories and shipping preferences.
- Extracted the busiest shopping days from the dataset.


![Screenshot 2025-03-24 214703](https://github.com/user-attachments/assets/80fc42ec-6c0e-4467-9df5-269ddcba8616)



#### **Findings**
- **Shipping Preferences**:
  - **Express Shipping**: Popular for Jewelry, Luxury Goods, and Baby Products.
  - **Standard Shipping**: Dominates categories like Furniture and Food & Beverages.
- **Shopping Days**:
  - Sunday was the busiest shopping day with 82 purchases, while Wednesday had the fewest (60).

#### **Recommendations**
- Offer express shipping bundles for high-demand categories.
- Target Sunday shoppers with flash sales and promotions.
- Incentivize purchases on Wednesdays to drive midweek sales.

---

### **5. Marketing and Ad Engagement**
#### **Steps Taken**
- Analyzed the impact of **Social Media Influence** on purchase amounts and product ratings.
- Grouped customers by influence levels: High, Medium, Low, None.


![Screenshot 2025-03-24 214837](https://github.com/user-attachments/assets/56b3e859-43a6-4db4-8286-3dca20ddeed3)



#### **Findings**
- **Purchase Amounts**: High influence customers contributed the most to total purchases ($76,192.92).
- **Product Ratings**: Average ratings were highest for customers with No Influence (3.06), suggesting a potential discrepancy between expectations and satisfaction.

#### **Recommendations**
- Target High Influence customers with premium products and campaigns.
- Address potential mismatches in product descriptions for social media advertisements.
- Develop strategies to engage Medium and Low Influence customers and increase their spending.

---

### **6. Return Rate and Product Quality**
#### **Steps Taken**
- Correlated **Product Ratings** with **Return Rates**.
- Identified the product categories with the highest return rates.


![Screenshot 2025-03-24 215104](https://github.com/user-attachments/assets/e20a4ea4-8418-455b-990a-6b8deda20530)



#### **Findings**
- **Low Ratings**: Products with low ratings (<3) had the lowest average return rate (0.90).
- **High Return Categories**: Travel & Leisure (Flights), Gardening & Outdoors, and Office Supplies.
- **Dissatisfied Customers**: Customers with Low Satisfaction scores accounted for the highest return rates.

#### **Recommendations**
- Improve quality control and set clear expectations for high-return categories.
- Focus customer service efforts on dissatisfied customers to prevent returns.
- Analyze why low-rated products show lower-than-expected returns to refine product offerings.

---



