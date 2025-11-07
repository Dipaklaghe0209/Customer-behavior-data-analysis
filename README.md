# 📖 Customer Behavior Analysis

A data analytics project investigating customer purchase patterns, product preferences, and discount behaviors to empower businesses to make data-driven decisions. This end-to-end analysis uses **Excel, Python, SQL,** and **Power BI** to extract actionable insights from customer data.

---

## 🧩 Overview / Objective

The primary goal of this project is to understand customer behavior by analyzing their interactions, purchase histories, and responsiveness to discounts. By uncovering underlying trends, businesses can tailor marketing strategies, optimize product offerings, and enhance customer retention.

---

## ⚙️ Tools & Technologies Used

- **Excel** – Initial data exploration and basic cleaning
- **Python (Jupyter Notebooks)** – Data cleaning, transformation, and deep-dive analysis
- **SQL** – Querying, aggregations, and advanced filtering
- **Power BI** – Interactive dashboards for business insights

---

## 🗂️ Dataset Description

The core dataset is customer purchase data, which may include:
- `customer_id` – Unique customer identifier
- `item_purchased` – Product or service bought
- `purchase_date` – Timestamp of each transaction
- `discount_applied` – Discount (%) on purchase, if any
- `previous_purchases` – Number of transactions before current purchase
- `purchase_amount` – Value of the transaction
- `customer_type` – New or Returning
- `payment_method` – Mode of payment (Credit Card, Cash, etc.)

(*Sample files housed in the `/data` folder*)

---

## 🔍 Project Workflow

1. **Data Collection & Import**
   - Gather purchase data (e.g., exports from CRM systems or e-commerce platforms).
   - Consolidate using Excel and import into Python for processing.

2. **Data Cleaning & Preparation**
   - Remove duplicates, handle missing values using `data_cleaning.py` and `data_cleaning.ipynb`.
   - Standardize data formats.
   - Save cleaned data as CSV.

3. **Database Integration & SQL Analysis**
   - Import data into a SQL database (`database_dump.sql`).
   - Run analytical queries (`sql_queries.sql`) to segment customers, calculate purchase frequencies, and aggregate discount data.

4. **Data Analysis in Python**
   - Perform in-depth analysis (customer segmentation, trend detection) using `analysis_functions.py`.

5. **Visualization & Storytelling**
   - Prepare visualizations in Jupyter (`visualization_preparation.ipynb`).
   - Export datasets for Power BI.

6. **Dashboard Development**
   - Build interactive dashboards in Power BI (`powerbi_dashboard.pbix`).
   - Showcase insights using visual storytelling.

7. **Reporting**
   - Summarize findings in a comprehensive PDF report and presentation slides.

---

## 📊 Key Insights & Results

*Examples of business insights from this analysis:*
- **Top Products:** Highest-selling items/categories based on frequency/amount.
- **Discount Impact:** Analysis of how discounts influence purchase amount and frequency.
- **Returning vs. New Customers:** Insights on retention rates and lifetime value.
- **Customer Segments:** Identification of high-value vs. price-sensitive customers.
- **Time Trends:** Purchase trends by month/day to aid inventory planning.

---

## 📁 Folder Structure

```bash
customer-behavior-analysis/
├── README.md
├── data/
│   ├── raw_data.xlsx
│   ├── cleaned_data.csv
│   └── database_dump.sql
├── scripts/
│   ├── data_cleaning.py
│   ├── sql_queries.sql
│   ├── analysis_functions.py
│   └── export_to_powerbi.py
├── notebooks/
│   ├── data_cleaning.ipynb
│   ├── exploratory_analysis.ipynb
│   └── visualization_preparation.ipynb
├── dashboards/
│   ├── powerbi_dashboard.pbix
│   └── screenshots/
│       ├── overview_page.png
│       └── insights_page.png
├── reports/
│   ├── project_report.pdf
│   └── presentation.pptx
└── requirements.txt
```

---

## 🚀 How to Run / Reproduce the Project

1. **Clone the repository**
   ```bash
   git clone https://github.com/Dipaklaghe0209/Customer-behavior-data-analysis.git
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Put your raw data in `/data/raw_data.xlsx`.**

4. **Run data cleaning scripts**
   - Via Jupyter: Open `notebooks/data_cleaning.ipynb`
   - Or via script: `python scripts/data_cleaning.py`

5. **Import cleaned data into SQL for further analysis**
   - Use `/scripts/sql_queries.sql` as needed for aggregation.

6. **Perform Python-based analytics**
   - Explore and run analysis in `/notebooks/` or `/scripts/`.

7. **Power BI Dashboard**
   - Use `/dashboards/powerbi_dashboard.pbix` to view insights.
   - Ensure exported data (`export_to_powerbi.py`) is up to date.

8. **View the final report and presentation in `/reports/`**

---

## 🔮 Future Improvements

- Integrate machine learning models to predict customer churn and recommend products.
- Automate Power BI dashboard refresh with new sales data.
- Incorporate real-time data streaming for live dashboards.
- Expand dataset with customer demographics and feedback for richer insights.
- Deploy web-based dashboards for on-demand analytics.

---

## 👤 Author

**Dipak Laghe**

- [LinkedIn](https://www.linkedin.com/in/dipak-laghe-3b169a281/)
- 📧 Email: dipaklaghe87.com



## 🪪 License
This project is licensed under the [MIT License](LICENSE).

_This repository demonstrates an end-to-end approach in customer data analytics and implementation using Excel, Python, SQL, and Power BI, suitable for both beginners and professionals._
