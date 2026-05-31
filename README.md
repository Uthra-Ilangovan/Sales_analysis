# Sales Analysis – Pharmaceutical Company (Power BI Dashboard)

A Power BI dashboard built to analyze raw sales data from a multinational pharmaceutical manufacturing company and generate insights into the performance of sales teams, customers, and distributors.

👉 Open In Power BI: (Add link here)

---

# 📊 Pharmaceutical Sales Analysis

In this Data Analysis project, we analyze a global pharmaceutical manufacturing company’s raw sales data and draw meaningful insights using Power BI.

---

# ⚡ Features

- Power BI Desktop  
- Power Query Editor (Data transformation & modeling)  
- Power BI Service (Web publishing & access without Power BI login)  
- Multi-page interactive dashboard for analysis and insights  

---

# 📑 Table of Contents

- Introduction  
- Objective  
- Dataset  
- Solution Approach  
- Exploratory Data Analysis (EDA)  
- Data Cleaning & Transformation  
- Data Model Creation  
- Report Creation  
- How to Use  
- License  
- Credits  
- Contact  

---

# 🏢 Introduction

Datamatrix-ml Pharmaceuticals is a leading global pharmaceutical manufacturing company with operations across multiple regions.

- Markets are divided by geography  
- Sales are managed via distributors (not direct sales)  
- Distributors share structured CSV sales data  
- Goal: derive insights down to retail level  

---

# 🎯 Objective

The company requested in-depth analysis of sales performance across different business dimensions.

## Requirements

| Requirement ID | For Whom | Requirement Description |
|----------------|----------|------------------------|
| DM-DA01-REQ-1 | Executive Committee | High-level overview of sales performance by year, month, customer city, channel, sub-channel, top drugs and product classes |
| DM-DA01-REQ-2 | Sales Manager / Sales Rep | Detailed breakdown of sales by distributors, products, top customers, cities, channels, and sub-channels |
| DM-DA01-REQ-3 | Head of Sales | Sales team performance analysis including reps, managers, product class contribution, and filtering by time |

---

# 📦 Dataset

The dataset contains pharmaceutical wholesale-to-retail sales data.

| Field | Description |
|------|-------------|
| Distributor | Name of wholesaler |
| Customer Name | Name of customer |
| City | Customer's city |
| Country | Customer's country |
| Latitude | Customer geo latitude |
| Longitude | Customer geo longitude |
| Channel | Buyer type (Hospital, Pharmacy) |
| Sub-channel | Buyer sector (Government, Private, etc.) |
| Product Name | Name of drug |
| Product Class | Drug category |
| Quantity | Quantity purchased |
| Price | Unit price |
| Sales | Total sales amount |
| Month | Month of sale |
| Year | Year of sale |
| Name of Sales Rep | Sales representative |
| Manager | Sales rep manager |
| Sales Team | Sales team name |

---

# 🧠 Solution Approach

| Requirement ID | Solution ID | Proposed Solution |
|----------------|------------|------------------|
| DM-DA01-REQ-1 | DM-DA01-SOL-1 | Executive dashboard with KPIs and filters (year/month) |
| DM-DA01-REQ-2 | DM-DA01-SOL-2 | Distributor & customer analysis dashboard with drill-down visuals |
| DM-DA01-REQ-3 | DM-DA01-SOL-3 | Sales team performance dashboard with time-based slicing |

---

# 🔎 Exploratory Data Analysis (EDA)

EDA was performed using Python (pandas) to understand dataset quality.

Key checks included:
- Missing values detection  
- Outlier detection  
- Negative or incorrect sales values  
- Data type validation  
- Categorical and numerical feature identification  

📌 Notebook: `data-exploration.ipynb`

---

# 🧹 Data Cleaning & Transformation

Performed using Power Query Editor:

- Standardized column headers  
- Assigned correct data types  
- Ensured data consistency  

---

# 🧱 Data Model Creation

A **Star Schema** was designed using Power BI Desktop:

- FACT Table: Sales transactions  
- DIM Tables: Customers, Products, Time, Geography, Sales Team  

This improves:
- Performance  
- Query efficiency  
- Scalability  

---

# 📊 Report Creation

## 1. Executive Summary Report (DM-DA01-SOL-1)
- High-level KPIs  
- Sales trends by time period  
- Breakdown by channel, city, product class  

---

## 2. Distributor & Customer Analysis (DM-DA01-SOL-2)
- Distributor performance  
- Customer-level insights  
- Product-level drill-down  

---

## 3. Sales Team Performance (DM-DA01-SOL-3)
- Sales rep performance  
- Manager contribution analysis  
- Product class contribution  
- Time-based filters (year/month)  

---

# 🚀 How To Use

## Option 1: Power BI Service (Recommended)
Open the dashboard directly in Power BI Service for interactive exploration.

👉 Open In Power BI: (Insert link here)

---

## Option 2: Power BI Desktop

1. Download `pharma-analysis.pbix` from the repository  
2. Open using Power BI Desktop  
3. Explore or modify the model and visuals  

---

# 📄 License

This project is licensed under the MIT License.

---

# 🙌 Credits

- Dataset Source: Foresight BI  
- Tool: Microsoft Power BI  

---

# 📬 Get in Touch

- Email: your-email@example.com  
- LinkedIn: your-linkedin-url  
- Portfolio: your-portfolio-url  
