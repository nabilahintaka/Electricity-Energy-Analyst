# ⚡ Electricity & CO₂ Emissions Analysis

## 📌 Overview

This project analyzes global electricity production data to identify the key drivers behind **CO₂ emissions, energy inequality, and economic influence on energy access**.

The analysis combines **data cleaning, exploratory data analysis (EDA), and visualization** to uncover patterns across energy sources (fossil, renewable, nuclear), and how they relate to **economic development and sustainability**.

---

## 📌 Executive Summary

This analysis reveals that **fossil fuel dependency is the primary driver of CO₂ emissions globally**, while renewable energy adoption—although growing—remains insufficient to offset emissions at scale.

Key findings include:

* Countries heavily reliant on fossil fuels produce **significantly higher CO₂ emissions**
* Renewable energy adoption is increasing but remains **uneven across regions**
* Higher **GDP per capita strongly correlates with better electricity access**
* Developing countries face a dual challenge of **increasing energy access while reducing emissions**

💡 These findings suggest that achieving sustainable energy goals requires balancing **economic growth, infrastructure readiness, and clean energy transition strategies**.

---

## 🔄 Data Processing

The dataset was prepared through several preprocessing steps:

* Standardized column names using **snake_case**
* Handled missing values and removed incomplete records
* Converted data types for accurate numerical analysis
* Performed data validation (no duplicate records found)
* Created new features such as **energy composition ratios**

---

## 📊 Exploratory Data Analysis

The analysis focuses on identifying relationships between energy production, emissions, and economic indicators:

### ⚡ Energy Production Analysis

* Compared electricity generation across:

  * Fossil fuels
  * Renewable energy
  * Nuclear energy
* Analyzed **energy mix composition by country**

### 🌍 Emissions Analysis

* Identified **top CO₂-emitting countries**
* Examined the relationship between:

  * Fossil fuel usage and CO₂ emissions
  * Renewable energy and emissions

### 📈 Economic & Accessibility Analysis

* Explored correlation between:

  * GDP per capita and electricity access
* Compared developed vs developing countries in:

  * Energy usage
  * Electricity accessibility

---

## 🎯 Key Insights

* ⚡ Electricity generated from fossil fuels shows a **strong positive correlation with CO₂ emissions**, confirming it as the primary emission driver
* 🌱 Renewable energy contributes to electricity production but has **not yet significantly reduced global emission levels**
* 🌍 Countries with higher GDP per capita achieve **near-universal electricity access**, while lower-income countries still face energy inequality
* 📊 Economic development plays a critical role in enabling both **energy access and cleaner energy transitions**
* 🔄 The global energy transition remains **uneven**, with developing countries still highly dependent on fossil fuels

---

## 📊 Key Visualizations

The project includes several visual analyses to support insights:

* 📊 **Energy Mix by Country (Stacked Bar Chart)**
* 🌍 **Top CO₂ Emitting Countries (Bar Chart)**
* 📈 **Fossil Fuel vs CO₂ Emissions (Regression Plot)**
* 📉 **Renewable Energy vs CO₂ Emissions (Scatter Plot)**
* 💡 **GDP per Capita vs Electricity Access (Regression Analysis)**
* 🔥 **Correlation Heatmap of Key Variables**

These visualizations highlight the relationships between **energy production, emissions, and economic development**.

---

## 📊 Dashboard

An interactive dashboard was built using Tableau to explore the data dynamically:

🔗 Tableau Dashboard:
https://public.tableau.com/views/ElectricalEnergyDashboard/Dashboard1

Features:

* KPI overview (CO₂ emissions, energy production, electricity access)
* Country-level filtering
* Energy source comparison
* Visual storytelling of global energy trends

---

## 🛠️ Tools & Technologies

* **Python** (Pandas, NumPy) → Data cleaning & analysis
* **Matplotlib & Seaborn** → Data visualization
* **Tableau** → Interactive dashboard

---

## 📂 Project Structure

* Data cleaning & transformation → Jupyter Notebook
* Exploratory analysis → Python (EDA)
* Visualization → Python & Tableau
* Insights & recommendations → Documentation

---

## 💡 Business Impact

This analysis provides insights that can support:

* Strategic planning for **clean energy transition**
* Identification of **high-emission risk regions**
* Understanding the link between **economic growth and energy accessibility**
* Policy development for **sustainable energy investment**

---

## ⚠️ Limitations

* Dataset is limited to publicly available data (Kaggle)
* No real-time data integration
* Limited variables (no policy, behavioral, or demographic factors)
* Analysis is based on historical trends (no predictive modeling) 

---

## 🚀 Future Work

* Develop **predictive models** for CO₂ emissions and energy demand
* Analyze **energy transition trends over time**
* Integrate additional datasets (policy, population, climate data)
* Build **real-time monitoring dashboards**
* Perform deeper analysis on **renewable adoption effectiveness**

---

## 📎 Dataset

Source: Kaggle - Global Sustainable Energy Dataset
https://www.kaggle.com/datasets/anshtanwar/global-data-on-sustainable-energy

---

## Author Notes

This project is part of a **Data Analyst Portfolio**, showcasing skills in:

* Data cleaning & preprocessing
* Exploratory data analysis (EDA)
* Data visualization & storytelling
* Insight generation for business decision-making
