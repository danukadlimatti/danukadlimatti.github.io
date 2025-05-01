# 🪔 Diwali Sales Analysis

This project analyzes Diwali sales data from a retail store to identify customer purchasing behaviors, key demographics, and high-performing product categories. The goal is to derive insights to support marketing and inventory decisions.

## 📌 Objective

- Analyze customer demographics and purchasing patterns
- Discover high-value customers and products
- Provide actionable business insights for festive season sales

## 🧰 Tools and Libraries Used

- **Python 3**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

## 📁 Dataset

- Filename: `Diwali Sales Data.csv`
- Contains customer demographic data and purchase information:
  - `Gender`, `Age Group`, `Marital Status`, `State`, `Occupation`
  - `Product Category`, `Amount`, etc.

## 📊 Analysis Workflow

### 1. Data Cleaning
- Dropped null values in `Amount` and `Product_Category`
- Removed unnecessary columns: `Status`, `unnamed1`
- Converted `Amount` to `int`

### 2. Exploratory Data Analysis (EDA)
- **Gender-wise** and **Age-wise** purchase analysis
- Marital Status distribution and spending comparison
- State-wise total sales
- Occupation-based spending trends
- Product category analysis

### 3. Visualizations
- Bar plots using Seaborn and Matplotlib
- Count plots for categorical data
- Pie charts and group summaries

## 🔍 Key Insights

- **Married women aged 26–35** are the top spenders.
- **Uttar Pradesh**, **Maharashtra**, and **Karnataka** generate the highest revenue.
- Product Categories like **Clothing & Apparel** and **Food & Beverages** perform best.
- **IT Sector and Healthcare professionals** are high-value customers.

## 📈 Visual Samples

> *Screenshots of charts can be included here if hosting on GitHub.*

## ✅ Conclusion

The analysis provides insights into customer preferences and highlights high-performing segments. These insights can drive targeted marketing campaigns, optimized inventory planning, and personalized customer experiences for future festive sales.

## 📌 Future Enhancements

- Add year-wise or monthly trends
- Build predictive models to forecast Diwali sales
- Perform RFM (Recency, Frequency, Monetary) customer segmentation

## 🧾 Requirements

Install the required libraries using:

```bash
pip install pandas numpy matplotlib seaborn

Danamma K
GitHub: @danukadlimatti
