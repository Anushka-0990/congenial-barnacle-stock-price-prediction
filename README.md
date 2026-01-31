📈 Stock Price Prediction using Machine Learning

📌 Overview

This project predicts future stock prices using real historical stock data fetched via Yahoo Finance. It uses simple regression models like Linear Regression and Random Forest to predict the next few days of a selected company's stock closing price.

Stock price prediction is a classic machine learning problem that involves time-series data and regression. The project helps you understand how to fetch live data, clean it, apply regression models, and visualize predictions.

📁 Data Source

- Source: Yahoo Finance (using yfinance library)
- Example: AAPL (Apple Inc.)
- You can change it to any other ticker like TSLA, INFY, TCS, etc.

🧠 ML Models Used

- Linear Regression
- Random Forest Regressor

📊 Features

- Download live stock data using `yfinance`
- Create new features like 5-day and 10-day moving averages
- Split dataset into training and testing sets
- Apply regression models to predict `Close` price
- Evaluate with R² score and plot real vs predicted prices

🛠️ Tech Stack

- Python 3.x
- Libraries: pandas, numpy, matplotlib, scikit-learn, yfinance

📂 Folder Structure

stock-price-prediction/
├── main_notebook.ipynb
├── README.txt
├── requirements.txt

🚀 How to Run

1. Install the libraries:
   pip install -r requirements.txt
2. Open Jupyter Notebook:
   jupyter notebook
3. Run `main_notebook.ipynb`
4. Change the stock symbol (ticker) to test different companies

🧯 Troubleshooting

❗ ModuleNotFoundError: No module named 'yfinance'
✔️ Run: pip install yfinance

❗ Graph is flat or prediction is weird
✔️ Make sure there's no missing data (drop NA values)
✔️ Try increasing training data or switching to a different ticker

❗ Linear Regression score is low
✔️ Try Random Forest or add more lag features (moving averages)

📌 Output

- Line graph: actual vs predicted stock prices
- R² score for model evaluation


