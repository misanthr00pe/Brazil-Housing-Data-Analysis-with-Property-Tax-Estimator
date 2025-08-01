# 🏡 Brazil Housing EDA & Property Tax Estimator

## 🧾 Overview

This project analyzes housing data across Brazil with the goal of identifying suitable cities for relocation based on expense factors tailored to different household types—bachelors, mid-sized families, and large families. It further leverages machine learning to build a predictive model that estimates monthly property tax (R$) using features such as property area, number of rooms, HOA fees, rent, and more. By combining data visualization and predictive analytics, the project provides actionable insights to support smarter housing decisions across various family profiles.


## 🧰 Tools & Technologies Used

- **Python** – Core language for data manipulation, analysis, and modeling
- **Pandas & NumPy** – Efficient handling of structured data and numerical operations
- **Matplotlib, Seaborn & plotly** – For creating insightful and visually appealing data visualizations
- **Excel** – Utilized for preliminary data exploration
- **Linear Regression & CatBoost** –  Applied for building and optimizing the property tax prediction model


## 🧭 Agenda

**Aspects to look at in case of a bachelor:**
- Property area should be small
- 1 bedroom
- 1 bathroom
- 1 or no parking plot

**Aspects to look at in case of a mid-sized family (3-4 members):** 
-  Property size moderate 
- 3  bedrooms
- 2  bathrooms 
- 1 or 2 parking plot preferable

**Aspects to look at in case of a large family (5-6 members):**
- Relatively bigger property
- 4  bedrooms
- 2  bathrooms
- Dual parking plot preferable
  

## 🎯 Objective

**Data Exploration & Preprocessing**
- Overview of dataset and key features
- Data wrangling, handling missing values, and feature engineering

**Exploratory Data Analysis (EDA)**

- Visual insights by city, room count, area, rent, etc.
- Comparison across household types (bachelors, families)

**Model Development**
- Regression models for property tax prediction
- Model selection, training, enhancement and evaluation

**Results & Interpretation**
- Key findings and insights from EDA
- Performance of prediction models

**Conclusion & Recommendations**
- Best cities based on affordability for different family sizes
- Use cases for the tax estimator tool
