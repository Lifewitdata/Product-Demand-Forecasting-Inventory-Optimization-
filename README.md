# 🛍️ Product Demand Forecasting & Inventory Optimization  
### Dataset: [UCI Online Retail Dataset](https://archive.ics.uci.edu/ml/datasets/online+retail)

## 📌 Project Objective
The goal of this project is to analyze historical retail transaction data to forecast product demand and optimize inventory levels. By identifying top-selling products, sales patterns, and anomalies, this project simulates how a company like Decathlon can make data-driven decisions for inventory planning and customer experience.

---

## 🔍 Dataset Overview
- **Source**: UCI Machine Learning Repository  
- **Transactions** from a UK-based online retailer (Dec 2010 – Dec 2011)
- **Fields**: InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country

---

## 📊 Key Tasks Performed
1. **Data Cleaning & Preprocessing**  
   - Removed canceled orders, missing values, and negative quantities.
   - Parsed date fields and engineered features like `InvoiceMonth`, `DayOfWeek`, and `TotalPrice`.

2. **Exploratory Data Analysis (EDA)**  
   - Identified top-selling SKUs and revenue-driving countries.
   - Analyzed monthly sales trends, product demand cycles, and seasonal spikes.

3. **Time Series Forecasting (Top Products)**  
   - Created daily aggregated sales data for the top 5 products.
   - Applied **Prophet** and **ARIMA** models for SKU-level demand forecasting.

4. **Inventory Risk Simulation**  
   - Simulated product-level inventory with thresholds for stockouts.
   - Suggested reorder points based on demand patterns.

5. **Market Basket Analysis (Apriori Algorithm)**  
   - Identified frequently bought together items.
   - Generated association rules for bundling and cross-selling.

6. **RFM Customer Segmentation**  
   - Segmented customers using Recency, Frequency, and Monetary values.
   - Identified high-value and churn-risk customer segments.

---

## 📈 Tools & Technologies
- **Languages**: Python  
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Plotly, statsmodels, Prophet, mlxtend  
- **Techniques**: Time Series Forecasting, RFM, Market Basket, Clustering  
- **Visualization**: Plotly, Seaborn  
  

---

## 📁 Project Structure
