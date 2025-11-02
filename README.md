# 🍴 QuickBite Crisis Recovery Analytics — Azure Synapse + ADF + Power BI

This end-to-end analytics project demonstrates how an **online food delivery startup** (QuickBite) recovered from a market crisis using **Azure Synapse Analytics**, **Azure Data Factory**, and **Power BI**.

---

## 🚀 Project Description
**Duration:** Jan–Sep 2025  
**Tech Stack:** Azure Data Factory • Azure Synapse Analytics • Data Lake • Power BI  

This solution tracks **revenue loss**, **customer churn**, **delivery delays**, and **sentiment trends** to enable strategic recovery decisions post-crisis.

**Key Highlights**
- Ingests CSV datasets using **ADF pipelines** into **Data Lake**  
- Transforms and models data using **Synapse SQL scripts**  
- Visualizes insights using **Power BI dashboards**

---

## 🧩 Data Model
Based on seven core entities:
`fact_orders`, `fact_order_items`, `fact_ratings`, `fact_delivery_performance`,  
`dim_customer`, `dim_restaurant`, `dim_delivery_partner`, `dim_menu_item`

Refer to [`docs/metadata_description.md`](docs/metadata_description.md) for column-level details.

---

## 📊 Insights Delivered
1. **Monthly Order Decline Analysis**
2. **City-wise Crisis Impact**
3. **Top Restaurant Performance Drops**
4. **Cancellation & SLA Compliance Trends**
5. **Customer Sentiment Word Cloud**
6. **Revenue & Loyalty Loss Estimation**

---

## 🏗️ Architecture Overview
![Architecture Diagram](docs/architecture_diagram.png)

**Flow:**
CSV → Azure Data Lake → Azure Data Factory → Synapse SQL → Power BI

---

## ⚙️ How to Recreate
1. Upload the CSVs from `/datasets` to your **Azure Data Lake**  
2. Import **ADF pipeline JSONs** from `/azure`  
3. Deploy Synapse scripts using **synapse_sql_scripts.sql**  
4. Connect Power BI to Synapse & publish dashboard

---

## 📈 Power BI Dashboard
Key pages:
- Crisis Overview  
- Customer Behavior  
- Restaurant Performance  
- Sentiment & Loyalty  

Screenshots available under `/powerbi/visuals_screenshots`.

---

## 📜 License
MIT License — free to use for educational and demonstration purposes.
