# IT362-DataScience-Project


# 🌙 Hajj & Umrah Hotel Price Analysis: Makkah, Madinah, and Taif (2026)

## 📌 Overview

This project focuses on analyzing hotel price patterns in Makkah, Madinah, and Taif during the Hajj and Umrah seasons. By collecting and processing data for the year 2026, we aim to understand how demand factors, seasonality, and location influence accommodation costs for pilgrims.

## 🎯 Project Objectives

* **Analyze Price Variations:** Investigate how prices fluctuate between peak seasons (Ramadan, Hajj Peak) and regular periods.


* **Identify Drivers:** Determine the impact of location, hotel rating, and seasonality on price changes.


* **Comparative Insight:** Use Taif as an alternative destination to provide insight into accommodation strategies for pilgrims.

--


## 📊 Key Findings (EDA Insights)

* **Geographic Concentration:** Hotel supply is highly concentrated in Makkah, which also experiences the highest average prices.


* **Seasonality:** Ramadan is the peak operational period with the highest volume of hotel listings.


* **Satisfaction vs. Price:** Correlation analysis revealed almost no linear relationship between hotel price and user rating; higher prices do not guarantee higher satisfaction.


* **Outliers:** Significant price outliers were identified in Makkah during the "Pre-Hajj" period, suggesting a "Dynamic Scarcity Model" for pricing.

--

## ⚙️ Modelling Approach

We evaluated four models to predict hotel prices based on available features:

1. **Mean Baseline:** Served as the initial reference point.


2. **Linear Regression (Selected Best Model):** Achieved the lowest RMSE (0.293), indicating that the relationship between features and prices is relatively linear.


3. **Decision Tree Regressor:** Showed signs of overfitting and performed worse than the baseline.


4. **Random Forest Regressor:** Produced higher error values and a negative $R^2$ score.

--

## 📂 Project Structure

* `DataScience.ipynb`: The main notebook containing the data collection, cleaning, EDA, and modeling phases.


* `PROCESSED_DATA.csv`: The final processed dataset used for modeling.


* `Unstructured _Data.csv`: Raw data collected for the analysis.


--
## 🚀 Technologies Used

* **Data Collection:** SerpApi (Google Hotels API).


* **Language:** Python.


* **Libraries:** Pandas (Manipulation), Matplotlib/Seaborn (Visualization), Scikit-learn (Modeling).



---
## 👥 Team Members

* **Najla Alhusaini**
* **Juri Alanazi**
* **Deema Alquwaei**
* **Amal Alenazi**
* **Maria Alshamrani**
