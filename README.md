# 🦠 COVID-19 Data Exploration – SQL Analysis Project

---

## 📌 Project Overview
This project explores global COVID-19 data using SQL to analyze infection rates, death counts, and vaccination progress across countries and continents.  

The goal is to demonstrate strong skills in **data cleaning, analysis, aggregation, and reporting**, producing datasets ready for visualization.

---

## 🎯 Objectives
- Analyze infection and death trends by country and continent  
- Identify countries with the highest infection and death rates relative to population  
- Track vaccination progress over time  
- Build reusable SQL queries, CTEs, and views for structured analysis  
- Prepare datasets for visualization in Power BI or Tableau  

---

## 📊 Dataset Description

**CovidDeaths**  
- Location, Continent, Date  
- Total cases, New cases  
- Total deaths, New deaths  
- Population  

**CovidVaccinations**  
- Location, Date  
- New vaccinations  

---

## 🛠 Tools & Technologies
- Microsoft SQL Server  
- SQL Server Management Studio (SSMS)  

**SQL Techniques:**  
- Joins (INNER, LEFT)  
- Common Table Expressions (CTEs)  
- Window Functions (`OVER`, `PARTITION BY`)  
- Aggregate Functions (`SUM`, `MAX`)  
- Data Type Conversion (`CAST`, `CONVERT`)  
- Creating Views  

---

## 🔄 Data Preparation
- Filtered aggregated rows using `continent IS NOT NULL`  
- Converted death and vaccination counts to numeric types  
- Calculated rolling vaccination totals per country using window functions  
- Standardized column names and cleaned missing values  

---

## 📈 Analysis Features
- **Case & Death Analysis:** Total cases vs total deaths per country, calculated death percentage  
- **Population Impact:** Percentage of population infected, ranked countries by infection rate  
- **Death Count Analysis:** Total deaths per country, aggregated deaths by continent  
- **Vaccination Analysis:** Rolling cumulative vaccinations, percentage of population vaccinated  
- **Global Metrics:** Global new cases, global new deaths, global death percentage  

---

## 💡 Key Insights
- Countries with high infection rates may not always have the highest death rates  
- Vaccination rollout trends vary across continents  
- Population size affects relative infection and death percentages  
- Rolling totals provide better insight into vaccination progress  

---

## 👤 Author
**Akhila Vitta**  
Master’s in Data Science  
Data Analyst | Data Engineer  

---

## 🚀 Future Enhancements
- Build interactive dashboards in Power BI or Tableau  
- Add time-series trend analysis  
- Compare vaccination rates with case and death trends  
- Incorporate additional health metrics for deeper insights  
