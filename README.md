# 🪔 Diwali Sales Analysis  
A detailed Exploratory Data Analysis (EDA) project focused on identifying customer purchasing patterns during the Diwali festival season.

---

## 📛 Project Badges  
![Python](https://img.shields.io/badge/Python-3.x-blue)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Pandas](https://img.shields.io/badge/Library-Pandas-yellowgreen)
![Matplotlib](https://img.shields.io/badge/Library-Matplotlib-lightblue)
![Dataset](https://img.shields.io/badge/Dataset-CSV-red)

---

## 📌 Project Overview  
This project performs an **Exploratory Data Analysis (EDA)** on Diwali sales data to uncover valuable **customer behavior insights**, focusing on demographics, spending habits, and top-performing product categories.  
The objective is to help businesses better understand their target audience and optimize marketing strategies during festive seasons.

---

## 📂 Dataset Description  
- **File Format:** CSV  
- **Sample Columns:**
| Column | Description |
|--------|------------|
| Gender | Customer gender |
| Age Group | Age segment (e.g., 18–25, 26–35, etc.) |
| State | Customer location |
| Marital_Status | Whether customer is married |
| Occupation | Professional background |
| Product_Category | Product group purchased |
| Orders | Number of orders |
| Amount | Total amount spent |

---

## 🛠️ Data Preprocessing  
Steps performed in the notebook:
✅ Dropped unnecessary columns (`Status`, `unnamed1`)  
✅ Removed null values using `dropna()`  
✅ Converted `Amount` to integer type  
✅ Used `describe()` to summarize numerical insights  

---

## 📊 Exploratory Data Analysis (EDA)

### 1️⃣ Demographic Insights (Customer Profiling)
- **Gender vs Total Amount & Orders:**  
  ➤ As shown in the gender-based sales charts, **females** contributed more to the total purchase amount compared to males.  

- **Age Group Analysis:**  
  ➤ The **26–35 age group** shows the highest engagement and spending during Diwali (see age vs amount chart).  

- **Marital Status:**  
  ➤ **Married customers**, especially married women, made higher purchases.  

### 2️⃣ Geographic Performance
- **State-wise Sales:**  
  ➤ Top contributing states include **Uttar Pradesh, Maharashtra, and Karnataka**, indicating strong demand in these regions.

### 3️⃣ Occupation-Based Trends
- **Occupation vs Amount:**  
  ➤ Customers from **IT, Healthcare, and Aviation sectors** dominated purchases (confirmed by occupation-wise bar charts).

### 4️⃣ Product Category Analysis
- **Top Categories Purchased:**  
  ➤ Most frequently purchased categories include **Food, Clothing, and Electronics**, as shown in product category charts.

---

## 📍 Key Insights Summary
✅ Female buyers are more likely to spend during Diwali.  
✅ Age group **26–35** is the most profitable demographic segment.  
✅ **Married individuals**, particularly women, are the major contributors.  
✅ Regions like **UP, Maharashtra, and Karnataka** drive maximum revenue.  
✅ **IT, Healthcare, and Aviation professionals** are high-value customers.  
✅ **Food, Clothing & Electronics** are top-performing product categories.

---

## 💼 Business Recommendations
📢 Based on the EDA, businesses should:
✅ Focus Diwali marketing campaigns on **married women aged 26–35**.  
✅ Target professionals from **IT, Healthcare, and Aviation** industries.  
✅ Provide **region-specific promotions** in **UP, Maharashtra, and Karnataka**.  
✅ Launch festive combo deals in **Food, Clothing, and Electronics** categories.  
✅ Offer loyalty rewards for high-value demographics.

---

## ▶️ How to Run This Project

### ✅ Prerequisites
Ensure Python and the required libraries are installed:
```bash
pip install numpy pandas matplotlib seaborn
