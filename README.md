# Stock Prediction With LSTM

This project utilizes LSTM (Long Short-Term Memory) neural networks to predict stock prices for four different symbols: Apple (AAPL), Nvidia (NVDA), Google (GOOGL), and Amazon (AMZN). The LSTM models are trained using historical stock price data fetched from Yahoo Finance and evaluated based on various performance metrics.

## Overview

The project consists of Python code written in Jupyter Notebook format (`stock_prediction_ltsm.ipynb`). It performs the following tasks:

- Fetches historical stock price data from Yahoo Finance.
- Prepares the data by selecting adjusted close prices, normalizing the data, and splitting it into training and testing sets.
- Creates input-output pairs for training the LSTM models with a specified look-back period.
- Defines the architecture of LSTM models, trains them, and evaluates their performance using metrics such as RMSE, MAE, MAPE, and R-squared.
- Visualizes the results by plotting actual and predicted stock prices for the training data.

## Installation and Setup

### Clone Repository
```bash
git clone https://github.com/yllvar/Stock-Prediction-LTSM.git
cd Stock-Prediction-LTSM
```

### Python Installation
Ensure you have Python installed. You can download it from [here](https://www.python.org/downloads/).

### Install Dependencies
```bash
pip install -r requirements.txt
```

### Jupyter Notebook Installation
If you want to execute the code in a Jupyter Notebook:
```bash
pip install jupyterlab
```

---

## Running the Code

### Jupyter Notebook
1. Open a terminal.
2. Navigate to the project directory.
3. Launch Jupyter Notebook.
```bash
jupyter notebook
```
4. Open and run the `stock_prediction_ltsm.ipynb` notebook.

---

## Acknowledgements
- This project utilizes various libraries such as NumPy, pandas, Matplotlib, TensorFlow, and scikit-learn for data manipulation, visualization, and machine learning tasks.
- Data fetching is performed using the yfinance library.
- The code structure and methodologies are inspired by machine learning literature and online resources.