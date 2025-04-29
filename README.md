# 🛒 Walmart Sales Analysis & Forecasting (BigQuery + Python)

This project focuses on performing in-depth sales analysis and forecasting for Walmart stores using data directly accessed from **Google BigQuery**. It combines **exploratory data analysis (EDA)**, **statistical computations**, and **linear regression modeling** to uncover insights and predict future demand for **Store 1**.

---

## 🧰 Tools Used

- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- **Google BigQuery** (for SQL-based data access)
- **Jupyter Notebook / Colab**
- **Linear Regression Modeling**

---

## 📊 Key Analysis Tasks & Results

### 1️⃣ Maximum Sales
- **Store 20** had the highest overall sales.

### 2️⃣ Sales Variability
- **Store 14** had the highest **standard deviation**, indicating significant variability in sales.
- **Coefficient of Variation (CV)** was also computed to standardize the variability against the mean.

### 3️⃣ Growth Rate (Q3 2012)
- **Quarterly sales growth** was analyzed; **Store 4** and **Store 14** showed the best performance in Q3 2012.

### 4️⃣ Holiday Impact
- Holidays like **Super Bowl** and **Thanksgiving** showed **higher-than-average** sales compared to non-holiday periods, indicating a **positive impact** for some.

### 5️⃣ Monthly & Semester Sales Trends
- Created **monthly and semester-wise aggregates**.
- Visualized trends showing **seasonality**, **mid-year sales dips**, and **holiday peaks**.

---

## 📈 Forecasting Model for Store 1

### Objective
Predict weekly sales for **Store 1** using a **linear regression** model.

### Features Used
- `Days_Since_Start` (derived from date)
- `Fuel_Price`
- `CPI`
- `Unemployment`

### Methodology
- Dates were transformed into sequential days since the earliest date.
- Model was trained and evaluated using R² and RMSE.
- Results showed that **fuel price and unemployment** had modest influence, while **date-based trends** were more significant.

---

