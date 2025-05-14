# 📊 Instacart Market Basket Analysis Dashboard

## 🔍 Executive Summary
The goal of this project is to create an interactive dashboard that provides insights into customer purchasing behavior, product demand, and order patterns using the Instacart Market Basket Analysis dataset. The dashboard will help visualize key metrics and trends, enabling data-driven decision-making for e-commerce and retail analytics.

---

## 📖 Table of Contents
1. **Project Objectives**
2. **Dataset Overview**
3. **Technologies & Tools**
4. **Methodology**
5. **Key Performance Indicators (KPIs)**
6. **Metrics**
7. **Customer Segmentation**
8. **Churn Analysis** 
9. **Project Timeline & Milestones**
10. **Roles & Responsibilities**
11. **Contributions & Support** 
---

## 🏆 Project Objectives
### **1- Analyze customer behavior and trends:**
-	Explore purchasing patterns, including the most in-demand categories and products. 
-	Understand the days and hours of peak purchases.
-	Determine the order frequency for each customer to understand purchasing habits.
### **2- Improving your personalized recommendation system:**
-	Develop an intelligent recommendation system based on past orders and customer behavior. 
-	Using market basket analysis to identify products that are frequently purchased together. 
-	Increasing conversion rates by suggesting related products.
### **3- Improve inventory and demand management:**
-	Predict seasonal demand fluctuations to avoid stockouts. 
-	Identify high-demand products to ensure consistent availability. 
-	Reduce waste from unwanted products through proactive analysis.
### **4- Boost customer loyalty and reduce customer churn:**
-	Implement proactive strategies such as personalized offers and discounts. 
-	Evaluate the impact of loyalty programs on increasing customer retention.   
### **5- Improve operational efficiency in ordering and delivery processes:**
-	Analyze average order fulfillment times and identify delay
-	Improve supply chain management to ensure speedy shipping.
-	Reduce operating costs by optimizing ordering and product distribution processes.
### **6- Explore market trends:**
-	Discover seasonal changes and emerging products through historical data analysis.
-	Identify the impact of external factors (such as holidays and seasons) on demand.
-	Provide strategic recommendations to marketing and sales departments to improve strategies.

---

