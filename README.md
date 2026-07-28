# 📊 AAL Sales Analysis using Python

## 📌 Project Overview

This project analyzes the fourth-quarter sales performance of **AAL**, an Australian apparel company, using Python. The objective is to clean, explore, and analyze sales data to identify regional performance, customer purchasing patterns, and business trends that can support data-driven decision-making.

The project follows a complete data analytics workflow, including data preprocessing, exploratory data analysis (EDA), statistical analysis, visualization, and business insights.

---

# 🎯 Objectives

* Analyze AAL's Q4 sales performance.
* Clean and preprocess the dataset.
* Identify high-performing and low-performing states.
* Compare sales across customer groups.
* Detect outliers in sales and units sold.
* Analyze sales trends over time.
* Generate actionable business insights.

---

# 📂 Dataset

The dataset contains **7,560 sales records** from the fourth quarter of 2020.

### Features

* Date
* Time
* State
* Customer Group
* Units Sold
* Sales

Additional features were created during preprocessing:

* Sales Normalized
* Unit Normalized

---

# 🛠 Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* Jupyter Notebook

---

# 🔄 Project Workflow

## 1. Data Loading

* Imported the dataset using Pandas.
* Examined dataset dimensions and data types.
* Performed an initial data inspection.

---

## 2. Data Cleaning & Preprocessing

The following preprocessing steps were performed:

* Checked for missing values
* Verified duplicate records
* Removed extra spaces from categorical columns
* Converted the Date column into datetime format
* Applied Min-Max Normalization to Sales and Units Sold

---

## 3. Exploratory Data Analysis (EDA)

EDA was conducted to better understand the dataset through:

* Summary statistics
* Distribution analysis
* Sales distribution
* Unit distribution
* Group-wise analysis
* State-wise analysis

---

## 4. Outlier Detection

Outliers were identified using **Tukey's Method (IQR)**.

Rather than removing them, they were retained because they likely represent genuine high-sales transactions and contain valuable business information.

---

## 5. Statistical Analysis

The following descriptive statistics were calculated:

* Mean
* Median
* Mode
* Standard Deviation

These metrics helped summarize sales and unit distributions.

---

## 6. Business Analysis

The project answers questions such as:

* Which state generated the highest sales?
* Which state generated the lowest sales?
* Which customer group contributes the most revenue?
* Which customer group performs the least?
* How do sales vary over time?
* Are there unusual purchasing patterns?

---

## 7. Time-Series Analysis

Sales performance was analyzed at multiple levels:

* Daily Sales
* Weekly Sales
* Monthly Sales
* Quarterly Sales

This helps identify sales trends and seasonal patterns.

---

# 📊 Visualizations

The project includes multiple visualizations such as:

* Sales Distribution
* Units Sold Distribution
* State-wise Sales Comparison
* Customer Group Analysis
* Time-Based Sales Trends

---

# 💡 Key Insights

Some important findings from the analysis include:

* **VIC** recorded the highest total sales.
* **WA** generated the lowest total sales.
* The **Men** customer group contributed the highest revenue.
* The **Seniors** customer group generated the lowest revenue.
* No missing values or duplicate records were found.
* Outliers represented legitimate business transactions and were retained.
* Time-based analysis provided insights into daily, weekly, monthly, and quarterly sales performance.

---

# 📁 Project Structure

```text
AAL-Sales-Analysis/
│
├── data/
│   └── AusApparalSales4thQrt2020.csv
│
├── notebooks/
│   └── AAL_Sales_Analysis.ipynb
│
├── images/
│   └── visualizations/
│
└── README.md
```

---

# 🚀 How to Run

1. Clone this repository.
2. Install the required Python libraries.

```bash
pip install pandas numpy matplotlib seaborn scipy
```

3. Open the Jupyter Notebook.
4. Run all cells sequentially.
5. Review the visualizations and business insights.

---

# 📈 Skills Demonstrated

* Data Cleaning
* Data Wrangling
* Exploratory Data Analysis (EDA)
* Data Normalization
* Outlier Detection
* Statistical Analysis
* Data Visualization
* Time-Series Analysis
* Business Insight Generation
* Python for Data Analytics

---

# 📌 Future Improvements

* Build an interactive Power BI dashboard.
* Perform predictive sales forecasting.
* Develop customer segmentation models.
* Create an executive business report.

---

# 👨‍💻 Author

**Jishnu Saji**

Aspiring Data Analyst | Python | SQL | PostgreSQL | Power BI | Data Visualization
