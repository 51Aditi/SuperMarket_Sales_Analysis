# 🛒 Supermarket Sales Analysis using EDA

## 📌 Project Overview
This project performs Exploratory Data Analysis (EDA) on supermarket sales data using Python. The main goal of this project is to analyze customer purchasing behavior, product performance, sales trends, and payment methods using data visualization techniques.

---

## 🎯 Objectives
- Analyze supermarket sales trends
- Understand customer purchasing behavior
- Identify popular product lines
- Analyze customer ratings
- Visualize business insights using graphs

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Dataset Information
The dataset contains supermarket transaction records including:
- Invoice ID
- Branch
- City
- Customer Type
- Gender
- Product Line
- Unit Price
- Quantity
- Tax
- Total
- Date
- Time
- Payment Method
- Rating

---

## 📊 Exploratory Data Analysis Performed

### ✔ Data Cleaning
- Checked missing values
- Removed duplicate records
- Converted date columns

### ✔ Univariate Analysis
- Customer rating distribution
- Branch analysis
- Product line frequency

### ✔ Bivariate Analysis
- Product line vs total sales
- Gender vs purchasing behavior
- Payment method analysis

### ✔ Correlation Analysis
- Heatmap for numerical features
- Relationship between sales variables

---

## 📈 Visualizations Used
- Histogram
- KDE Plot
- Countplot
- Boxplot
- Heatmap

---

## 🔍 Key Insights
- Certain branches generated higher sales
- Customer ratings were evenly distributed
- Some product lines were more popular
- E-wallet and cash were commonly used payment methods
- Total sales strongly correlated with quantity purchased

---

## 🚀 Future Scope
This project can be extended using machine learning techniques for:
- Sales prediction
- Customer segmentation
- Demand forecasting

---

## 📁 Project Structure

```text
Supermarket-Sales-EDA/
│
├── dataset/
│   └── supermarket_sales.csv
│
├── notebook/
│   └── supermarket_sales_analysis.ipynb
│
├── images/
│   └── charts.png
│
├── README.md
│
└── requirements.txt
```

---

## ▶️ How to Run the Project

```bash
pip install pandas numpy matplotlib seaborn
```

```bash
jupyter notebook
```

Run all cells in the notebook.

---

## 📌 Conclusion
This project demonstrates how Exploratory Data Analysis (EDA) can be used to extract meaningful business insights from supermarket sales data using Python visualization libraries.
