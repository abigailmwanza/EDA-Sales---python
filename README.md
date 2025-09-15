# 🏪 Rossmann Store Sales Analysis  

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)  
![Pandas](https://img.shields.io/badge/Pandas-Analysis-yellowgreen)  
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-orange)  
![Matplotlib](https://img.shields.io/badge/Matplotlib-Charts-blueviolet)  

## 📌 Overview  
This project explores and analyzes the **Rossmann Store Sales dataset**, which contains over **1 million sales records** across **1,115 stores**.  
The goal is to understand **sales drivers, customer behavior, and the impact of promotions**, and prepare the data for predictive modeling.  

---

## 📊 Dataset  
The dataset comes from the [Kaggle Rossmann Store Sales Competition](https://www.kaggle.com/c/rossmann-store-sales/data).  

- **train.csv** → Daily sales and customers data  
- **store.csv** → Metadata about each store  

### Features:
- **Sales** → Target variable (store sales per day 💰)  
- **Customers** → Number of customers per day 👥  
- **Promo** → Promotion flag (yes/no 📢)  
- **StateHoliday** → Type of holiday (public, Easter, Christmas, none 🎉)  
- **SchoolHoliday** → If schools were closed 📚  
- **StoreType, Assortment, CompetitionDistance** → Store-specific info 🏬  

---

## 🔍 Key Analysis Steps
1. **Data Loading & Cleaning**  
   - Removed closed store entries  
   - Handled missing values for competition & promo info  

2. **Exploratory Data Analysis (EDA)**  
   - Distribution of sales, customers, and promotions  
   - Correlation heatmap of numerical features  
   - Seasonal & holiday sales patterns  

3. **Feature Engineering**  
   - Extracted **Year, Month, Day, DayOfWeek** from Date  

4. **Visualizations**  
   - 📅 Average sales & customers per month, day, weekday  
   - 🏷️ Sales trends by store type  
   - 📢 Effect of promotions on sales & customers  

---



---
