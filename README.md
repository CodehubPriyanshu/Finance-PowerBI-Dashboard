# 💰 Personal Finance Dashboard - Power BI
A Microsoft Power BI project that analyzes personal financial data and visualizes expenses through an interactive dashboard.

##🗣 "Data analysis is not just about presenting data, but to build a story and create a meaningful narrative from the raw data. At the end of the day, that's what analytics is all about - not about writing code, not about crunching numbers, not about memorizing formula syntax - it's about deriving meaning and context from the data and, more importantly, using it to make real change."## 
- Chris Dutton, Maven Analytics

# 🎯 Problem Statement
I have been tracking my daily expenses using Microsoft Excel. While sorting/filtering in Excel gives a basic overview, a deeper financial analysis requires an interactive dashboard.

## 🔍 This project transforms static Excel data into dynamic Power BI dashboards, providing detailed insights into spending habits.

# 📌 Project Goals
The Power BI dashboard aims to answer:

### ✔️ Monthly spending trends (for a given year)
###  ✔️ Total spending per item category
###  ✔️ Detailed expense list with comments
### ✔️ Spending distribution by location
### ✔️ Number of purchases in different price ranges
### ✔️ Quarterly and weekly spending insights
### ✔️ Average spending per week, month, day
### ✔️ Food vs. restaurant spending comparison
### ✔️ Spending behavior when I am sick
### ✔️ Comparison of weekday vs. weekend spending

## 📊 Data Analysis Summary
📌 Below are screenshots of the Power BI dashboards:

### 1️⃣ Executive Summary Dashboard
![executive_summary](https://github.com/user-attachments/assets/5fc80af3-5e23-45a5-92a7-a65b010c8923)

### 2️⃣ Granular Financial Insights Dashboard
![granular_info](https://github.com/user-attachments/assets/0494a081-4fa7-4d5b-b803-99fea734910c)

# 🛠 Hardware & Software Used
Microsoft Power BI Desktop (v2.93)
Microsoft Excel (for raw financial data)
Python (v3.8) (for pre-processing)
Python Libraries: openpyxl, os
Windows 10 Machine
Apple iPad (7th Gen) + Pencil (for handwritten annotations)

# 📌 Overview of Microsoft Power BI
Microsoft Power BI is a business intelligence (BI) tool for loading, modeling, and visualizing data. It was first released in July 2011 and has since evolved into a powerful data visualization platform.

Power BI offers two modes:

### ✔️ Power BI Desktop (for local analysis)
### ✔️ Power BI Service (for cloud-based dashboards & collaboration)

Power BI enhances data storytelling through interactive visualizations called dashboards.

## 📂 Project Files & Structure
File/Folder	Description
Finance_Data/20xx/	Folder containing monthly Excel expense data (Aug 2018 - Dec 2020).
change_excel_sheets.py	Python script to rename all Excel sheets to "Sheet1" (Power BI requirement).
Finance_Data.xlsx	The original Excel file tracking daily expenses.
Personal_Finance_Dashboard.pbix	Power BI Dashboard file with financial visualizations.

### 📊 Data Collection & Cleaning
### 📥 Data Collection
I manually recorded my expenses by keeping purchase receipts and inputting details into Excel, including:
Date
Item Category
Price
Purchase Location
Additional Comments

🧹 Data Cleaning & Preprocessing
### ✔️ Standardized categories (e.g., merging "Hair-Cut", "hair cut" → "Hair Cut")
### ✔️ Formatted date columns (converted text-based dates to correct format)
### ✔️ Handled missing values (few rows were removed)
### ✔️ Reformatted Excel sheets for Power BI compatibility

## 📊 Measure Creation & Visualizations
To generate meaningful insights, I created lookup tables and DAX measures in Power BI:

## 📌 Lookup Tables Created:
## 1️⃣ Calendar Lookup – Created month, quarter, and week-based time analysis.
## 2️⃣ Item Lookup – Added a manual filter to include/exclude rent payments.
## 3️⃣ Location Lookup – Consolidated distinct purchase locations.

## 📌 DAX Measures Created:
### ✔️ Total Cost Calculation
### ✔️ Spending Trends by Week, Month, Year
### ✔️ Price Ranges for Purchases
### ✔️ Average Cost Per Day & Week
### ✔️ Boolean Filter for Sick Days Analysis

## 📌 Visual Elements Used:
Slicers for granular filtering (by year, month, day, category).
Comparison Visuals for food vs. restaurant expenses.
Interactive Charts to analyze spending habits over time.

# 🚀 How to View My Power BI Dashboard
## 🖥️ Step 1: Install Power BI Desktop
## 🔗 Download Power BI for Free

## ⚙️ Step 2: Configure Power BI Settings
Open Power BI Desktop
Go to: File → Options and settings → Options
Under Global Settings, disable all Preview Features
Under Current File → Data Load, deactivate auto-detect relationships
## 📥 Step 3: Download Project Files
Clone this GitHub repository
git clone https://github.com/your-username/personal-finance-powerbi.git
cd personal-finance-powerbi
Open Personal_Finance_Dashboard.pbix in Power BI
Explore & analyze the dashboards 🚀
# 🔮 Future Enhancements
# 💡 Ideas for future improvements:

### ✔️ Improve UI/UX with modern dashboard templates
### ✔️ Generalize the dashboard for wider public use
### ✔️ Add automated Excel data processing with Python
### ✔️ Create mobile/tablet-optimized views in Power BI

## 🙏 Acknowledgements
## 🚀 Microsoft Power BI Team – for creating a powerful BI tool.
