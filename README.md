# 📊 Sales Performance Analysis

## 📊 Project Overview
This project analyzes sales performance to identify trends, profitability drivers, and improvement opportunities across products, customers, and regions.

### Project Objectives
- Evaluate overall sales and profit performance
- Identify high-performing and low-performing categories
- Analyze regional sales distribution
- Understand customer purchasing behavior
- Provide actionable insights for revenue growth and cost optimization

---

## 🗂️ Data Source
This dataset was provided by my institute as part of a **Sales Performance Analysis academic project**.  
The dataset contains **transaction-level structured sales data**.

### Dataset Size
- **List of Orders Table:** 500 rows and 10 columns  
- **Order Details Table:** 1500 rows and 9 columns  
- **Sales Target Table:** 36 rows and 3 columns  

### Key Variables
- Category  
- Sub_Category  
- Customer Name  
- State  
- City  
- Country  
- Order Date  
- Order ID  
- Sales / Revenue  
- Profit  
- Quantity  

---

## 🛠️ Tools & Technologies
- **Visualization Tool:** Power BI  
- **Data Transformation:** Power Query  
- **Data Modeling:** Power BI Data Model  
- **DAX Functions:** Calculated Columns and Measures  
- **Documentation:** Microsoft Word  

---

## 🧹 Data Cleaning & Preparation
The following steps were performed to prepare the dataset for analysis:

- Removed duplicate records  
- Handled missing or blank values  
- Corrected data types (Date, Decimal, Whole Number, Text)  
- Formatted the **Order Date** column properly  

### Calculated Columns Created
- Month-Year  
- Revenue  
- Profit Margin  

### Data Modeling
- Created **one-to-many relationships** from the **Category table** to:
  - Order Details table
  - Sales Target table

---

## 🔍 Exploratory Data Analysis (EDA)

Key business questions explored during analysis:

- What is the overall sales trend over time?
- Which product categories generate the highest revenue and profit?
- Which states and cities contribute the most to total sales?
- What is the monthly and yearly sales performance?
- How does quantity sold impact profitability?

### Dashboards Created
- Sales Overview Dashboard
- Regional Performance Dashboard
- Category & Sub-Category Analysis
- Profitability Analysis

### KPI Color Logic & Thresholds
The dashboard uses **color indicators** to show whether **sales targets were met or missed**.

---

## 💡 Key Insights

**Revenue vs Profit**  
- Total Revenue: ₹4.31 Lakh  
- Profit Margin: 5.55%

**Primary Drivers**
- Electronics and Clothing are the top contributors to both revenue and profit.

**Regional Leaders**
- Madhya Pradesh and Maharashtra generate the highest revenue.

**Category Challenges**
- Furniture generates reasonable sales volume but significantly lower profit margins compared to other categories.

---

## 🚀 Recommendations

- Focus marketing efforts on high-performing regions to maximize revenue.
- Improve pricing or cost strategy for low-profit sub-categories.
- Introduce targeted promotions during peak sales months.
- Optimize inventory planning based on seasonal demand trends.
- Develop customer segmentation strategies for better retention and growth.

---

## ⚙️ How to Use

1. Download the **.pbix file** from the repository.
2. Open it using **Power BI Desktop**.
3. Refresh the dataset if connected to an external source.
4. Navigate through the dashboard pages using the report tabs.

### If External Data Sources Are Used
- Update the **data file path in Power Query**.
- Click **Refresh** to load updated data.
