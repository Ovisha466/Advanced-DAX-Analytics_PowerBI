# 📊 Advanced DAX Analytics in Power BI
## 📸 Dashboard & Analytics Preview

![Moving Average customer sales and profit](https://github.com/Ovisha466/Advanced-DAX-Analytics_PowerBI/blob/main/Screenshot%202026-03-10%20192222.png)

![Customer Sales Ranking](iterator_functions/customer_sales_ranking.png)

![Store Performance Comparison](table_and_filter_function/store_sales_percent.png)
## 🚀 Project Overview

This repository showcases a collection of advanced **DAX (Data Analysis Expressions)** techniques implemented in Power BI.

The goal of this project was to move beyond basic dashboards and deeply explore how analytical logic is built inside a Power BI data model.

Using a retail-style dataset containing sales, customers, employees, products, and stores, I implemented a wide range of DAX functions to analyze business performance, manipulate filter context, and perform complex calculations across multiple dimensions.

The project demonstrates how DAX can transform raw transactional data into meaningful analytical insights.

---

## 🧠 Key DAX Concepts Explored

This project focuses on several important areas of advanced DAX development:

• Filter Context Manipulation  
• Table Functions and Virtual Tables  
• Iterator Functions  
• Relationship Functions  
• Advanced Time Intelligence  
• Custom Calendar Modeling  

Each concept is implemented through dedicated examples and visual validations inside Power BI.

---

# 📂 Repository Structure

The repository is organized by DAX concept to make navigation easier.

## 📅 4-5-4 Calendar Modeling

Folder: `454_calendar`

This section demonstrates how a **custom 4-5-4 retail calendar** can be used to build time intelligence calculations when standard Power BI date functions are not sufficient.

Key highlights include:

• Quarter-to-date sales, Year-to-date calculations
• Week over week percentage change in customer sales
• Custom fiscal period logic  
• Time comparisons across non-standard calendar structures

---

## ➕ ADDCOLUMNS Function

Folder: `add_column_function`

Examples of building **virtual tables with additional calculated columns** using the `ADDCOLUMNS` function.

These calculations demonstrate how intermediate table structures can be created dynamically inside DAX measures.

---

## ⏳ Advanced Time Intelligence

Folder: `advanced_time_intelligence_function`

This section includes calculations such as:

• Last quarter's sales(PARALLELPERIOD, PREVIOUSQUARTER,)  
• Last year sales(SAMEPERIODLASTYEAR)
• Moth over month and year over year percentage change in customer sales

These measures demonstrate how DAX can detect trends and smooth fluctuations in performance data.

---

## 🔗 CROSSJOIN Operations

Folder: `cross_join`

Examples using the `CROSSJOIN` function along with VALUES() to generate combinations of multiple tables for analytical scenarios.

This technique is useful when creating complex virtual tables for intermediate calculations.

---

## 🧾 DATATABLE Function

Folder: `data_table`

Demonstrates how custom tables can be created directly inside DAX using the `DATATABLE` function.

These examples show how synthetic data structures can support testing and advanced modeling scenarios.

---

## 🔍 INTERSECT Table Logic

Folder: `intersect`

Examples showing how the `INTERSECT` function can identify common values across tables wth ADDCOLUMNS() to compute:

• Revenue intersections  
• Profit calculations based on overlapping filters

---

## 🔁 Iterator Functions

Folder: `iterator_functions`

Iterator functions evaluate expressions row-by-row across tables.

Examples implemented include:

• Moving averages of customer sales using AVERAGEX()  
• Calculating sales by employees name using CONCATENATEX()  
• Calculating top 5 products using RANKX()

These functions are essential for advanced analytical calculations.

---

## 🔄 Relationship Functions

Folder: `relationship_functions`

Examples demonstrating advanced relationship manipulation including:

• Merchandise goal using TREATAS() and SUMMARIZE()  
• Using CROSSFILTER() to establsh temporary relationship between two tables which aren't physially connected to each other.  
• Utilizing SELECTCOLUMNS() to create new tables by selecting specific columns from an existing table.

These techniques allow DAX calculations to temporarily modify or activate relationships within the data model.

---

## 🧮 Table and Filter Functions

Folder: `table_and_filter_function`

This section focuses on manipulating filter context using functions such as:

• KEEPFILTERS()
• REMOVEFILTERS() 

These functions are critical for building dynamic calculations such as:

• Percentage of store sales  
• Context-aware comparisons across dimensions

---

## 🧱 Table Constructor Examples

Folder: `table_constructor`

Examples demonstrating how DAX table constructors can generate inline tables used for intermediate analytical logic.

---

# 📸 Example Visual Outputs

Each folder includes screenshots of:

• DAX measure implementations  
• Matrix or table visuals validating the calculations  
• Filter interactions demonstrating dynamic results

These visuals help demonstrate how the calculations behave within the Power BI reporting environment.

---

# 🛠 Tools Used

• Power BI Desktop  
• DAX (Data Analysis Expressions)  
• Data Modeling Techniques  
• Business Intelligence Design Principles  

---

# 🎯 Key Takeaways

Through this project I gained deeper understanding of:

• DAX evaluation context  
• Row context vs filter context  
• Virtual tables and intermediate calculations  
• Advanced relationship manipulation  
• Custom time intelligence logic

These concepts are essential for building scalable analytical models in Power BI.

---

# 👨‍💻 Author

Ovisha Sanyal  

Aspiring Data Analyst focused on transforming raw data into actionable insights through analytics, modeling, and visualization using Power BI.
