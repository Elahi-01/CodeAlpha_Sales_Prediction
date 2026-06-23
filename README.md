# 📈 Sales Prediction Using Machine Learning

This repository contains the Task 4 project for the **CodeAlpha Data Science Internship**.

## 📌 Project Overview
The objective of this project is to build a Machine Learning model that can predict future sales based on advertising expenditure across multiple marketing channels: **TV**, **Radio**, and **Newspaper**.

## 📊 Dataset Used
- **File:** `Advertising.csv`
- **Features Captured:** - `TV`: Investment in TV advertisement campaigns (in thousands of dollars).
  - `Radio`: Investment in Radio campaigns.
  - **`Newspaper`**: Investment in Newspaper print ads.
- **Target Variable:** `Sales` (in thousands of units).

## 🛠️ Technologies & Libraries Used
- **Language:** Python
- **Environment:** Jupyter Notebook (`task_04.ipynb`)
- **Libraries:** `Pandas`, `Matplotlib`, `Seaborn`, `Scikit-Learn`
- **Algorithm:** Multiple Linear Regression (`LinearRegression`)

## 🚀 Workflow & Key Insights
1. **Data Preprocessing:** Dropped the auto-generated index column (`Unnamed: 0`). Checked for missing values and found the dataset to be 100% clean.
2. **Exploratory Data Analysis (EDA):** Plotted linear regression pair-plots (`sns.pairplot`). 
   - **Key Business Insight:** `TV` advertising showed the strongest positive linear correlation with sales, followed by `Radio`. `Newspaper` ads showed almost zero predictable impact on sales growth.
3. **Model Training:** Split the data into an 80:20 Train-Test split and trained a standard `LinearRegression` model.
4. **Feature Coefficients:** Extracted mathematical weights to show which advertising medium yields the highest Return on Investment (ROI).

## 📈 Model Performance
- **$R^2$ Score:** **0.8994** *(The model successfully explains ~90% of the variance in sales).*
- **Mean Absolute Error (MAE):** `1.46` units.

---
*Internship Project completed by **Elahi** (@Elahi-01)*
