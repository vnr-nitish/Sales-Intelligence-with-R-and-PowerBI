# 🛍️ Superstore Sales & Profit Analysis | R + Power BI  
**Author:** Nitish Raj Vinnakota | [LinkedIn](https://linkedin.com/in/vnr-nitish)

---

## 🔍 Project Overview

This project provides a comprehensive analysis of the Superstore dataset using two tools:

- 📊 **R**: For in-depth exploratory data analysis, data cleaning, visualization, and classification modeling using logistic regression.
- 📈 **Power BI**: For interactive dashboards showcasing regional, segment, and product-level business insights.

Together, these tools demonstrate an end-to-end data analysis workflow from raw data to visualization and modeling.

---

## 📁 Dataset Details

- **Source**: Super_Store.csv  
- **Rows**: 9994  
- **Features**:
  - Categorical: Region, State, Category, Segment, Sub-Category, Ship Mode
  - Numerical: Sales, Quantity, Discount, Profit

✅ Clean and complete dataset  
✅ No missing values  

---

## 🧠 R-Based Analysis Highlights

### 🧹 Preprocessing:
- Dropped unnecessary columns
- Converted relevant fields to factor/numeric
- Created a binary target variable `High_Profit` based on median profit

### 📊 Exploratory Data Analysis:
- **Bar Charts & Pie Charts**:
  - Sales and profit by **Region**, **Segment**, **Category**, and **State**
- **Correlation Heatmap**:
  - Analyzed relationships between numerical features

### 🔎 Logistic Regression Model:
- Built a model to classify whether a transaction results in **high or low profit**
- **Features used**: Sales, Discount, Quantity
- Evaluated with:
  - Confusion Matrix
  - Accuracy, Precision, Recall, F1-Score

### ✅ Model Metrics:
- **Precision, Recall, F1 Score**: Interpreted model effectiveness  
- **Accuracy**: Highlighted classification performance

---

## 📈 Power BI Dashboard Features

- **Sales & Profit by City, State, Region, Segment, Ship Mode**
- **Sub-Category breakdown** by Quantity, Sales, and Profit
- **Interactive visuals** using bar charts, pie charts, and stacked columns

### Key Insights:
- 🔹 **Phones, Chairs, and Copiers** dominate in sales and profit  
- 🔹 **New York City, Los Angeles, and Seattle** are top-performing cities  
- 🔹 **Consumer segment** and **Standard shipping** have the highest sales volume  
- 🔹 **Tables and Bookcases** are lower-profit sub-categories  

---

## 🧰 Tools Used

- **R**: `dplyr`, `ggplot2`, `caTools`, `reshape2`, `scales`
- **Power BI Desktop**
- **RStudio**
- **CSV Input File**: Super_Store.csv

---

## 🏆 Skills Demonstrated

- Data cleaning and transformation  
- Data visualization using `ggplot2` and Power BI  
- Classification using Logistic Regression  
- Business analytics reporting  
- Cross-tool storytelling (R + BI dashboards)

---

## 🚀 Future Improvements

- Deploy logistic regression as a web app (Shiny or Streamlit)  
- Perform advanced classification using XGBoost or Random Forest in R  
- Add dynamic slicers and drill-downs in Power BI  
- Automate R script and Power BI refresh using scheduling tools

---

## 📫 Contact

📧 **Email:** nvinnako2@gitam.in  
🔗 **LinkedIn:** [linkedin.com/in/vnr-nitish](https://linkedin.com/in/vnr-nitish)

---

> *"From raw data to actionable insights—analyzing profit and performance across every corner of the store."*
