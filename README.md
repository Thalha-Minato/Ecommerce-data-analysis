# Ecommerce-data-analysis
An end-to-end e-commerce data analysis project using Python (Pandas) and Power BI. Includes data cleaning, KPI generation, visual dashboards, and business insights.

# 🛍️ E-Commerce Data Analysis Project

A data analysis project focused on understanding sales, customer behavior, and performance trends in an e-commerce store using Python (Pandas) for preprocessing and Power BI for data visualization.

---

## 🎯 Project Objective

- Clean and transform raw e-commerce transaction data  
- Analyze key metrics like total sales, customer segments, and product performance  
- Create insightful Power BI dashboards to support business decision-making

---

## 📊 Dataset

- **Source**: [Kaggle – E-Commerce Data](https://www.kaggle.com/datasets/carrie1/ecommerce-data)  
- **Size**: ~500,000 records  
- **Fields**: InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country

---

## 🧰 Tools & Libraries

- **Python**
  - `Pandas` – data manipulation
  - `NumPy` – numerical operations
  - `Matplotlib` / `Seaborn` – basic plots (optional)
- **Power BI**
  - Interactive visual dashboards
  - KPI tracking and storytelling
- **Jupyter Notebook** – for Python development

---

## 🗂️ Project Structure

ecommerce-data-analysis/
├── data/ # Raw and cleaned datasets
├── notebooks/ # Jupyter Notebooks for preprocessing
├── dashboards/ # Power BI .pbix files and images
├── images/ # Charts/screenshots from Power BI
├── README.md # Project documentation
└── requirements.txt # Python dependencies

---

## 🚀 Steps Followed

### 1️⃣ Data Cleaning with Python
- Removed missing values and duplicates
- Handled invalid entries (e.g., negative quantities)
- Converted date columns and calculated total sales

### 2️⃣ Feature Engineering
- Created fields like `TotalAmount = Quantity * UnitPrice`
- Extracted `Year`, `Month`, `Weekday`, and `Hour` from `InvoiceDate`
- Grouped data by Customer, Country, and Product

### 3️⃣ Power BI Dashboard
- Imported cleaned data into Power BI
- Created visuals like:
  - **Sales Over Time**
  - **Top Selling Products**
  - **Sales by Country**
  - **Customer Segmentation**
  - **Returns & Cancellations**
- Added filters, slicers, and drill-down features

---

## 📈 Sample KPIs

| KPI                        | Value (Example)  |
|---------------------------|------------------|
| Total Revenue             | $1.2M            |
| Top Country by Sales      | United Kingdom   |
| Average Order Value       | $45              |
| Repeat Customer Rate      | 32%              |

> Note: These are illustrative figures.

---

## 📷 Sample Power BI Visuals

![Dashboard Screenshot](images/powerbi_dashboard.png)

---

## ✅ Learning Outcomes

- Real-world data cleaning and transformation using Pandas  
- Experience building analytical dashboards in Power BI  
- Interpreting business metrics from e-commerce data  
- Communicating insights visually

---

## 📬 Contact

- 🔗 [LinkedIn](https://linkedin.com/in/mohammedthalhas)
- 🐙 [GitHub](https://github.com/Thalha-Minato)
- 📧 Email: mohammadtalha112003@gmail.com

---

## 🙌 Contributions

Feel free to fork the repo, raise issues, or submit pull requests with improvements.
