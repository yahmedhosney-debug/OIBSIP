# OIBSIP - Data Analytics Internship (Oasis Infobyte)

## Task 1: Exploratory Data Analysis on Retail Sales Data

### Objective
Perform an exploratory data analysis (EDA) on a retail sales dataset to uncover sales patterns, customer behaviour, and actionable business insights.

### Dataset
- **Source:** Superstore Sales Dataset (Kaggle, by Rohit Sahoo)
- **Size:** 9,800 orders, 18 columns
- **Period:** 2015 - 2018

### Tools
Python, pandas, matplotlib, seaborn, Jupyter Notebook (Google Colab)

### Analysis Steps
1. Data loading and inspection (shape, dtypes, null values)
2. Descriptive statistics (mean, median, std, min, max)
3. Time series analysis: monthly and quarterly sales
4. Customer analysis: segments and regions
5. Product analysis: top 10 products and revenue by category
6. Correlation heatmap
7. Additional analysis: top 10 states by sales
8. Conclusion with business recommendations

### Note on Customer Demographics
The dataset does not contain age or gender columns. Customer analysis was therefore done using **Segment** (Consumer, Corporate, Home Office) and **Region** instead.

### Key Findings
- Sales show an upward trend from 2015 to 2018.
- Q4 (November and December) is the strongest period every year.
- Consumer is the largest segment; Technology leads category revenue.
- California and New York generate a large share of total sales.
- Sales growth comes from order volume, not higher order values.

### Business Recommendations
1. Prepare stock and promotions ahead of Q4.
2. Prioritize the top states (California, New York) and test marketing in weaker regions.
3. Focus campaigns on top products and the Consumer segment.

### Files
- `Task1_EDA_Retail_Sales.ipynb`: full analysis notebook

### Author
Youssef Ahmed Hosney
