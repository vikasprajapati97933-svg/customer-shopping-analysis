# 🛍️ Customer Shopping Behavior Analysis
## 🚀 End-to-End Data Analysis Project (Python → SQL → Power BI)

---

## 📖 Project Overview

This project delivers a comprehensive analysis of customer purchasing behavior. The goal is to uncover actionable business insights related to:

- 👥 Customer demographics
- 🔔 Subscription impact
- 🛍️ Product performance
- 🔄 Purchasing patterns

💡 The project follows a complete real-world data workflow, from raw data cleaning to business recommendations.

---

## 🎯 Business Objectives

- 💎 Identify high-value customer segments
- 📊 Analyze the impact of subscription on revenue & loyalty
- 🛍️ Understand product/category performance
- 🔍 Discover patterns in customer purchasing behavior

---

## 🛠️ Tech Stack

| Tool | Purpose |
| ---------- | ----------------------------- |
| Python | Data Cleaning & Preprocessing |
| Pandas | Data Manipulation |
| NumPy | Numerical Operations |
| MySQL | Data Analysis (SQL Queries) |
| SQLAlchemy | Python–SQL Integration |
| Power BI | Dashboard & Visualization |

---

## 🔄 Data Preparation Workflow

### 🔍 Data Exploration
- Performed initial analysis using `df.info()` and `df.describe()`
- Identified data types, distributions, and inconsistencies

### 🧹 Data Cleaning
- Detected **37 missing values** in `review_rating`
- Applied **median imputation** (category-wise) to preserve data integrity
- Standardized column names:
  - Lowercase formatting
  - Replaced spaces with underscores (SQL-friendly)

### ⚙️ Feature Engineering

| Feature | Details |
| -------------------- | --------------------------------------- |
| 👥 Age Groups | Young Adult, Adult, Middle-aged, Senior |
| 🔁 Purchase Frequency | Converted categorical values to numeric |
| 🎯 Customer Segments | New, Regular, Loyal |

---

## 📊 Key KPIs

| Metric | Value |
| ----------------------- | ------- |
| 💳 Subscriber Loyalty Rate | 78% |
| 💰 Subscriber Revenue Share | 45% |
| 🚚 Express Avg Spend | $65 |
| 📦 Standard Avg Spend | $58 |

---

## 🔍 Key Insights

### 👩 Gender-Based Performance
- Female customers generate **slightly higher** total revenue than males

### 💳 Subscription Impact
- Subscribers show **78% loyalty rate**
- Contribute to **45% of total revenue**

### 🚚 Shipping Behavior
- Express shipping users spend **~12% more** per transaction:
  - 🚀 Express → **$65**
  - 📦 Standard → **$58**

### 👗 Product Performance
- **Blouses & Dresses** receive the highest customer ratings

---

## 💻 SQL Analysis Highlights

This project includes **advanced SQL queries** to extract business insights:

| Query Type | Description |
| -------------------- | ----------------------------------------------- |
| 📊 Revenue Analysis | Total revenue breakdown by age group |
| 🧠 Customer Intelligence | Identification of high-value "smart shoppers" (high spend + promo code usage) |
| 🏆 Category Leaders | Top 3 most purchased products per category using **window functions** |

---

## 📈 Dashboard Preview

<img width="657" height="384" alt="Customer Shopping Dashboard" src="https://github.com/user-attachments/assets/67c43919-263c-42fb-bda6-da0594179e9e" />

### 📊 What the Dashboard Shows
- Revenue by category & age group
- Subscription vs non-subscription sales
- Average ratings across products
- Customer segmentation insights

---

## 💡 Strategic Recommendations

### 📈 1. Boost Subscriptions
- Convert non-subscribers with **exclusive benefits**
- Highlight loyalty perks and early access offers

### 🎯 2. Enhance Loyalty Programs
- Reward returning customers to increase retention
- Introduce **tiered rewards** based on purchase frequency

### 📣 3. Targeted Marketing
- Focus campaigns on:
  - 👶 Young Adults
  - 💰 High-spending segments
  - 🚀 Express shipping users

---

## 📁 Project Structure

```
📦 customer-shopping-analysis
 ┣ 📁 data/
 ┃  ┗ 📄 shopping_dataset.csv
 ┣ 📁 notebooks/
 ┃  ┗ 📜 data_cleaning_eda.ipynb
 ┣ 📁 sql/
 ┃  ┗ 📜 sql_analysis.sql
 ┣ 📁 dashboard/
 ┃  ┗ 📊 dashboard.pbix
 ┣ 📁 presentation/
 ┃  ┗ 📊 presentation.pptx
 ┗ 📄 README.md
```

---

## 🚀 How to Run

```bash
# 1. Clone the repository
git clone https://github.com/sunitaprajapati6561-hue/Customer-Shopping-Behavior-Analysis

# 2. Install dependencies
pip install pandas numpy matplotlib seaborn sqlalchemy pymysql

# 3. Run the data cleaning notebook
jupyter notebook notebooks/data_cleaning_eda.ipynb

# 4. Execute SQL queries in MySQL
# Open sql/sql_analysis.sql in MySQL Workbench

# 5. Open Power BI dashboard
# Open dashboard/dashboard.pbix in Power BI Desktop
```

---

## 🧑‍💻 Author

**Vikas Prajapati**
📌 Aspiring Data Analyst
📌 Python | SQL | Power BI | Excel

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vikas-prajapati-0ba9302ba/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sunitaprajapati6561@gmail.com)
