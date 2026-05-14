 # 🧠 Suicide Mortality Rate Analysis — Python

> Analyzing suicide mortality trends across **European Union, South Asia, and Sub-Saharan Africa**
> from 2000 to 2021 using **World Bank data** — contributing to **SDG 3** (Good Health and Well-being).

---

## 📋 Project Overview

This project examines regional suicide mortality rates using Python, exploring how rates have
evolved over two decades across three major global regions. The analysis involves data
wrangling, reshaping, and visualization to uncover regional patterns and long-term trends
in suicide mortality.

---

## 🎯 Objectives

- Analyze **suicide mortality trends** across three regions from 2000 to 2021
- Reshape and clean **World Bank data** for time-series analysis
- Visualize **year-wise regional trends** using Python
- Contribute to evidence base for **SDG 3** (Good Health and Well-being)

---

## 📊 Key Findings

| Region | 2000 | 2021 | Trend |
|--------|------|------|-------|
| **European Union** | 14.86 | 12.09 | 📉 Consistent decline |
| **South Asia** | 14.95 | 11.54 | 📉 Gradual decline |
| **Sub-Saharan Africa** | 6.95 | 7.30 | 📈 Slight increase |

- 🔵 **EU** showed the most consistent decline over 20 years
- 🟠 **South Asia** remained nearly stable with a slight decline
- 🟢 **Sub-Saharan Africa** had the lowest rates but showed a recent slight rise
- ⚠️ EU and South Asia rates are approximately **twice as high** as Sub-Saharan Africa

---

## 🛠️ Tools & Libraries

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

---

## 🔄 Analytical Workflow

### 1. 📥 Data Import & Preview
- Loaded Excel dataset using **Pandas**
- Previewed structure, column names, and data types

### 2. 🧹 Data Reshaping
- Converted **wide format** to **long format** using `pd.melt()`
- Converted year column to integer for time-series plotting

### 3. 📊 Pivot Table
- Created a pivot table with **Year as rows** and **Region as columns**
- Rounded values to 2 decimal places for readability

### 4. 📈 Visualization
- Plotted **year-wise suicide mortality rates** by region
- Used **Seaborn line plot** with markers and distinct line styles
- Applied clean styling with no gridlines for professional output

---

## 📁 Repository Structure
