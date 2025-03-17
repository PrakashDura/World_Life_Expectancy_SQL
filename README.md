# 🌍 World Life Expectancy Analysis

## 📝 Project Overview
This project explores **global life expectancy trends**, using **MySQL** for **data cleaning and exploratory data analysis (EDA)**. The dataset consists of **2,941 rows** and **18 columns**, providing insights into **life expectancy, GDP, mortality rates, and other health indicators** over multiple years.

The project consists of two key phases:
1. **Data Cleaning**: Identifying and fixing duplicates, inconsistencies, and missing values.
2. **Exploratory Data Analysis (EDA)**: Extracting insights on life expectancy trends, GDP correlation, and other key health indicators.

---

## 📂 Dataset Information
### ✅ **Dataset Overview**
- **Total Rows:** 2,941
- **Total Columns:** 18
- **Key Features:**
  - `Country`: Name of the country
  - `Year`: Year of recorded data
  - `Life expectancy`: Average life expectancy in years
  - `GDP`: Gross Domestic Product per capita
  - `BMI`: Average Body Mass Index
  - `Adult Mortality`: Mortality rate of adults
  - `Status`: Whether a country is **Developed** or **Developing**

---

## 🛠️ Data Cleaning Process

## ✅ Steps Performed:
### 🔍 Identifying and Removing Duplicates
- Checked for **duplicate country-year combinations**.
- Removed duplicate records using **subqueries and DELETE operations**.

### 🏷️ Standardizing Data
- Fixed **missing or incorrect country status** (Developed/Developing).
- Standardized **country names** and ensured consistency in data.

### 📌 Handling Missing Values
- Identified missing values in **Life Expectancy** and imputed values using the **average of previous and next year**.

### 📏 Validating Data Integrity
- Ensured that **GDP, BMI, and Life Expectancy** had valid values.
- Verified that **Adult Mortality trends were logically consistent**.

---

#3 📊 Exploratory Data Analysis (EDA)

## 📈 Key Insights Explored:
- **Life Expectancy Trends Over the Past 15 Years.**
- **Impact of GDP on Life Expectancy.**
- **Correlation Between BMI and Life Expectancy.**
- **Comparison Between Developed and Developing Countries.**
- **Rolling Total of Adult Mortality Rates Over the Years.**

---

## 🚀 Technologies Used
- **Database:** MySQL
- **Techniques:** Data Cleaning, SQL Joins, Aggregations, Subqueries
- **Tools:** SQL Workbench / MySQL CLI

---

## 📌 How to Use This Repository
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/world-life-expectancy-analysis.git
