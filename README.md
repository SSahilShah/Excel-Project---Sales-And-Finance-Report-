# 🛠️ AtliQ Sales and Financial Report Analysis

🎯 **Objective:**  
AtliQ is a hardware company that sells products like PCs, mice, printers, and more. Their customers fall into two categories:  
1. **Brick & Mortar stores** - e.g., Croma, Best Buy  
2. **E-commerce platforms** - e.g., Amazon, Flipkart  

The company provided data with over 1.5 million records to generate comprehensive sales and financial reports.

---

## 📊 **Reports Included:**
- **Sales Report**  
- **Customer Performance Report**  
- **Market Performance Report**  
- **Top 10 Products**  
- **Division Level Analysis**  
- **Top & Bottom 5 Products**  
- **New Product Launch - 2021**  
- **Top 5 Countries by Sales**  
- **Finance Report**  
  - P&L Yearly  
  - P&L Monthly  
  - P&L Market View  
  - GM% Quarterly  

---

## 🔄 **Steps Involved in Report Creation:**

### 1️⃣ **ETL (Extract, Transform, Load):**
- Loaded CSV files into **Power Query**.  
- Ensured data integrity:
  - Checked for missing values.
  - Ensured unique keys in dimension tables.  
  - Removed duplicates and fixed spelling errors.  
- Loaded the cleaned data into **Power Pivot** for further processing.

### 2️⃣ **Data Modeling:**
- Created a **star schema** by connecting all tables.  
- Generated a `dim_date` table with date, month, and year columns.  
- Added a **fiscal year column** (September to August) for AtliQ Hardware and linked it with other tables.

### 3️⃣ **Pivot Table & Power Pivot:**
- Built a **Pivot Table** for quick insights and used **Power Pivot** to create measures.  
- Utilized **Power Query** for smooth data transformation and seamless integration.

### 4️⃣ **DAX (Data Analysis Expressions):**
- Created **10+ measures** like:
  - Net Sales  
  - Gross Margin (GM)  
  - GM %  
  - COGS (Cost of Goods Sold)  
- Added new columns using functions like `RELATED()`, `CALCULATE()`, and `FORMAT()`.  
- Extracted **fiscal year quarters** by adjusting months.

### 5️⃣ **Conditional Formatting:**
- Applied **conditional formatting** to:
  - Highlight trends.
  - Format numbers and text.
  - Improve data readability for actionable insights.

---

## 💡 **Key Insights:**
- **Top Market:** India achieved the highest net sales in 2021 at **$161.3M**, while Sweden had the lowest at **$1.8M**.  
- **Top Product:** The **AQ Master Wired X1 MS** sold **4.2M units**, while the **AQ Home All-in-1 Gen2** only sold **8.8K units**.  
- **Seasonal Surge:** Sales and profits peaked during the festive months (October-December) in India.  
- **Top Customers:** The top contributors to net sales were **Amazon**, **AtliQ Exclusive**, and **AtliQ e-store**.  
- **New Product Launch:** 2021 saw the release of **16 new products**, with **AQ Qwerty** leading sales at **22M units**.

---

## 📑 **Finance Knowledge:**
- **Profit & Loss (P&L) Statement:**  
  A financial report summarizing the company’s performance over a month, quarter, or year.  
  - Metrics included:
    - **Net Sales**  
    - **COGS (Cost of Goods Sold)**  
    - **Gross Margin**  
    - **GM%**  

These metrics offer insights into profitability, pricing strategies, and financial health.

---

Feel free to explore the full project! 🚀  
![image](https://github.com/user-attachments/assets/ffff3e58-cc4e-46fe-8b33-41668c7b52b6)
