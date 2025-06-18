# 🛍️ Retail Sales Analysis using PySpark

This beginner-friendly project analyses real-world retail transaction data using PySpark and Python in Google Colab. It focuses on cleaning, transforming, and analysing sales records to extract valuable business insights such as monthly sales trends and top-selling products.

---

## 📁 Dataset

- **Source**: UCI Machine Learning Repository  
  [Online Retail Dataset](https://archive.ics.uci.edu/ml/datasets/Online+Retail)
- **Original Format**: Excel (`Online Retail.xlsx`)
- **Used Format**: Sampled and converted to CSV → `retail_data_mini.csv`
- **Size**: 2000 rows (sampled for GitHub upload)

---

## 🚀 Key Features

- ✅ Loaded real-world sales data in PySpark using `SparkSession`
- ✅ Removed null values and filtered out negative quantities
- ✅ Analysed:
  - Monthly sales trends using `groupBy` and aggregation
  - Top 10 best-selling products by total quantity
- ✅ Used `Spark SQL` and `DataFrame API` for analysis
- ✅ Executed everything in **Google Colab** using Python and PySpark

---

## 🛠 Tools Used

- Python 3.x
- PySpark (Spark SQL, DataFrame API)
- Google Colab
- Pandas (for file conversion)
- Matplotlib (optional for plotting)

---

## 📈 Sample Output

### 🔸 Monthly Sales Trend (Total Quantity Sold)
| Month | Quantity |
|-------|----------|
| Jan   | 349,147  |
| Nov   | 681,888  |
| Dec   | 599,693  |

### 🔸 Top 10 Products
- Found using `groupBy("Description").agg(sum("Quantity"))`

---

## 📂 Project Structure

---

## 📌 Skills Gained

- Working with PySpark on real datasets
- Performing ETL in a distributed environment
- Using Spark SQL and aggregations
- Data cleaning and business insight generation
- Hosting and managing projects on GitHub

---

## 🙋‍♂️ Author

**Annu Priya**  
Beginner in Data Engineering & Analytics  
[LinkedIn](https://www.linkedin.com/in/https://www.linkedin.com/in/annu-priya-42a181219//) | [GitHub](https://github.com/Annupriya28)

---

## 🔗 Project Link

[👉 View this project on GitHub](https://github.com/Annupriya28/retail-sales-analysis-pyspark)