## 📁 Dataset Overview
- **Source**: [ Data link ](https://www.kaggle.com/datasets/psparks/instacart-market-basket-analysis)
   
### **Dataset Description:**
  The Instacart Market Basket Analysis dataset is a comprehensive collection of anonymized data detailing over 3 million grocery orders from more than 200,000 Instacart users. This dataset encompasses information on user purchase histories, product details, and the sequence of orders, making it a valuable resource for various data analysis projects.   
#### **Dataset Components:**
The dataset is organized into several interconnected tables:
  - **Orders:** Contains information about each order, including the user ID, order sequence number, day of the week, and time of day the order was placed.
  - **Products:** Lists all products available, along with their unique product IDs and corresponding department and aisle IDs.
  - **Order Products:** Details the products included in each order, specifying whether each product is a first-time purchase or a reorder.
  - **Departments:** Provides department IDs and their respective names, categorizing products into broader groups.
  - **Aisles:** Offers aisle IDs and names, further refining the product categorization within departments.

To know more about dataset click [HERE](https://github.com/DEPI-Pioneers/project/blob/main/Instacart%20Market%20Basket%20Analysis%20Dataset.pdf)

---

## 🛠 Technologies & Tools
| Functionality | Tools |
|--------------|-----------------------------|
| **Business Intelligence** | Tableau |
| **Data Science & Machine Learning** | Python, Scikit-learn, TensorFlow |
| **Data Management** | SQL |
| **Version Control** | Git, GitHub |

--- 
## 📌 Methodology

### **1. Data Collection & Preprocessing**
- Collected **Instacart Market Basket** dataset, integrating multiple tables: **orders, products, users, aisles, and departments**.
- Cleaned data by handling missing values, removing inconsistencies, and standardizing categorical variables.
- Engineered features such as **"days since last order," "purchase frequency," and "customer recency."**

### **2. Exploratory Data Analysis (EDA) & Feature Engineering**
- Identified **top-selling products, reorder trends,** and **time-series shopping patterns.**
- Created **basket-level features** (average order size, most purchased category, etc.).
- Applied **dimensionality reduction (PCA)** for optimizing high-dimensional categorical data.

### **3. Customer Segmentation & Behavioral Analysis**
- Used **RFM (Recency, Frequency, Monetary) analysis** to classify customers into high-value, loyal, and churn-risk segments.
- Implemented **K-Means clustering** for segmentation based on purchase behavior.
- Conducted **market basket analysis (Apriori Algorithm)** to identify frequently purchased product associations.

### **4. Reporting & Business Recommendations**
- Built **interactive dashboards (Power BI, Tableau)** to visualize trends and key insights.
- Recommended **personalized promotions** and **inventory optimizations** based on customer behavior.
- Suggested **marketing strategies** to improve customer retention and maximize revenue.

---
## 📌. KPIs – Key Performance Indicators

- **Total Orders:** The total number of orders placed on the platform.
- **Total Customers:** The number of unique customers who have made a purchase.
- **Average Products per Order:** The average number of products purchased in each order.
- **Reorder Rate:** The percentage of orders that involve repurchasing products.
- **Top Ordered Products:** A list of the best-selling products.
- **Most Popular Categories:** The most frequently ordered product categories (e.g., fruits, dairy, beverages).
- **Average Time Between Orders** Measure the average gap between orders for each customer using the "days_since_prior_order" field.
- **Peak Order Times:** Identify the hours and days with the highest number of orders using the "order_dow" and "order_hour_of_day" fields.
- **Total New Customers:** Count the customers who placed their first order, determined by order_number = 1.
- **Department Orders:** The departments that have the highest number of orders.
- **Top Products for New Customers:** The products most commonly purchased in a customer’s first order.
- **Average Time Between Reordering the Same Product:** The average period between repurchases of the same product.

---

## 📌. Metrics 

- **Customer Retention Rate:** The percentage of customers who make repeat purchases after their first order.
- **Average Orders per Customer:** The average frequency of orders per customer.
- **Most Reordered Products Rate:** Focuses on the products that are repurchased frequently.

---

## 📌. Segmentation – Customer Segmentation

### By Number of Orders:
- **New Customers:** Customers who have only placed one order.
- **Returning Customers:** Customers who have placed more than one order.
- **VIP Customers:** Customers with a very high number of orders compared to others.

### By Preferred Product Types:
- **Healthy Shoppers:** Customers who focus on healthy products (e.g., fruits and vegetables).
- **Convenience Shoppers:** Customers who purchase ready-to-eat meals or snacks.

### By Basket Size (Number of Products per Order):
- **Small Basket Customers:** Those who purchase 1–3 products per order.
- **Medium Basket Customers:** Those who purchase 4–10 products per order.
- **Large Basket Customers:** Those who purchase more than 10 products per order.

---

## 📌. Churn Analysis – Lost/Inactive Customers 

- **Last Purchased Product Before Churn:** Identify the last product a customer purchased before they stopped ordering.
- **Inactive Customer Rate:** Define inactive customers as those who placed only one order or stopped ordering after a few orders, and calculate their percentage out of all customers.
- **Top Products Bought by Churned Customers:** Analyze which products were commonly purchased by customers before they became inactive.


---
## Dashboard

![Screenshot 1](Screenshot%202025-05-13%20200446.png)  
![Screenshot 2](Screenshot%202025-05-13%20200511.png)  
![Screenshot 3](Screenshot%202025-05-13%20200524.png)  
![Screenshot 4](Screenshot%202025-05-14%20041307.png)
![Screenshot 5](Screenshot%202025-05-13%20200550.png)

---

## 📅 Project Timeline & Milestones
| Phase        | Key Activities | Duration |
|-------------|----------------|----------|
| **Phase 1** | Project Intuition & Requirement Gathering | 1 week |
| **Phase 2** | Data Collection | 1 week |
| **Phase 3** | Data Cleaning & Preprocessing | 1 week |
| **Phase 4** | Data Transformation & Feature Engineering | 1 week |
| **Phasa 5** | Dashboard Development in Tableau | 1-2 weeks |
| **Phase 6** | Final Review, Documentation & Deployment | 5 days |

---

## 👥 Roles & Responsibilities

| Team Member | Role | Responsibilities |
|-------------|------|-----------------|
| [**Abdulrahman Hakim**](https://www.linkedin.com/in/abdelrahman-hakim) | Team Leader & Data Manipulation | - Oversee the project, manage tasks, and ensure smooth workflow.  <br> - Handle data preprocessing, transformation, and ensure data accuracy.  <br> - *Supports BI & Statistical Analysis when needed.* |
| [**Suhaila Elnemr**](https://www.linkedin.com/in/suhaila-elnemr) | Data Manipulation & Feature Engineering | - Clean, transform, and structure data for analysis.  <br> - Ensure data consistency, handle missing values, and perform feature engineering for potential ML models.  <br> - *Supports BI & Statistical Analysis when needed.* |
| [**Amany Ehab**](https://www.linkedin.com/in/amany-latif) | Data Visualization & Dashboarding | - Create interactive dashboards using Power BI/Tableau.  <br> - Analyze trends and present data insights effectively.  <br> - *Supports BI & Statistical Analysis when needed.* |
| [**Shaimaa Elsayed**](https://www.linkedin.com/in/shimaa-el-saed-093ba4291) | Business Intelligence & Presentation & Statistical Analysis | - Define KPIs and analyze metrics.  <br> - Extract business insights and perform statistical analysis.  <br> - Lead project presentations. |



---

## ⭐ Contributions & Support
If you find this project valuable, give it a ⭐ and contribute via pull requests!  

---


