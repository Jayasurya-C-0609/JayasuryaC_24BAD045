# ML Lab 3: Regression Analysis Projects

This repository contains two machine learning projects focused on regression analysis using different datasets.

## Projects Overview

### 1. Student Academic Performance Prediction
**Notebook:** `student academic performance/Student performance.ipynb`

This project analyzes student performance in exams and predicts final scores based on various demographic and educational factors.

#### Dataset
- **Source:** [Students Performance in Exams - Kaggle](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)
- **File:** `StudentsPerformance.csv`
- **Features:** Gender, race/ethnicity, parental level of education, lunch type, test preparation course
- **Target:** Final Score (average of math, reading, and writing scores)

#### Key Features
- Data exploration and preprocessing
- Feature encoding for categorical variables
- Correlation analysis and feature selection
- Multiple regression models:
  - Linear Regression
  - Ridge Regression
  - Lasso Regression
- Model comparison and evaluation using R² score, MSE, and RMSE
- Feature coefficient analysis

---

### 2. Vehicle Fuel Efficiency Prediction
**Notebook:** `vehicle fuel efficiency/Fuel.ipynb`

This project predicts vehicle fuel efficiency (MPG - Miles Per Gallon) based on vehicle characteristics using polynomial regression techniques.

#### Dataset
- **Source:** [Auto MPG Dataset - Kaggle](https://www.kaggle.com/datasets/uciml/autompg-dataset)
- **File:** `auto-mpg.csv`
- **Features:** Cylinders, displacement, horsepower, weight, acceleration, model year, origin
- **Target:** MPG (Miles Per Gallon)

#### Key Features
- Data cleaning (handling missing values in horsepower)
- Feature selection and scaling
- Polynomial regression with multiple degrees
- Ridge regression for regularization
- Model comparison and bias-variance tradeoff analysis
- Visualization of polynomial fits

---

## Requirements

### Python Libraries
```
numpy
pandas
matplotlib
seaborn
scikit-learn
```

### Installation
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

---

## How to Run

1. **Clone or download** this repository
2. **Install dependencies** using the command above
3. **Download datasets** from the provided Kaggle links and place them in respective folders:
   - `StudentsPerformance.csv` in `student academic performance/` folder
   - `auto-mpg.csv` in `vehicle fuel efficiency/` folder
4. **Open Jupyter Notebook** and run the notebooks:
   ```bash
   jupyter notebook
   ```
5. Navigate to the desired notebook and run all cells

---

## Project Structure

```
Lab 3/
│
├── student academic performance/
│   ├── Student performance.ipynb
│   └── StudentsPerformance.csv
│
├── vehicle fuel efficiency/
│   ├── Fuel.ipynb
│   └── auto-mpg.csv
│
└── README.md
```

---

## Methodology

### Student Performance Analysis
1. **Data Preprocessing:** Load data, check for missing values
2. **Feature Engineering:** Create final score from math, reading, and writing scores
3. **Encoding:** Convert categorical variables to numerical using Label Encoding and One-Hot Encoding
4. **Feature Scaling:** Standardize features using StandardScaler
5. **Feature Selection:** Correlation analysis to identify important features
6. **Model Training:** Train multiple regression models (Linear, Ridge, Lasso)
7. **Evaluation:** Compare models using R², MSE, and RMSE metrics

### Fuel Efficiency Prediction
1. **Data Preprocessing:** Load data, handle missing values in horsepower
2. **Feature Selection:** Select relevant numerical features
3. **Feature Scaling:** Standardize features using StandardScaler
4. **Polynomial Features:** Create polynomial features of different degrees
5. **Model Training:** Train polynomial regression and Ridge regression models
6. **Evaluation:** Compare models and analyze bias-variance tradeoff
7. **Visualization:** Plot polynomial regression curves

---

## Key Results

### Student Performance
- Successfully predicted student final scores using demographic and educational factors
- Identified key features influencing academic performance
- Compared regularization techniques (Ridge vs Lasso)

### Fuel Efficiency
- Accurately predicted vehicle MPG using vehicle characteristics
- Analyzed the effect of polynomial degree on model performance
- Demonstrated regularization benefits using Ridge regression


