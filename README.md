# Customer-behavior-data-analysis
data analytics project showcasing project customer behavior analysis using  Excel Python SQL Power BI 
# 🛒 Customer Shopping Behavior Analysis  

![Python](https://img.shields.io/badge/Python-3.9-blue?logo=python)
![SQL](https://img.shields.io/badge/SQL-MySQL-orange?logo=mysql)
![PowerBI](https://img.shields.io/badge/Power%20BI-Data%20Visualization-yellow?logo=powerbi)
![Excel](https://img.shields.io/badge/Excel-Data%20Cleaning-green?logo=microsoft-excel)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-blueviolet?logo=plotly)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-9cf)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

## 📊 Project Overview  
The **Customer Shopping Behavior Analysis** project explores 3,900 customer purchases to uncover insights into spending patterns, customer loyalty, and revenue drivers.  
Using **Excel, Python, SQL, and Power BI**, this project demonstrates a complete end-to-end data analytics pipeline — from cleaning and exploration to visualization and business recommendations.

---

## 🧩 Objectives  
- Analyze customer demographics and purchase trends  
- Identify top-performing products and customer segments  
- Evaluate the impact of discounts, subscriptions, and shipping preferences  
- Provide actionable business recommendations  

---

## 🗂️ Dataset Overview  
- **Total Records:** 3,900  
- **Features:** 18  
- **Geographic Coverage:** 50 locations  
- **Missing Values:** 37 (handled using median imputation)  

| Column | Description |
|--------|-------------|
| `customer_id` | Unique identifier for each customer |
| `gender` | Male / Female |
| `age_group` | Categorized customer age group |
| `item_purchased` | Product purchased |
| `purchase_amount` | Total spent in each transaction |
| `discount_applied` | Whether discount was applied (Yes/No) |
| `subscription_status` | Subscriber or Non-subscriber |
| `shipping_type` | Standard or Express |
| `review_rating` | Customer satisfaction score |
| `previous_purchases` | Number of past orders |

---

## 🧠 Tools & Technologies Used  

| Tool | Purpose |
|------|----------|
| **Excel** | Data overview, cleaning, and descriptive analysis |
| **Python (Pandas, NumPy, Matplotlib, Seaborn)** | Data preparation and EDA |
| **SQL (MySQL)** | Query-based customer and product analysis |
| **Power BI** | Interactive dashboards for visualization and storytelling |

---

## 🐍 Python Workflow  
1. Imported and explored dataset using `pandas`  
2. Cleaned and imputed missing values in `review_rating`  
3. Created derived columns (age group, purchase frequency)  
4. Visualized key patterns using `matplotlib` and `seaborn`  
5. Exported cleaned dataset to database and Power BI  

📁 Notebook: [`Customer_Shopping_Behavior_Analysis.ipynb`](./Customer_Shopping_Behavior_Analysis.ipynb)

---

## 🧾 SQL Insights  

📂 SQL file: [`customer_behavior_sql_queries.sql`](./customer_behavior_sql_queries.sql)

| Analysis | Description |
|-----------|-------------|
| **Revenue by Gender** | Compared male vs. female spending |
| **Discount Effectiveness** | Found high-spending customers who used discounts |
| **Top Products** | Ranked items by average review rating |
| **Shipping Impact** | Compared average spend between shipping types |
| **Subscription Impact** | Measured spend differences between subscribers and non-subscribers |
| **Customer Segmentation** | Classified customers into *New*, *Returning*, and *Loyal* |
| **Top 3 Products per Category** | Used window functions for ranking |
| **Repeat Buyers Analysis** | Checked correlation between repeat buyers and subscriptions |
| **Revenue by Age Group** | Summarized revenue by customer age bracket |

---

## 📊 Power BI Dashboard Highlights  

### 🔹 Key Visuals  
- **Revenue by Gender and Age Group**  
- **Customer Segmentation (New, Returning, Loyal)**  
- **Subscription vs. Non-subscription Analysis**  
- **Top Performing Products**  
- **Shipping Type vs. Average Spend**

### 🔹 Business Insights  
- Female customers generate **slightly higher total revenue**  
- **Express shipping users** spend ~12% more per purchase  
- **Subscribers** show **68% higher spend** and **78% loyalty rate**  
- **Discount-driven customers** are high-value targets for premium offers  

📸 *(Optional)* Add a screenshot of your Power BI dashboard here:

yaml
Copy code

---

## 💡 Strategic Recommendations  
1. **Boost Subscriptions** – Highlight exclusive benefits to increase subscriber base  
2. **Loyalty Programs** – Reward repeat buyers for long-term retention  
3. **Targeted Marketing** – Focus on high-revenue age groups and express-shipping users  
4. **Product Positioning** – Promote top-rated items in marketing campaigns  
5. **Optimize Discounts** – Balance between driving sales and profit margins  

---

## 📁 Repository Structure  
Customer-Shopping-Behavior-Analysis/
│
├── data/ # Raw and cleaned datasets
├── Customer_Shopping_Behavior_Analysis.ipynb # Python EDA
├── customer_behavior_sql_queries.sql # SQL queries
├── Customer-Shopping-Behavior-Analysis.pptx # Project presentation
├── PowerBI_Dashboard.png # Power BI visualization (optional)
└── README.md # Project documentation

yaml


---

## 🧩 Key Learnings  
- Built an integrated workflow using **Excel → Python → SQL → Power BI**  
- Strengthened skills in **data cleaning, feature engineering, and EDA**  
- Improved ability to derive **business insights from analytical findings**  

---

## 🚀 Future Enhancements  
- Add ML models to predict purchase behavior or churn  
- Automate data pipeline using Python scripts and SQL scheduling  
- Deploy interactive dashboard with live data refresh  

---

## 👤 Author  

**Dipak Laghe**  
📍 Pune, India  
💼 Data Analyst | Python | SQL | Power BI | Tableau  
📧 [your.email@example.com]  
🔗 [LinkedIn](https://www.linkedin.com/) | [GitHub](https://github.com/yourusername)

---

⭐ *If you found this project interesting, consider giving it a star on GitHub!*
