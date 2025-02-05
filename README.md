# vrinda-store-Excel-Data-Analysis
# 📊 **Vrindha Store Annual Report 2022 | Excel Dashboard**  

## 📌 **Project Overview**  
This project focuses on **cleaning, transforming, and visualizing sales data** for Vrindha Store using **Microsoft Excel**. The dashboard provides **insights into customer demographics, order statuses, regional performance, sales trends, and platform-wise sales**.  

## 🛠 **Tools & Techniques Used**  
- **Microsoft Excel** (Pivot Tables, Charts, Slicers, Data Validation)  
- **Data Cleaning & Transformation** (Formulas, Text-to-Columns, Find & Replace)  
- **Data Analysis** (Pivot Tables, Aggregations, Conditional Formatting)  
- **Data Visualization** (Bar Charts, Pie Charts, Line Graphs, Filters)  

## 🧹 **Data Cleaning & Preprocessing**  
Before creating the dashboard, the dataset was **cleaned and refined** through the following steps:  

✅ **Removed unwanted columns** to focus on relevant insights.  
✅ **Checked and removed duplicates** to maintain data integrity.  
✅ **Handled missing values** by filling or removing incomplete records.  
✅ **Standardized date format** and extracted **Month** for better time-based analysis.  
✅ **Created a new column:**  
   - **Age Group**: Segmented customers into groups (Teenager, Adult, Senior).  
✅ **Used Find & Replace, Text-to-Columns, and Trim functions** for data formatting.  
✅ **Ensured consistency in categorical variables** (e.g., standardized gender values as "Male" & "Female").  

## 📂 **Dataset Overview**  
The cleaned dataset consists of the following key columns:  
- **Order Details**: `Order ID`, `Cust ID`, `SKU`, `Qty`, `Amount`, `Currency`, `Category`, `Size`  
- **Customer Details**: `Gender`, `Age`, `Age Group`  
- **Date Details**: `Date`, `Month`  
- **Order Status**: `Status` (Delivered, Returned, Cancelled, Refunded)  
- **Sales Channels**: `Channel` (Amazon, Flipkart, Myntra, etc.)  
- **Shipping Details**: `ship-city`, `ship-state`, `ship-postal-code`, `ship-country`  
- **Business Type**: `B2B`  

## 🎯 **Key Insights & Features**  

### **1️⃣ Sales Trends Analysis**  
- Monthly **sales performance visualized using line charts**.  
- **"Month" column** used to analyze trends over time.  

### **2️⃣ Customer Demographics & Behavior**  
- **Gender-based sales distribution**:  
  - **Women: 64%**, **Men: 36%** of total sales.  
- **Age Group Segmentation**:  
  - **Teenagers (21.13%)**, **Adults (34.59%)**, **Seniors (5.91%)**.  

### **3️⃣ Order Status Breakdown**  
- **92% orders successfully delivered**, with:  
  - **3% Cancelled**, **3% Returned**, **2% Refunded**.  

### **4️⃣ Sales by Platform & Region**  
- **Top 3 platforms based on sales**:  
  - **Amazon (35%)**, **Flipkart (22%)**, **Myntra (23%)**.  
- **Highest-selling states** identified using a bar chart.  

## 📈 **Impact & Business Value**  
✅ **Improved customer targeting** using **Age Group segmentation**.  
✅ **Better inventory planning** with **monthly sales insights**.  
✅ **Optimized marketing strategies** by identifying top-performing platforms.  
✅ **Streamlined operations** by analyzing **order statuses**.  

## 🔗 **Next Steps**  
🚀 **Enhance analysis with Power BI for real-time insights**.  
🚀 **Automate data updates using Power Query & macros**.  
🚀 **Develop predictive models for demand forecasting**.  
