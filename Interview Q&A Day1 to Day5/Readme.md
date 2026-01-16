# 📊 Data Analytics Interview Q&A (Day 1 – Day 5)

This repository contains **important interview questions, answers, and core concepts** covered in my **5-day Data Analytics preparation**, including:
- Fundamentals
- NumPy
- Pandas
- Data Visualization
- Statistics  

Written in **easy language**, focused on **interview clarity** and **real-world understanding**.

---

## 🟦 DAY 1: FUNDAMENTALS OF DATA ANALYTICS

### 🔑 What is Data Analytics?
Data Analytics means:

> Collecting, cleaning, analyzing, and presenting data to support decision-making.

---

### 🔄 Data Analytics Life Cycle
1. **Data Collection** – CSV, Excel, Databases, APIs  
2. **Data Cleaning** – Handle missing values, duplicates  
3. **EDA (Exploratory Data Analysis)** – Understand patterns and trends  
4. **Modeling (Optional)** – Predictions and forecasting  
5. **Visualization** – Charts and dashboards  
6. **Insights** – Business decisions  

---

### 🎯 Types of Analytics

| Type | Meaning | Example |
|----|----|----|
| Descriptive | What happened? | Sales last year |
| Diagnostic | Why did it happen? | Reason for sales drop |
| Predictive | What will happen? | Sales forecast |
| Prescriptive | What should we do? | Discount strategy |

---

### 💬 Interview Questions

**Q1. Difference between Data Analyst and Data Scientist?**  
➡ Data Analyst focuses on **data cleaning, analysis, and insights**  
➡ Data Scientist focuses on **machine learning models and predictions**

**Q2. What is EDA?**  
➡ Exploring data using **statistics and visualizations** before modeling

**Q3. Structured vs Unstructured data?**  
➡ Structured: Tables, rows, columns  
➡ Unstructured: Images, text, videos, audio

---

## 🟦 DAY 2: NUMPY

### 🔑 Why NumPy?
✔ Faster than Python lists  
✔ Uses less memory  
✔ Supports vectorized operations  

### 🔥 Important Concepts
  ndarray – Homogeneous data type
  Shape – Dimensions of array
  Broadcasting – Operations on arrays of different shapes
  Indexing & Slicing
### Axis
  Axis = 0 → Columns
  Axis = 1 → Rows
### 🧮 Important Functions
Function   	  Use
np.mean()	    Average
np.sum()	    Sum
np.std()	    Spread
np.reshape()	Change shape
np.where()	  Conditional logic

### 💬 Interview Questions
Q1. Why is NumPy faster than Python lists?
➡ Uses C language internally and contiguous memory allocation
Q2. What is broadcasting?
➡ Performing operations on arrays of different shapes
Q3. Difference between reshape and resize?
➡ reshape → returns new view
➡ resize → modifies original array

### DAY 3: PANDAS
🔑 What is Pandas?
A Python library used for structured data analysis.

Series – One-dimensional (single column)
DataFrame – Two-dimensional table

🧹 Data Cleaning (Interview Favorite)
Task	Method
Missing values	        isnull(), fillna()
Duplicates	            drop_duplicates()
Rename columns	        rename()
Change data type      	astype()

### 🔄 GroupBy (MOST IMPORTANT)
df.groupby("Gender")["Survived"].mean()
➡ Split → Apply → Combine
🔗 Merge vs Join vs Concat
Method	Use
merge	SQL-style joins
join	Index-based joining
concat	Stack datasets

## 💬 Interview Questions
Q1. Difference between loc and iloc?
➡ loc → Label-based
➡ iloc → Index-based
Q2. What is groupby?
➡ Used to perform aggregation based on categories
Q3. How do you handle missing values?
➡ Drop them or fill using mean / median / mode

### DAY 4: DATA VISUALIZATION
📊 Chart Selection
Chart	Use
Bar Chart	Compare categories
Histogram	Data distribution
Line Chart	Trends over time
Boxplot	Detect outliers
Scatter Plot	Relationship between variables

## 💬 Interview Question
Q. Difference between matplotlib and seaborn?
➡ matplotlib → Low-level, more control
➡ seaborn → High-level, statistical, better visuals

### DAY 5: STATISTICS
📐 Measures of Central Tendency
Measure	Use
Mean	Average
Median	Best for skewed data
Mode	Most frequent value
📏 Measures of Dispersion
Metric	Meaning
Variance	Spread of data
Standard Deviation	Volatility / risk
IQR	Robust measure of spread
✅ Final Notes
Always explain logic + business meaning in interviews
Prefer median over mean when outliers exist
Visualization is storytelling, not decoration

🚀 Author
Neeraj Solath
Aspiring Data Analyst | MCA Student
