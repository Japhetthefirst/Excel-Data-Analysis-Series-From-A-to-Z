# D for Delivery

##🚗 Overview

This is the fourth part of my Excel Data Analysis A–Z Seriesand this particular series is on an Amazon Delivery Data.
Using a Dataset from Kaggle, this analysis focuses analyzing products ordered and delivered, agents making the deliveries, store locations and drop locations, product categories, weather and traffic condtion and finally the vehicle used in the actual delivery.

## 📊 Objectives
- Data cleaning
- Simple EDA
- Data Visualization
- Building Excel dashboard
- Understanding Patterns
- Drawing conclusion on the factors influences how fast a product is delivered.

---

## 🧹 Data Cleaning Steps
- Formated Data Types e.g Converted numerical columns to number data types
- Checked for duplicates
- Duplicated the main datasets one for performance evaluation and the other for distance evaluation. The main dataset had about 500 rows with unusable data (i tried my best to clean it but then mean coordinates will birth an outlier in the my engineered distance(km) column. One table was complete and used for some descriptive analysis and some diagnostic analysis while the other was cleaned properly for the major performance visualisation that had to do with the distance(km) column
- Engineered certain columns for simple EDA: age_group (15-20, 21-30, 31-40, and 41-50), delivery time(hr), distance(km) (gotten from calulating the distance between the store and the drop coordinates).
- Used Dax to create simple measure like avg agent_rating, avg_distance(km), order_count, avg delivery time(hr) for easy pivoting.

---

## 📈 Others
- Using Data Analysis Toolpak i performed descriptive statistics on the numeric columns (agent_rating, agent_age, store and drop coordinates, delivery_time, and distance(km)) to get a general undertsanding on the data.

---

## 📊 Dashboard Visuals
The final Excel dashboard includes:
- 🚗 Combo chart: How vehicle type and distance covered affects delivery time?
- 🏭 Tree Map: How does traffic affect delivery time?
- Pie Charts: distribution of age and and vehicles majorly used for deliveries.
- Line chart: How does weather affect delivery time?, How does area of drop affect delivery time?
- KPI Cards: Order Count, Average Delivery Time, Average Rating, and Average Distance(km).

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/1aecc932-5925-4421-bff1-c345cf4caf76" />

---

## ⚙️ Tools & Features Used
- Microsoft Excel
- Power Query (for data cleaning)
- Pivot Tables & Pivot Charts
- DAX for creating measures

---

## 📂 Dataset
Source: https://www.kaggle.com/datasets/sujalsuthar/amazon-delivery-dataset?utm_source=chatgpt.com

---

## 🧠 Key Insights
- 43739 orders were made to different amazon stores. With delivery agents ranging from ages 15 to 50 with majority being with the age group (21-30). The company's avg rating is 4.6
- Most orders were made from Metropolitan area and electronics were the most ordered category even though shoes had the highest avg delivery rating. The least order category was clothing but it did not have the lowest avg rating.
- Motorcycles were mostly used to complete deliveries and they travelled the 2nd longest distances after scooters. Vans covered the longest distances in one of the shortest of time. It took an least avg of 2.6 hrs to complete a delivery
- Cloudy day affected the delivery time the most (mainly beacuse of what come with the cloud such as rain, high winds etc), vans are the most efficient form of category delivery, it took longer time to deliver products in semi-urban areas probably because of bad roads and improper house naming conventions and high/dense traffic affects delivery time.

---

## 🧠 Solution
- Orderss to Urban and Metropolitan areas should be proitized as most products are ordered from there. If semi-urban location would not be discontinued, the services of drones should be employed to reduce delivery time.
- Customers should be notifed if there would be any delay due to the weather/traffic to avoid bias reviews.
- Vans and scooters should be the main form of delivery as they cover longer distances over shorter period of times.

--

## Next in the Series
➡️ E for Education
---

## 🧑‍💻 Author
Olusegun Japhet Abiola
📧 olusegunjapheth@gmail.com
🔗 www.linkedin.com/in/japhetolusegunabiola

Feel free to perform your own analysis and critic my work.
I would appreciate any and all feedbacks.