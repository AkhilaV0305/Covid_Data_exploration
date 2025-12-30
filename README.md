project:
  name: "COVID-19 Data Exploration (SQL)"

overview:
  - Analyze global COVID-19 data using SQL
  - Study infection rates, death counts, and vaccination progress
  - Perform country-level and continent-level analysis

skills_used:
  - SQL Joins
  - Common Table Expressions (CTEs)
  - Temporary Tables
  - Window Functions (OVER, PARTITION BY)
  - Aggregate Functions (SUM, MAX)
  - Data Type Conversion (CAST, CONVERT)
  - Creating Views

datasets:
  CovidDeaths:
    - Location
    - Date
    - Total cases
    - New cases
    - Total deaths
    - Population
  
  CovidVaccinations:
    - Location
    - Date
    - New vaccinations

analysis_performed:
  data_cleaning:
    - Filtered aggregated rows using continent IS NOT NULL
    - Focused only on country-level data

  case_vs_death_analysis:
    - Compared total cases with total deaths
    - Calculated death percentage per country

  population_impact:
    - Calculated percentage of population infected
    - Identified countries with highest infection rates

  death_count_analysis:
    - Ranked countries by total deaths
    - Analyzed death counts by continent

  global_numbers:
    - Calculated total global cases
    - Calculated total global deaths
    - Computed global death percentage

  vaccination_analysis:
    - Joined CovidDeaths and CovidVaccinations tables
    - Calculated rolling vaccination totals
    - Measured percentage of population vaccinated

sql_techniques_used:
  - INNER JOIN and LEFT JOIN
  - Window functions with PARTITION BY
  - CTEs for structured queries
  - Temporary tables for intermediate storage
  - Views for reusable analysis

output:
  - Clean datasets ready for visualization
  - Country-level and continent-level insights
  - Suitable for Power BI or Tableau dashboards

tools:
  - Microsoft SQL Server
  - SQL Server Management Studio (SSMS)

next_steps:
  - Build interactive dashboards
  - Add time-series analysis
  - Compare vaccination rates with deaths
