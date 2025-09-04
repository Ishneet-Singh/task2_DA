# task2_DA
Supermarket sales 
This project explores and analyzes a **Supermarket Sales dataset** using Python.  
The goal is to perform Exploratory Data Analysis (EDA), visualize trends, detect outliers, and uncover patterns across different product categories and regions.

 📂 Dataset
The dataset contains 9,994 rows and 11 columns, including details such as:
- Order ID, Customer Name, Category, Sub Category, City, Region, State
- Sales, Discount, Profit, Order Date

🔗 Dataset Source:* [Kaggle – Supermarket Sales](https://www.kaggle.com/datasets)

🛠️ Technologies Used
- Python 3.
- pandas → data manipulation
- numpy → numerical operations
- matplotlib & seaborn → data visualization
Analysis Steps

1. Data Understanding
- Checked dataset structure with:
  ```python
  df.info(), df.describe(), df.isnull().sum(), df['Category'].value_counts()
Verified no missing values.

2. Missing Data Analysis
Used seaborn heatmap to check for missing values.
✅ No missing data detected.

3. Distribution Analysis
Histplot: Sales distribution
Boxplot: Profit by category
Pairplot: Relationship between Sales, Profit, Discount
Countplot: Frequency of product categories

4. Correlation Analysis
Created a correlation heatmap of numeric variables (Sales, Profit, Discount).
Observed positive correlation between Sales & Profit, slight negative impact of Discount on Profit.


**Key Insights
-Snacks, Bakery, Fruits & Veggies contribute the highest number of sales.
-West & East regions dominate sales volume, while North region has minimal sales.
=Discounts have a slight negative effect on Profit, but not strongly correlated.
-Some categories show outliers in Profit, indicating occasional very high/low margins.
