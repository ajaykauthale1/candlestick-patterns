# Candlestick Patterns & Price-Direction Models

A set of notebooks exploring short-term stock direction prediction and candlestick pattern recognition.

| Notebook | What it does |
| --- | --- |
| `apple.ipynb` | 1-minute AAPL bars; up/down target; Random Forest and KNN classifiers; Plotly candlestick charts |
| `random_forest.ipynb` | 15-minute GOOGL bars; feature engineering, train/test split, Random Forest with model persistence |
| `pattern_signals.ipynb` | Scans S&P 500 tickers for TA-Lib candlestick patterns and plots them with mplfinance |
| `sentiment_analysis.ipynb` | Scrapes FinViz headlines and scores them with NLTK VADER |

## Tech
Python, pandas, scikit-learn, TA-Lib, yfinance, yahoo_fin, mplfinance, Plotly, NLTK, PyCaret.

## Run
```bash
pip install -r requirements.txt   # TA-Lib needs its C library installed first
jupyter notebook
```

## Credits
Pattern-recognition and sentiment notebooks are adapted from
[Automating Technical Analysis: Pattern Recognition](https://medium.datadriveninvestor.com/automating-technical-analysis-pattern-recognition-bcbc85e4ec3c);
the random-forest notebook builds on
[Predict Stock Prices Using Random Forest Regression](https://medium.com/@maryamuzakariya/project-predict-stock-prices-using-random-forest-regression-model-in-python-fbe4edf01664).
