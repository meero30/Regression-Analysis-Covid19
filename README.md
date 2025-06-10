# COVID-19 Cases and Vaccination Analysis in the Philippines (2022)

This project presents an analysis of COVID-19 active cases and vaccination doses in the Philippines for the year 2022 using regression techniques, particularly least squares linear regression.

## 📊 Project Overview

Using data gathered from reliable public sources, this study explores whether there is a statistical relationship between the number of COVID-19 cases and the number of vaccine doses administered monthly.

The project utilizes:
- **Python** (Jupyter Notebook) for data visualization and regression modeling
- **Pandas**, **NumPy**, and **Matplotlib** for data processing and plotting
- **Google Sheets** for additional regression forecasting using the `FORECAST` function

## 🎯 Objectives

- Apply least squares linear regression to COVID-19 and vaccine data
- Visualize trends and explore potential inverse relationships
- Predict trends for future months (January–March 2023)
- Evaluate the impact of outliers and data limitations

## 📈 Data Summary

The dataset includes:
- Monthly active COVID-19 case counts in the Philippines for 2022
- Monthly administered vaccine doses during the same period

> Data sources:
> - [Our World in Data](https://ourworldindata.org/covid-vaccinations?country=PHL)
> - [Worldometer - Philippines](https://www.worldometers.info/coronavirus/country/philippines/)

## 🧪 Methodology

1. Load data using `pandas`
2. Plot lag and regression graphs
3. Identify outliers and trends
4. Forecast future data points (2023) using:
   - Python regression models
   - Google Sheets’ `FORECAST` function

## 📉 Findings

- A visible downward trend in both vaccination and COVID-19 case data.
- A large outlier in February 2022 skewed the regression for COVID-19 cases.
- Due to this outlier and limited data points, forecasts were found to be unreliable (producing negative values).

## 📌 Conclusion

While the data showed decreasing trends in both metrics, the analysis concluded there is little to no direct correlation between vaccination numbers and active COVID-19 cases. Forecasting was limited due to outliers and data sparsity.

## 👨‍💻 Contributors
- **Miro Manuel L. Hernandez** – *Main coder and data analyzer*, Python programming, Data Processing, Analysis
- **Marcus Luis M. Chua** – Project Description, Alternative Design, Analysis
- **Matthew R. Orga** – Python programming, Data Processing, Analysis
- **Lorenzo Agustin B. Ramos** – Introduction, Data Gathering, Analysis, Conclusion

## 📅 Submitted for

**De La Salle University – NUMMETS ER1**  
*Term 1, A.Y. 2022 – 2023*  
**Instructor**: Engr. Gerald P. Arada  
**Date**: December 15, 2022
