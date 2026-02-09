# TCS Stock Price Prediction & Trading Strategy

## Project Overview
This project analyzes 19 years of historical stock data for Tata Consultancy Services (TCS) to predict closing prices and automate trading signals. By leveraging machine learning and financial indicators, the goal was to provide a data-driven framework for investment decisions.

## Key Features
- **Exploratory Data Analysis (EDA):** Visualized long-term trends and volatility from 2002 to 2021.
- **Predictive Modeling:** Built a Linear Regression model achieving an **R-Squared score of 0.9999**.
- **Feature Engineering:** Extracted temporal features (Year, Month, Day) and implemented "Previous Close" lag features to improve model accuracy.
- **Algorithmic Strategy:** Developed a Moving Average Crossover strategy (50-day vs. 200-day) to generate Buy/Sell signals.

## Technical Stack
- **Languages:** Python.
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn.
- **Deployment:** Model serialized using Pickle for production readiness.

## Model Performance
The model demonstrated exceptional precision with the following metrics:
- **Mean Squared Error (MSE):** 39.05.
- **R-Squared:** 0.9999.



## Visualizations
### 1. Stock Price Over Time
Visualizing the growth of TCS stock from 2002 to 2021.
<img width="1009" height="523" alt="TCS2" src="https://github.com/user-attachments/assets/bb956b9e-aac6-40ab-b87f-69a5fb80a946" />


### 2. Moving Average Crossover Strategy
Identifying entry and exit points using 50-day and 200-day averages.
<img width="984" height="529" alt="TCS1" src="https://github.com/user-attachments/assets/a0265efa-7d06-4df2-b7fe-24517bf0c48d" />


## How to Run
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`.
3. Run the Jupyter Notebook: `TCS_stock_analysis.ipynb`.
