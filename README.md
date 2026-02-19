#  Retail Sales Performance Analysis & Forecasting

Note - Please refer to the Roshana Notebook BIS.ipynb file in this repository to view the analysis, including all codes and results.

##  Project Overview
This project analyzes a retail transactional dataset to understand sales performance, customer behavior, revenue distribution, and future sales trends. 
The analysis follows a structured four-phase approach combining exploratory, statistical, predictive, and operational analysis to support data-driven business decision-making.

---

##  Business Problem
The main objective of this project is to identify the key factors influencing sales performance and determine how revenue is distributed across customers, regions, product categories, and time. 
The analysis also examines whether the business depends heavily on a small number of high-value customers, detects seasonal patterns, and forecasts future sales trends to improve revenue stability and strategic planning.

---

## Dataset Description
The dataset consists of retail transaction records containing:

- Order Date  
- Customer ID & Customer Name  
- Product Category & Sub-Category  
- Region & State  
- Sales Amount  ...etc

The dataset enables both operational and strategic performance analysis.

Link for Data Set( Store Sales - Time Series Forecasting) - /kaggle/input/sales-forecasting

---

##  Analytical Process

### 1. Data Understanding
- Overview of dataset variables
- Summary of data types, missing values, and key statistics

### 2. Data Preprocessing
- Convert dates to datetime format
- Handle missing values and duplicates
- Create additional features (Month, Year)
- Ensure correct data types for analysis

### 3. Phase 1 — Exploratory Data Analysis (EDA)
- **Sales Trend Over Time** (Matplotlib)
- **Sales by Region** (Seaborn)
- **Sales by Category** (Plotly Interactive)
- **Top 10 Products**

### 4. Phase 2 — Statistical Analysis
- Descriptive Statistics (Core Statistical Foundation)
- Sales Distribution Analysis (Understand Skewness)
- Variance & Standard Deviation (Measure Volatility)
- Category-Level Statistical Comparison
- Region-Level Statistical Comparison
- Monthly Sales Statistics (Time-Based Analysis)
- Month-over-Month Growth Rate (Advanced & Impressive)
- Rolling Average (Trend Smoothing — Strong Statistical Concept)
- Coefficient of Variation (Professional Metric)

### 5. Phase 3 — Forecasting
- Prepare Monthly Data
- Linear Regression Forecast
- Model Evaluation
- Actual vs Predicted Plot
- Bokeh Interactive Forecast

### 6. Phase 4 — Operational Analytics
- RFM Customer Segmentation
- Visualization of Customer Spending
- Geographic Sales Map
- Product Hierarchy Sunburst Chart
- Pareto Analysis (80/20 Rule) – VERY IMPRESSIVE
- Customer Purchase Frequency Distribution
- Individual Transaction Trends Over Time
- Distribution Density of Sales by Category
- Time-Series Feature Correlation Heatmap
- Clustering Analysis


---

##  Key Findings
- Refer to the .ipynb file 

---

##  Tools & Technologies Used
###Environment / Platform

- Kaggle Notebook Editor – used to run and manage the Python scripts and notebooks
- Python 3.x

###Libraries / Technologies

- Pandas – data manipulation and preprocessing
- NumPy – numerical computations
- Matplotlib – plotting line charts and bar charts
- Seaborn – statistical visualizations
- Plotly – interactive visualizations
- Bokeh – interactive forecasting visualizations
- Scikit-learn – linear regression and statistical analysis

---

##  How to Run This Project
1. Clone the repository  
2. Install required Python libraries  
3. Open the Jupyter Notebook (`.ipynb` file)  
4. Run the cells sequentially  

Note- All codes are functioning correctly. However, in the notebook environment, some outputs may not appear unless the respective cells are run separately or the entire notebook is executed in order. 
If output is not visible, please run the specific cell again or select “Run All” to ensure all results are displayed properly.
---

##  Author
**E.R.N.L. Fernando**
**INDEX NO 21020272**
Undergraduate – BSc (Hons) Information Systems  , University of Colombo School of Computing

