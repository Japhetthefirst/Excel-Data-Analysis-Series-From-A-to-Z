# 🅰️ A for Automobiles — Excel Data Analysis Project

##🚗 Overview

This project is part of my Excel Data Analysis A–Z Series, where I explore datasets across different domains — starting with Automobiles.
Using an Automobile Dataset from Kaggle, this analysis focuses on data cleaning, transformation, and basic insights using Excel.

## 📊 Objectives
- Data cleaning in Excel
- EDA
- Data Visualization to identify the safest KPI's
- Building a clean and interactive Excel dashboard

---

## 🧹 Data Cleaning Steps
- Peformed research on the column names as i did not know much about automobiles
- Replaced some missing values with Mean value and removed other missing valuesce.g Replaced “?” and “NaN” with appropriate values
- Formated Data Types e.g Converted numerical columns to number data types
- Added a custom column which i did not later use (price levels)

---

## 📈 Analysis Performed
- Using Data Analysis Toolpak i performed descriptive statistics on the numeric columns (price, horsepower, length etc) to get a general undertsanding on the data
- Pivot table analysis to identify trends by make, body-style, and fuel-type (this part took alot of my time because i really do not know anything about automobiles)
- Scatter plots to visualize city vs highway MPG relationships
- Determined the fastest car, most expensive car, and least safeest cast.

---

## 📊 Dashboard Visuals
The final Excel dashboard includes:
- 🚗 Scatter Plot: Price vs Engine 
- 🏭 Clustered Bar Chart: City vs Highway MPG (with R² trendline)
- Combo Chart: Prices vd HorsePower with respectc to the body-type
- 🛡️ Safety Ranking Chart: Cars with lowest symboling scores
- Simple slicer (car make)
- KPI Cards: Average Price for each car wrt to the slicer, count and safety.

---

## ⚙️ Tools & Features Used
- Microsoft Excel
- Power Query (for data cleaning)
- Pivot Tables & Pivot Charts
- Power Pivot for creating measures
- Correlation Analysis (CORREL function)
- Dashboard design and layout

---

## 📂 Dataset
Source: https://www.kaggle.com/datasets/toramky/automobile-dataset?utm_source=chatgpt.com

---

## 🧠 Key Insights
- There was Strong positive correlation between city-mpg and highway-mpg because the highway mpg was always higher than the city mpg
- In the year 1985, the safest car was volvo and the least safest was the porshe.
- The most-expensive being the Mercedez benz
- The data showed that the bigger the engine in the car the more expensive the car would be.
- The data showed us that majority of the car were not so safe (about 50%)
- Finally the fastest cars were cars with Hatchbacks body types both in the city and highway. They also consume a significant amount of fuel.

---

## Next in the Series
➡️ B for Banking: Analysis of financial transactions dataset

---

## 🧑‍💻 Author
Olusegun Japhet Abiola
📧 olusegunjapheth@gmail.com
🔗 www.linkedin.com/in/japhetolusegunabiola

I did not capture a lot of information from this data. Feel free to perform your own analysis and send to my mail. 
I would appreciate any and all feedbacks.