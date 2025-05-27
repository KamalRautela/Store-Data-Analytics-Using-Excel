# Store-Data-Analytics-Using-Excel
Annual Sales Report for a Retail Store using Excel - Includes data cleaning, pivot tables, charts, and key insights.

# 🛒 Store Annual Sales Report 2024 - Excel Dashboard Project

## 📌 Objective

The goal of this project is to help a retail store analyze its 2024 sales data to understand customer behavior, identify trends, and support better business decisions in 2025.

---

## 📁 Project Files

- `Store Data Analysis.xlsx` – Contains raw data, cleaned data, and Excel dashboard
- `Dashboard Preview.png` – Visual snapshot of the final dashboard
- `Dataset Preview.png` - Visual snapshot of the Dataset

---

## 📊 Sample Business Questions

- Which month had the highest sales?
- What gender contributes the most to sales?
- Which states generate the highest revenue?
- What is the success rate of order delivery?
- Who are the most valuable customers based on age group?
- Which sales channels are most effective?

---

## 🧾 Dataset Description

![Dataset](https://github.com/KamalRautela/Store-Data-Analytics-Using-Excel/blob/main/Dataset%20Preview.png)

| Column Name         | Description                                               |
|---------------------|-----------------------------------------------------------|
| `Order ID`          | Unique identifier for each transaction                    |
| `Cust ID`           | Unique identifier for the customer                        |
| `Gender`            | Gender of the customer (Men/Women)                        |
| `Age`               | Age of the customer                                       |
| `Age Group`         | Age-based group: Teenager, Adult, Senior                  |
| `Date`              | Order date                                                |
| `Month`             | Extracted from the `Date` column                          |
| `Status`            | Order status (Delivered, Returned, Refunded, etc.)        |
| `Channel`           | Source of purchase (Amazon, Flipkart, etc.)               |
| `SKU`               | Product SKU code                                          |
| `Category`          | Product category (kurta, Western Dress, etc.)             |
| `Size`              | Product size (S, M, L, XL, etc.)                          |
| `Qty`               | Quantity ordered                                          |
| `Currency`          | Currency type (INR)                                       |
| `Amount`            | Total sale amount                                         |
| `ship-city`         | Shipping destination city                                 |
| `ship-state`        | Shipping destination state                                |
| `ship-postal-code`  | Shipping postal code                                      |
| `ship-country`      | Country of delivery                                       |
| `B2B`               | Business-to-business flag (True/False)                    |

---

## 🧹 Data Cleaning

- Replaced inconsistent gender values (`M`, `W`) with standardized values (`Men`, `Women`)
- Converted categorical `Qty` values (`One`, `Two`) to numeric (`1`, `2`)
- Checked for and filtered null or irrelevant values

---

## ⚙️ Data Processing

- **Age Group**: Created using  
  `=IF(E2>=50,"Senior",IF(E2>=30,"Adult","Teenager"))`
- **Month**: Extracted using  
  `=TEXT(G2,"mmm")`

---

## 📈 Data Analysis & Visualization (Excel Pivot Charts)

1. **Orders vs Sales by Month** – Column chart
2. **Sales by Gender** – Pie chart
3. **Order Status Distribution** – Pie chart
4. **Top 5 States by Sales** – Bar chart
5. **Orders by Age Group & Gender** – Column chart
6. **Orders by Sales Channel** – Pie chart
7. **Interactive Dashboard** – Slicers added for `Month`, `Channel`, and `Category`

![Dashboard](https://github.com/KamalRautela/Store-Data-Analytics-Using-Excel/blob/main/Dashboard%20Preview.png)

---

## 🔍 Key Insights

- **March** had the highest sales and order count
- **Women** contributed 64% of sales, significantly more than men
- **92%** of orders were successfully delivered
- Top 3 revenue-generating states: **Maharashtra**, **Karnataka**, **Uttar Pradesh**
- **Adults (30–49)** generated the highest sales (50%)
- **Amazon, Flipkart, and Myntra** contributed to 80% of total orders

---

## 📌 Conclusion

To increase sales in 2025, the store should:

- Target **Women** aged **30–49**
- Focus marketing in **Maharashtra, Karnataka, and Uttar Pradesh**
- Invest more in ads and promotions on **Amazon, Flipkart, and Myntra**

---

## 📦 Tools Used

- **Microsoft Excel**
  - Data Cleaning
  - Pivot Tables
  - Charting
  - Slicers
  - Dashboard Design

---

## 🚀 How to Use

1. Download `Store Data Analysis.xlsx`
2. Explore the "Dashboard" worksheet for interactive charts
3. Use slicers to filter and analyze different segments
