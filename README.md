# CodeAlpha_SalesPrediction
# Sales Prediction using Python

This project is part of my Data Science Internship at **CodeAlpha**.

## About
The goal is to predict product sales based on advertising spend across three channels — TV, Radio, and Newspaper — using a regression model, and to identify which channel drives sales the most.

## Dataset
The dataset (`Advertising.csv`) contains 200 samples with the following features:
- TV (advertising spend)
- Radio (advertising spend)
- Newspaper (advertising spend)
- Sales (target)

## Steps Followed
1. Loaded and explored the dataset
2. Cleaned the data (dropped the unnecessary index column)
3. Visualized relationships using a correlation heatmap and scatter plots
4. Split the data into training and test sets
5. Trained a **Linear Regression** model
6. Evaluated performance using R² score and Mean Squared Error
7. Analyzed model coefficients to see each channel's impact on sales

## Results
TV advertising showed the strongest impact on sales, followed by Radio. Newspaper advertising had the weakest relationship with sales. The model achieved a strong R² score, showing it explains most of the variation in sales.

## Tools Used
- Python
- Pandas
- Matplotlib & Seaborn
- Scikit-learn

## How to Run
1. Open the notebook `CodeAlpha_Task4_Sales_Prediction.ipynb` in [Google Colab](https://colab.research.google.com)
2. Upload `Advertising.csv` when prompted
3. Run all cells in order

## Internship
This project was completed as part of the **Data Science Internship at CodeAlpha**.
