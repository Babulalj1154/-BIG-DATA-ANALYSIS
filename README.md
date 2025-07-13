# -BIG-DATA-ANALYSIS

*COMPANY* : CODTECH IT SOLUTIONS

*NAME* : BABULAL JANGID 

INTERN ID : CT06DF2423

DOMAIN : DATA ANALYTICS 

DURATION : 6 WEEKS 

MENTOR : NEELA SANTOSH


# 🛒 Big Data Analysis with PySpark – Walmart Dataset

This repository presents a Big Data analysis project using **PySpark**, focusing on the Walmart Retail Sales dataset. The goal is to apply Spark’s distributed computing capabilities to process, analyze, and visualize large-scale retail data efficiently. This task was performed in **Google Colab** using the dataset downloaded from **Kaggle**.

---

## 📌 Project Objective

The primary aim of this project is to:
- Analyze retail sales patterns from Walmart stores.
- Understand how external factors like temperature, fuel prices, holidays, and unemployment influence weekly sales.
- Demonstrate the capabilities of PySpark for scalable and efficient big data analysis.

---

## 📁 Dataset Used

- **Name**: Walmart Sales Forecasting Dataset  
- **Source**: [Kaggle - Walmart Retail Sales Forecasting](https://www.kaggle.com/datasets)
- **File Used**: `Walmart_Sales.csv`

### Columns Overview:
- `Store`: Store ID  
- `Date`: Week Date  
- `Weekly_Sales`: Sales in that week  
- `Holiday_Flag`: Indicates if the week includes a holiday (1 = Yes)  
- `Temperature`: Average temperature in the region  
- `Fuel_Price`: Cost of fuel  
- `CPI`: Consumer Price Index  
- `Unemployment`: Unemployment rate

---

## 🛠️ Tools & Technologies

- **Apache Spark (PySpark)** – Big data processing
- **Google Colab** – Cloud-based Jupyter environment
- **Python 3** – Programming language
- **Matplotlib / Pandas** – Visualization and tabular analysis

---

## 🔍 Key Features & Analysis Performed

- **Data Loading** using `spark.read.csv()` with schema inference
- **Schema Inspection** and Data Exploration:
  - Summary statistics via `df.describe().show()`
  - Checking for nulls using `isNull()` and `when()`
- **Group-wise Analysis**:
  - Average weekly sales by temperature, fuel price, and store
  - Count of transactions by values
- **Filtering**:
  - Weekly sales greater than a specific threshold
- **Visualizations**:
  - Bar chart of average weekly sales per store
  - Scatter plot of temperature vs weekly sales
  - Comparison of holiday vs non-holiday weekly sales

---

## 📊 Insights Discovered

- Some stores consistently outperform others in weekly sales.
- Temperature and weekly sales do not follow a strong linear pattern.
- Average weekly sales on **non-holidays** tend to be **higher** than on holidays.
- Certain fuel prices appear frequently in the dataset, possibly indicating stable pricing periods.

---

## ▶️ How to Run

1. Open [Google Colab](https://colab.research.google.com/)
2. Upload the script or notebook and `Walmart_Sales.csv` file
3. Run the cells in sequence
4. All required libraries (like `pyspark`, `matplotlib`, and `pandas`) can be installed via pip in the first cell:
```python
!pip install pyspark
```

---

## 📚 Folder Structure (Example)

```
big-data-walmart/
├── Walmart_Sales.csv                 # Input dataset
├── Task_1_big_data_Analysis.ipynb    # Main notebook (Google Colab)
├── README.md                         # Project documentation
```

---

## ✅ Use Cases

- Academic project for Data Analytics or Big Data coursework
- Demonstration of Spark for real-world dataset processing
- Intern-level data engineering or data science tasks
- Retail industry analysis and forecasting

---

## 📬 Contact

**Author**: Babulal Jangid  
**Email**: jangidbabulal760@gmail.com
---

## 📜 License

This project is licensed under the MIT License - feel free to use, share, or modify with attribution.
