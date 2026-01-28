# Machine Learning Lab 1 - Exploratory Data Analysis (EDA)

This repository contains Jupyter notebooks demonstrating Exploratory Data Analysis (EDA) techniques on various real-world datasets.

## 📁 Project Structure

```
Lab 1/
├── Banking.ipynb                 # Customer Personality Analysis
├── Ecommerce.ipynb               # E-commerce Sales Analysis
├── Hospital.ipynb                # Diabetes Patient Records Analysis
├── House.ipynb                   # Housing Price Analysis
├── E_commerce_Sales_Data.csv     # E-commerce dataset
├── Hospital_Patient_Records.csv  # Patient records dataset
├── Housing_Dataset.csv           # Housing dataset
├── marketing_campaign.csv        # Marketing campaign dataset
└── README.md                     # This file
```

## 📊 Notebooks Overview

### 1. Banking.ipynb - Customer Personality Analysis
**Dataset:** [Customer Personality Analysis](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis)

This notebook analyzes customer data from a marketing campaign to understand customer behavior and demographics.

**Key Analysis:**
- Data loading and initial exploration (`head()`, `tail()`, `shape`, `info()`, `describe()`)
- Missing value detection
- Feature engineering: Customer age calculation from birth year
- Age distribution visualization (bar chart & boxplot)
- Income distribution analysis (boxplot & histogram)
- Total spending calculation across product categories (Wines, Fruits, Meat, Fish, Sweets, Gold)
- Spending pattern visualization

**Libraries Used:** pandas, numpy, seaborn, matplotlib

---

### 2. Ecommerce.ipynb - E-commerce Sales Analysis
**Dataset:** [E-commerce Data](https://www.kaggle.com/datasets/carrie1/ecommerce-data)

This notebook explores e-commerce transaction data to identify sales trends and top-performing products.

**Key Analysis:**
- Data loading with encoding handling (latin-1)
- Basic data exploration and statistics
- Missing value analysis
- Feature engineering: Sales calculation (Quantity × UnitPrice)
- Product performance analysis (grouping by product description)
- Top 10 best-selling products visualization
- Time series analysis: Daily sales trend

**Libraries Used:** pandas, numpy, seaborn, matplotlib

---

### 3. Hospital.ipynb - Diabetes Patient Records Analysis
**Dataset:** [Pima Indians Diabetes Database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)

This notebook analyzes patient health records to explore factors related to diabetes.

**Key Analysis:**
- Data loading and exploration
- Handling zero values as missing data (Glucose, BloodPressure, SkinThickness, Insulin, BMI)
- Missing value analysis after data cleaning
- Glucose level distribution (histogram & boxplot)
- Age distribution analysis (histogram & boxplot)

**Libraries Used:** pandas, numpy, seaborn, matplotlib

---

### 4. House.ipynb - Housing Price Analysis
**Dataset:** [Housing Price Prediction](https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction)

This notebook explores housing data to understand factors affecting property prices.

**Key Analysis:**
- Data loading and initial exploration
- Statistical summary of housing features
- Missing value detection
- Area vs Price scatter plot visualization
- Correlation heatmap for numeric features

**Libraries Used:** pandas, numpy, seaborn, matplotlib

---

## 🛠️ Requirements

```
pandas
numpy
seaborn
matplotlib
```

## 🚀 Getting Started

1. Clone this repository or download the files
2. Install the required libraries:
   ```bash
   pip install pandas numpy seaborn matplotlib
   ```
3. Open any notebook in Jupyter Notebook or VS Code
4. Run the cells sequentially to reproduce the analysis

## 📚 Datasets

| Notebook | Dataset | Source |
|----------|---------|--------|
| Banking.ipynb | Customer Personality Analysis | [Kaggle](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis) |
| Ecommerce.ipynb | E-commerce Data | [Kaggle](https://www.kaggle.com/datasets/carrie1/ecommerce-data) |
| Hospital.ipynb | Pima Indians Diabetes Database | [Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database) |
| House.ipynb | Housing Price Prediction | [Kaggle](https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction) |

## 📈 Common EDA Techniques Used

- **Data Loading:** Reading CSV files with pandas
- **Data Inspection:** `head()`, `tail()`, `shape`, `info()`, `describe()`
- **Missing Value Analysis:** `isnull().sum()`
- **Feature Engineering:** Creating new calculated columns
- **Visualization:**
  - Bar charts for categorical distributions
  - Histograms for continuous variable distributions
  - Boxplots for outlier detection
  - Scatter plots for relationship analysis
  - Heatmaps for correlation analysis
  - Line plots for time series trends

