# AI-Driven-Supply-Chain-Analytics-Dashboard-using-Power-BI-Python-KPI-Analysis-Inventory-Optimization
<!-- HEADER -->

<h1 align="center">📊 AI-Driven Supply Chain Analytics Dashboard</h1>

<p align="center">
  🚀 Power BI | 🤖 AI Forecasting | 📈 Business Intelligence | 📦 Supply Chain Analytics


## 🚀 Project Overview

This project showcases a complete **end-to-end data analytics solution** that transforms raw supply chain data into **business insights and AI-driven predictions**.

💡 It combines:

* 📊 Power BI Dashboards
* 🧮 DAX KPI Modeling
* 🤖 Predictive Analytics

---

## 🎯 Key Objectives

✔ Analyze business performance (Sales & Profit)
✔ Optimize inventory and reduce stockouts
✔ Identify demand vs supply gaps
✔ Forecast future demand using AI
✔ Enable data-driven decision-making

---

## 📂 Project Structure

```bash
AI-SupplyChain-Dashboard/
│
├── 📊 PowerBI_Dashboard.pbix
├── 📈 Dataset.xlsx
├── 🤖 Forecast_Model.ipynb
├── 📄 README.md
```

---

# 📊 DASHBOARDS

---

## 🟢 1. Executive Dashboard

💼 **Business Performance Overview**

### 🔑 KPIs

| KPI              | Value    |
| ---------------- | -------- |
| 💰 Total Sales   | $549.71M |
| 📈 Total Profit  | $154M    |
| 📊 Profit Margin | 28.11%   |
| 📦 Units Sold    | 10M      |
| ⏱ Avg Lead Time  | 7.5      |
| ⚠️ Stockout Rate | 0%       |

### 📊 Visuals

* 📈 Sales Trend (Time Analysis)
* 🌍 Sales by Region
* 🏷 Profit by Product
* ⚠️ Stockout Risk Analysis

---

## 🟡 2. Inventory Dashboard

📦 **Inventory Optimization & Risk Monitoring**

### 🔑 KPIs

* ⚠️ Stockout Rate %
* ⏱ Average Lead Time
* 📉 Demand Gap
* 📊 Average Inventory

### 📊 Visuals

* 📊 Demand vs Inventory (Scatter)
* 🌍 Stockout by Region
* 📦 Inventory by Product

---

## 🔵 3. AI Forecasting Dashboard

🤖 **Predictive Analytics & Future Planning**

### 🔑 KPIs

* 📊 Average Demand
* 🤖 Predicted Demand
* 🎯 Forecast Accuracy
* ⚠️ Predicted Stockout Risk

### 📊 Visuals

* 📈 Actual vs Predicted Demand
* 📦 Predicted Demand by Product
* 🌍 Predicted Stockout Risk by Region

---

# 🧮 DAX MEASURES

```DAX
-- Total Sales
Total Sales = SUM('Cleaned_SupplyChain_For_PowerBI'[Sales])

-- Total Profit
Total Profit = SUM('Cleaned_SupplyChain_For_PowerBI'[Profit])

-- Profit Margin
Profit Margin % = DIVIDE([Total Profit], [Total Sales], 0)

-- Units Sold
Total Units Sold = SUM('Cleaned_SupplyChain_For_PowerBI'[Order_Quantity])

-- Lead Time
Average Lead Time = AVERAGE('Cleaned_SupplyChain_For_PowerBI'[Lead_Time])

-- Stockout Rate
Stockout Rate % =
DIVIDE(
    SUM('Cleaned_SupplyChain_For_PowerBI'[Stockout]),
    COUNT('Cleaned_SupplyChain_For_PowerBI'[Order_ID]),
    0
)

-- Demand Gap
Demand Gap =
SUM('Demand') - SUM('Order_Quantity')

-- AI Metrics
Average Demand = AVERAGE('Demand')
Average Predicted Demand = AVERAGE('Predicted_Demand')

Predicted Stockout Risk % =
DIVIDE(
    SUM('Predicted_Stockout'),
    COUNT('Order_ID'),
    0
)
```

---

# 📸 DASHBOARD PREVIEW

```text
<img width="1003" height="574" alt="image" src="https://github.com/user-attachments/assets/bf318313-b119-4e96-893f-d8ff880b553c" />
<img width="1003" height="570" alt="image" src="https://github.com/user-attachments/assets/5ca36bdf-0940-49a7-8dbc-59ddcec903bd" />
<img width="1008" height="575" alt="image" src="https://github.com/user-attachments/assets/d91025ea-b9c9-4eb3-ba10-cb82fc2a7a9b" />

```

```markdown
![Executive Dashboard](images/executive.png)
![Inventory Dashboard](images/inventory.png)
![AI Dashboard](images/ai.png)
```

---

# 🛠️ TECH STACK

| Tool        | Purpose                     |
| ----------- | --------------------------- |
| 🟡 Power BI | Dashboard & Visualization   |
| 🔵 Python   | Data Cleaning & Forecasting |
| 🟠 DAX      | KPI & Measures              |
| 🟢 Excel    | Data Preparation            |

---

# 📈 KEY INSIGHTS

✔ Revenue exceeds **$549M**
✔ Profit margin ~ **28% (strong performance)**
✔ Inventory optimized → **0% stockout risk**
✔ AI predictions closely match actual demand
✔ Efficient supply chain operations

---

# 💡 BUSINESS IMPACT

This dashboard enables:

✔ Better inventory planning
✔ Reduced operational risks
✔ Improved supply chain efficiency
✔ AI-driven decision-making
✔ Strategic business insights

---

# 🏆 PROJECT HIGHLIGHTS

🔥 End-to-End Analytics Pipeline
🔥 Business + Technical Integration
🔥 Real-world Supply Chain Use Case
🔥 AI-Based Forecasting

---

# 🔗 CONNECT WITH ME

https://www.linkedin.com/in/banoth-ganesh-80801b391/
---

# ⭐ If you like this project, give it a star!
