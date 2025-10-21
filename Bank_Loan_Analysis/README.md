# B for Bank— Excel Data Analysis Project

##🚗 Overview

This is the second part of my Excel Data Analysis A–Z Series, where I explore datasets across different domains. This particular series is on Bank Loan.
Using a Dataset from Kaggle, this analysis focuses analyzing customers in a certain bank during a loan campaign perio.

## 📊 Objectives
- Data cleaning
- Simple EDA
- Data Visualization to identify the safest KPI's
- Building a clean and interactive Excel dashboard

---

## 🧹 Data Cleaning Steps
- I researched on the column names as again some of the banking terms like Securities account etc,were foreign to me.
- Formated Data Types e.g Converted numerical columns to number data types
- Converted binary data types to text (Yes and No).
- Added 2 custom columns (income level and Loan Approval)

---

## 📈 Analysis Performed
- Using Data Analysis Toolpak i performed descriptive statistics on the numeric columns (age, experience, family size, income, CCAvg and Mortage etc) to get a general undertsanding on the data.
- Pivot table and charts for EDA

---

## 📊 Dashboard Visuals
The final Excel dashboard includes:
- 🚗 Bar chart: Loan Uptake vs Income Range, Loan Uptake vs Education, Loan Status
- 🏭 Funnel Chart: Avg Mortage for Loan Uptakes.
- Pie Charts: % of customers with CD Accounts, % of customers with Securities Account, % of customers that had loan uptakes, % of customers that use internet banking system, Loan Uptake by family size, % of customers that took loans based on their approval statuses.
- KPI Cards: Total Applicatnts, Total Loan Uptakers, Average Mortage, Average Income.


https://github.com/user-attachments/assets/bf93a379-5903-42a2-8396-2d48144abd13


---

## ⚙️ Tools & Features Used
- Microsoft Excel
- Power Query (for data cleaning)
- Pivot Tables & Pivot Charts
- DAX for creating measures

---

## 📂 Dataset
Source: https://www.kaggle.com/datasets/itsmesunil/bank-loan-modelling?utm_source=chatgpt.com

---

## 🧠 Key Insights
- There were a total of 480 loan uptakers out of a total of 4948.
- Single individuals were noted to take loans that other family sizes. 
- Using the custome column "Income level" which i divided into High, Mid and Low, it was noted that middle income individuals or families had the highest loan applications.
- A large majority of the loan takers were also undergraduates. The probably needed the loans to pay of their school fees.
- Finally, from my perspective, i developed a criteria for the approval, rejection and review of loans using the formular below:
### 🧮 Loan Approval Decision Logic

| Condition No. | Income (₦’000) | CCAvg (Credit Card Avg. Usage) | Online Presence | Securities Account | Decision     |
|---------------|----------------|--------------------------------|-----------------|--------------------|---------------|
| 1             | ≥ 50            | ≥ 1.0                          | Yes             | Yes                | **Approved**  |
| 2             | ≥ 50            | ≥ 0.8                          | Yes             | No / Blank         | **Reviewing** |
| 3             | Any other case  | Any                            | Any             | Any                | **Rejected**  |

**Formula Used in Excel**
```excel
=IF(AND([@Income]>=50, [@CCAvg]>=1, [@[Online_Presence]]="Yes", [@[Securities Account]]="Yes"), 
   "Approved", 
   IF(AND([@Income]>=50, [@CCAvg]>=0.8, [@[Online_Presence]]="Yes"), 
      "Reviewing", 
      "Rejected"))

---

## Next in the Series
➡️ C for  Customer Segmentation

---

## 🧑‍💻 Author
Olusegun Japhet Abiola
📧 olusegunjapheth@gmail.com
🔗 www.linkedin.com/in/japhetolusegunabiola

Feel free to perform your own analysis and critic my work.
I would appreciate any and all feedbacks.