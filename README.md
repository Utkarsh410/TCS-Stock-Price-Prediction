# TCS Stock Price Prediction & Trading Strategy

## Project Overview
This project analyzes 19 years of historical stock data for Tata Consultancy Services (TCS) to predict closing prices and automate trading signals. By leveraging machine learning and financial indicators, the goal was to provide a data-driven framework for investment decisions.

## Key Features
- [cite_start]**Exploratory Data Analysis (EDA):** Visualized long-term trends and volatility from 2002 to 2021[cite: 1, 12].
- [cite_start]**Predictive Modeling:** Built a Linear Regression model achieving an **R-Squared score of 0.9999**[cite: 132, 140].
- [cite_start]**Feature Engineering:** Extracted temporal features (Year, Month, Day) and implemented "Previous Close" lag features to improve model accuracy[cite: 115, 124].
- [cite_start]**Algorithmic Strategy:** Developed a Moving Average Crossover strategy (50-day vs. 200-day) to generate Buy/Sell signals[cite: 196, 197].

## Technical Stack
- [cite_start]**Languages:** Python[cite: 1, 2].
- [cite_start]**Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn[cite: 1, 2, 3, 4, 5, 6].
- [cite_start]**Deployment:** Model serialized using Pickle for production readiness[cite: 172, 175].

## Model Performance
The model demonstrated exceptional precision with the following metrics:
- [cite_start]**Mean Squared Error (MSE):** 39.05[cite: 139].
- [cite_start]**R-Squared:** 0.9999[cite: 140].



## Visualizations
### 1. Stock Price Over Time
[cite_start]Visualizing the growth of TCS stock from 2002 to 2021[cite: 58, 64].


### 2. Moving Average Crossover Strategy
[cite_start]Identifying entry and exit points using 50-day and 200-day averages[cite: 208].


## How to Run
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`.
3. Run the Jupyter Notebook: `TCS_stock_analysis.ipynb`.
