# Task 1 – Exploratory Data Analysis (EDA)
### Data Analytics Internship – Oasis Infobyte

##  Objective
The objective of this task is to perform Exploratory Data Analysis (EDA) on the given retail sales dataset.  
The goal is to understand the structure of the data, clean and preprocess it, analyze trends, and extract useful insights through visualizations.

---

##  Dataset Used
**Warehouse_and_Retail_Sales.csv**  
The dataset contains warehouse and retail sales information with fields such as:
- YEAR  
- MONTH  
- ITEM TYPE  
- SUPPLIER  
- RETAIL SALES  
- WAREHOUSE SALES  

---

##  Tools & Technologies Used
- **Python**
- **Jupyter Notebook**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **VS Code** (for running notebook)

---

##  Steps Performed

###  Data Loading
Loaded the CSV file using pandas and viewed:
- First few rows  
- Data types  
- Initial structure  

###  Data Cleaning & Preprocessing
- Filled missing values (Supplier, Item Type, Retail Sales)
- Converted negative sales to absolute values
- Created a new **DATE** column from YEAR and MONTH
- Removed formatting inconsistencies

###  Descriptive Statistics
Calculated:
- Mean  
- Median  
- Mode  
- Standard Deviation  

###  Time-Series Analysis
Plotted retail sales over time to observe monthly patterns.

###  Categorical Analysis
- Total sales by **Item Type**
- Top **10 Suppliers** based on Retail Sales
- Year-wise sales comparison

###  Correlation Analysis
Generated a **Correlation Heatmap** for numerical variables:
- YEAR  
- MONTH  
- RETAIL SALES  
- WAREHOUSE SALES  

---

##  Visualizations Included
- Line Graph (Monthly Sales Trend)
- Bar Graph (Sales by Item Type)
- Bar Graph (Top 10 Suppliers)
- Bar Graph (Year-wise Sales)
- Correlation Heatmap

---

##  Key Insights
- Liquor, Wine, and Beer are the major contributors to retail sales.
- A few suppliers generate most of the revenue.
- Retail and warehouse sales show moderate positive correlation.
- Monthly and yearly sales show no strong upward or downward trend.
- Non-alcohol and supply categories have very low sales.

---

##  Project Files
Inside this folder:
- `Task1_EDA.ipynb` → Jupyter Notebook containing full analysis  
- `readme.md` → Documentation (this file)

---

##  Outcome
Successfully completed full EDA, derived insights, and visualized important trends in the retail sales dataset.  
This task helped build hands-on experience in data cleaning, visualization, and exploratory analysis.

---
