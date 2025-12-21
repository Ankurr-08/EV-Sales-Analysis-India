# 🚗 Electric Vehicle (EV) Sales Analysis in India

## 📌 Project Overview
This project performs an exploratory data analysis (EDA) on Electric Vehicle (EV) sales data across Indian states.  
The objective is to understand EV adoption trends over time, identify leading states, and analyze vehicle-type preferences driving India’s transition toward electric mobility.

The analysis focuses on **descriptive insights and visualizations** to uncover meaningful patterns in EV sales.

---

## 📊 Dataset Information
- **Source:** Clean Mobility Shift (scraped and preprocessed)
- **Time Period:** 2014 – 2024
- **Granularity:** State-wise, vehicle-type-wise EV sales
- **Format:** CSV

### Key Columns:
- `Year`
- `Month_Name`
- `Date`
- `State`
- `Vehicle_Class`
- `Vehicle_Category`
- `Vehicle_Type`
- `EV_Sales_Quantity`

---

## 🛠 Tools & Technologies
- **Python**
- **Pandas** – data manipulation
- **Matplotlib & Seaborn** – data visualization
- **Jupyter Notebook**

---

## 🔍 Steps Performed

### 1️⃣ Data Cleaning
- Converted incorrect data types (Year, Date, categorical columns)
- Verified no missing values or duplicate records
- Standardized categorical values where necessary

### 2️⃣ Exploratory Data Analysis (EDA)
- Distribution analysis of EV sales
- Year-wise EV sales trend
- Month-wise EV sales pattern
- State-wise EV adoption comparison
- Vehicle category analysis
- Vehicle type analysis
- Vehicle class analysis

---

## 📈 Key Insights
- EV sales in India are **highly right-skewed**, with most state-month records showing low or zero sales.
- EV adoption was minimal before 2018 and increased rapidly after 2021.
- A small number of states (Delhi, Maharashtra, Karnataka, Tamil Nadu, Uttar Pradesh) contribute a large share of total EV sales.
- **Two-wheelers** dominate EV adoption across most states due to affordability and daily usage.
- **Three-wheelers** show strong adoption in states with high shared mobility demand.
- EV sales show mild seasonality, with higher sales in specific months.

---

## 📌 Conclusion
The analysis highlights strong regional and vehicle-type disparities in EV adoption across India.  
While EV growth has accelerated significantly in recent years, adoption remains concentrated in a few states and vehicle segments.  
These insights can help policymakers, manufacturers, and infrastructure planners make informed decisions to support India’s EV ecosystem.

---

## 🔮 Future Scope
- Predict EV sales using machine learning models
- Include charging infrastructure data for deeper insights
- Perform city-level EV adoption analysis
- Build interactive dashboards using Power BI or Tableau


