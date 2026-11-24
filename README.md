# ☕ Starbucks Data Analysis | Power BI Project

An interactive Power BI dashboard analyzing Starbucks beverage performance across nutritional content, beverage categories, global presence and caffeine consumption. The project transforms Starbucks beverage data into meaningful business insights, helping understand product distribution, nutritional trends and beverage characteristics through data-driven visualization.

## 🎯 Business Objectives

- Which beverage categories have the highest calorie content?
- Which beverages have the strongest presence in Starbucks' product range?
- Which beverage categories contribute the most to the overall menu distribution?
- Which beverage categories contain the most caffeine on average?
- Identify the top 5 highest Caffeine Beverages.

## 🛠️ Tools & Technologies

- **Power BI Desktop** – Dashboard development and data visualization.
- **Power Query** – Data transformation and preparation.
- **Data Modeling** – Organizing beverage data for analytical reporting.
- **DAX** – KPI calculations, aggregations and analytical measures.

## 📊 Dashboard Overview

The project consists of an interactive dashboard providing an overview of Starbucks beverage performance and nutritional characteristics.

### Starbucks Beverage Analysis

<img width="1440" height="806" alt="image" src="https://github.com/user-attachments/assets/289de687-0eaa-4923-8d66-83d1a157e783" />


**Key Business Insights:**

- Smoothies have the highest average calories (**282**), followed by Frappuccino beverages (**277**).
- White Chocolate Mocha and Java Chip leading the global presence, while Coffee and Caffè Mocha have comparatively lower representation.
- Classic Espresso Drinks lead with **21%**, while other beverage category distributions are **15% or lower**.
- Brewed Coffee leads with **294mg**, followed by Caffè Americano (**188mg**) and Iced Brewed Coffee (**173mg**).
- Coffee ranks first (**293.75mg**), followed by Classic Espresso Drinks (**122.07mg**), Frappuccino Blended (**101.81mg**), Frappuccino Light (**99.58mg**) and Iced Beverages (**98.53mg**).

## 📁 Dataset & Data Model

**Dataset:**
- The dashboard analyzes Starbucks beverage data covering nutritional information, beverage categories and product characteristics.
- The dashboard displays **33 beverages** in its overall beverage KPI.

The dataset covers:
- Beverage names and categories.
- Beverage preparation types.
- Calories and sugar content.
- Caffeine content.
- Protein content.

**Data Model:** No data model created in this project, because we have only one useful table that contain required data to analyze Starbucks beverage performance.

## 🔍 KPIs or DAX Measures

The dashboard highlights the following key performance indicators:
```dax
Total Beverages = DISTINCTCOUNT(starbucks[Beverage])

Avg Sugar = AVERAGE(starbucks[ Sugars (g)])

Avg Calories = AVERAGE(starbucks[Calories])

Avg Caffeine = AVERAGE(starbucks[Caffeine (mg)])
```

## 🎛️ Interactive Features

The dashboard includes interactive filters and slicers:

- Protein Range
- Beverage Preparation Methods

## 💡 Key Skills Used

- Data Cleaning & Transformation
- Data Modeling
- DAX & KPI Development
- Exploratory Data Analysis
- Business Problem Solving
- Data Visualization & Storytelling
- Interactive Dashboard Development

## 🚀 Project Presentation

Here is a short dashboard walkthrough that demonstrating the dashboard layout, interactive filters, nutritional comparisons and beverage category analysis:

https://github.com/user-attachments/assets/017fcf36-4bfa-429d-ba96-030a9c2a5aa4



## 👨‍💻 About Me

**Chandrashekhar Burde | Data Analyst**

As I work on real-world projects and find new ways to use data for businesses, my goal is not just to create charts and visuals, but to understand what the data tells us and turn it into useful insights that help make better decisions.

**Skills:** Power BI | Power Query | Excel/Google Spreadsheets | ETL/ELT | DAX | Data Cleaning | Data Visualisation
