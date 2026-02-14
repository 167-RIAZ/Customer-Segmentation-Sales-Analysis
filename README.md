
<!-- PROJECT BANNER -->
<h1 align="center">📊 Customer-Segmentation-Sales-Analysis
</h1>
<h3 align="center">End-to-End Data Analytics Project | Python • SQL • Power BI</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Python-EDA-blue?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/PostgreSQL-SQL Analysis-336791?style=for-the-badge&logo=postgresql">
  <img src="https://img.shields.io/badge/PowerBI-Dashboard-yellow?style=for-the-badge&logo=powerbi">
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge">
</p>

---

## 🔎 Project Overview
This project analyses customer shopping behaviour using transactional data to uncover insights into revenue patterns, customer segments, product performance, and purchase trends.

The project demonstrates the **complete data analytics workflow** from raw dataset to business recommendations:
- Data cleaning and EDA in Python  
- Business queries in SQL (PostgreSQL)  
- Interactive dashboard in Power BI  
- Final presentation and reporting  

---

## 🎯 Business Objective
- Identify high-value customer segments  
- Understand revenue drivers  
- Analyze product and discount performance  
- Support data-driven marketing and retention strategies  

---

## 🗂 Dataset Summary
- ~3,900 transactions  
- 18 features (demographics, purchases, behavior, shipping, discounts)  
- Minimal missing values handled during preprocessing  
- Suitable for segmentation, revenue analysis, and behavioral insights  

---

## 🛠 Tech Stack

| Tool | Purpose |
|------|--------|
| **Python (Pandas, NumPy, Matplotlib, Seaborn)** | Data cleaning & EDA |
| **PostgreSQL** | Business analysis using SQL |
| **Power BI** | Dashboard & visualization |
| **Gamma** | Presentation & reporting |

---

## ⚙️ Project Workflow

### 🐍 Data Preparation (Python)
- Loaded dataset using Pandas  
- Explored structure with `.info()` and `.describe()`  
- Handled missing values  
- Standardized column names  
- Created derived features (age groups, frequency metrics)  

---

### 🗄 SQL Business Analysis (PostgreSQL)
Key business questions answered:
- Revenue contribution by gender  
- Customer segmentation (New / Returning / Loyal)  
- Top rated and most purchased products  
- Shipping type comparison  
- Subscriber vs Non-subscriber behavior  
- Discount dependency analysis  

---

### 📊 Dashboard (Power BI)
The dashboard includes:
- KPI cards for revenue and customer metrics  
- Segment-wise revenue breakdown  
- Product performance visuals  
- Purchase trends and filters  

---

## 📈 Key Insights
- Loyal customers contribute the majority of revenue  
- Some discounted customers still generate high purchase value  
- Shipping type slightly impacts transaction amount  
- Certain products consistently show higher ratings and demand  

---

## 💼 Business Impact
This analysis enables businesses to:
- Improve customer targeting strategies  
- Optimize discount usage  
- Promote top-performing products  
- Design loyalty and subscription programs  
- Make faster data-driven decisions  

---

## 📁 Project Structure

Customer-Shopping-Analysis/
│
├── data/                 # Raw dataset
├── notebooks/            # Python analysis notebooks
├── sql/                  # SQL scripts
├── dashboard/            # Power BI file
├── presentation/         # Gamma report / slides
└── README.md

---

## ▶️ How to Run the Project

### 1️⃣ Python Setup
```bash
pip install pandas numpy matplotlib seaborn psycopg2

Run the notebook to clean and export the dataset.

⸻

2️⃣ PostgreSQL Setup
	•	Create database
	•	Import cleaned dataset
	•	Execute SQL queries from /sql

⸻

3️⃣ Power BI
	•	Open .pbix file
	•	Connect to PostgreSQL or dataset
	•	Refresh to load visuals

⸻

👨‍💻 Author

Syed Md Riaz
Aspiring Data Analyst | Python • SQL • Power BI

📧 syed.riaz1406@gmail.com
🌍 India

