# 🏦 Banking Analysis Project

This project focuses on analyzing banking customer data to uncover trends and insights using Python for EDA and Power BI for interactive visualizations. The dataset was extracted from a SQL database using Python (`pymysql` and `read_sql`).

---

## 📌 Objective

To explore and visualize customer financial behavior and risk profiles to support decision-making in retail banking operations.

---

## 📁 Project Structure

📂 Banking-Analysis-Project
│
├── 🔌 sql_data_extraction.ipynb # Extract data from MySQL using pymysql and read_sql
├── 📊 EDA_Banking.ipynb # Univariate & bivariate analysis using Python (matplotlib, seaborn, pandas)
├── 📁 PowerBI_Report.pbix # Final interactive Power BI dashboard
├── 📄 banking.csv # Cleaned dataset used in EDA and visualization
├── 📄 insights.txt # Written summary of key business insights
└── 📄 README.md # Project documentation (this file)

---

## ⚙️ Technologies Used

- **MySQL** – Data source
- **Python (Jupyter Notebook)** – Data extraction and analysis
  - `pandas`, `matplotlib`, `seaborn`, `pymysql`
- **Power BI Desktop** – Data visualization and dashboard creation
- **Git & GitHub** – Version control and project sharing

---

## 🚀 How to Use

1. **🔌 Data Extraction**
   - Open `sql_data_extraction.ipynb`
   - Use `pymysql.connect()` and `pd.read_sql()` to extract data from MySQL database
   - Save the resulting DataFrame as `banking.csv`

2. **📊 Exploratory Data Analysis**
   - Use `EDA_Banking.ipynb` to:
     - Clean and rename categorical codes (e.g. GenderId, BRId)
     - Detect & handle outliers
     - Perform univariate and bivariate analysis
     - Generate visual insights (bar plots, box plots, heatmaps)

3. **📈 Build Power BI Dashboard**
   - Open `PowerBI_Report.pbix` in Power BI Desktop
   - Load `banking.csv` as the data source
   - Explore visualizations such as:
     - Risk Weighting by Nationality
     - Income Band by Occupation
     - Credit Products Distribution
     - Customer Segments by Investment Advisor

4. **📝 Review Insights**
   - Read the `insights.txt` file for business interpretations
   - A documentation text box is also included on the 2nd page of the Power BI report

---

## 📊 Key Insights

- Most customers are classified under moderate risk (Risk Weighting 2 and 3).
- Income and product ownership trends vary significantly by occupation and nationality.
- Customers with higher superannuation savings tend to hold more diversified products.
- A few Investment Advisors (e.g. Victor Dean, Jeremy Porter) manage most of the high-risk clients.

---
